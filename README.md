# Budget-Tracker

This web application features a progressive budget tracker which enables a user to manage their personal finances. This is achieved with or without a stable or viable internet connection.

The budget history is tracked and visualized via a slope graph with the respective data being stored on a MongoDB database. All relevant files concerning this application are cached in the browser. This allows the application to operate the same and predictably even offline. 

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
* Heroku 

# Links

Link to deployed application on [Heroku](https://pure-earth-91183.herokuapp.com/).

Link to [GitHub repository](https://github.com/LukeMcM89/Budget-Tracker).

# Screenshots

<img width="1440" alt="budget4" src="https://user-images.githubusercontent.com/80003989/137391598-22a2a456-15dc-4f14-a395-652e2e8ce28d.png">
<img width="1440" alt="budget3" src="https://user-images.githubusercontent.com/80003989/137391425-47027851-fc6d-4d09-b40e-1bb97acbbf20.png">
<img width="1407" alt="budget-service" src="https://user-images.githubusercontent.com/80003989/137389197-3bda8683-fb9c-4a09-b4a2-0f6a48d0739f.png">
<img width="1440" alt="Screen Shot 2021-10-14 at 4 30 31 PM 1" src="https://user-images.githubusercontent.com/80003989/137391387-0e658e9c-5f82-4501-9376-1f67521889f8.png">

# Contributors

Front-End code provided by University of Richmond Flex Full-Stack Coding Bootcamp.

