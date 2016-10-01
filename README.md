# FCC-FS-Stock-Tracker

## Install
In order to use this project, you must install Node.js and Express.js You can acquire
node through the [Node.js](https://nodejs.org/en/) website. After you have it, you can
install Express globally with the following command:
`npm install -g express`

You can install all other dependencies with this command: `npm install`

## How to Use
`npm start` will start up a webpack server for developing a front end react app.

`npm run build` will build the project and place the files in a `public` folder.

`npm run serve` will serve whatever is in the `public` folder on `localhost:8080` with an express server.

`npm run prod` will build and then serve the project.

If you want to use the original datavis only boilerplate, then use the `datavis-only` branch.

## Project Description:
FreeCodeCamp has a series of projects with increasingly complex [requirements](https://www.freecodecamp.com/challenges/chart-the-stock-market).
This project utilizes web sockets to create a dynamic stock tracking app.

### Requirements
1. User Story: I can view a graph displaying the recent trend lines for each added stock.
2. User Story: I can add new stocks by their symbol name.
3. User Story: I can remove stocks.
4. User Story: I can see changes in real-time when any other user adds or removes a stock. For this you will need to use Web Sockets.

### Technologies Used:
+ HTML/CSS/JS
+ Node
+ Express
+ Heroku
+ web Sockets
+ [Highcharts](http://www.highcharts.com/)
+ [Quandl](https://www.quandl.com/)

### Live Demo:
Coming Soon
