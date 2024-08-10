Problem statement
Now that you have converted the class components to functional components, your task is to implement the feature to add and remove a transaction.

Expected Output:

Flow of Code:
Use the doc to understand the application clearly:
Link

Tasks:

- Complete the add and delete expenses functions in the App Component.
- Implement the click functionality of the "Add transaction" button to add new expenses to the list "expenses".
- Update the "balance", "income", and "expense" values correctly when a new transaction is added to the list.
- Calculate the "balance" as the sum of all transactions, "income" as the sum of transactions with values greater than 0, and "expense" as the sum of transactions with values less than 0.
- Implement the functionality to delete a transaction from the list when the delete button is clicked in the Transaction component.
- Ensure that the "balance", "income", and "expense" values are updated correctly after the transaction is deleted.

Note:
Use the current Date as the id for the expense. {id: new Date().getTime()}
