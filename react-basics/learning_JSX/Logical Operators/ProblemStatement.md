Problem statement
Create a React component named App that utilizes logical operators to render components conditionally.

Expected Output:

If the user is not logged in and the name is not set

If the user is logged in and the name is set

Tasks:
The scaffold has four components: Login, App, Home, Premium.
The Login and Home component has already been created. You just have to complete the App and Premium Component.
For the App component, we have variables for the name and a isLoggedIn variable to check whether the user is logged in or not.

Note: You have to set the values here manually. There is no need to implement the logic for changing the values of name and isLogged dynamically.

If your name is not defined, it should display a default name (use “Guest”) in the Welcome Message using the h1 tag.
On the basis of the flag, only one component should be rendered, either Home or Login.
For the Premium Component, create a simple button without any event handler.
Test Cases:
App should render any one component

Only one component should be rendered on the screen, either Home or Login.

If the Home component is rendered, then it should contain the button from the Premium Component.
