Problem statement
Create a React application that allows users to input student details, including the student's name and their obtained marks and render those data in a table.

Expected Output

Tasks
There are two main components, namely the Form component and the Result component. Your task is to complete both of these components.
The application should incorporate a form to collect the name and marks of students.
Form Component:

When the user clicks the button, the student's name and marks should be dynamically inserted into a table, which will be displayed below the student form.
Within the Result component, you should render a table that displays the names and marks of all the students.
It's crucial that the entire page does not reload during this process.
Result Component:

Test Cases
App should render a form

The application should correctly render a form to collect student details.

App should render form with 2 inputs and a button

The form should contain two input fields for name and marks and a button to submit the student details.

App should render a table

The application should properly render a table to display student details.

App should render the table with correct table headings

Test that the table contains the appropriate headings, including "Student's name" and "Marks" using the “th” tag.

Hints
When you submit the form it will refresh the page, use preventDefault() function to restrict the page from refresh.
Rerender the App after every button click.
