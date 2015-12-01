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
* x Get css into scss form using css2sass.herokuapp.com to practice good habits. 
  (Actually, no need; just add a couple variables.)
* x Update sample push cycle to include scss compilation
* Small maps miss some dots. Take screenshots of close-in views, then overlay for better size/thoroughness
* x Arundel
* x Carroll
* x Harford 
* x Howard
* x I'm using a ___-point stroke to size up dots. Yellow stroke color: #dace32 ... Black stroke color: #151514 ... each stroke at 80% opacity on the outside.
* x Push to server again. 
* Do remaining items on Adam's list
*  x Put the main head/chatter in our site (serif) styles, then put everything below that in Lato.
*  x Change "chevrons" to "arrows"
*  x Add "map may take a moment to load."
*  x Slightly more leading in the chatter
*  x Make "to view legend ... " italic
*  x Simplify popups - lose labels (per example in email)
*  x On legend, move "public housing" above "tax credits-elderly"
*  x More leading in the chatter here as well. Can probably be same as above. 
*  x Add some padding above the source and make it italic
*  x Add a credit line for yourself
*  x Add a mention of the fact that the small, static maps are not to scale 
*  x Fix fonts for uniform display
*  x See additional notes in email on things to fix on blocks at various sizes 
* Convert the "black and yellow dots" to "black, brown and yellow dots" per notes in your planner
* Remove the base map entirely so as to avoid giving too much location information about individual houses
* Add a Baltimore County breakout map
* Redo the other flat maps to reflect the new color scheme. 
  (This should be fairly quick, since our county shapes remain the same.)
* Add new chatter from our reporter
* Switch to other mapping project, assuming it is Tuesday. If not, keep moving on these TODOs.
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
* Set up scss syntax highlighting as well for similar reasons

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
