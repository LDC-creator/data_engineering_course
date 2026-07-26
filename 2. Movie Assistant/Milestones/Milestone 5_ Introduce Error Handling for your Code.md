# Milestone 5: Introduce Error Handling for your Code

Currently, the code is very fragile, and will easily break if the user selects an invalid genre or movie, for example.
It's time to fix this by raising the right errors in the right places.

---

<details>
<summary><h4>Prerequisites Content: Task 1</h4></summary>

`1. What is Python?` `2. Google Colab` `3. Variables` `4. Comments` `5. Numbers` `6. Strings` `7. Booleans` `8. Lists` `9. Dictionaries` `10. Tuples` `11. Sets` `12. Intro to Control Flow ` `13. For Loops, Iteration and Control Flow Tricks` `14. Functions ` `15. Error Handling with Control Flow`

</details>

<details>
<summary><h3>Task 1: Validate the user's genre choice.</h3></summary>

Redefine the `get_user_genre_choice` function to validate the input and make sure that it's actually one of the genres from the dataset.

If the value is not valid, then raise an error.

Open this [notebook](../project-data/milestone_5.ipynb) to get started, and follow the instructions for this milestone. You should work in this notebook for each task of this milestone.

</details>

<details>
<summary><h3>Task 2: Raise a specific type of error.</h3></summary>

Raise a `ValueError` with a useful error message `"This is not a valid genre"`.

</details>

<details>
<summary><h3>Task 3: Handle the error.</h3></summary>

If the genre selected is not valid, and your code successfully raises an error when that is the case, handle the error so that instead of your code failing and stopping, it asks the user to try again.

HINT: You may want to use an infinite `while` loop, and break out of it only if the error is not raised.

The code should handle only the specific type of error that is raised if the genre is not valid.

</details>

