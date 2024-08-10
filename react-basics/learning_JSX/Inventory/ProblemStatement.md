Problem statement
You want to create a simple dashboard for an electronic store, displaying the name, selling price, quantity, and total revenue for the sold products in a table format.

Expected Output:

Test Cases:

1. App should render the table correctly:

Ensure that the app renders the table with the appropriate structure, including the <thead>, <tbody>, and <tfoot> elements.

2. App should render 4 columns with correct labels:

Create columns inside the table header (<thead>) with appropriate labels ("id," "name," "selling price," "quantity") using the "th" tag to match the expected output image.

3. App should render table data correctly:

Iterate over the provided data and ensure that the application renders the appropriate fields inside the table body (<tbody>) for each sold item.

Check that the displayed data matches the provided information accurately. 4. App should render table footer correctly:

Create a table footer (<tfoot>) and display the total revenue of the sold items. Verify that the displayed total revenue matches the sum calculated from the provided data.

It should have two columns, one with “Total Revenue” and the other displaying the total value.

Note:
Use the same data as provided in the scaffold, any modification in the scaffold code will lead to failure of test cases.
You can learn more about reduce method through this link:
Link
