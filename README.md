# Eat-the-Burger-ORM-Example
### Practice with a scratch ORM to track burgers
* Deployed Application: (https://eatdaburger-ormapp.herokuapp.com/)

This practice application allows a user to track burgers they'd like to and have eaten. Users can add burgers, and those they want to eat show up on the left, and those that theyve 'devored' appear on the right. 

# Design Notes

This app uses a home-brewed ORM to interface with the databse and store burgers in the database. Additionally, the front-end is rendered with the use of handlebars.

## Viewing and using the website
Follow the link to the deployed application above, or 

Download the repo:

Install the node dependencies:
`npm install`
* express
* express-handlebars
* mysql

Initialize the database and seed if you'd like:
* /db/schema.sql
* /db/seeds.sql

 and then initalize the server through:
`server.js`

<!-- Here is an example of the front end:
![Mainpage Screenshot Demo](/public/assets/images/Duly_noted_ex.png) -->

<!-- ### HTML Routes
This is a single-page app
* `/` - `index.html`, or Home page

### API Routes

  * GET `/api/burgers` -  `db.json` returns saved burgers.

  * POST `/api/burgers` - new burger from the request body

  * DELETE `/api/burgers/:id` - Deletes burger with matching 'id'  -->

All website assets are contained within the repo (https://github.com/anzook/Eat-the-Burger-ORM-Example)
.env should include MYSQL_ROOT_PASS={user's mysql root password}

## Acknowledgements and Credits

Website created as an assignment for the Johns Hopkins full-stack web development bootcamp (in partnership with Trilogy Education Services).
Guidance and assistance provided by:
* Stetson Lewis (Instructor)
* Donald Hesler (TA)
* Dan Thareja (Inspiration)