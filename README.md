# Uncommon CSS `calc()` Errors
This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS.  The `bug.css` file shows examples of these errors, while `bugSolution.css` provides corrected versions.  These errors often stem from unit incompatibility and the omission of spaces around arithmetic operators.

**Common Problems**

* **Unit Incompatibility:**  `calc()` requires compatible units in its expression; mixing incompatible units will lead to unexpected outcomes or parsing errors.
* **Missing Spaces:**  Spaces are mandatory around the +, -, *, and / operators within the `calc()` function.  Missing spaces can cause unexpected behavior or render the calculation invalid.