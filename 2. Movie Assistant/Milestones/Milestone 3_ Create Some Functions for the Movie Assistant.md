# Milestone 3: Create Some Functions for the Movie Assistant

Build the individual components of the system that will later be composed to produce the entire solution.

---

<details>
<summary><h4>Prerequisites Content: Task 1</h4></summary>

`1. What is Python?` `2. Google Colab` `3. Variables` `4. Comments` `5. Numbers` `6. Strings` `7. Booleans` `8. Lists` `9. Dictionaries` `10. Tuples` `11. Sets` `12. Intro to Control Flow ` `13. For Loops, Iteration and Control Flow Tricks` `14. Functions ` `15. Error Handling with Control Flow` `16. Assertions` `17. Context Managers`

</details>

<details>
<summary><h3>Task 1: Load in the full `movies` dataset from a file.</h3></summary>

Using a context manager, you will open the file `movies.json` and load the data from this file into a variable called `movies`. A `JSON` file is a text-based data format used for storing and exchanging structured information, often in configuration, data storage, or data exchange between different programs. To open a `JSON` file and use it with a context manager you will need to run the following line first: `import json`. This will make the functionality of the `json` module available for use in your Python program, allowing you to work with `JSON` data, including reading and writing.

You should open the file, as with any context manager, using the `with` statement, and then you can use the `json.load(filename)` function to load the contents of the `JSON` file (which in this example is called `filename`), and parse it into a Python data structure. You should store the results in the variables `movies`.

Put this inside a function named `load_movies_data` which takes no parameters and returns the list of movies, each as a dictionary.

Open this [notebook](../project-data/milestone_3.ipynb) to get started, and follow the instructions for this milestone. You should work in this notebook for each task of this milestone.

</details>

<details>
<summary><h3>Task 2: What are the unique genres?</h3></summary>

Define a function called `get_unique_genres` that returns a set of unique genres. The function should return a set, not a list.

</details>

<details>
<summary><h3>Task 3: Filter by genre.</h3></summary>

Define a function called `get_movies_in_genre` which returns a list of only movies in that genre. The function should take in a genre as a string.

The movies should be returned in their usual dictionary format.

</details>

