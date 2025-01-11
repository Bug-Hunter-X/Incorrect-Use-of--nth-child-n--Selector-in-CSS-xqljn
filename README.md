# Incorrect Use of :nth-child(n) Selector in CSS
This repository demonstrates a common error when using the `:nth-child(n)` selector in CSS to style elements. The original CSS contains a flawed implementation, leading to incorrect styling. A solution is provided to correct the selector logic.

## Bug
The bug lies in the `bug.css` file where the `:nth-child(n)` selector was used to target every other list item. However, due to an error in the calculation, this logic only partially achieves the intended effect. 

## Solution
The corrected CSS in `bugSolution.css` demonstrates the proper use of the `:nth-child(n)` selector to successfully style every other list item. This example illustrates the importance of carefully choosing the correct formula for the `n` parameter to select the target elements accurately.

