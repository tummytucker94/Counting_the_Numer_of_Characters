# 2: Counting_the_Numer_of_Characters

Programming Language: Python
Goal: To get comfortable using basic sequential operations (input, process, output) in creating programs.

Constraints:

  --Be sure the output contains the original string.
  --Use a single output statement to construct the output.
  --Use a built-in function of the programming language to determine the length of the string.

Understanding the Problem
  What are the features of this application (or program)?
    --Prompts for an input string
    --Prints output that shows the input string and the number of characters that the string contains
  
  Problem Statement:
    Create a program that prompts for an input string and then prints output that shows the input string and the number of characters that the string contains.
------------------------------------------------------------------------

Discover the Inputs, Processes, Outputs (IPO)
  Input:
    --string
  
  Process:
    --prompts
    --prints
    
  Output:
    --string
    --number_of_characters
-------------------------------------------------------------------------

Test Plan
  Input:
    --name: "Jermaine Tucker"
  
  Expected Results:
    --Jermaine Tucker has 15 characters.
    
  Actual Results:
    --Jermaine Tucker has 15 characters.
--------------------------------------------------------------------------

Algorithm in Psuedocode
  1)Start
  2)Get a value for "string" by prompting the user with the message 'What is the input string? '
  3)Set the value of "name_of_string" to the function that counts the length of a string and set its parameters to the value of "string".
  4)Print the message ' "string", has, "num_of_characters", characters. '
  5)Stop
