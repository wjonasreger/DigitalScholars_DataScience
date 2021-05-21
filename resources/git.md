---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: content
title: setting-up-git
---

## Setting Up git for Data Science
To set up git, there are certain commands you will run:

1. Once for the entire semester (“Course Setup”),
2. Once for each computer you use (“Computer Setup”),
3. Once each time you work on Data Science assignments (“Assignment Setup”)

<hr/>

## Course Setup
To begin to work on assignments and turn in work, you will need to create a git repository for the course.

* Follow the link below to create your repository. You **DO NOT** need to go to the link given to you, you will use that link later in Step 3.
* Visit: <a href="" target="_blank">https://edu.cs.illinois.edu/create-ghe-repo/stat107-sp20/</a>

<hr/>

## Computer Setup
1. On your computer, go to **your Desktop** (you may need to minimize some windows) and create a `datascience` folder on your Desktop

2. Now, going back and **using your command line**, run the following commands to navigate into your `datascience` folder:
    * `cd Desktop`
    * `cd datascience`

3. **Clone** a local copy of your git repository with the following command (making sure to replace `YOUR-GIT-REPO-URL` with the URL from the “Course Setup” above):
    * `git clone YOUR-GIT-REPO-URL`

4. Navigate into your git directory by going into your NetID-named folder:
    * `cd NETID`

5. Set up a connection to the `_release` repository where code will be released for you:
    * If the command worked, nothing will show up when you run this command. *(No output means no error! :))*
    * If you are not sure, you can run it again and it will say that “the remote already exists”.
        * `git remote add release https://github-dev.cs.illinois.edu/stat107-sp20/_release.git`

6. Let git know who you are **REPLACE YOUR NAME and EMAIL with your name/email**:
    * `git config user.name "Your Name"`
    * `git config user.email "netid@illinois.edu"`

### Common Setup Errors

#### Windows 10 - “Invalid Credentials”
If you are using Windows 10 and getting “invalid credentials”:

1. In your Start menu, type “Credential Manager” and run it.
2. Inside of the credential manager, click “Windows Credentials”
3. Under “Generic Credentials”, find **github-dev.cs.illinois.edu** and edit your password.

<hr/>

## Assignment Setup
Each assignment will provide specific instructions on how to use git to fetch and submit your work.

*Modified from <a href="http://courses.las.illinois.edu/spring2020/stat107/resources/git/">Wade Fagen-Ulmschneider & Karle Flanagan’s STAT 107 - Fall 2019/Spring 2020 guides</a> with permission.*