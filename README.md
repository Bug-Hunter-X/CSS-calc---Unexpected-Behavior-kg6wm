# CSS calc() Unexpected Behavior

This repository demonstrates a common issue with the CSS `calc()` function where unexpected results can occur due to floating-point numbers and order of operations. The `bug.css` file shows the problematic code, while `bugSolution.css` provides a solution.

## Problem

The `calc()` function is powerful, but it can produce unexpected output if not used carefully. Incorrect rounding and unexpected order of operations are common problems.

## Solution

The solution involves using explicit units and carefully considering the order of operations within the `calc()` function.  In some cases, avoiding `calc()` altogether and using pre-calculated values might be necessary for consistency across different browsers.