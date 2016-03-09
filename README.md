# node-js-getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone https://github.com/ankybhagat/aob2869_cse5335-project-1-.git # or clone your own fork
$ cd aob2869_cse5335-project-1-
$ npm install
$ npm start
```
	

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku login			#login using heroku credentials
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Run locally,

$ git clone https://github.com/ankybhagat/aob2869_cse5335-project-1-.git # or clone your own fork
$ heroku login			#login using heroku credentials
$ heroku create
$ git push heroku master
$ heroku local web

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)



#  server framework
- I chose nodejs as server framework because it is open source and widely used. Also, I had never worked on this framework so I took it as an opprtunity to learn it.

# client framework
- I chose Jquery as it is very popular and again a new thing to learn.

# What aspect of the implementation did you find easy, if any, and why?
- Deploying the application to heroku and using it was something new and it was pretty simple than I thought.

# What aspect of the implementation did you find hard, if any, and why?
- Being a layman to web development in client-server framework, I faced challenges which I eventually overcame, in understanding the concepts and integrating the server and client side scripts.
- 
# What components OTHER than your client and server framework did you install,
if any, and if so, what is their purpose for your solution?
- Nothing else was required. Apart from an Editor- I use Sublime Text.

f. What Ubuntu commands are required to deploy and run your server?
$heroku create
$git push heroku master

#Run Server
$heroku open
