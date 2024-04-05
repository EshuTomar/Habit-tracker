
### Description

A full stack app which help you to Create , Read, Update, Delete your habit. It is user specific app, which mean a particlar user can track his/her habit, and mark it as
done , or not done. The project is built using a tech stack consisting of Node.js for the server-side scripting, Express for handling HTTP requests and routing, MongoDB 
for storing and managing the data, and EJS for rendering the views and templates


### Tech Stack

Node , Express, Mongodb , EJS , javaScript , html, css

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````


### Features

  User view of homePage - signUp - SingIn
  

### Folder Structure

```
Habit Tracker
    |
    |               |--->css
    |--->assets---->|--->images
    |               |---> js
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->habbit_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->user_controller.js
    |
    |               |-->habit.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->habit.js
    |--->routes---->|-->index.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |--->forget_password.ejs
    |              |--->home.ejs
    |--->views---->|--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
    
