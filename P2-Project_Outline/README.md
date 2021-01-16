# Project Outline

## Overview
This is a mobile app to loudly remind forgetful folks to do something if they start to leave the bounds of a location.
 
Imagine you borrowed a crockpot from your parent.  Everytime you visit them, you forget to grab the crockpot on your way out of the house. If you knew you were visiting them later today you can use this app to *quickly* remind yourself to grab the crockpot. If you leave the house without grabbing it, an alarm with a notification message will sound. 

## Features
### Initial basic feature goals:
 - **Leave alert:** Users will be able to create an alert for leaving their current location.
 - **Alarm:** The app will play a loud alarm and display a notificaiton when leaving a location
 - **Cancel alarm:** Users will be able to cancel the "leave alert" to avoid an alarm going off
 - **Background running:** App will stay open in the background with notification until user uses an exit app button or slider

### Future app expansion if there is time:
 - Add location via address or map
 - Manage task lists for various locations (or wifi connections)
 - Custom radius distance User will be able to adjust how far location to remind them 
 - Allow configuring whether an alarm, notification, or both is played
 - Record voice alarms to play for better driving safety and convenience
 - Integrate into Google assistant with key phrase "before I leave..."

## Technologies
 - [Dart language](https://dart.dev/)
 - [Flutter framework](https://flutter.dev/)
 - [SQLite](https://pub.dev/packages/sqflite) or [Hive](https://pub.dev/packages/hive) database
 - *Possibly* [Google Maps API](https://developers.google.com/maps/documentation/)
 - *Possibly* Wifi Hotspot recognition: Would reduce GPS sensor and battery usage but would be less flexible

## What I'll Have to Learn
 - **Utilizing Map provider API:** Completely new to this outside of configuring wordpress plugins with API keys.
 - **Dart & Flutter:** I'm half way through self-paced course, have basic functional knowledge currently.
 - **Hive Db or other local persistence options in flutter:** Already pretty familiar with SQlite but it's looking like hive is very popular for dart apps.
 - **Agile development:** I utilize the instructional design (training development) equivalent called SAM at my day job, but will want to learn to use Agile to prototype and improve my app throughout the course.
 - **Dart unit testing:** 

## Project Tracker
https://trello.com/invite/b/RiYZaWOH/0c400155c0ce35eca06729d571216a0b/ike-ah-loe-liftoff-project-board
