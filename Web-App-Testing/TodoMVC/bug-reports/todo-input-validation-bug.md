# Bug Report: Input Validation Issue

## Title
Single-character input is not saved under certain conditions

## Description
When entering a single character as a task, it is not saved. However, in some cases where additional hidden input is present (e.g., non-visible special character), the task gets saved successfully.

## Steps to Reproduce
1. Open TodoMVC application
2. Enter a single character (e.g., "a")
3. Press Enter

## Expected Result
The task should be saved successfully

## Actual Result
The task is not saved

## Additional Observation
When input includes additional non-visible characters (e.g., copied text), the task gets saved

## Impact
Leads to inconsistent input handling and may confuse users

## GitHub Issue Link
[(Check this out)](https://github.com/tastejs/todomvc/issues/2291#issue-4135264886)
