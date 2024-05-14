# My Favorite Movies DB

## Description

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Create a `.env` file in the root directory of the project.
3. Add the following line to the `.env` file, replacing `<YOUR_MONGO_DB_URI>` with your MongoDB connection URI:

   ```plaintext
   MOVIE_DB=<YOUR_MONGO_DB_URI>
   
4. Install dependencies by running:

`npm install`

5. Start the server:

`cd server` -> `cd server.js` -> `npm run dev`

6. Start React:

`cd client` -> `cd movie-poster-db` -> `npm run dev`

## Environment Variables

You need to set the following environment variable in your `.env` file:

- `MOVIE_DB`: This variable should contain your MongoDB connection URI.

## Endpoints

- `POST /api/favmovies`: Add a favorite movie to the list.
- `GET /api/favmovies`: Retrieve all favorite movies.
- `PATCH /api/favmovies/:id`: Update a favorite movie's status or comment.
- `DELETE /api/favmovies/:id`: Delete a favorite movie from the list.
