#  Install Poetry:
$ pip3 install poetry

# Check version of Poetry:
$ poetry --version

# Poetry help and list all commands:
$ poetry --help
$ poetry list

# Create a new project
$ poetry new {name}
$ poetry new env_lesson_17

# Init a project (you can make it without creating a new environment in case you already have a project)
$ poetry init 

# Create a new virtual env
$ poetry shell

# Add new library to project
$ poetry add selene==2.0.0rc2


# Change config (for example set up virtualenvs.in-project AS true)
$ poetry config virtualenvs.in-project true


# Install all dependencies from toml file
$ poetry install


# Add to dev dependencies
$ poetry add --group=dev flake8


# STEPS HOW TO BEGIN
$ poetry new env_lesson_17
$ 

# Work with env
$ poetry env list
$ poetry env remove --all