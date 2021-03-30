cookiecutter-datascience-simple
===============================

Cookiecutter template for "simple" datascience projects. These projects are characterized by the following:

* primarily for single developer
* its conda virtual environment is based on some existing activated environment
* most analysis done in notebooks
* may be some Python code in .py files
* want easy importing of user created Python code into notebooks without install
* no intention of creating distributable package
* no automated testing (e.g. pytest)
* simple folder structure
* basic Sphinx documentation is initialized

This cookiecutter was developed for use in teaching a Python based analytics course 
that includes some basic software engineering content. One of the first topics we
talk about is project structure and I wanted a very simple cookiecutter to use
for quickly setting up a reasonable project folder structure.

More complex cookiecutters will
be developed and used for use in the course as well when talking about, say, creating
deployable Python packages. 

Usage
-----
To start a new project from this cookiecutter, first activate your desired conda environment. Then, if you haven't already, install [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) and then do the following from the directory into which a new project directory is to be created:

```bash
cookiecutter gh:misken/cookiecutter-datascience-simple
``` 

**Note:** This cookiecutter includes a conda YAML environment file called `aap.yml` that you
can use to create a conda environment containing the packages used in this class.

Documentation
--------------

We'll use Sphinx because it's powerful, widely used in Python community
and rst isn't terribly different than md for simple things. During development
of this module we'll also test out the new MyST parser which allows md files
and mixing of md with rst.

    conda install -c conda-forge myst-parser
    
> To use the MyST parser in Sphinx, simply add: extensions = ["myst_parser"] to your conf.py and all documents with the .md extension will be parsed as MyST.

Then what?
-----------

Navigate into your newly created project directory and read the README in there.
Do those things and then get to work.


