# cart
a cart application using React.

## Technologies
* react.js: 18.2.0
* vite: 4.1.0

## Setup
To run this project, install it locally using npm:
$ npm install
$ npm run dev

or see demo on: https://jwcart.netlify.app/

## Inspiration
I went through the cart lesson from Udemy course "React 18 Tutorial and Projects Course (2023)" by John Smilga, built this app successfully.

## What I learned from this project
Way of using _useContext_ to share variable Globally.
First, I add a file called context.js, which is responsible for sharing global variable fuctionality, and create a function inside it named 'useGlobalContext', for being access for any component that need. using _useReducer_ give action option when upating state.
Also put actions option in separate js file and access throgh them:
* distinguish by name from actions.js
* option logic from reducer.js

logic function for control interaction put in utils.js. 
file structure makes context.jsx more clear on variable sharing mission.



