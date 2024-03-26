# Random-Number-Generator
This code generates a sequence of random numbers and saves them to a CSV file named 'random_numbers.csv'.

Importing Libraries: The code imports the csv module and the random module.

Defining Parameters: The total number of random numbers to generate is set to 50,000.

Calculating Number of Numbers in Each Range: Based on a specified percentage, the code calculates the number of numbers to generate in the ranges 15-20 and 10-14, 26-30.

Generating Random Numbers: Random numbers are generated within each range using list comprehensions and the random.randint() function. For the range 10-14, 26-30, the random.choice() function is used to select a random number between 10-14 or 26-30.

Combining Random Numbers: The generated lists of random numbers are combined into a single list called random_numbers.

Shuffling the List: The list of random numbers is shuffled to randomize the order.

Writing to CSV File: The random numbers are written to a CSV file named 'random_numbers.csv'. Each number is written in a separate row under the column header 'Random Numbers'.

Print Confirmation: Finally, a message is printed to confirm that the random numbers have been saved to the CSV file.

![Random Numbers](https://github.com/IndikaAnuradha/Random-Number-Generator/assets/122884553/7900693c-8593-4eb8-929e-1158eb011979)
