# UV

`uv` is a tool that simplifies Python project management by handling tasks like creating virtual environments, installing dependencies, and running Python scripts without directly interacting with `pip` or `venv`. It’s useful for developers who want a streamlined workflow with minimal manual setup.

Here’s what `uv` does:
- **Manages virtual environments**: It automatically creates and activates a virtual environment, eliminating the need to manually use `venv` or `virtualenv`.
- **Manages dependencies**: You specify your dependencies in a `uv.toml` file (similar to how `pip` uses `requirements.txt` or `pyproject.toml`), and `uv` handles installing them.
- **Runs scripts**: You can run your Python scripts directly through `uv` without needing to activate the virtual environment or manually run `python3`.

## Documentation
https://docs.astral.sh/uv/

## See also
[[ML - just]]