# CSS Inheritance Issue with Nested List Items

This repository demonstrates an uncommon CSS bug related to inheritance and specificity when styling nested list items.  The main CSS file (`bug.css`) contains a rule that should apply a red background color to all list items. However, due to how inheritance and specificity interact, this doesn't work consistently for nested list items.

The solution file (`bugSolution.css`) provides a corrected approach to ensure all list items consistently inherit the background color.