## Smart Brain

Smart Brain is a full stack, face-recognition application. It uses the Clarifai API to detect and create a bounding box bordering faces from uploaded images. By copying and pasting random image urls from the internet, Smart Brain will create a border, as well as keep track of image counts by incrementing entries on a user's profile.

This is a project I wanted to take on to improve my React skills in the front end and Node.js in the back. It is part of one of my favorite instructors from Udemy, Andrei Neagoie's course, The Complete Web Developer 2019: Zero to Mastery. It was tough following along as it got more and more advanced, although taught me different strategies and techniques to build a full on app.

Users are able to register with an email, name, and password. It is passed on to the database built in PostgreSQL. The credentials are stored in the DB for future sign in. The database also keeps track of entries, or how many images a user has detected a face.

Front End: - React.js, tachyons, CSS, Javascript

Back End: - Express, Node.js, Knex, PostgreSQL, Clarifai API
