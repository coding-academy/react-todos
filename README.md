# Project Description

This project contains the following topics

* Stateless functional components
* Using PropTypes
* Immutable updating
* Handmade functional utils: pipes and partials 
* Handmade (simplified) Routing and Linking
* Using React Context: childContextTypes, getChildContext, contextTypes
* Full CRUD with json-server



This proect is for learning purpases and contains various manual techniques that (for real life) are better achieved with ready-made-libraries (such as react-router)
It also contain `no state managment` solution 


Install the project dependencies with npm

* `npm install`

To run this application, you will need to have the mock API server **and** the web pack dev server running in separate terminal sessions.

## Setup The API Server

This project uses [json-server](https://github.com/typicode/json-server) to provide a local REST service that uses a `.json` file as its data source.

### Install json-server

You can install it globally with `npm i -g json-server`. This is a one-time setup.

### Running json-server

Be sure to `cd` into the project's root directory. From there, run:  

* `json-server -p 8080 db.json`
  * This will run the server on port `8080` and use `db.json` as the data source

## Running the Project

In a separate terminal session from the API server, you can start the React application with the included npm script

* `npm start`

This will run the `webpack-dev-server` that is configured through `create-react-app`

