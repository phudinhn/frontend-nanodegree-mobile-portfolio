# Website Performance Optimization portfolio project

## How to view
1. Download or clone the project files from: https://github.com/dwds/frontend-nanodegree-mobile-portfolio
2. Open index.html in Chrome (moving pizzas in background will not work in Firefox)

## Optimizations made

### Changes to index.html
* Resize pizzeria.jpg to 100x75px
* Add 'async' attribute to Google Analytics script
* Add 'media="print"' to print.css link
* Move style.css to internal stylesheet
* Remove Google Fonts

### Changes to views/style.css
* Add translateZ hack to .mover class

### Changes to main.js
* Create a variable to store the .randomPizzaContainer NodeList
* Incorporate sizeSwitcher() into changePizzaSizes(), and delete determineDx()
* Size pizzas based on percentage value instead of pixels
* Create scrollTop variable in updatePositions(), so it is not calculated inside the loop
* Store .move NodeList in a variable outside of the loop
* Limit pizza generation to a number based on window size.
* Store #movingPizzas1 in a variable outside of the loop
* Use getElementById and getElementsByClassName instead of querySelector and querySelectorAll
* Create phases array to store the five possible phase values, removing the repeated calculation that was in a for loop.
* Move the definition of pizzasDiv outside of the for loop
