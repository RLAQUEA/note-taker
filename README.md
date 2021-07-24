# Note Taker Application 

This application uses express.js.  When the user navigates to the home page, they are shown a log where they can add new notes, delete notes and view notes that have previously been saved.  To add a note, the user will click their cursor into the space that says "Note Title", add their title, and then can click below into "Note Text" to add their text.  Once they've finished their note, they can save it with the save icon in the top right corner.  If they want to delete the note, they can click the trash can next to the note and it will be deleted.  The notes are saved to a database (db), and anytime it is altered in any way (adding or deleting a note) the application will be rewriting the database dynamically.  The application uses HTML routes to bring the user the information, or the "view", and the API routes are used to channel the data to their correct endpoints.  

<img width="1786" alt="Screen Shot 2021-07-24 at 6 18 49 PM" src="https://user-images.githubusercontent.com/30808137/126882374-5e9712e4-d3bd-4355-aa17-390fb86dcfc3.png">

Link to deployed application on Heroku: 
https://shielded-garden-14858.herokuapp.com/notes