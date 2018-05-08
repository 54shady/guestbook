# guestbook

## System Requirement

virtualenv package is require

    sudo pip install virtualenv

## Project Usage

Download source

	git clone https://github.com/54shady/guestbook.git
	cd guestbook

Depoly the virtual develop enviroment

	virtualenv .venv
	source .venv/bin/activate

Makesure using the correct python

	python -c 'import sys; print sys.executable'

Install the package from source code to virtual enviroment

	(.venv)$ pip install -e .

Running the application

	(.venv)$ guestbook
	This is python project depoly example

Deactive the enviroment

	(.venv)$ deactivate

Package all files into tarball(guestbook-1.0.0.tar.gz)

	python setup.py sdist

Install package from tarball

	pip install guestbook-1.0.0.tar.gz

Update the enviroment package if the requirement is changed

	(.venv)$ virtualenv --clear .venv
	(.venv)$ pip install -e .

## List Packages

List packages installed in current enviroment using command below

	pip freeze
