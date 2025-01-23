# CSS calc() Unexpected Results

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with a mix of percentages and other units (like pixels).  The order of operations and unit compatibility can cause unexpected layout behavior.

The `bug.css` file contains the problematic CSS, while `bugSolution.css` provides a corrected approach.

## Problem
The `calc()` function in CSS, while powerful, can be tricky when combining percentages and fixed units.  The order of operations and unit compatibility can lead to inconsistencies and unexpected layout results.

## Solution
The solution often involves careful consideration of the order of operations and ensuring units are compatible.  In some cases, alternative approaches, such as using Flexbox or Grid, may provide a more reliable and predictable layout.