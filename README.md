#ShareBnB
Share BnB is an web application to monetize and utilize front/backyard home assets which can be rented with a frictionless platform using the web app’s system of finding potential matches based on geographical proximity. By streamlining the process of viewing local neighborhood outdoor assets such as swimming pools, yard, BBQ, driveways, tennis courts etc. with a simple web application. This is an untapped resource for the host to rent his outdoor facilities which can be monetized when not in use. Similar to AirBnb of collaborative consumption and sharing app but for the outside the home instead of inside.  Host offer experiences and use of outdoor facilities instead of accommodation to guests by using  a variety of filters types, dates, location and price. Before booking users must provide a valid name, email address and contact information. 

*ScreenShot*
![alt text](public/images/readme.png "ShareBnb a ")



## Prerequisites ##
1. Run npm init
2. Configure the config.json file with your database details with your own mysql database.
3. Remove the git repository from this project with rm -rf .git
4. Initialize your own git repo with git init
5. Connect your local git repo to your remote git repo with git remote add origin your-github-repo-ssh-key-goes-here
6. Configure the package.json with your own information.
7. Run the server with npm start or node server.js.
8. Navigate to localhost:3000

## Need to know ##
1. The public folder contains all public assets such as client side javascript files, css, and images.
2. The controller folder contains all server side controllers and routes. Api and html routes and separated into separate files.
3. home.js and testApi.js are files which contain functions which we will use as callbacks in our routes files.
4. We have a partial folder in our views folder for any partial templates.

## Sequelize
Our database is a global object. No need to require and export the the instance of our Sequelize connection (db). Access any of your models from anywhere in your project like so:

db.User.create({ name: username, password: password });


Give examples
Installing
A step by step series of examples that tell you how to get a development env running

Say what the step will be

Give the example
And repeat

until finished
End with an example of getting some data out of the system or using it for a little demo


Give an example
Deployment
Add additional notes about how to deploy this on a live system

##Built With
•	HTML/CSS
•	Boostrap
•	Javascript
•	Jquery
•	SQL
•	AJAX
•	Google Geocode API
•	Google Maps API
•	GitHUB
•	Node and Express Web Server
•	MySQL Database with a Sequelize ORM
•	Heroku
•	Google 0Auth 3.0




##Authors
Mike White- Lead Developer
Nicholas Chan - Developer
Rishi Mehta- PM/Developer
Elmalick Ndiaye- Researcher/Developer

##Acknowledgments
Our badass teacher and TA's 












