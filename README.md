# Pre-commit cleared Jupyter notebooks

This repository is an example/template for using pre-commit to automatically
clear ouputs from Jupyter notebook files.

## Usage

To use this repository you need:

- Python >= 3.9

You should use a virtual environment to install dependencies associated with
this project:

```bash
cd jupyter-precommit

python -m venv venv
```

You should activate the virtual environment and install the dependencies
specified in `requirements.txt`.

```bash
# on linux/MacOS
. venv/bin/activate

# on Windows
. venv/Scripts/activate

pip install -r requirements.txt
```

