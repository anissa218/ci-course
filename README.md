[![Run unit tests](https://github.com/anissa218/ci-course/actions/workflows/unit-tests.yml/badge.svg)](https://github.com/anissa218/ci-course/actions/workflows/unit-tests.yml)
[![Run on multiple os](https://github.com/anissa218/ci-course/actions/workflows/os-tests.yml/badge.svg)](https://github.com/anissa218/ci-course/actions/workflows/os-tests.yml)
[![Run coverage tests](https://github.com/anissa218/ci-course/actions/workflows/coverage-tests2.yml/badge.svg)](https://github.com/anissa218/ci-course/actions/workflows/coverage-tests2.yml)
[![BCH compliance](https://bettercodehub.com/edge/badge/anissa218/ci-course?branch=main)](https://bettercodehub.com/)
# OxRSE Continuous Integration course

This project contains a small Python project. We are going to use free cloud services to automate:

- unit testing on multiple Python versions
- unit testing on multiple operating systems
- coverage testing
- static analysis
- documentation generation

To make sure all dependencies are installed, we recommend creating a new virtual environment.
From the directory containing this file:

```bash
python3 -m pip install --user virtualenv
python3 -m venv venv
```

Activate the virtual environment:

Linux / macOS:
```bash
source venv/bin/activate
```

Windows cmd.exe:
```bash
venv\Scripts\activate.bat
```

Windows PowerShell:
```bash
venv\Scripts\Activate.ps1
```

Windows using Git Bash:
```bash
source venv\Scripts\activate
```

Upgrade the build tools and install this project:

```bash
pip install --upgrade pip setuptools wheel
pip install -e .[dev,docs]
```
