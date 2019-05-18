# imaGEN

[![Build Status](https://travis-ci.com/ubclaunchpad/imaGEN.svg?branch=master)](https://travis-ci.com/ubclaunchpad/imaGEN)

Generate Background images using machine learning!

## Developer Installation

Dependency management - [pipenv](https://pipenv.readthedocs.io/en/latest/).

```bash
git clone https://github.com/ubclaunchpad/imaGEN.git
cd image-generator/
pip install pipenv
pipenv install --dev
```

`pipenv` will manage a [virtualenv](https://virtualenv.pypa.io/en/stable/),
so interacting with the program or using the development tools has to be done
through pipenv, like so:

```bash
pipenv run <some command>
```

This can get inconvenient, so you can instead create a shell that runs in the managed
environment like so:

```bash
pipenv shell
```

and then commands can be run like normal.

CI system - [Travis CI](https://travis-ci.com/ubclaunchpad/mimic)
To run the same checks locally, we provide `scripts/build.sh`;
this can be run with:

```bash
./scripts/build.sh
```