# How Can I Contribute?

Don't know how to start of open source and Contribute to our Open Source Project ? Welcome to the world of hacking!

The steps to follow to contribute to any projects:

1.  ## Install git
     
    If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

2.  ## Fork this repository

    Fork this repository by clicking on the fork button on the top of this page.
    This will create a copy of this repository in your account.

3.  ## Clone the repository

    Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

    Open a terminal and run the following git command:

    ```
    git clone "url you just copied"
    ```

4.  ### Add a upstream link to main branch in your cloned repo
    ```
    git remote add upstream <original repository>
    ```
5.  ### Keep your cloned repo upto date by pulling from upstream
    This will also avoid any merge conflicts while committing new changes
    ```
    git pull upstream main
    ```
6.  ### Create your feature branch
    Always create new branch
    ```
    git checkout -b <feature-name>
    ```
7.  ### Track your changes
    ```
    git add .
    ```
8.  ### Check for your changes.
    ```
    git status
    ```
9.  ### Commit all the changes
    Write commit message as "Small Message"
    ```
    git commit -m "Write a meaningfull but small commit message"
    ```
10. ### Push the changes for review
    ```
    git push origin <branch-name>
    ```
11. ### Create a PR on Github.
        Just hit the create a pull request button, you must write a PR message to clarify why and what are you contributing
    <hr>
