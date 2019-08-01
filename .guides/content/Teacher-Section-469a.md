## Skills required
Students will need to be able to:

 - use multiple criteria with boolean operators (AND, OR)
 - apply modular arithmetic
 
## Advice
Students need to know how modular arithmetic works before tackling this challenge.

The solution to this challenge need only be a few lines of code but the hardest part for many students is to take the guidance they are given about calculating leap years and representing it with code.

Make sure that students are aware of how leap years are calculated. Many will think that if the year is divisible by 4 then it must be a leap year - this is incorrect. Please see below:

### How to calculate a leap year

 1. If the year is evenly divisible by 4, go to step 2. Otherwise, go to step 5.
 2. If the year is evenly divisible by 100, go to step 3. Otherwise, go to step 4.
 3. If the year is evenly divisible by 400, go to step 4. Otherwise, go to step 5.
 4. The year is a leap year.
 5. The year is not a leap year.

Please see this page for further information: https://support.microsoft.com/en-us/kb/214019

## Solution

    year = int(input("Enter a year"))
    if year % 4 == 0 and (year % 100 != 0 or year % 400 == 0):
      print("LEAP YEAR")
    else:
      print("NOT A LEAP YEAR")