# Reminders task 

Your task is to get this sample running and extend it with one more section - “Reminders”. 
This section should have a list of reminders which user has entered as well as a way for 
users to add new reminders. When user wants to add a new reminder he/she should be able 
to enter a title for the reminder (e.g. Pick up groceries), more detailed description of 
the reminder (e.g. groceries are to be picked up at Coles in KX) as well as the due date 
(e.g. 17/07/2017). The user has to be able to save the reminder. 

## Build

Assuming you have installed node.js, git, bower and polymer-cli, check out the code from
https://github.com/ajambrovic/reminderpolymer and run 

    bower install
    polymer serve

## Implemented functionalities

* Add Reminder
* Edit Reminder
* Delete Reminder
* Persistence through Local Storage


## Further development

Possible upgrades of the application could include implementing:

* Persistence through a RESTfull interface
* User input validation
* Application optimization (resource minification, Polymer build optimization etc.)
* Adding a time component
* Adding a more robust ID generating functionality (currently id's are Strings made from title)
* Fixing the Datepicker component on mobile (it's an[open issue](https://github.com/bendavis78/paper-date-picker/issues/120#issuecomment-239686154)) or switching to another one
* Analyze date handling, I believe there could be a simpler implementation than the current one
* Switch to an interface when doing operations on the reminder instead of accessing localhost 
directly (this is a prerequisite for a simpler switch to a backend)