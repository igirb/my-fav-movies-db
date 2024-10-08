# My Favorite Movies DB

<div>
  <br />
    <a href="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_1.png">
      <img src="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_1.png" alt="Project Banner">
    </a>
  <a href="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_2.png">
      <img src="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_2.png" alt="Project Banner">
    </a>
  <a href="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_3.png">
      <img src="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_3.png" alt="Project Banner">
    </a>
  <a href="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_4.png">
      <img src="https://github.com/igirb/my-fav-movies-db/blob/main/assets/moviedb_4.png" alt="Project Banner">
    </a>
  <br />
  <div />

## Description

Introducing a sleek and intuitive movie tracking experience powered by the Open Movie Database API. With the elegance of HBO GO and the convenience of modern design, this project is your ultimate companion for organizing and remembering your favorite films. Save and categorize your must-watch movies, add personal comments, and mark them as seen or unseen with just a click. Say goodbye to forgetting that blockbuster you've been dying to watch, and hello to effortless movie management with style.

## Powered by Cutting-Edge Tech

Fuelled by the powerhouse combination of Mongoose, MongoDB, Express, Node.js, and React with Vite, this project is a testament to the latest in web development innovation. Seamlessly integrating backend data management with frontend interactivity, it's the perfect marriage of efficiency and elegance. Get ready to experience a fluid, lightning-fast movie tracking solution that's as robust as it is beautiful.

<a href="https://react.dev/" target="_blank">
  <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
</a>
<a href="https://www.mongodb.com/" target="_blank">
  <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248" alt="mongodb" />
</a>
<a href="https://nodejs.org/" target="_blank">
  <img src="https://img.shields.io/badge/-Node_JS-black?style=for-the-badge&logoColor=white&logo=node.js&color=339933" alt="node.js" />
</a>
<a href="https://expressjs.com/" target="_blank">
  <img src="https://img.shields.io/badge/-Express_JS-black?style=for-the-badge&logoColor=white&logo=express&color=000000" alt="express.js" />
</a>
<a href="https://mongoosejs.com/" target="_blank">
  <img src="https://img.shields.io/badge/-Mongoose-black?style=for-the-badge&logoColor=white&logo=mongoose&color=880000" alt="mongoose" />
</a>

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
