# Covid-19 Tracker App

#Wireframe
![](Covid Tracker wireframe.JPG)

My App Website Deployment URL: https://covid-19-tracker-personal-proj.web.app

This Project is a beginner friendly project I built using React. Some key Aspects:

- Shows Live Cases, Recoveries, Deaths (clickable tabs)
- Shows Worldwide cases and Country Based cases
- Line Chart shows fluctuations over days, hover around to see exact figures
- Clickable Markers on Map show Country stats

extensions for the data for my app
https://disease.sh/

1. Create Wireframe
2. Create React App - build by guys from facebook. It allows me create app with one command line and it will set
up the entire app to get the things started for my first react app
3. Cleanup Project - Everytime i set up a react project, i like to run a clean up process so i get rid of bunch
of files inside the directory such as 'app.test.js', 'setupTest.js', 'logo.svg'
4. Structure of Covid Tracker - Building out the layout of the app such as containers (<div>)
5. Create header
6. Create Info Box
7. Create table
8. Create Chart
9. Create Map
10. Styling
11. Deploy

#My personal notes

npm i -g firebase-tools

revisit app.js (useEffect)
revisit util.js

npx create-react-app covid-19-tracker-personal-project

Icons that i used for this project
https://material-ui.com/components/material-icons/

flex box is a way for me to easily structure websites such as putting into rows, columns. 
Restructuring how the layout is going to be like.

/* Align all items evenly */
justify-content: space-between;

Difference between margin and padding

padding adds space inside of the container element
margin adds space outside of the container element

State is like a short term memory for React.
STATE = How to write a variable in REACT

JSX - It allows me to combine HTML with Javascript

UseEffect = Runs a piece of code based on a given condition

useEffect(() => {
    // The code inside here will run once 
    // when the component loads and not again after

}, [countries]); //It will load when the countries variable changes

async -> sends a request, wait for it, do something with the info

Map is essentially like a loop.

For example: we have an array [item1, item2, item3]
It's gonna loop through this array. The first time it loops through and gets item 1, i am returning an object in a shape
which is the name and value

It will go to item 2 and it will do the same thing

Difference between a map and for each

map is going to return the array we sort of transforming

@media (max-width:990px) - When the screen goes past 990px, change to a column


@media (max-width: 990px) {
  .app {
    flex-direction: column;
  }

overflow: scroll;
height: 400px;


