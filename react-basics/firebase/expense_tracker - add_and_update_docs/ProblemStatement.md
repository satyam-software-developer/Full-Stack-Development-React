Problem statement
Set up and initialise a Cloud Firestore project and integrate it into the React application to manage expenses.
The application should add a new document to the collection when the user submits the ExpenseForm. Additionally, when the user selects the update option in the ExpenseForm, the corresponding document in the database should be updated accordingly.

Test Cases:

Add Expense to Firestore on Form Submission:

- When the user submits the ExpenseForm, the application should adds the corresponding expense to the Firestore database using the “addDoc” method.

Update Expense in Firestore on Form Submission:

- When the user selects the update option in the ExpenseForm, the application should update the corresponding expense in the Firestore database using the “setDoc” method.
  Note:
  For updating a transaction use the setDocs methods by finding the particular transaction using it id.
