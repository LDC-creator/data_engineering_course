# Milestone 4: Build the Movie Assistant

In this milestone, we will put together the functions we have defined so far and build the complete movie assistant project. The goal is to write some code that will ask the user to select a genre and then select a movie from a list presented.
Once they do that, they should see the details of that movie printed.

---

<details>
<summary><h3>Task 1: Ask the user what genre they are interested in.</h3></summary>

Before you ask a user for their input, print out all of the available options.

Get this from your `get_unique_genres` method defined earlier.

Then, take a user input using the `input()` function and assign it to the variable `genre_choice`.

Put all of this in a function called `get_user_genre_choice`.

Open this [notebook](../project-data/milestone_4.ipynb) to get started, and follow the instructions for this milestone. You should work in this notebook for each task of this milestone.

</details>

<details>
<summary><h3>Task 2: Show the movies in the selected genre.</h3></summary>

Write some code to show the user the movies in the genre they selected.

Use your `get_movies_in_genre` function to get a list of movies in the genre selected.

Print each movie within the selected genre on a new line. At the start of the line, print the integer index of the movie.

Make sure to:

- Use the built-in `enumerate` function
- Use an f-string to format the printed text

To avoid confusing users, make the indexing start from 1 rather than zero. For example, one line should look something like: `"3: The Dark Knight"`.

</details>

<details>
<summary><h3>Task 3: Select and display the details of a movie.</h3></summary>

Define a new function called `get_movie_by_index`. The function should do the following:

- Print out all the movies in the genre selected
- Ask the user to select a movie by entering the index of the movie
- Assign this to a variable named `selected_movie_index`
- Print the key-value pairs of the selected movie's dictionary each on a new line
- On each line, print the key and the value, separated by a comma  (`,`)
- The program should end after this

HINT: Be careful of what data type is returned from the `input()` function, and ,ake sure to use the `.items()` method of the dictionary to get the key-value pairs.

</details>

