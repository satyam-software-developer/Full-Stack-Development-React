Problem statement
You have created an online course-buying platform called CodeTube Catalog, where users can buy courses and follow/unfollow their favorite instructors.

Expected Output:

Tasks :

- Create two reusable components named “Button” and “Container” using styled-components in the resuable.styled.js file.
- The Button Component should be used in the Course.js and Sidebar.js file in place of the existing button tag as mentioned using comments in scaffold.
- The Container div should be used in the List.js and Sidebar.js file to enclose all the courses and instructor present.
- The Button component should be passed with a bg props which should be used to set the background color of button, while the Container should be passed with a flex props that sets the flex value(which should be an integer).
- Usage:

* Container : < Container flex="1">
* Button: < Button bg="blue"/>

Hints :
Learn more about Styled Component from here: Link
Test Cases :

1. App should render data correctly

- Ensure that the application renders data correctly, including the instructors and courses from the data.js file.
- There should be three instructors and courses.

2. Buttons and bag item count work correctly

- The "Add to Bag" and "Follow" buttons should work correctly, and the bag item count on the navbar should update accordingly on clicking the “Add to Bag” button.

3. Styled components are exported correctly

- The styled components, Container and Button, should be exported as named export instead of default export.

4. Test Styled Components Properties:

- The props passed in the styled component, such as background color and flex value, should be applied accordingly.
