# Babydoge Coin Tracker

This project implements a monitoring dashboard of the current price and ammount of babydoge coins in a wallet. It is meant to be shown in a public office space. The dashboard updates itself every few minutes.

<img width="1386" alt="Bildschirmfoto 2022-08-02 um 13 51 41" src="https://user-images.githubusercontent.com/44783000/182368253-04561678-1984-4693-be5d-2c424a186900.png">

Here you can see the live version here: [Tracking-Dashboard](https://insightgroup-capell.github.io/baby-doge-coin/)

## Tech Stack

- **React** - This is a live React App hosted on GitHub Pages
- **Java Scripts** - All backend communication is implemented in JS

## Project setup

After cloning the repository onto your machine via git you need to make sure to install `npm`. This repo uses the version `8.1.*`. Next you want to install all necessary dependencies. If you are in the rigth folder just run:

`npm install`

After this step you need to add enviorment variables like the token for the API. Create a file in the `src/` folder `.env` with the following content:

```
REACT_APP_API_TOKEN=*******************
```

Now your project is set up!

## Build the app

Run `npm start` to start the app on your machine.

Run `npm run deploy` to deploy the app on the web.

## Changes

So if you want to change something first set up the project, then change the variables, then deploy the app again and push your changes to GitHub.
