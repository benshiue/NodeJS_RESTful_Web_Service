# CF Sample App Node.js

A sample [Express](http://expressjs.com/) application to deploy to Cloud Foundry which works out of the box.

## Run locally

1. Install [Node.js and npm](https://nodejs.org/)
1. Run `npm install`
1. Run `npm start`
1. Visit [http://localhost:3000](http://localhost:3000)

## Run in the cloud

1. Install the [cf CLI](https://github.com/cloudfoundry/cli#downloads)
1. Run `cf login -a api.iii-cflab.com -u <Your account> -p <Your password> `
1. Run `cd NodeJS_RESTful_Web_Service `
1. Run `cf push`
1. Visit the given URL
