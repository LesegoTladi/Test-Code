# Testing Your Code

Welcome to my "Testing Your Code" repository! This notebook is designed to help me practice debugging and testing Python functions. The challenge involves identifying and fixing errors in the provided functions, ensuring they produce the expected outputs. I'll be using an autograder to verify my solutions.

## Instructions

- **Do not add or remove cells** in the notebook. **Do not edit or remove** the `### START FUNCTION` or `### END FUNCTION` comments. Any structural changes will result in a mark of 0%.
  
- I need to read each question carefully, identify what the function is supposed to do, and fix the errors in the provided code to get the correct result.

- After fixing the code, I will use the **autograder** to test my solutions.

- While I'm allowed to use online resources like Google or StackOverflow, **I cannot copy** code from other students. Doing so will result in a mark of 0%, as it violates the honor code.

---

## Honor Code

By submitting this notebook, I confirm that the solutions I provide are my own work and that I am following the [EDSA Student Manifesto](https://drive.google.com/open?id=1FXCIf425JLRx3JQi-ltSWppj8BCF3Np1).

Not adhering to the honor code will lead to a mark of 0%.

---

## Challenge Overview

There are three functions in this notebook that contain errors. My task is to identify what each function is supposed to do based on the expected outputs and fix the code accordingly.

---

## Functions to Fix

### Function 1: `function_1(a, b)`

This function is supposed to perform a mathematical operation on the two inputs, `a` and `b`, but the logic is incorrect. I need to adjust the code to produce the correct output.

```python
### START FUNCTION
def function_1(a,b):
    c = (a * b) - a
    return c
### END FUNCTION
Expected Outputs:

python
Copy
function_1(1,1) == 0
function_1(1,2) == 1
function_1(5,2) == 5
function_1(5,6) == 25
function_1(-5,-6) == 35
Function 2: function_2(a, b)
In this function, the condition checks the value of a, but the code doesn't produce the expected result. I'll need to modify it so that it works as intended.

python
Copy
### START FUNCTION
def function_2(a,b):
    if a < 2:
        return a
    else:
        return b
### END FUNCTION

Expected Outputs:
function_2(1,1) == 1
function_2(1,2) == 1
function_2(5,2) == 2
function_2(5,6) == 6
function_2(-5,-6) == -5

Function 3: function_3(a, b)
This function should return a tuple based on the values of a and b, but currently, it doesn't work correctly. I need to fix the logic to return the expected tuple.
### START FUNCTION
def function_3(a,b):
    c = a*b*2
    return (c,c-1)
### END FUNCTION

Expected Outputs:
function_3(1,1) == (2,1)
function_3(1,2) == (4,3)
function_3(5,2) == (20,19)
function_3(5,6) == (60,59)
function_3(-5,-6) == (60,59)


## How I Will Use This Notebook
1. Fix the Errors:
   I will carefully read through each function, compare it with the expected output, and modify the code to ensure it works correctly.

2.Test My Code:
  Once I’ve made my changes, I’ll run the tests to check if my solutions are correct, and if not, I’ll examine the error messages and adjust the code 
  accordingly.

3.Submit My Code:
  Once I’m confident that all errors are fixed, I’ll submit the notebook for grading, and the repository is licensed under the MIT License – see the 
  LICENSE file for details.
