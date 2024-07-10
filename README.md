# Louis-Module-14-Model-View-Controller
## Description
I've been task with making a tech blog using MVC. 
Then I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in when I visit the site for the first time.
Then I am taken to the homepage when I click on the homepage option.
Then I am prompted to either sign up or sign in when I click on any other links in the navigation.
Then I am prompted to create a username and password when I choose to sign up.
Then my user credentials are saved and I am logged into the site when I click on the sign-up button.
Then I am prompted to enter my username and password when I revisit the site at a later time and choose to sign in.
Then I see navigation links for the homepage, the dashboard, and the option to log out when I am signed in to the site.
Then I am taken to the homepage and presented with existing blog posts that include the post title and the date created when I click on the homepage option in the navigation.
Then I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment when I click on an existing blog post.
Then the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created when I enter a comment and click on the submit button while signed in.
I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post when I click on the dashboard option in the navigation.
I am prompted to enter both a title and contents for my blog post when I click on the button to add a new blog post.
The title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post when I click on the button to create a new blog post.
I am able to delete or update my post and taken back to an updated dashboard when I click on one of my existing posts in the dashboard.
I am signed out of the site when I click on the logout option in the navigation.
I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts when I am idle on the site for more than a set time.
Lastly, I made sure to leave the code better than I found it.

## What's Included
* config Folder
* controllers Folder
* db Folder
* models Folder
* Public Folder
    * javascript Folder
    * stylesheets Folder
* utils Folder
* views Folder
    * layouts Folder
    * partials Folder
* .env
* package.json
* .gitignore
* README.md
* server.js
  
## How to setup
  * First gitclone the application to your machine.
  * Next open the application in vscode. 
  * Then open a terminal in vscode.
  * Enter in the following npm packages
      * bcrypt
      * connect-session-sequelize
      * dotenv
      * express
      * express-handlebars
      * express-session
      * pg
      * sequelize
  * Open Postgresql and start it up.
  * Enter into the terminal "psql -U postgres", and enter your password to connect to the sever.
  * Then enter "CREATE DATABASE tech_blog_db"
  * After creating a database create an .env File.
  * With your .env enter in your database name, username, and password.
  * Enter in npm run seed.
  * Then in chrome Open http://127.0.0.1:3001 and should have your website up and running.


## Screenshot


## Deployed Website
https://louis-module-14-model-view-controller.onrender.com/
