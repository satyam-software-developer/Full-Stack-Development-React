Problem statement
For the given scaffold you are using different handler functions for different components.

Refactor the code so that it should have a single handler function which should be used for all the components.

In scaffold the FavouriteFood component is already defined and should be used to render the favourite food.

The FavouriteFood component should only be rendered when a food item is clicked.

Expected Output:

Test Cases:
Handler Function is Defined:

The handleFoodClick function should be defined.
App should render each food item with a heading and image

Ensure that the app renders each food item with a heading and an image.

Ensure that the FavouriteFood component is only rendered when a food item is clicked.

Hints:
You can pass an argument to the common handler function to set the favourite food.
To render the FavouriteFood component only when the favouritefood is defined you can use the logical operator (&& or ||).
