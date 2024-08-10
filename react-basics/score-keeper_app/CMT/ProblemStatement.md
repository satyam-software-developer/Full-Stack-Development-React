Problem statement
To manage the people of a Restaurant, create a form to get the details of the customers, like the guest count, name, and phone number and complete the table to show the records of the customers as shown in the output.

Expected Output:

Tasks:
Form creation

Create a form to get the name, count and phone number with a submit button to submit the form.

Form Submission and Record Display

When the form is submitted, the "Seats Left" should decrease by the guest count, and a new entry should be added in the table.
Deletion Feature

Clicking on "Delete" in the "Remove Entry" column should delete the record and increase the "seat left" accordingly.
Guest Count Validation

When the count of guests exceeds "Seats Left", an alert should show the message "Guest count exceeds capacity."

"Seats Left" should never exceed "Total Capacity" or have a negative value.
Duplicate Name Entry Handling

Optionally handle duplicate name entries by showing an alert with the message "Customer already exists" when someone tries to add an entry with a name that already exists in the records table.

Test Cases:
App should render a form with 3 inputs and a button

The application should render a form with 3 inputs (for guest count, name, and phone) and a submit button.

App should render a table with 5 columns

The application should render a table with 5 columns (Count, Name, Phone, Check In, Remove Entry) and the content should be updated on submitting the form.

Hint: (click to expand)

Each customer should have the following data -
{ name, phone, count, checkin}
Use the Date object to get the current timestamp as the checkin time.
