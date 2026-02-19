# Bug report for Kernel Suspend/Resume Issue

## Summary

Suspend/resume results in a system freeze on kernel 6.12.1-arch1-1. The issue does not occur on the LTS kernel (6.6.63-1-lts), maybe suggesting a regression or incompatibility introduced in the newer kernel.

## System Details

- Laptop: Lenovo ThinkPad E14 Gen 3
- Model: 20Y7CTO1WW
- CPU: AMD Ryzen with Radeon Graphics (Lucienne)
- GPU: AMD Lucienne (Driver: amdgpu)
- Kernel: 6.12.1-arch1-1 (not working), 6.6.63-1-lts (working)
- OS: Arch Linux x86_64
- Bootloader: Systemd-boot
- Kernel Parameters
```plaintext
initrd=\initramfs-linux.img root=PARTUUID=17a4b077-180c-4310-8a22-7e72bcf92312 zswap.enabled=0 rw rootfstype=ext4
```

## steps to reproduce

1. Boot into kernel 6.12.1-arch1-1
2. Suspend the system using `systemctl suspend`
3. Attempt to resume the system
4. Observe that the system freezes (no keyboard, mouse, or login functionality)

## expected behavior
The system should resume from suspend without freezing, as it does on kernel 6.6.63-1-lts

## observed behavior
The system becomes unresponsive upon resuming from suspend. The issue requires a hard reboot to recover

## relevant logs
The following are log excerpts which I think might be related to the suspend/resume issue. I've produced them immediately after the system froze and I rebooted it, with:

```bash
dmesg | grep -iE "amdgpu|psp|error|suspend|resume"
dmesg | grep -i acpi
journalctl -b -1 | grep -iE "suspend|resume|amdgpu|error"
```

##### Kernel Logs
```plaintext
amdgpu: unknown parameter 'securedisplay' ignored
amdgpu: psp gfx command LOAD_TA(0x1) failed and response status is (0x7)
amdgpu: psp gfx command INVOKE_CMD(0x3) failed and response status is (0x4)
amdgpu: Secure display: Generic Failure.
amdgpu: SECUREDISPLAY: query securedisplay TA failed. ret 0x0
amdgpu: Runtime PM not available
```

##### Journalctl Logs
```plaintext
amdgpu: psp gfx command LOAD_TA(0x1) failed and response status is (0x7)
amdgpu: psp gfx command INVOKE_CMD(0x3) failed and response status is (0x4)
amdgpu: Secure display: Generic Failure.
amdgpu: SECUREDISPLAY: query securedisplay TA failed. ret 0x0
amdgpu: Runtime PM not available
systemd-logind[594]: The system will suspend now!
systemd-sleep[1669]: Performing sleep operation 'suspend'...
```

##### ACPI Logs
```plaintext
ACPI: Reserving NVS region
ACPI: Reserving data region
ACPI: PM-Timer IO Port: 0x408
```

If full logs are needed I can provide them

I hope this helps. Please let me know if additional details or testing are required to further investigate this issue.


