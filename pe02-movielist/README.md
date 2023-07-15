This is a React project that implements a Movie List component with filtering functionality. The component displays a list of movies and allows users to filter the movies based on their genre. Additionally, clicking on a movie will trigger an alert displaying the movie title.

INPUT:

The Movie List component takes an array of movie objects as input. Each movie object has the following properties:

Title (string): The title of the movie.
Genre (string): The genre of the movie.
ReleaseYear (number): The year the movie was released.
The movie data is provided within the component itself in the moviesData array.

PROCESS:
The Movie List component processes the input data and performs the following steps:

Renders the list of movies:

Iterates over the movie data array and displays each movie as a separate list item or card.
Displays the movie title, genre, and release year for each movie.
Implements the filter functionality:
Creates a dropdown select element that contains all the unique genres from the movie data.
When the user selects a genre from the dropdown, filters the movies based on the selected genre and displays only the movies that match the selected genre.
If the user selects "All Genres" from the dropdown, displays all the movies.

Handles user events:
When the user clicks on a movie, triggers an alert with the movie title.

OUTPUT:

The Movie List component renders the following output:

.A list of movies with the movie title, genre, and release year displayed for each movie.
.A dropdown select element for filtering the movies by genre.
.An alert with the movie title displayed when a movie is clicked.






