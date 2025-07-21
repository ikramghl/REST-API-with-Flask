# REST-API-with-Flask
This is a simple Flask-based demo written in Python. It provides a REST API for basic user data management using in-memory storage (a Python dictionary), supporting standard CRUD operations.

## Technologies Used

- Python 3.13.2
- Flask 3.1.0
- Postman 11.55.0 (for testing)
- JSON (data format)

---

## Objective

To build a REST API that can:
- Create users.
- Retrieve all users or a specific user by ID.
- Update user informations.
- Delete users.

  <h2>📸 API Testing Screenshots</h2>

<div style="margin-bottom: 20px;">
  <h3>1. POST /users – Create User</h3>
  <img src="postuser1.png" alt="POST Create User" style="width: 600px; border: 1px solid #ccc;" />
  <p>This screenshot shows the creation of a new user (Alice) using the POST method.</p>
</div>

<div style="margin-bottom: 20px;">
  <h3>2. GET /users – Get All Users</h3>
  <img src="getallusers.png" alt="GET All Users" style="width: 600px; border: 1px solid #ccc;" />
  <p>This screenshot displays all the users currently stored in memory.</p>
</div>

<div style="margin-bottom: 20px;">
  <h3>3. GET /users/&lt;id&gt; – Get User by ID</h3>
  <img src="getuserbyID.png" alt="GET User by ID" style="width: 600px; border: 1px solid #ccc;" />
  <p>This shows how to fetch a specific user (with ID 1) using the GET method.</p>
</div>

<div style="margin-bottom: 20px;">
  <h3>4. PUT /users/&lt;id&gt; – Update User</h3>
  <img src="updateuser.png" alt="PUT Update User" style="width: 600px; border: 1px solid #ccc;" />
  <p>This screenshot shows how we updated the email address of the user using the PUT method.</p>
</div>

<div style="margin-bottom: 20px;">
  <h3>5. DELETE /users/&lt;id&gt; – Delete User</h3>
  <img src="deleteuser.png" alt="DELETE User" style="width: 600px; border: 1px solid #ccc;" />
  <p>This shows how a user (ID 1) was deleted from the system using the DELETE method.</p>
</div>
