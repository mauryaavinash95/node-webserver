# node-webserver

## The most basic node webserver

The motive of this project was to start delving into nodejs. Learning how to render some static contents and pages through the webserver. 
The application just creates routes in [expressjs](https://expressjs.com) and renders templates using [hbs](https://www.npmjs.com/package/handlebars) to the client.

Clone the repo and run
```
npm install               #to install dependencies.
npm start                 #to start the web-server.
```
To view the live version of the app visit https://my-node-webserver.herokuapp.com/

###### Since the dynos on heroku sleep after 1 hour of inactivity, the app may be slow to load if loaded for first time within the given hour.
