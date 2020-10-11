# Starting point
The Meteor React Tutorial is where to start learning the basics of Meteor with React.

A few tips before you start:

If you want to check the final code of each step, you can always go to the ``` src ``` folder.

Each folder inside ``` src ``` folder is a tutorial. 

Inside each you have one folder for each steps final state. Each step folder is a Meteor app - you can run them at any time.

Install it: ``` meteor npm install ```
Run it: ``` meteor ```

# Creating the app

## Install Meteor

OSX or Linux:

```
curl https://install.meteor.com/ | sh
```
Windows: First install Chocolatey, then run this command using an Administrator command prompt:

```
choco install meteor
```

## Create Meteor Project

Command meteor create with the option --react and your project name:

```
meteor create --react simple-todos-react
```
Meteor will create all the necessary files.

The files located in the client directory are setting up your client side (web), you can see for example ``` client/main.jsx ``` where Meteor is rendering your App main component into the HTML.

Also, check the server directory where Meteor is setting up the server side (Node.js), you can see the ``` server/main.js ``` is initializing your MongoDB database with some data. You don’t need to install MongoDB as Meteor provides an embedded version of it ready for you to use.

You can now run your Meteor app using:

```
meteor run
```
Don’t worry, Meteor will keep your app in sync with all your changes from now on.

Your React code will be located inside the ``` imports/ui directory ```, and ``` App.jsx ``` file is the root component of your React To-do app.