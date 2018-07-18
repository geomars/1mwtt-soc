# Week 1 - Introduction to Python

## Learning Tracks

 1. Getting Started: Installing Python on Windows, Mac
 2. Numbers
 3. Letters
 4. Variables and Assignment
 5. Mixing It Up
 6. More About Functions and Methods
 7. Flow Control
 8. Arrays and Iterators
 9. Writing Your Own Functions 
 10. Classes

## Resources

### Get Started: Installing and Configuring Python

#### A. Install Conda/Miniconda

The following native Conda/Miniconda installation steps is taken from [here](https://conda.io/docs/user-guide/install/index.html)

##### Installing on Windows

  1. Download the installer:
     * [Miniconda installer for Windows](https://conda.io/miniconda.html)
     * [Anaconda installer for Windows](https://www.anaconda.com/download/)
 
  2. Double-click the `.exe` file.
 
  3. Follow the instructions on the screen.
 
     If you are unsure about any setting, accept the defaults. You can change them later. When installation is finished, from the Start menu, open the Anaconda Prompt.

  4. [Test your installation](https://conda.io/docs/user-guide/install/test-installation.html)

##### Installing on macOS

  1. Download the installer:
     * [Miniconda installer for macOS](https://conda.io/miniconda.html)
     * [Anaconda installer for macOS](https://www.anaconda.com/download/)
     
  2. Install:
     * Miniconda—In your Terminal window, run:

           `bash Miniconda3-latest-MacOSX-x86_64.sh`

     * Anaconda—Double-click the `.pkg` file.

  3. Follow the prompts on the installer screens.
  
  4. If you are unsure about any setting, accept the defaults. You can change them later. To make the changes take effect, close and then re-open your Terminal window.
  
  5. [Test your installation](https://conda.io/docs/user-guide/install/test-installation.html)

##### Installing on Linux

  1. Download the installer:
     * [Miniconda installer for Linux](https://conda.io/miniconda.html)
     * [Anaconda installer for Linux](https://www.anaconda.com/download/)
     
  2. Install:
     * Miniconda:

          `bash Miniconda3-latest-Linux-x86_64.sh`

     * Anaconda:    
  
         `bash Anaconda-latest-Linux-x86_64.sh`

  3. Follow the prompts on the installer screens.
  
  4. If you are unsure about any setting, accept the defaults. You can change them later. To make the changes take effect, close and then re-open your Terminal window.
  
  5. [Test your installation](https://conda.io/docs/user-guide/install/test-installation.html)

#### B. Install native Python (alternative to Conda/Miniconda installation)

The following native Python installation steps is taken from [here](https://www.cc.gatech.edu/~simpkins/teaching/python-bootcamp/installing-python.html), with few adaptation.

**Step 1: Download and install the Python 3 installer**

Download the latest Python 3 installer for your operating system at https://www.python.org/downloads

Once Python is installed, you need to ensure that you can run it from the command line, that is, that the `python3` executable is on your `path`. If you run Linux, you probably don't need help with this. If you run Mac OS X it just works. If you run Windows, follow these steps:

 1. Go to the control panel, however you do that on your version of Windows.
Go to the place for "advanced system settings." There should be a button labelled "Environment Variables..." -- click on it.
 2. In the Environment Variables dialog find the Path variable under system variables (not user variables). Select it and click the Edit.. button below.
 3. In the Edit dialog box put your cursor at the beginning of the entry (DON'T ERASE ANYTHING!) and type `C:\Python34;`. The semicolon delimits directory entries in the path. Click OK.
 4. If your OS shell was open, close it and re-open it.

Note: these instructions assume that you accepted the defaults when you installed Python. If you installed Python somethere else, enter that location in place of `C:\Python34;`.

**Step 2: Checking Your Python Installation**

 1. Open a terminal, i.e., operating system (OS) command shell.
    * The Mac OS X terminal is `/Applications/Utilities/Terminal.app` in the Finder. You should drag Terminal to your dock -- you'll use it often.
    * On Windows search for and run `cmd.exe`
 2. At the command prompt type `python3 --version`. You should get a response like Python 3.4.0. Note: on Windows the Python 3 command is just python (without the 3).

#### The OS Shell Versus the Python Shell

The prompt for the OS shell typically ends with `$` on Unix, usually following the form `user@computer-name:pwd $` where `pwd` means present working directory.

The prompt for the Python shell is `>>>`, three greater-than symbols.

#### Additional Libraries

 * If you run on Mac OS X, you will need ActiveTcl as well - read [this](http://www.python.org/download/mac/tcltk/)


### Materials


#### eBooks

Note: list only contain **free** and **legal-to-share** ebooks

 1. Think Python, 2nd Edition, by Allen B. Downey, O’Reilly Media, December 2015. Available free at [greenteapress](http://greenteapress.com/wp/think-python-2e/) 
    * [PDF](http://greenteapress.com/thinkpython2/thinkpython2.pdf)
    * [HTML](http://greenteapress.com/thinkpython2/html/index.html)    
 2. Dive Into Python 3, by Mark Pilgrim, Apress 2009. Available free at [diveintopython3](http://www.diveintopython3.net/)
    * [PDF](https://github.com/downloads/diveintomark/diveintopython3/dive-into-python3.pdf)
    * [HTML](http://www.diveintopython3.net/)
 3. Python for Everybody: Exploring Data in Python 3, by Charles R. Severance, April 2016. Available free at [PY4E](https://py4e.com/book.php)
    * [PDF](http://do1.dr-chuck.com/pythonlearn/EN_us/pythonlearn.pdf)
    * [HTML](https://py4e.com/html3)
 4. The Hitchhiker's Guide to Python: Best Practices for Development 1st Edition, by Kenneth Reitz and Tanya Schlusser, O'Reilly Media, September 2016.
    * [HTML](http://docs.python-guide.org/en/latest/)
 5. Wikibooks: Python Programming
    * [PDF](https://upload.wikimedia.org/wikipedia/commons/9/91/Python_Programming.pdf)    
    

#### Videos

 * [How to Download and Install Python 3.6 on Windows 10](https://youtu.be/dX2-V2BocqQ)
 * [Install Anaconda, Jupyter Notebook, Spyder on Windows 10](https://youtu.be/Q0jGAZAdZqM)
 * [How to Install Python 3 on Mac](https://youtu.be/0hGzGdRQeak)
 * [Python Tutorial for Beginners 1: Install and Setup for Mac and Windows](https://youtu.be/YYXdXT2l-Gg)
 * [Python Programming Tutorial for the Absolute Beginner Part 1](https://youtu.be/cZT7i5IH114)
 * [Python Programming Tutorial for the Absolute Beginner Part 2](https://youtu.be/8zqEzFBloPg)
 * [Python Programming Tutorial for the Absolute Beginner Part 3](https://youtu.be/v0hhYqPB8dY)
 * [Python Programming Tutorial for the Absolute Beginner Part 4](https://youtu.be/5sMoG5AIP4A)
 * [Python Programming Tutorial for the Absolute Beginner Part 5](https://youtu.be/qPHEeRkDK6o)
 * [Python Programming Tutorial for the Absolute Beginner Part 6](https://youtu.be/Sbwh10gWPXs)
 

#### Courses

 * [Google's Python Class](https://developers.google.com/edu/python/)
 * [w3schools' Python](https://www.w3schools.com/python/default.asp)
 

#### Cloud IDE

 * [pythontutor](http://pythontutor.com/visualize.html)
