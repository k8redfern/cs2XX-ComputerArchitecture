# cs2XX-ComputerArchitecture

CS 2XX: Computer Architecture

Your typical computer architecture course starting with transistors and ending with assembly language.

The course can be found [here](http://modsurski.com/csci263).


# Setup

## Windows

Have administrative privileges and run from cmd

```sh
python -m venv --clear --prompt cs263 venv
venv\Scripts\activate.bat
pip install --upgrade pip setuptools wheel
pip install --editable .
```

## Bash

```sh
python3.10 -m venv --clear --prompt cs263 venv
. venv/bin/activate
pip install --upgrade pip setuptools wheel
SETUPTOOLS_ENABLE_FEATURES="legacy-editable" pip install --editable .
```

# Formatter

```sh
format # just type this
```

# Unit Tests

```sh
python -m unittest # May need python3
```

# Build

```sh
sphinx-build -b html "$SOURCEDIR" "$OUTPUTDIR"
```

# Contribute

Check out the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
