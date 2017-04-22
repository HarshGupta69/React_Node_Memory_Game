# Memory Game

This is a very simple Memory Game. This is currently in development, Please find introduced and pending features in description below.

This application is being developed using Node/React/Redux technologies.

Author - Harshit Gupta & Shubham Gupta

Flow of the game -

User will click on play and he will get two deck of cards
First one will get data from getchars API
Second deck will get data from shuffle API using the response from the first API call.

User will click a card and  this will flip the card and display the value fetched from response of the getalphabet API.

A piar of click on each deck will increement the move value.

Components ->

1. App Component -> Smart Component
	a. Header
	b. LeaderBoard - Dynamic Component
	
2. Card Component -> Dumb Component
	-- Only for rendering 
	
Services - 

1. Call to getchars - Successful
2. Call to shuffle - 
3. Call to getAlphabet - Successful

External tools used

-- Redux
-- Redux middleware for consuming  external APIs

Funtionality Completed - 

- UI of application
- Data from getchars API and getalphabet API
- Partial Logic

Functionality Reamining -

- Data from shuffle API in the second deck
- Partial Logic
- Session storage of leaderboard values in server side.

To start the application you can now run: `yarn start`

## Available commands

- `yarn lint` Run code linting
- `yarn test` Run tests using jest
- `yarn test-coverage` Run tests using jest and display coverage
- `yarn build` Bundle the application
- `yarn start` Run the development environment
- `yarn deploy` Build the application in production mode
- `yarn deploy-windows` Build the application in production mode under Windows

