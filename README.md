## Python Version Requirement

This project must be run using **Python 3.12**.

Some dependencies --- especially `pydantic-core` (required by
`pydantic`) --- do not currently support Python 3.13 on Windows, causing
installation errors related to Rust/Cargo compilation.

If you attempt to install dependencies using Python 3.13, the
installation will fail.\
Therefore, always create and use a virtual environment based on Python
3.12.

### Recommended Setup

``` sh
# Create a virtual environment using Python 3.12
py -3.12 -m venv .venv

# Activate the virtual environment
.\.venv\Scriptsctivate

# Install project dependencies
pip install -r requirements.txt
```

Make sure your editor or IDE (such as VS Code) is configured to use the
interpreter from `.venv` before running the project.
