---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: content
title: command-line-interface
---

## Command Line Interface
If you think about how you usually use a computer, you probably navigate to a file by clicking on directories and open a program or file by double clicking on them. When you are programming a computer, you often need to run programs and send them options, called arguments, which is nearly impossible to do with only a click.

Because of this, every operating system contains a Command Line Interface (CLI) that lets you interact with your computer using a keyboard. You can do everything you already do on a computer via the command line, but you can also do a whole lot more!

### Windows: Opening your command line
1. Press [Windows Key] to bring up the “Windows menu”
2. Type: `Anaconda Prompt` (If `Anaconda Prompt` is not found you will need to <a href="" target="_blank">install Python</a>.)
3. Press [Enter]
4. A black box titled “Anaconda Prompt” will open

### Mac OS X: Opening your command line
1. Press [Command]+[Space] to open Spotlight, or open up Spotlight or App Launcher
2. Type: `Terminal`
3. Press [Enter]
4. A white box titled “Terminal” will open

<hr/>

## Command prompt
Both command line tools start every line with a prompt that shows the current working directory of the command line tool. By default, both Windows and Mac starts you off in the base folder for your user account. The syntax varies only slightly between the two (assuming a user named Tamun), so the initial prompt should be one of the following:

* Windows: `C:\Users\Tamun\>`
* OS X: `Tamun-MacBook-Pro:~ Tamun$`

### Current working directory
When using the command line, you are always “inside” of one specific folder (much like when you double-click a folder you see the contents of everything in that folder and only that folder). The current folder that your command line tool is in is referred to as the current working directory.

In Data Science, we recommend that you **work within a directory called `datascience` on your desktop**. In order to navigate to that directory, we need to first navigate to your Desktop and then navigate to the `datascience` directory. Both of these things can be done with the cd command (cd for “change directory”):

* `cd Desktop`
* `cd datascience`

You can visually verify that you are now in your Data Science directory by looking at the prompt:

* Windows: `C:\Users\Jonas\Desktop\datascience>`
* OS X: `Jonas-MacBook-Pro:~ datascience$`

### Useful Command: Listing Files
When using a command line tool, you often want to know what files are in your current working directory. To list all files in the current directory:

* Windows: `dir`
* OS X: `ls`

### Useful Command: Moving Up a Directory
In addition to moving “forward” or “deeper” into your directories, the special `cd ..` will change your directory “up” one directory.

* Moves into `datascience` from your Desktop (one level deeper): cd `datascience`
* Moves back to your Desktop from `datascience` (one level shallower): `cd ..`