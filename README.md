# Buggy python code
## Overview
This project demonstrates testing and debugging a Python program using Python's unittest framework. It follows the RED → FIX → GREEN cycle to identify bugs, correct the implementation, and verify the results using unit tests.

## Files
student_utils.py — Contains functions for calculating average marks, checking passing status, and assigning grades.
test_student_utils.py — Contains nine unit tests to verify the expected behavior of the functions.
red_output.txt — Records the test results before fixing the bugs.
green_output.txt — Records the test results after fixing the bugs.
## Bugs Identified
Average calculation: The incorrect denominator produces an incorrect average and causes division by zero for a single mark.
Passing boundary: A mark of 40 is incorrectly treated as failing.
Grade ordering: The distinction condition is checked after the first-grade condition.
## How to Run the Tests
Make sure Python is installed, then run this command from the project directory:

python test_student_utils.py
## Expected Result
After fixing the bugs, all nine tests should pass, and the output should display OK.

## Testing Process
RED: Run the tests against the buggy implementation and record the failures.
FIX: Correct the bugs in student_utils.py without changing the test expectations.
GREEN: Run the same tests again and confirm that all nine tests pass.
## Conclusion
This project demonstrates how unit testing helps identify programming errors and verifies that code corrections produce the expected behavior.
