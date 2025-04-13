# CRUD App

A simple Express.js application that allows users to create, view, edit, and delete posts.

## Features
- View all posts
- Create a new post
- View a single post
- Edit a post
- Delete a post

## Technologies Used
- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- Method-Override
- UUID for unique post identifiers

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/tejaskumavat08/crud-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd post-management-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage

1. Start the server:
   ```sh
   node index.js
   ```
   or with nodemon (if installed):
   ```sh
   npx nodemon index.js
   ```
2. Open your browser and go to:
   ```
   http://localhost:8080/posts
   ```

## Project Structure
```
post-management-app/
│-- views/          # EJS templates
│   │-- index.ejs   # Displays all posts
│   │-- new.ejs     # Form to create a new post
│   │-- show.ejs    # View a single post
│   │-- edit.ejs    # Form to edit a post
│-- public/         # Static assets (CSS, JS, images)
│-- index.js        # Main server file
│-- package.json    # Project dependencies
│-- README.md       # Project documentation
```

## API Endpoints

### GET /posts
Displays all posts.

### GET /posts/new
Renders a form to create a new post.

### POST /posts
Creates a new post and redirects to `/posts`.

### GET /posts/:id
Displays a specific post.

### GET /posts/:id/edit
Renders an edit form for a specific post.

### PATCH /posts/:id
Updates a post's content.

### DELETE /posts/:id
Deletes a post and redirects to `/posts`.



## Future Enhancement
We can add registration and login page for user also we can post the images/videos instead of only text. 

## License
This project is licensed under the MIT License.

---
Feel free to contribute and improve the project!

