# Voting Eligibility System

## Project Details

**Project Name:** Voting Eligibility System\
**Project Type:** Python Console-Based Project

## Description

The Voting Eligibility System checks whether a person is eligible to
vote based on their age and Indian citizenship.

A person is eligible to vote if: - Their age is 18 years or above. -
They are an Indian citizen.

The program also validates user input and displays a final summary of
the people checked.

## Requirements

-   Python 3.x
-   Any Python editor or IDE (IDLE, VS Code, PyCharm, etc.)

## How to Run

1.  Save the program as `voting_eligibility_system.py`.

2.  Open a terminal or command prompt in the folder containing the file.

3.  Run:

    ``` bash
    python voting_eligibility_system.py
    ```

## Program Features

-   Accepts the person's name.
-   Accepts and validates age (0 to 120).
-   Accepts citizenship input (`y` or `n`).
-   Checks voting eligibility.
-   Shows the reason when a person is not eligible.
-   Allows checking multiple people in one run.
-   Displays a final count/summary.

## Sample Test Cases

  -----------------------------------------------------------------------
  Test                    Input                   Expected Result
  ----------------------- ----------------------- -----------------------
  Normal case             Aman, 25, Indian        Eligible
                          citizen (`y`)           

  Boundary case           Neha, 18, Indian        Eligible
                          citizen (`y`)           

  Below age limit         Ravi, 17, Indian        Not eligible; 1 year
                          citizen (`y`)           left

  Invalid age input       Amit, `abc`, `-5`, then Invalid entries
                          `30`; citizen `y`       rejected; age 30
                                                  accepted; Eligible

  Non-citizen             Riya, 30, citizen (`n`) Not eligible; not an
                                                  Indian citizen
  -----------------------------------------------------------------------

## Input Validation

-   Age must be a whole number between 0 and 120.
-   Non-numeric age entries are rejected.
-   Negative ages and ages above 120 are rejected.
-   Citizenship must be entered as `y` or `n`.

## Files

-   `voting_eligibility_system.py` --- Python source code.
-   Output screenshots --- examples of program execution.
-   Test cases --- inputs and expected outputs.

## Author

Ankit Jha
