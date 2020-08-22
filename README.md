# Loungewie
> React Native Mobile Application built for [Singapore Airlines AppChallenge 2020 - Singapore Student track](https://appchallenge.singaporeair.com/en/challenges/students)

This application is created to help provide a more seamless ground experience for SIA passengers. Specifically tackling the issue of manual arrangement and reservations of facilities - this application implements a queue management system for the SilverKris Lounge services. 

## How it Works
##### Click here for our [proposal deck](https://docs.google.com/presentation/d/1yRswJf0sVKfrPtqS9K4Q9lyq0gFSD6semtGMa_vpFFc/edit?usp=sharing).
##### Click here for our [video demo](https://youtu.be/mzXnCWA0fqc)

In this prototype, as an example we developed a queue for user to book shower rooms. A user will have to check into a SilverKris Lounge by scanning a barcode and can only enter if they are eligible to use the lounge services. A barcode will also be available to scan to request a shower room. If there is an empty shower room, the user will be notified and they can use it immediately. Otherwise, they will be added into a queue. With our mobile application, they can check how many people are in the queue in front of them and see when they have been allocated a shower room to use. 

This feature can be implemented for a number of different services in the future. Examples include Buggy Rides and Food Ordering Services.

## Set Up
This application is build using React Native, Django, and PostgreSQL. The back-end services and a prototype database is deployed on Heroku, while the app itself is run using Expo.io for demo purposes.
### Front-End
The codebase for the Frond-End portion of the application can be found [here](https://github.com/gabybenedicta/SIA-Hackathon-2020-FE). 
### Back-End
The codebase for the Back-End portion of the application can be found [here](https://github.com/gabybenedicta/SIA-Hackathon-2020-BE).

## Contributors
- Gabriella Benedicta Christianti
- Margaret Claire Koesno
- Stephanie Audrey Susanto
