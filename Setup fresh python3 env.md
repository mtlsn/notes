# Setup fresh python3 env

`sudo apt install python-pip3`

going to be using pipenv instead of virtualenv

`pip3 install --user pipenv`

`pip3 install jupyter ipykernel`

Ensure that jupyter-notebook is on the PATH

## Using pipenv

create and cd project directory

start shell `pipenv shell`, this will create the venv

Install packages inside venv with

`pipenv install <package>`

To make jupyter available within venv

`pipenv install ipykernel`

`python -m ipykernel install --user --name=<my-virtualenv-nam>`

start notebook with `jupyter notebook` and switch the kernel via Kernel menu