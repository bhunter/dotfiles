dotfiles
========

Work-in-progress collection of files commonly used by me. Note this id Deveopment specific!


Linux/OS X installs of all basic tools for Python and javascript stack development. Includes installation of global packages and any config/rc files.
Assumes fresh(ish) OS install.

Emacs, git, mercurial
---------------------

	sudo apt-get install emacs git mercurial


Python-specific stuff
---------------------

Assumes Python 2.7 (not moving to 3 YET). It is possible that the Linux install does not have the Python headers or development files -a real PITA.

###Check Version

	 $ python -V

###Install development packages

	 $ sudo apt-get install build-essential python-dev libsqlite3-dev libreadline6-dev libgdbm-dev zlib1g-dev libbz2-dev sqlite3 zip 

###Install Python 3 (Optionl)

	 $ sudo apt-get install python3 python3-dev

###easy_install

To use easy_install you need setuptools -quite possibly the most annoying thing about Python ... Fortunately, its small and pretty quick to install.

   $ wget https://bitbucket.org/pypa/setuptools/raw/bootstrap/ez_setup.py
   $ python ./ez_setup.py



###VirtualEnv

	sudo easy_install virtualenv
	sudo pip install virtualenv-wrapper

Need to configure virtualenv here...