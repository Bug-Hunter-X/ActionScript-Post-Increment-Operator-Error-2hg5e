# ActionScript Post-Increment Operator Bug

This repository demonstrates a common error in ActionScript related to the post-increment operator (`++`).  The bug arises from attempting to use a variable's value and then incrementing it within the same statement. ActionScript's handling of this situation results in a runtime error. 

## Bug Description

The provided `bug.as` file contains a function that attempts to use `someVar` in a `trace` statement and then increment it using the post-increment operator (`++`) in the same line. This leads to an error. 

## Solution

The `bugSolution.as` file provides a corrected version of the code. To fix the bug, the increment operation should be separated into a distinct line of code, ensuring the trace statement uses the correct value of `someVar` before modification.