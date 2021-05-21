---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: content
title: data-science-setup-for-windows
---

## Data Science Setup for Mac OS X
Data Science requires a few tools to help us discover interesting features in our data. We will primarily use two tools and several libraries within each of these tools. The two tools are:

* **python**, a simple programming language *(this allows for the computer to do the work for us)*
* **git**, a distributed version control system/repository tool *(this runs technology behind “github”)*

All of these tools are free (and open-source), so it just takes a few minutes for you to install them to get started!

<hr/>

## Installing python
You will need Python 3.6 (or later). We will first check if you have Python already (if you have done Data Science) and install it if you don’t already have it.

### Checking for existing Python
1. Open up your <a href="{{ site.baseurl }}/resources/cli.html">command prompt</a>

2. Type `python --version` and press **Enter**.

* If you see `Python 3.7.1` (or similar), you are all set – no need to install Python. *(Skip to the git section.)*

* If you see `'python' is not recognized as an internal or external command, operable program or batch file.`, install it now:

### Installing Python
1. Visit <a href="https://conda.io/miniconda.html" target="_blank">https://conda.io/miniconda.html</a> to get Miniconda, a light-weight version of the python programming language

2. Download the latest Mac OS X, **64-bit bash** installer for the latest version of Python (eg: 3.7).

3. Open up your <a href="{{ site.baseurl }}/resources/cli.html">command prompt</a> and run the script you downloaded by running the following:
    * `cd Downloads`
    * `bash Miniconda3-latest-MacOSX-x86_64.sh`

You will need to press `q` to exit the license screen and all default options are fine.
1. Restart your terminal

<hr/>

## Installing git
Any modern version of git works. We will first check if you have git and install it if you don’t already have it.

### Checking for git
1. Open up your <a href="{{ site.baseurl }}/resources/cli.html">command prompt</a>

2. Type `git --version` and press **Enter**.

* If you see `git version ...` (or similar), you are all set – no need to install git! *(You’re done!)*

* If OS X gives a popup about installing git, click “Install” (or similar option) to Install git directly from Apple

### Non-Apple Install
**Only if** typing `git` provides no version and no popup, you can install git by downloading it from the Internet:
1. Visit <a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a> to get git, a distributed version control system/repository tool

2. Download and install the latest Mac OS X installer. You may need to Ctrl+Click to install it.

3. After the install finishes, verify it installed by following the steps above.

*Modified from <a href="http://courses.las.illinois.edu/spring2020/stat107/resources/osx-setup/">Wade Fagen-Ulmschneider & Karle Flanagan’s STAT 107 - Fall 2019/Spring 2020 guides</a> with permission.*