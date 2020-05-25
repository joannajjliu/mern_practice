### Notes:
- backend folder is usually separate from frontend folder:
    - But for simplicity, both folders will be located in the same location, for this app.
### Folders: 
- backend: mongoose "models" and express HTTP "routes"
- src: App.js and "components" folder for React front-end code
### Dependencies/ 3rd party packages:
#### Backend dependencies:
- Express:
    - Bodyparser is included in new versions of Express (since mid-2019)
- Cors: "cross origin resource sharing",
    - allows resource access from remote hosts (skipping same origin policy)
    - provides express middleware: access something outside our server, from within our server
- Mongoose: Allows easier interaction with MongoDB through NodeJS
- Dotenv: 
    - Loads environment variables from .env file, into process.env
    - Makes development simpler; don't need to set env variables on our machine, can be stored in a file instead
#### Frontend dependencies:
- Axios: connecting frontend with HTTP request, and response data (for CRUD operations)
- bootstrap: css library
- react-datepicker
- react-router-dom