node-scheduler-demo
===================

Demo of dhtmlxScheduler with NodeJs + MongoDB as backend

### How to start

To run the app, do the next after cloning the repo

~~~
npm install
npm start
~~~

after that, open in a browser http://localhost:3000/init to generate a test data, and http://localhost:3000 to check the calendar. 

### DB config

App expects to find the mongoDB on localhost, you can change the server address in the app.js 

## Log
A "npm start" script was added to the package.json
The config file was created and injected into the app to setup the mongodb connection