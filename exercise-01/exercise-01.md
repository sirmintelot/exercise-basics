# Exercise 01 - Function basics

## Aim

In this exercise, we learn how to write basic functions that can be tested.

## Exercise

Write a function that takes in a number of at least 0 and returns a grade as string.

There are multiple grades:

- 0 - 50: N
- 51 - 70: R
- 71 - 90: SR
- 91 - 100+: UR

## Proposed Solution

I would firstly try and breakdown the steps required to form this function. 

Step 1: Accept an input of at least 0 or more. This input data value would be most suited as a integer as we will later need to take this value and step parameters within a number range to categorise it's grade

Step 2: We can then go for a if / elif statement to cover off 99% of ranges

I would therefore type:


number = int(input("What is the number?: "))

if number >90:

  print("Your Grade is UR")
  
elif number >70:

  print("Your Grade is SR")
  
elif number >=50:

  print("Your Grade is R")
  
else:

  print("Your Grade is N")

Step 3: I would then need to close off any fringe or "edge" outcomes on this code, such as if the number was in the negative: i.e. -1. 

Step 4: Amend code with an appropriate solution.



