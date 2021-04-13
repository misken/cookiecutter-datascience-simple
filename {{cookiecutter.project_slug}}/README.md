# {{cookiecutter.project_name}}

Information on using this cookiecutter

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:{{cookiecutter.github_username}}/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

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


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

├── {{cookiecutter.project_name}}
	│   .gitignore					<- Common file types for git to ignore
	│   README.md					<- The top-level README for developers (you) using this project
	│   template-nb.ipynb			<- A Jupyter notebook template
	│
	├───data						<- Final and intermediate data
	│   └───raw						<- The original, immutable data dump
	│
	├───docs
	│       notes.md				<- Simple markdown template for project notes
	│
	└───output
			readme.md				<- Guidance for using this folder


Documentation
--------------

In this very simple project structure template, we've just included a markdown file with some typical
section headings to use for project notes. Expand as desired. Later in the semester we will learn how to
use Sphinx with restructuredText to write and generate documentation.



