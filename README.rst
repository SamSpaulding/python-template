Python template
=========================

This project is based on a best-practices template Python project which integrates several different tools. It saves you work by setting up a number of things, including documentation, code checking, and unit testing.

* Sphinx for documentation
* Pylint for style checking
* Pytest for unit testing

If you are new to Python or new to creating Python projects, see Kenneth Reitz's `Hitchhiker's Guide to Python`_ for an explanation of some of the tools used here.

- [Sphinx](http://sphinx-doc.org/)
- [pytest](http://pytest.org/latest/)
- [pylink](http://pylint.org/)
- [Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/)

##Tasks

#### Install the project's development and runtime requirements

`make install` will use pip to install the packages in **requirements.txt**

`make test` will run the unit tests

`make lint` will run pylint over the *.py files in `GameController/` You can add other files to the linter by editing the Makefile
