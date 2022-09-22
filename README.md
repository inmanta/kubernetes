# kubernetes Module

> :warning: This module has been used in proof of concepts, to illustrate that inmanta can integrate with kubernetes.  This module
> is in a very early development state, and is not being actively worked on at the moment, it does not reflect how modules are usually
> built at inmanta.

## Running tests

1. Setup a virtual env 

```bash
mkvirtualenv inmanta-test -p python3
pip install -r requirements.dev.txt
pip install -r requirements.txt

mkdir /tmp/env
export INMANTA_TEST_ENV=/tmp/env
export INMANTA_MODULE_REPO=git@github.com:inmanta/
```

2. Run tests

```bash
pytest tests
```
