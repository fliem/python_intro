# Introduction to Python


## Install
We are going to use the anaconda python distribution and the VS Code IDE. These need to be installed separately.

### Anaconda
The Anaconda Python distribution is the most convenient way
to install python.
The installation is free and you don't need to register (you are asked
for to register during the installation, but this is optional).


* got to the [Anaconda Download page](https://www.anaconda.com/products/individual#Downloads)
* select your operating system
* download the latest installer for python 3.x (e.g., 3.8, Graphical Installer recommended)
* install with default options (If asked select: "Install for me only")
* There is the suggestion to install PyCharm. You can skip this.


Optional but recommended: test your installation now:

* In Windows: open the Anaconda Prompt (a program that has been
installed just now)
* In Mac/Linux: open the Terminal (Terminal.app)

Type the following into the prompt and hit enter:
```
python -c "import sys;print(sys.executable)"
```

This should print the path to anaconda's python executable, something like this on Mac:
```
/Users/your_username/opt/anaconda3/bin/python
```
or this on Windows:
```
C:\Users\your_username\anaconda3\python.exe
```

### VS Code
Visual Studio Code (VS Code) is an IDE (integrated development environment) that we are going to use for writing and
executing code.

1. Install [VS Code](https://code.visualstudio.com)
1. Install the [Python extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
(open the site and click on the 'install' button)
