### The plan

#### Prepare the system

Install necessary packages

**base-devel**: essential tools for building software(make, gcc, pkg-config, binutils)

**ncurses**: Library for creating text-based user interfaces (menus, forms) used by `make menuconfig` the text-based configuration tool for customizing kernel options

**fakeroot**: simulates root permissions for package building. to install and build during compilations

**bc**: command-line calculator (for configuring timers)

**flex**: a lexical analyzer generator for parsing and processing configuration files during the build

**bison** a parser generator, for generating parsers needed duting the build for processing coniguration and code files

**openssl** toolkit for secure communication

**perl** the kernel build system uses perl for tasks during compilation

`sudo pacman -S base-devel git ncurses fakeroot bc flex bison openssl perl`

DONE

### Git bisect

After cloning `https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git` 

I tried the following:
```bash
git tag | grep 6.11
```

and got the following output (rc stands for release candidates):

```plaintext
v6.11
v6.11-rc1
v6.11-rc2
v6.11-rc3
v6.11-rc4
v6.11-rc5
v6.11-rc6
v6.11-rc7
```

I should use 6.11.9 (which is a minor release) because I know it works. it doesn't appear in the output. I'll try obtaining it with `git fetch --tags`

The output is the same so Ill use `6.11`

As for the other one I won't use `6.12` because the bug could have apperared only on `6.12.1` and I'd be losing time. So, I'll try compiling and testing kernel `6.12`

