# SleepQualityTracker app - using Room 

## Overview

The SleepQualityTracker app is a an app that helps you collect information about your sleep. 
* Start time
* End time
* Quality
* Time slept

The following **required** functionality is completed:
* [x] User can click on stat button to start recording current system time. End button gets enabled
* [x] User clicks on end button when they are done. it takes user to sleep quality screen, where user can select sleep quality from 0-5
* [x] updates database with data and displays overview of all sleeps recorded so far on home screen
* [x] User can clear their data from database at any time. User gets to see a message upon clearing data.


## Screenshots
<p align="center">
<img src="screenshots/sleep_quality_tracker_start.png" width="256" height="455" >
<img src="screenshots/sleep_quality_tracker_stop.png" width="256" height="455" >
<img src="screenshots/sleep_quality_tracker_quality.png" width="256" height="455" >
</P>

This app demonstrates the following views and techniques:
* Room database
* DAO
* Coroutines
* Transformation map
* Data Binding in XML files
* ViewModel Factory
* Using Backing Properties to protect MutableLiveData
* Observable state LiveData variables to trigger navigation
