# Developer Notes

This document provides information useful to developers working on confluent-kafka-python.


## Build

    $ python setup.py build

If librdkafka is installed in a non-standard location provide the include and library directories with:

    $ C_INCLUDE_PATH=/path/to/include LIBRARY_PATH=/path/to/lib python setup.py ...


## Generate Documentation

Install sphinx and sphinx_rtd_theme packages:

    $ pip install sphinx sphinx_rtd_theme

Build HTML docs:

    $ make docs

or:

    $ python setup.py build_sphinx

Documentation will be generated in `docs/_build/`.


## Tests


See [tests/README.md](tests/README.md) for instructions on how to run tests.

