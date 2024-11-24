# lang_chain_lab
lang chain lab

## How to start project

### Create venv
`python -m venv venv`

### Activate venv on Mac OS
`source venv/bin/activate`

### Activare venv on Windows
`venv\Scripts\activate`

### install requirements
`pip install -r requirements.txt`

## How to add new packages using pip-tools

Add package name to `requirements.in` file. Run `pip-compile` command to regenerate new `requirements.txt` file.
