# Outside-In API Testing Challenge 

## Objectives
- Test-drive a new API endpoint to add a review to your database

### Features:
- Test-drive a `POST` request to an endpoint for a new review that successfully adds that data to your database and returns success status in JSON response 
- As it currently stands, the existing API routes in this repository use a local data store (`movies.JSON`) instead of a database. You will need to replace this functionality with connection to an actual PostgreSQL database for the `POST` route you are responsible for creating.

### Back End Service Setup:
- Fork and clone this repository using git
- To install dependencies, `cd` into the `server` folder run `npm install`
- To start the server, run `npm run start`
- The server will be available at `http://localhost:{port}` (`port` is specified in the `app.js` file) 

#### Existing Service Endpoints
- `GET /` - returns `{greeting: "Hello World"}`
- `GET /movies` - returns a list of all movies
