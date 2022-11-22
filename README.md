# nuwe_coding_exercice1 ✏

What is the smallest positive number that is evenly divisible by all of the numbers from 1 to 20?

## solution 📔

Instead of going crazy with Bucles , we make use of 2 methods:
1. lcm() : Finds Lowest common multiple of specified numbers (the downside is that it doesn't accept lists)
2. reduce() : Allows us to pass the lcm() as a function and apply it to an iterable containing a range from 1 to 20
