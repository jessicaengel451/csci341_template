# csci341_template

# Template for CSCI 341

Creating and using this repositiory is by no means necessary. I just almost lost all my files  :/ and I figured some students may want to back up their files also.

# IMPORTANT
- [Make sure you repo is PRIVATE online!](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility)
- Github will require you to have an ssh key or a personal access token. Tokens in my opinion are easier to [setup](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) and [use](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
# Cloning and using this repo
To create a local copy of this repo, use git clone where ever you would like the main folder to be created. Preferably in a folder you create:

```git clone https://github.com/jessicaengel451/341.git```

You then should have all the files that are a part of this repo. To add your assignments, drag them into you file explorer, finder, or whatever your operating system uses. Then use

```git add .``` // Adds all files in your current directory to the git repository
```git commit -m "INSERT WHATEVER MESSAGE YOU WANT :)"``` //says that you actually want to add them to the online repo.
```git push``` // adds them to the online repo

Also helpful:
```git status``` // will show you what is being modified to the repo at any given time
# Heirarchy
There are currently 5 folders in this repo:
- autograder
- homework
- labs
- weekly response
- examples (can have whatever you want. Mine has a hello world script from online that I wanted to run in RARS)

and 2 files:
- A .gitignore lets git know which files should **NOT** go into the repo.
The gitignore currently has the default C .gitignore and [two other modifications](https://github.com/jessicaengel451/csci341_template/blob/656b49cbb642101a809c8d1c16ea89b7aa20007c/.gitignore).
- A resource made by me consisting of references we were given by instructors


