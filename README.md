# CSS Specificity and Inheritance Bug

This repository demonstrates an uncommon bug related to CSS specificity and inheritance. The bug showcases scenarios where the expected cascading behavior might not occur due to the way browsers handle specificity when nested elements are involved.

## Bug Description

The primary issue revolves around how CSS rules are applied when multiple selectors target the same element. Specifically, the challenge involves understanding how specificity plays a role when inheritance is also at play, especially with nested elements.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css` to view the problematic CSS and its solution.
3. Inspect the corresponding HTML elements in your browser's developer tools to observe the rendered colors.

## Solution

The solution involves a deeper understanding of CSS specificity and using more specific selectors to ensure the desired styling is applied correctly.