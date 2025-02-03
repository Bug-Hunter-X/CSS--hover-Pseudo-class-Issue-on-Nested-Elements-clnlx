# CSS :hover Pseudo-class Issue
This repository demonstrates a common issue with the CSS `:hover` pseudo-class not working as expected when applied to nested elements. The problem is that the inner element's hover style is not triggered when hovering over the outer element.

The `bug.css` file contains the erroneous code, and the `bugSolution.css` file provides the corrected code and explanation.

## Bug
The inner div's background color should change when hovering over the outer div, but it does not.

## Solution
The solution involves carefully examining the CSS selectors' specificity and ensuring that the `:hover` selector is correctly applied and not overridden by other styles.