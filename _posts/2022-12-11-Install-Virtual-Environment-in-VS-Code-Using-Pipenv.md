---
title: "Install-Virtual-Environment-in-VS-Code-Using-Pipenv"
date: 2022-12-11
---
# Install Virtual Environment in VS Code Using Pipenv
Create a directory in your project named .venv. Be sure the directory is empty. This directory must exist in order for pipenv to install into it. Otherwise the virtual environment will be installed in the global location.
```
cd C:\\your_project
py -m pipenv install --ignore-pipfile

-- OR --

py -m pipenv shell
```

When prompted to point VS Code to the virtual environment, do so.

It's a good idea to close and reopen VS Code. It will now point to the virtual environment by default. You can verify VS Code is pointing to the virtual environment by opening a terminal window in VS Code and confirming the prompt is prefixed with the name of your project.

# Install packages
```
cd C:\\your_project
pipenv install pandas
```
