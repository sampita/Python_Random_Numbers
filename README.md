# Python_Random_Numbers

Practice: Random Numbers
Instructions
Use the following code to create a list of 10 random numbers. Each number will be between 0 and 6.

import random

my_randoms = list()
for i in range(10):
    my_randoms.append(random.randrange(1, 6))
The my_randoms list will now contain random numbers

[1, 3, 1, 2, 4, 2, 5, 4, 2, 5]
Then iterate a different list of numbers that are sequential from 1 to 10. Use the following code as your starting point.

import random
"""
Print a message to the console indicating whether each value of
`number` is in the `my_randoms` list.
"""

my_randoms = list()
for i in range(10):
    my_randoms.append(random.randrange(1, 6))

# Generate a list of numbers 1..10
numbers_1_to_10 = range(1, 11)

# Iterate from 1 to 10
for number in numbers_1_to_10:
    the_numbers_match = False

    # Iterate your random number list here

    # Does my_randoms contain number? Change the boolean.

    print(f'{number} is in the random list')
Example Output in the Terminal
my_randoms list contains 0
my_randoms list does not contain 1
my_randoms list does not contain 2
my_randoms list contains 3
my_randoms list contains 4
my_randoms list does not contain 5
NOTE: Each run will produce different output.
