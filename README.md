[![Coverage Status](https://coveralls.io/repos/github/mirkobronzi/dl_training/badge.svg?branch=master)](https://coveralls.io/github/mirkobronzi/dl_training?branch=master)

# dl_training

Re-implementing the transformer architecture with the main goal of learning
PyTorch and best practices when working on a project.

## Install

Install all the requirements: (from the root folder)

    pip install -r requirements.txt

Test the installation: (all tests should pass)

    python -m unittest discover
    
Then setup pre-commit hooks:

    cd .git/hooks/ && ln -s .hooks/pre-commit . && cd -
