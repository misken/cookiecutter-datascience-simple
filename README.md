cookiecutter-datascience-simple
===============================

Cookiecutter template for "simple" datascience projects. These projects are characterized by the following:

* primarily for single developer
* its conda virtual environment is based on some existing activated environment
* most analysis done in notebooks
* may be some Python code in `.py` files
* want easy importing of user created Python code into notebooks without install
* no intention of creating distributable package
* no automated testing (e.g. pytest)
* simple folder structure
* basic documentation is initialized with a markdown file

This cookiecutter was developed for use in teaching a Python based analytics course 
that includes some basic software engineering content. One of the first topics we
talk about is project structure and I wanted a very simple cookiecutter to use
for quickly setting up a reasonable project folder structure.

More complex cookiecutters will
be developed and used for use in the course as well when talking about, say, creating
deployable Python packages. 

The [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) package is already installed in the conda virtual environment we are using in class. See the installation instructions if you need to install it in some other virtual environment.

Usage
-----
To start a new project from this cookiecutter, first activate your desired conda environment. Then, do the following from the directory into which a new project directory is to be created:

```bash
cookiecutter gh:misken/cookiecutter-datascience-simple
``` 

Then what?
-----------

Navigate into your newly created project directory and read the README in there.
Do those things and then get to work.


