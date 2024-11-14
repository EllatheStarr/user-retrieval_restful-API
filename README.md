Project Overview:
This project is a basic RESTful API built using Node.js and Express. The objective is to read and retrieve user data from a JSON file (users.json) and make it accessible through various GET endpoints. The API provides functionality to list all users, get a user by their ID, profession, or name.

Objectives:
Learn how to set up a basic Node.js project.
Understand how to use the fs module to read and parse JSON data.
Implement and handle multiple GET endpoints using Express.
Test API endpoints using tools like Postman.
Gain experience with Git for version control and deploying to GitHub.

What I Learned:
How to set up and structure a Node.js project using Express.
Using the fs module for file handling and parsing JSON data.
Building RESTful APIs and routing in Express.
Handling requests and sending JSON responses.
Basic error handling for non-existent data requests.
The importance of version control and documenting projects on GitHub.

Implementation of GET Endpoints:

List All Users (/users): Used the `fs.readFile` method to read and parse `users.json`, then sent the parsed data as a JSON response.
Get User by ID (/users/:id): Retrieved the user by matching the `id` parameter with the `id` property from the parsed data, sending the user details if found or an error message if not.
Get User by Profession (/users/profession/:profession): Filtered users whose profession matched the provided route parameter and returned the results.
Get User by Name (/users/name/:name): Searched for the user whose name matched the provided route parameter and returned the user details or an error message.



