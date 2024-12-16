# Unexpected CSS calc() Behavior with Percentages and Units

This repository demonstrates a bug related to unexpected behavior when using the `calc()` function in CSS with a mix of percentages and other units.  The calculated value does not match expectations.

## Bug Description

The `calc()` function in CSS is not producing the correct result when combining percentages and other units. This leads to unexpected layout and styling issues.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`. Note the difference in how `calc()` is handled.
3. Open `index.html` (if applicable) in a browser to view the visual effects of the bug.

## Solution

The solution involves careful consideration of unit conversions and the order of operations within the `calc()` function. This is explained in `bugSolution.css`.