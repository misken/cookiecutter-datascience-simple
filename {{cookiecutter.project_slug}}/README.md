# {{cookiecutter.project_name}}

Information on using this cookiecutter

1 Development workflows
=======================

1.1 Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:{{cookiecutter.github_username}}/cookiecutter-datascience-simple
```

1.2 git
-------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named {{cookiecutter.project_name}}, then do;

```bash
git remote add origin git@github.com:{{cookiecutter.github_username}}/{{cookiecutter.project_name}}.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


1.3 Conda Environments
----------------------

### Introduction

For **local dependency managment** (LDM), we rely on [conda](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).


### Conda Environment

If you are using the virtual machine I created, I've already created a conda virtual environment named `aap`. If you are not using the VM, you can create the conda virtual envirnoment with the **aap.yml** environment file provided. Obviously you can customize and change that file. The following command will create a new conda environment
named `aap`. If you want to rename it, use the commented out command (using either the project name from 
cookiecutter) or replace `{{cookiecutter.project_name}}` with some other name like `someothername`.

```bash
conda env create -f aap.yml
# conda env create -f aap.yml -n {{cookiecutter.project_name}}
```

### Folder Structure


### Documentation





