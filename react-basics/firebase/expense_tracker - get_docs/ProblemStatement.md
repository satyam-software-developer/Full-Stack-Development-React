Problem statement
In the previous question you have used firebase to add new expense and update the expense. Now let's get those expense using the getDocs() method of firebase.

Tasks:

- When the app mounts, retrieve all documents of expenses from the collection, and store them in the "expenses" state. Use appropriate hook so that on mounting all the expenses are automatically fetched from the collection.
- You can use the same firestore config which you used in the previous question.

Note:

- You only need to get the expense from collection and set it to "expenses" state in the App component.
- You can learn more about getDoc through the link: Link
