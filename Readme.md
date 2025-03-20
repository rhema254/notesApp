# Note Taking App

A Flask-based note-taking application with MongoDB for data storage, JWT authentication for security, Jinja templates for rendering HTML, and JavaScript for client-side interactivity.

## Features

- **User Authentication**: JWT-based authentication for secure login and registration.
- **CRUD Operations**: Users can create, read, update, and delete notes.
- **MongoDB Integration**: Notes and user data are stored securely in MongoDB.
- **Jinja Templating**: Server-side rendering with Jinja templates.
- **JavaScript Enhancements**: Dynamic UI updates without page reloads.
- **RESTful API Endpoints**: API access for authentication and notes management.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. **Create a Virtual Environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up Environment Variables**
   Create a `.env` file in the project root and add all the env variables in `config.py`:
   
5. **Run the Flask App**
   ```bash
   flask run
   ```

## API Endpoints

### Authentication
- `POST /register` - Register a new user.
- `POST /login` - Authenticate and get a JWT token.

### Notes Management
- `GET /notes` - Retrieve all notes for the authenticated user.
- `POST /notes` - Create a new note.
- `PUT /notes/<note_id>` - Update a specific note.
- `DELETE /notes/<note_id>` - Delete a specific note.

## Frontend
- Uses Jinja for rendering templates.
- JavaScript for enhancing user interactions (e.g., dynamic note updates, AJAX requests).

## Technologies Used
- **Flask**: Backend framework
- **MongoDB**: NoSQL database
- **JWT**: Authentication mechanism
- **Jinja**: Server-side templating
- **JavaScript**: Frontend interactivity

## Contributing
Feel free to fork the repository and submit a pull request!

## Contact
For any issues, reach out via [GitHub Issues](https://github.com/rhema254/notesApp/issues).

