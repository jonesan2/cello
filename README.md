# Cello App

Project management and collaboration, based on Trello
Built using React.js and Node/Express.js with MongoDB

## Setup
1. `cd` into client and run `yarn install` from the command line to install all dependencies
2. `cd` into server and run `yarn install` from the command line to install all dependencies

## DataBase Setup

1. Once your MongoDB cluster is created, under Clusters tab, click connect and copy the connection string which will look something like this `mongodb+srv://<username>:<password>@cluster0.ioku4.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`. Instead of `<username>` there will be your username, and you will need to replace `<password>` with your password.
2. Inside your project folder, `cd` into server, create new file `.env` and enter `DB=<paste the string from above here>`. It will look similar to this `DB=mongodb+srv://srdjan:mypass@cluster0.ioku4.mongodb.net/reaction?retryWrites=true&w=majority`.

## Running the app
While in the server directory, run `npm run dev` to start the live server.
