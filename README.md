# My Favorite Movies DB

## Description

Introducing a sleek and intuitive movie tracking experience powered by the Open Movie Database API. With the elegance of HBO GO and the convenience of modern design, this project is your ultimate companion for organizing and remembering your favorite films. Save and categorize your must-watch movies, add personal comments, and mark them as seen or unseen with just a click. Say goodbye to forgetting that blockbuster you've been dying to watch, and hello to effortless movie management with style.

## Powered by Cutting-Edge Tech

Fuelled by the powerhouse combination of Mongoose, MongoDB, Express, Node.js, and React with Vite, this project is a testament to the latest in web development innovation. Seamlessly integrating backend data management with frontend interactivity, it's the perfect marriage of efficiency and elegance. Get ready to experience a fluid, lightning-fast movie tracking solution that's as robust as it is beautiful.

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

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

If you found this project useful and would like to get in touch, feel free to contact me on [LinkedIn](https://www.linkedin.com/in/igirb/). Your feedback and suggestions are always welcome!
