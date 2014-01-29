Azure Mobile Services and Android
=================================

Azure Mobile services allows for a quick and easy way to get a RESTful backend staged up.
This code example shows how to create a simple Todo application and persist the data to 
Azure.

Azure Mobile Services Backend
=============================
The backend is quite easy to set up and in the end looks like this:

![Screenshot](/res/images/ams.PNG)


Android App
============
Here is what the app looks  like:

![Screenshot](/res/images/app.PNG)


Todo
=====
* Refactor using android annotations http://androidannotations.org/ , looks to be the best framework for creating clean maintainable code for android.
* Put the data access layer into a Datacontext package
* Put the POJO models into a Models package
* Separate the view model logic out
* Research async callbacks
