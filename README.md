# CSS Calc() Percentage Calculation Issues

This repository demonstrates a common issue with the CSS `calc()` function when using percentages, especially within nested elements. The problem arises from the order of calculation and how percentages are resolved within the context of parent elements.

The `bug.css` file showcases the buggy implementation, and `bugSolution.css` provides a corrected version.  Read the comments in the CSS files for details. This issue can manifest as incorrect element sizing or layout discrepancies.  The solution often involves restructuring the CSS, making calculations more explicit, or using alternative layout methods to avoid the complex percentage calculations within `calc()`.