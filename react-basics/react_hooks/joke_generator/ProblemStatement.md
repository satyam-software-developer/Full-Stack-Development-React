You and your friend are building a joke generator application. Your friend has asked you to create a custom hook for fetching jokes that returns the joke data, loading status, error, and a function to fetch new jokes.

Test cases:
Renders loading text when loading is true
Ensure that the "Loading..." text is displayed during the data fetching process.
Renders error text when error is not null
Verify that the "Something went wrong…" message appears in case of an error during the API request.
Renders joke and handles new joke button click
Implement the "New Joke" button functionality to display a new joke when clicked. Make sure to include an onClick function for this feature.

Note:
Use npm install --force to install the node modules if an error occurs.
On loading the application a new joke should automatically be fetched using the useFetch() hook.
