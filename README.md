# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* This repository contains a map of public housing, tax credits and opportunities, using source materials from the University of Maryland's National Center for Smart Growth Research & Education. 

### Development history ###

Gist and bitbucket versions of this predated any github version. I am hoping that a frequent development workflow for future projects will be gist > private bitbucket > public github. 

### Todo list ###

* All major tasks have been completed as of launch time. See history for previous todos.

### Contribution guidelines ###

The general deployment pattern for this repository is as follows: Make all changes (including compilations of scss) on local workstation; test on local workstation; push to bitbucket; clone to server. A sample push cycle on a local worksation after edits: 

cd housing-map

sass style.scss style.css

git add *

git commit -m 'Describe your recent changes here so the team knows what you changed'

git push -u origin master

... and a sample pull cycle on the server: 

cd housing-map

git pull origin master

### Moving to github ###

I am planning to move this repository from bitbucket to github using the method here:

http://stackoverflow.com/a/26702623/3817717

### Who do I talk to? ###

Patrick Maynard is running development on this project.
