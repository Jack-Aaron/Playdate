# Playdate

### Overview

Organize events, meet-ups, sports and games with friends. Share your availability - *not* your schedule - with other users. Discover what times are shared among all particpants. Then go enjoy an activity together!

![Demo of Coding Quiz Challenge](demo.gif?raw=true)

### Development Process

This application attempts to solve a problem that is difficult to conceptualize. We had to map out the data structure in a variety of different ways until it started to make sense. To make a minimum viable product, we simplified that structure to a single day with a timeframe of hours hard-coded into the model.

Since this application as it develops will match and compare schedules across different dates, users, and activities that our users are attempting to schedule, we beleive a relational SQL database is the method of organizing user data.

Currently we have front-end JavaScript logic governing the scheduler, however, in future versions we will use more complex SQL queries to allow for more flexible and advanced scheduling capabilites.

### Technologies Used
* HTML/CSS
* Javascript ES6
* Bootstrap
* jQuery
* JSON
* [Moment.js](https://momentjs.com/)
* [Passport](https://www.npmjs.com/package/passport)
* Express.js
* MySQL
* Sequelize
* JawsDB
* Heroku

### Links
* [Application](https://project-playdate.herokuapp.com/)

### Future Improvements
* Split userbase up into groups
* Users can create their own groups
* Groups can have multiple activities
* Scale beyond one single day to any day in the future
* See list of other users in group and/or activity
* See users who have already submitted
* See users' schedules (if permitted)
* Publicize activities/groups to searches
* Users can have profiles
* Users can add other users as friends


## Meet The Team
* [Jonathan Alpart](https://github.com/Jack-Aaron/): Back-end
* [Emily Gaska](https://github.com/egaska): Front-end
