# Open-Event
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fossasia/open-event?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The FOSSASIA Open Event Project aims to make it easier for events, conferences, tech summits (maybe more types in future) to easily create Web and Mobile (only Android right now) micro Apps. The project comprises of a data schema for easily storing event details, a server and web frontend that are used to view, modify, update this data easily by the event organisers, a mobile-friendly webapp client to show the event data to attendees, an Android app template which will be used to generate specific apps for each event.   

Each specific component's source code has it's own Github Repo, links provided in the subsections below . This repository is for tracking milestones and issues, and maintaining a wiki about the project. Also, documentation about the JSON Schema, and how to use the template will be hosted on this repo.

### Communication
Please join our mailing list to discuss questions regarding the project: https://groups.google.com/forum/#!forum/open-event

Our chat channel is here: https://gitter.im/fossasia/open-event

### RoadMaps and Documentation

Please see the [GSOC 2015](docs/GSOC2015) and [GSOC 2016](docs/GSOC2016) for documentations and roadmaps and feature descriptions from GSOC 2015 and GSOC 2016 period. 

## Projects

### Open-Event Organiser Server
[Github Repo](https://github.com/fossasia/open-event-orga-server)   
The server which will manage all the data of the event. Backed by a database, it provides API endpoints to fetch the data, and also to modify/update it.    

### Open-Event WebApp
[Github Repo](https://github.com/fossasia/open-event-webapp)   
A mobile-friendly webapp, which shows all information about the event like Sessions, Speakers, Map of location, Sponsors etc. The idea is to make a ready-to-port webapp, that can be wrapped into iOS, Windows, Chrome etc apps - ie. those platforms we are not immediately supporting natively.    

### Open-Event Android App
[Github Repo](https://github.com/fossasia/open-event-android)   
A native Android app template which shows all information about the event like Sessions, Speakers, Map of location, Sponsors etc. Each event needs to make a copy of this template, change only a handful of basic stuff like icon, package name, backend URL, and generate a unique app for their own event. The idea is the create a template from which anyone can generate an app in 10 minutes, without having any knowledge of Android development.    


## Developers and Contributors
### GSOC 2015
 * **Arnav Gupta**   
 * **Manan Wason**     
 * **Rafal Kowalski**   

This project initially started as part of a GSoC 2015 initiative, under the mentorship of **Mario Behling, Duke Leto, Abhishek Batra, Mohit Kanwal** and others.  

### GSOC 2016

#### Students
 - Aayush Arora
 - Aditya Vyas
 - Arnav Gupta
 - Avi Aryan
 - Harshit Dwivedi
 - Manan Wason
 - Niranjan Rajendran
 - Rafal Kowalski
 - Saptak Sengupta
 - Shivam Mamgain

#### Mentors
 - Mario Behling
 - Duke Leto
 - Justin Lee
 - Abhishek Batra
 - Aruna Herath
 - Oren Golan
