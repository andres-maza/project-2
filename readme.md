Project 2 Message Board
-----------------------
This is a simple message board. Users can create posts, comments and comment replies and 'like' each separately, similarly to reddit.

Wireframes
----------
![index](http://i.imgur.com/QVCp2zP.png)  
![new post](http://i.imgur.com/iv6Qj3c.png)  
![show](http://i.imgur.com/uJngUq2.png)

User Stories
------------
* As a user I should be able to see all available posts
* As a user I should be able to create a new post
* As a user I should be able to 'like' a post
* As a user I should be able to see all comments within a post
* As a user I should be able to comment on a specific post
* As a user I should be able to 'like' a comment or comments
* As a user I should be able to reply to a comment and see replies from other users
* As a user I shoudld be able to 'like' a reply


ERD
---
![ERD](http://i.imgur.com/jQzZ33C.png)

npm Modules
-----------
1. **Express**  
• Used for Node.js server
2. **Morgan**  
• Terminal logger
3. **Async**  
• Allows us to run functions asynchronously
4. **Body Parser**  
• Allows us to parse HTML and find json object based on input/textarea names
5. **EJS**  
• For EJS templates and getting content from json objects
6. **Marked**  
• Parses markdown to HTML
7. **Path**  
•  Used to set up public folder for static files
8. **Pg-Promise**  
• Used to read SQL queries on Node
9. **Method Override**
• Used for PUT and DELETE requests

Download Project & Install
----------------
1. [Git clone or download this project]('https://github.com/andres-maza/project-2')
2. Create a PostgreSQL database called 'project_2_db'
3. On your terminal, run psql -d project_2_db -f migrations/migrations.sql
4. If you haven't already, install nodemon package (npm install -g nodemon)
5. Run nodemon, app should be available on localhost:3000
