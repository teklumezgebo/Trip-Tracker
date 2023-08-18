# Destination Tracker 🔗 -> https://destination-tracker.onrender.com/

Destination Tracker is full stack web application that allows user to post destinations and review them while also being able to see other people's reviews. Users have the ability to create accounts that are password protected. Reviews posted by users can be deleted and edited by the user as well.

###

Ruby on Rails and PostgreSQL are used to create an optimal backend and React is used for an interactive frontend. The users, destinations, and reviews models are used in a many-to-many relationship to associate reviews to both users and desinations. Authentication is acheived by using BCyrpt as well as cookies.  Validations are used to prevent duplicate users and duplicate destinations along with other validations within the review model. This app is deployed on render which is where the database is stored as well. 