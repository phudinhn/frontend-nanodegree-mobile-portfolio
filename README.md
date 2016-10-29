## Website Performance Optimization portfolio project

### Changes to index.html
* Resize pizzeria.jpg to 100x75px
* Add 'async' attribute to Google Analytics script
* Add 'media="print"' to print.css link
* Move style.css to internal stylesheet
* Remove Google Fonts

### Changes to main.js
* Create a variable to store the .randomPizzaContainer NodeList
* Incorporate sizeSwitcher() into changePizzaSizes(), and delete determineDx()
* Size pizzas based on percentage value instead of pixels
* Create scrollTop variable in updatePositions(), so it is not calculated inside the loop
* Store .move NodeList in a variable outside of the loop
