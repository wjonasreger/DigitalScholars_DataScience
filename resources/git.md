---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: content
title: setting-up-git
---

## Setting Up git for Data Science
**Warning:** Using Git/GitHub is optional due to the challenge it may present to students during an intense 5-week course. If a student has experience using Git/GitHub or Command Line tasks then they may attempt to use it. For students who do not have any previous experience using these tools I would recommend not worrying about Git/GitHub since it is not an important tool to use for this class.

To set up git, there are certain commands you will run:

1. Once for the entire semester (“GitHub Repository Setup”),
2. Once for each computer you use (“Computer Setup”),
3. Once each time you work on Data Science assignments (“Assignment Setup”)

<hr/>

## GitHub Repository Setup
To begin to work on assignments and turn in work, you will need to create a git repository for the course.

* Create a new repository in your GitHub account and give it a name with your first name initial, full last name, and "discover". E.g. `wreger-discover`
* Make the repository private and then add Jonas as a collaborator. His GitHub username is `wjonasreger`.

<hr/>

## Computer Setup
1. On your computer, go to **your Desktop** (you may need to minimize some windows) and create a `datascience` folder on your Desktop

2. Now, going back and **using your command line**, run the following commands to navigate into your `datascience` folder:
    * `cd Desktop`
    * `cd datascience`

3. **Clone** a local copy of your git repository with the following command (making sure to replace `YOUR-GIT-REPO-URL` with the URL from the “Course Setup” above):
    * `git clone YOUR-GIT-REPO-URL`

4. Navigate into your git directory by going into your NetID-named folder:
    * `cd YOUR-REPOSITORY-NAME`

5. Let git know who you are **REPLACE YOUR NAME and EMAIL with your name/email**:
    * `git config user.name "Your Name"`
    * `git config user.email "netid@illinois.edu"`

### Setup Errors

* If you experience errors that you can't resolve during these steps, please visit Jonas during his office hours on Thursdays from 2-4 pm CDT.

<hr/>

## Assignment Setup
If a student opts to submit their work via GitHub, then their repository must be private and Jonas added as a collaborator. Each lab assignment would be pushed to the same repository as a new file.

*Modified from <a href="http://courses.las.illinois.edu/spring2020/stat107/resources/git/">Wade Fagen-Ulmschneider & Karle Flanagan’s STAT 107 - Fall 2019/Spring 2020 guides</a> with permission.*
