# SetupReactNode

This README outlines the details of this setup of React with a node server ready to deploy on Heroku.
[FE setup with create-react-app.](https://github.com/facebook/create-react-app)

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)

## Installation

* `git clone https://github.com/Brian06/SetupReactNode.git`
* `cd SetupReactNode`
* `npm install`
* `cd client`
* `npm install`

## Running / Development

* `cd ..`
* `npm start` **To start the FE and the BE
* Visit your app at [http://localhost:3000](http://localhost:3000).

If you want to run only the BE:

*`npm run server`

If you want to run only the FE:

*`npm run client`

## Deploy

* Create a new branch preferably called deploy.
* `cd client`
* `npm run deploy`
* Go to [Heroku](https://dashboard.heroku.com/apps) with your account.
* Create new App.
* Connect with GitHub.
* Select deploy branch.
* Enable Automatic deploys.
* Remove the build folder from your .gitignore file
* Push your changes.
* Go to activity tab on Heroku page and verify the build status.
* Click on open app to see your page. 

## Test

You can look the console to see the Hello World! from your server when you click the button to verify that all is working good, now you can modify the diferent folders to add new code, enjoy! 
