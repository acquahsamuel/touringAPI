# touringAPI

API and backend with node.js for frictional web app (tourer). 

## Project Structure
 
Check the .gitignore file to see all the files and folders that will be ignore because some are auto-generated by the IDE, log files, editor files and folders etc.


### Files you will be working with:

- <b>Controllers </b> Renders the Application Logic 
- <b> Dev-data </b>  Contains Images , JSON format data , templates UI (Additional Components )
- <b> Model </b>  Renders the Business Logic 
- <b> Public </b> Renders the Application Logic 
- <b> Routes </b> Renders the Application Logic 
- <b>Controllers </b> Renders the Application Logic 


## Choose your  Server mode  
The server contains 2 files the 

- <b> Server.js </b> 
- server.js for production config 


- <b> Server-local.js </b> 
- Server-local.js for local development configuration


## What to fix
config.env file 

The config.env file contains your key and sensitive data
create your config.env and add your account details 
NODE_ENV=
PORT=
DATABASE=
DATABASE_LOCAL=
DATABASE_PASSWORD= 
 

### testing the whole application
Using postman for testing purpose. Testing various endpoints to see if they are working properly
-  Testing with postman

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
Start this server for local development
npm start:local

Start either one of these server for production development 
npm start:prod || npm start:dev
```

See [Configuration Reference](`https://www.npmjs.com/`).
# npm.org