# MATH 371 - Spring 2025

## Course Resources

### Getting started with Python and Jupyter
As a file, each Jupyter notebook has the file extension `.ipynb` (short for <span style="color:blue;">IPy</span>thon <span style="color:blue;">N</span>ote<span style="color:blue;">b</span>ook). The assigned notebooks for class will be found on the course website.

Editing and running a Jupyter notebook can be done in a number of ways. Here are two ways.
1. Working in the cloud through Google's Colaboratory (Colab). 
    * If you have not used Google Colab before, then go to [Google Colab](https://colab.google/) in your web browser. When prompted where to create your first notebook, select Google Drive. After this, you may create, edit, run, and save Jupyter notebooks from your favorite folder in Google Drive.
    * If you have used Google Colab before then you may simply place the `.ipynb` file in your Google Drive -- in your favorite folder. Click on the filename to open the notebook and begin working. (Depending on your settings, you might need to right-click and tell Google Drive to "open with" Colab.)
2. Installing and running Python and Jupyter on your own computer: there is a wealth of possibilities for this; which is best for you depends on your personal preferences and operating system. In any event, you will probably want to download an IDE. (When installing an IDE you must also install Python.)
    * Visual Studio Code is a development environment that is useful for many different coding needs, not just Python. I've written instructions below for getting started with this option. (VSCode is also fairly easy to use when starting with Python and Jupyter. It is not open source, but is free for individual or "small enterprise" use.)
    * Another popular option is to install [Jupyterlab through Anaconda](https://anaconda.org/anaconda). It has been several years since I used Anaconda for writing IPython notebooks. Historically, there were a few challenges in using recent versions of Python with it &ndash; particularly on Windows for a few Python libraries.
    * A third option is [PyCharm](https://www.jetbrains.com/pycharm/) from JetBrains. I've tried this out a bit, but have a preference for VSCode. 

---

### To Install and Setup Python and Virtual Studio
* **Python.** [Download](https://www.python.org/downloads/) the latest version of Python. When the installer runs, make sure to **check "Add to Path"** before selecting "Install Now."
* **Virtual Studio Code.** [Download](https://code.visualstudio.com/) VS Code. When running the installer, use all default options.
* You might need to restart your computer after these installations. Then open VS Code.
* Open the command line (either `` Ctrl+` `` within VS Code, or open a command terminal from Windows). Then, type `py --version` and hit Enter. If Python is installed correctly, it should print out the Python version you installed (most likely, something starting with 3.13).
* Now, select Extensions from the sidebar (`` Ctrl+Shift+X ``). Some good extensions to install are: Python, Jupyter, and Pylance. Potentially, also install the LaTeX extension. 