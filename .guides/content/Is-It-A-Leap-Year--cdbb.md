## Task
Write a program called `challenge4.py` that:
 - allows a user to enter an integer (the year)
 - outputs a message stating whether it’s a leap year or not.
 

## Advice

How to calculate whether it's a leap year.

 1. If the year is evenly divisible by 4, go to step 2. Otherwise, go to step 5.
 2. If the year is evenly divisible by 100, go to step 3. Otherwise, go to step 4.
 3. If the year is evenly divisible by 400, go to step 4. Otherwise, go to step 5.
 4. The year is a leap year.
 5. The year is not a leap year.
 
## Test Data
Here is some test data to use:

| Test Data     | Exp. Output     |
| ------------- | --------------- |
| 1992          | Leap Year       |
| 2000          | Leap Year       |
| 1900          | Not a Leap Year |

Now pick a few more years yourself to use as test data.