# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* This repository contains a map of public housing, tax credits and opportunities, using source materials from the University of Maryland's National Center for Smart Growth Research & Education. 

### Development history ###

A gist with early development history lives (for now) at https://gist.github.com/borpglass/f6c9c651c9cc7e28c4f1  ... but will be going away after deployment. 

### Todo list ###

* x Get formatting working on main map
* x Test column formatting below that
* x Add bottom maps
* x In Arc, update info windows to always show type of record
* x In Arc, size down the gray boxes to match the size of the black boxes.
* x Fix scrolling bug on large screens.
* x Set up small width-selected snippet to collapse columns, make big map full-width
* x Change extent for Arundel
* x Change the other extents to match surrounding counties. Use comment tags to keep page relatively fast
* x Consider switching small maps to static images - load times are getting pretty laggy
* x Add BSMG branding on top
* x Add main chatter 
* x Add quick bits of chatter over individual maps
* x Add general credit text to the bottom, with a link out to the ESRI version of the map
* x Move from gist to bitbucket and update documentation
* x Start doing all your dev/testing on your mac rather than the server. This will allow scss compilations
* x Extract css into its own file
* Get css into scss form using css2sass.herokuapp.com to practice good habits. (Actually, no need; just add a couple variables.)
* Update sample push cycle to include scss compilation
* Small maps miss some dots. Take screenshots of close-in views, then overlay for better size/thoroughness
* - Arundel
* - Carroll
* - Harford 
* - Howard
* Do remaining items on Adam's list
* Hand-code a legend - make it hot-swappable with arrow instructions, since you did not discuss this with Adam.
* Talk with the team on Monday about where we stand
* Iterate with even better static images (preferably gif or png versions of a larger image, scaled down)
* If time allows, consider trying to link each static image to js that reloads the large map at the appropriate extent
* Integrate headline fetcher
* User testing
* Delete development notes 
* Create storylink
* Make ESRI map public
* Deploy
* Get a MarkDown syntax module for your local text editor, since it currently freaks every time you type a quote in a README.md

### Contribution guidelines ###

The general deployment pattern for this repository is as follow: Make all changes (including compilations of scss) on local workstation; test on local workstation; push to bitbucket; clone to server. A sample push cycle on a local worksation after edits: 

cd housing-map

sass style.scss style.css

git add *

git commit -m 'Sundries'

git push -u origin master

... and a sample pull cycle on the server: 

cd housing-map

git pull origin master

### Who do I talk to? ###

Patrick Maynard is running development on this project.
