cloudspokes-meteor-projectstatus
================================

My first Cloudspokes challenge submission: 
"First Time Submitter - January 2013"
(http://www.cloudspokes.com/challenges/2000).
This app keeps track of multiple Project statuses in the cloud. Users can edit the Project items and others viewing the page see the updates in realtime.
NOTE: In its current form, this app should only be deployed on an internal network as no user authentication/security has been built in.

## Availability
A Project Status demo can be viewed at http://projectstatus.meteor.com/.  NOTE: This app is publicly available - anyone can edit the content.
Thus, this author assumes no liability for content found on this webpage.

## Installation
* Meteor.js 
	* Mac/Linux: See http://docs.meteor.com/#quickstart.
	* Windows: See http://win.meteor.com/.
* Project Status app
	* Fork the application from GitHub.
	* Change into the project's directory and then execute command "meteor".
	* Open browser and navigate to http://localhost:3000/.

## Useful Notes:
To insert Project via browser console: 
Projects.insert({Title: "3", DateCompleteOrig: "1/1/2013", DateCompleteCur: "2/1/2013", Status: "Behind", Notes: "this is a note."});

To remove all Projects via console:
Projects.remove({});