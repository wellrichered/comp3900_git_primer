

# Git Primer

### Due Week 3 Lab Time

This is an individual exercise.

## Background

This course requires the use of Github as source control for your project. Every project **must** use Github and you will be graded throughout the term on your use of Git and Github. Consequently, you are required to complete this exercise to ensure you understand how to

(1) Use Git to clone, pull, push, commit, checkout
(2) Use Github to submit a pull request

This exercise is worth 2% of your course grade.

## Running the application

```
repository/
├── app.py
├── templates/
│   ├── index.html
│   └── calculator.html
```

To run this application use `python3 main.py`. You will need to first install `Python` which can be done online at https://www.python.org/downloads/ and you will need to install any necessary dependencies such as Flask using `pip install Flask` on the commandline after installing Python. **You are not required to actually run the application** when you show your tutor. You will simply need to show your tutor your Github commit history and open pull request.

## Exercises

There are some bugs in this code and features we need to add. To make sure you have correctly installed Flask and cloned this repo, when you run the application and open the link in your browser (http://127.0.0.1:5000/) you should see a welcome page that says "Welcome to COMP3900".

Setting up the repo
* You will be cloning my repo but working on your own. To do this, you must first setup your own personal Github account and create a **PRIVATE** repo called `comp3900_git_primer`. Please **do not fork this repo**.
* Next, clone this repo (the one we are currently in NOT your private one) and then `cd 24t3_comp3900_git_primer` to go into the repo.
* We are going to transfer this to your Github repo. To do this, use the command `git remote set-url origin git@github.com:GITHUB_USERNAME/REPO_NAME.git` replacing `GITHUB_USERNAME` and `REPO_NAME` with the ones for the repo you created.
* Now run `git push` and you can get started with the exercise.

