# CoviCare

🚀 Checkout the website live at : https://covicare-app.herokuapp.com/

## 💡Lessons Learned
-	First full-stack web application
-	ExpressJS
-	MongoDB database design
-	Bootstrap 4
-	Intergration with API's
<!-- -	Optimizing performance, security, and accessibility using Google Lighthouse -->
<!-- -	Integration testing with Jest
-	Code review with Codacy and CodeClimate
-	CI/CD with CircleCI
-	Creating SVG illustrations -->
-	Deploying app to Heroku and Database to MongoDB Atlas

## 🛠 Technologies
|Graphic Design|Front-End|Back-End|Database|Deployment|
|------------- | ------- | ------ | ------ | -------- |
|Inkscape	     |HTML5	   |Node.js |Mongoose|Heroku	  |
|.			       |CSS3		 |ExpressJS|MongoDB|MongoDB Atlas|
|.			       |Bootstrap 4|EJS	  |.		   |Git		    |
|.			       |Javascript|.		  |.		   |.		      |

## ⚖️ Methodology
-	[Bootstrap 4](https://getbootstrap.com/) as the CSS framework to keep the UI simple and quick to build.
-	[ExpressJS](https://expressjs.com/) as the Node.js application framework for its basic functionality. Some companies still use ExpressJS so it was important to implement it.
-	[PassportJs](https://github.com/jaredhanson/passport) for the authentication and authorization.
-	NoSQL database for the flexibility compared to a SQL database, [MongoDB](https://www.mongodb.com/) in particular because of its prevalence in the industry.


## ⚙️ Features
-	Login, sign-up, Admin role
-	REST API (create, read, update, delete) for Hospitals, comments, and reviews
-	Create routes have authentication
-	Edit, Update, and Delete routes have authentication and authorization
-	[Google Maps API](https://developers.google.com/maps/documentation)

<!-- To Do:
-	Sort campgrounds by review, distance, country, and state
-	Disallow duplicate campgrounds. I.e. no more than one unique campground
-	Not safe for work (NSFW) picture filter
-	Allow multiple photos to be uploaded
-	Write comment directly on show page
-	Write review directly on show page
-	Show 1/3, 1/2, and 2/3 of a star
-	Forgot password, change username, change password
 -->
## 🚀 Getting Started
Create an .env file and add values to the following variables:
```
GEOCODER_API_KEY=
API_KEY=
DATABASEURL=
PASSPORT_SECRET=
ADMIN_CODE=
```
In a terminal window, initialize a Mongoose Database 
```
$ ./mongod
```
In a second terminal window, display the Mongoose Database 
```
$ mongoose
```
In a third terminal window, install dependencies using npm:

```
$ npm install
```
And then run the application with
```
$ npm start
```
<!-- or
```
$ nodemon app.js
``` -->

## 📐 Tests
The integration tests using [Jest](https://jestjs.io/) test the creation of data, the functionality of the schema, and the functionality of the validation. The tests are iterated over each of the models: covicare, comments, reviews, users.
To run the tests:
```
$ npm test
```

<!-- ## 📣 Acknowledgments
-	The skeleton of this project was based on [Colt Steele's YelpCamp](https://github.com/Colt/yelp-camp-refactored) during the Web Development Bootcamp. -->

## 🔒 License
Copyright Notice and Statement: currently not offering any license. Permission only to view and download.
