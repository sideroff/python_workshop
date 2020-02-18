# python_workshop
python basics workshop

## Installing python
  Go to [python.org](https://www.python.org/downloads/release/python-381/) and download the latest version ( workshop will use 3.8.1 ). ( If you happen to have python already installed, I'd recommend sticking to one version since having more can often cause problems when installing external packages as every python version has a different folder it installs packages into. ) On the first step of the installation proccess make sure the 'Add Python X.X to PATH' checkbox is ticked to ensure the python cli will work. This will install 3 important things:
  
  `python` - the python executable
  `py` - the python launcher, useful when using 2 or more versions of python ( similar to nvm )
  `pip` - pythons package manager ( similar to nuget, npm...)

   After the installation make sure everything is correct by running 'py --version' and 'pip --version'. If you see an error, it's most likely related to your environment variables.

## Modules and packages
  ### Python standard library
  Python comes, as some say, with 'batteries included' meaning it has many built in modules that provide system functionality and standartized solutions for many everyday problems. Many of these packages are abstracted enough from the underlying system such that you won't have to worry about OS specific problems. A full list
  can be found [here](https://docs.python.org/3/library/)