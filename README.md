# python_workshop
python basics workshop

## The Zen of Python
  `>>> import this`

  ```
  Beautiful is better than ugly.  
  Explicit is better than implicit.  
  Simple is better than complex.  
  Complex is better than complicated.  
  Flat is better than nested.  
  Sparse is better than dense.  
  Readability counts.  
  Special cases aren't special enough to break the rules.  
  Although practicality beats purity.  
  Errors should never pass silently.  
  Unless explicitly silenced.  
  In the face of ambiguity, refuse the temptation to guess.  
  There should be one-- and preferably only one --obvious way to do it.  
  Although that way may not be obvious at first unless you're Dutch.  
  Now is better than never.  
  Although never is often better than *right* now.  
  If the implementation is hard to explain, it's a bad idea.  
  If the implementation is easy to explain, it may be a good idea.  
  Namespaces are one honking great idea -- let's do more of those!
  ```

## Setup
  ### Installing python
**workshop will use python 3.8.1**
    
Go to [python.org](https://www.python.org/downloads/release/python-381/) and download the latest version . ( If you happen to have python already installed, I'd recommend sticking to one version since having more can often cause problems when installing external packages as every python version has a different folder it installs packages into. ) On the first step of the installation proccess make sure the 'Add Python X.X to PATH' checkbox is ticked to ensure the python cli will work. This will install 3 important things:

`python` - the python executable  
`py` - the python launcher, useful when using 2 or more versions of python ( similar to dnvm, nvm )  
`pip` - pythons package manager ( similar to nuget, npm )  
    
After the installation make sure everything is correct by running 'py --version' and 'pip --version'. If you see an error, it's most likely related to your environment variables.

  ### IDE
**workshop will use Visual Studio Code**

There are 2 popular choices:
1. [PyCharm](https://www.jetbrains.com/pycharm/)
2. [Visual Studio Code](https://code.visualstudio.com/) with the [ms-python.python](https://github.com/Microsoft/vscode-python) extension  

## Syntax
  ### Naming convention
  Preffered: 
  ```
  my_variable = 5
  
  MY_CONSTANT = 5

  class MyClass()...
  ```
  
  ### Comments
  ```
  # single line comment
  
  '''
  Multiline
  comment
  '''  
  ```

  ### Documentation
  Python will know a string is meant to be documentation if it's the first thing in the function block.

  ```
  def my_function(x:int):
      '''This is my custom documentation
      it can be multiline'''
      
      return x*2
  
  ```

You can dynamically access these docstrings by reading the __doc__ property on any function, or calling the pydoc.help method with the function you want to see the docstring of.

  ### Comprehensions
  Python allows us

## Modules and packages
  ### Python standard library
  Python comes, as some say, with 'batteries included' meaning it has many built in modules that provide system functionality and standartized solutions for many everyday problems. Many of these packages are abstracted enough from the underlying system such that you won't have to worry about OS specific problems. A full list
  can be found [here](https://docs.python.org/3/library/).

## OOP
  ### Public, private & protected
  ```
  public_variable = 5
  _private_variable = 5
  __protected_variable = 5
  ```

## Resources
### 1. [Dive into Python 3](https://diveintopython3.problemsolving.io/)
### 2. [Python PEPs](https://www.python.org/dev/peps/)
### 3. [Softuni Python course by Ivan Vankov & Boris Chervenkov](https://softuni.bg/trainings/1281/python-programming-january-2016)
