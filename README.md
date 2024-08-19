In this practice project, the main objective was to get user input, 
compare the input with a set of pre-defined answers,
and output a response after comparing the users response to the answers.

For my first attempt i wanted to create a list of strings which contained related locations, 
in this regard i created a list of areas in and around cape town and wanted to ask the user to name one place in cape town and check if the place they named was in this area.
The first iteration does this well enough although with a few limitations.
With the time constraint of only 30 minutes however, it was satisfactory.

For the second attempt i used an array to store the answers and created a score variable, effectively making it a quiz game and adding a degree of complexity to the challenge.
The time constraints remain the same (30 min) only this time I had the first iteration to work from.
Meaning that i had some time to look into different ways other developers have solved similar problems online.
Leading me to come across this block of code:

if (Array.Exists(testStrings, element => element.Equals(answer, StringComparison.OrdinalIgnoreCase)))       
            return true;
        else
            return false;
            
This if statement reduced the lines of code i would have to write in order to compare the possible user inputs and the pre-defined answers
