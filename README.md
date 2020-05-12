# React Google Book Search 

This is a Google Books Search that uses React to query and display books based on user searches. They can then also save books to review or purchase later due to the use of Node, Express, and MongoDB.  As a SPA (Single Page Application), it uses react-router-dom to navigate, hide, and show React components without changing the route within Express.

## Application works as follows:

* This application has 2 pages:
- Search Page
    - User can search for books via the Google Books API and see them rendered on this page. 
    - User has the option to "View" a book, bringing them to the book on Google Books
    - User can "Save" a book, saving it to the Mongo database.
* Saved Page: this page renders all books saved to the Mongo database 
    - User has an option to "View" the book, bringing them to the book on Google Books
    - User has the option to "Delete" a book, removing it from the Mongo database.

* Books have the following fields: 
- title - Title of the book from the Google Books API
- authors - The books's author(s) as returned from the Google Books API
- description - The book's description as returned from the Google Books API
- image - The Book's thumbnail image as returned from the Google Books API
- link - The Book's information link as returned from the Google Books API


<!-- Add the following Express routes for your app:

/api/books (get) - Should return all saved books as JSON.
/api/books (post) - Will be used to save a new book to the database.
/api/books/:id (delete) - Will be used to delete a book from the database by Mongo _id.
(get) - Will load your single HTML page in client/build/index.html. Make sure you have this after all other routes are defined. -->

<!-- Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. -->


<!-- * Refer to the GIF below for an app demo.

![Google Book Search](assets/.../.gif) -->


<!-- Try it out at: url of deployed app -->


<!-- ## Future version to include: 

* live Updates to Saved Books

* Use React routing and socket.io to create a notification or a component that triggers whenever a user saves an book; message includes the title of the saved book.

* Say you have multiple browsers open, each one visiting your site. If you save an book in one browser, then all of your browsers should notify you that a new book was saved.

* Socket.io NPM package  -->

