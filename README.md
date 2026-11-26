# Testing Fare Calculator

This program calculates ticket prices based on age.

Rules are:
Children between 0 and 12 years old pay 50 SEK.
Visitors between the ages of 13 and 64 pay 100 SEK.
Visitors who are 65 years of age or older pay 80 SEK.
If the age is a negative number, the program should return a ValueError.

In the given code I spotted an error. The code basically charges 13 year old visitors 50SEK instead of 100SEK. This was a simple fix, just had to change the number from 13 to 12.
However I've spotted another mistake where the test does not check for age 12, 13 and also 64. I'm gonna add the boundaries for it so whenever the test is ran it also check's the max limit age for the values presented. Unsure if this is needed but I'll add it just in case.

After adding the checks for age 12, 13 and 64 I have tested and gotten 15 passes total, meaning that...well everything works

Please ignore the extra files, I had to fix my VS Code and I do not have the energy to fix this folder fully. Sorry :(