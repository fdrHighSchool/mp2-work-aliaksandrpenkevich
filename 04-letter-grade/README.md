# Letter Grade
#### Respond to the following:

1. Write a plan for the following extension:
  * Attach a "+" on their grade if the grade ends in a 7, 8 or 9 (eg: 78 -> C+, 89 -> B+)
  * Attach a "-" on their grade if the grade ends in a 0, 1 or 2 (eg: 92 -> A-, 61 -> D-)

    * **YOUR WRITING HERE**
We must use the method of checking the last digit in a number to determine whether X >= 7 or X <= 3 is greater

2. Discuss how you would make sure 100 is not misrepresented as an A-.
  * **YOUR WRITING HERE**
  * I would create a separate method for this case, for ex: 
if (n >= 100) {
s = "+";
}

3. Discuss how you would make sure grades that are an F are not mislabeled as F- or F+ (eg: 49 -> F+ and 52 -> F-)
  * **YOUR WRITING HERE**
  
else if (num =< 65) {
            letter = "F";
        }
