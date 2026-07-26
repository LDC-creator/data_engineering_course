# Milestone 2: Explore the Data

Develop a set of functions and implement the necessary code to calculate and display essential information about the `movies` dataset.

---

<details>
<summary><h4>Prerequisites Content: Task 1</h4></summary>

`1. What is Python?` `2. Google Colab` `3. Variables` `4. Comments` `5. Numbers` `6. Strings` `7. Booleans` `8. Lists` `9. Dictionaries` `10. Tuples` `11. Sets` `12. Intro to Control Flow ` `13. For Loops, Iteration and Control Flow Tricks` `14. Functions `

</details>

<details>
<summary><h3>Task 1: Display all the movies' titles.</h3></summary>

Define a function called `print_every_movie_title` that iterates through the list of movies and prints the title of each movie, one by one. The function should only execute the printing task and should not return any values.

Open this [notebook](../project-data/milestone_2.ipynb) to get started, and follow the instructions for this milestone. You should work in this notebook for each task of this milestone.

</details>

<details>
<summary><h3>Task 2: What is the length of a given movie's description?</h3></summary>

Define a function called `get_movie_description_length` that takes in one of the movies from the list of movies.
You should pass the entire dictionary from the relevant entry in the list of movies as an input argument to the function.
The function should then return the exact number of characters in its description, formatted as an integer.

Test the function you have defined by using it to check the description of the the first entry in the `movies` list (i.e. `movies[0]`).

</details>

<details>
<summary><h3>Task 3: What is the average length of any movie description?</h3></summary>

Define a function called `get_avg_movie_description_length` that returns the average number of characters in each movie description, averaged across the whole dataset.
The function should return a floating point number, rounded to 1 decimal place.

To avoid repeating code, make sure that you use the function you defined earlier for getting the movie description length inside this function.

</details>

<details>
<summary><h3>Task 4: What is the maximum length of any movie name?</h3></summary>

Define a function called `get_max_movie_name_length`.

It should return two things, in this order:

- The length of the longest movie name, formatted as an integer
- The name of the movie

</details>

