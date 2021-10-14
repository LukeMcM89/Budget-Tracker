# Budget-Tracker

This web application features a progressive budget tracker which enables a user to manage their personal finances. This is achieved with or without a stable or viable internet connection.

The budget history is tracked and visualized via a slope graph with the respective data being stored on a MongoDB database. All relevant files concerning this application are cached in the browser. This allows the application to operate the same and predicatbly even offline. 

In the absence of a viable internet connection, which means no database with which to communicate with, any offline input on the user side is/are stored through IndexedDB via the browser. 

When internet connection is restored, the cached data is fetched directly to the database itself. 

# Technologies Utilized / Required

* HTML5
* CSS
* Bootstrap Styling
* Javascript
* Express
* Node.js
* MongoDB database
* IndexedDB 
* Service Workers
* Manifest.json

# Links

Link to deployed application on [Heroku](https://pure-earth-91183.herokuapp.com/).

Link to [GitHub repository](https://github.com/LukeMcM89/Budget-Tracker).

# Screenshots

<img width="1440" alt="budget2" src="https://user-images.githubusercontent.com/80003989/137389143-279ad2f2-5345-43ed-8535-46166b0e4279.png">
<img width="1407" alt="budget-service" src="https://user-images.githubusercontent.com/80003989/137389197-3bda8683-fb9c-4a09-b4a2-0f6a48d0739f.png">

