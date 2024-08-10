Problem statement
The following project contain an image gallery with a unique functionality for saving images. Each image within the gallery is equipped with an icon on the side, allowing users to save their preferred images with a simple click.
To access and view all the saved images, users can conveniently click on the 'Saved Posts' button located in the navbar.
Also, there a reset button which can be used to un save all the images.

Create a custom context provider and a hook to get the value of context in multiple components.

Expected Output:
Tasks:

- Create a context to manage saved posts and a custom provider to consolidate all the context logic inside of a single file in "postContext.js" file.
- The post context should have add and reset post functionality such that it matches the given output gif.
- Create a custom hook that returns the context value and use it inside components to reduce the need to repeatedly import the context and useContext hook in every file.
