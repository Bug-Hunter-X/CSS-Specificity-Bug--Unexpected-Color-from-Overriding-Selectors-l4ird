# CSS Specificity Bug

This repository demonstrates a common yet subtle bug in CSS related to selector specificity.  The bug arises from the unexpected behavior of CSS selectors with varying levels of specificity.  The provided CSS file (`bug.css`) contains a series of styles that demonstrate this issue. 

The `bugSolution.css` file offers a solution by restructuring the CSS rules or being more specific with classes and IDs to achieve the desired visual result.

## How to Reproduce

1. Clone the repository.
2. Open the `index.html` file (if provided) in your web browser.
3. Observe the unexpected color rendering of the `div` elements.

## Understanding the Problem

CSS specificity determines which style rule takes precedence when multiple selectors apply to the same element.  The level of specificity increases with ID selectors, then class selectors, then element selectors.   The example illustrates how a more specific selector unintentionally overrides other rules.