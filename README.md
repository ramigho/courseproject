# courseproject
Basics in Python Programming course project.


# about the project
This program processes open-source weather data collected from Finnish Meteorological Institute.

The user can input a weather data text file (.csv-format) of some FMI observation station (i.e. Kumpula, Helsinki) and process the data to obtain the amount of sunshine time per time units in some period.

Note! The data has to be in correct format and stored in the same directory as the program files. See formatting from example data sets provided in the reposetory. 


Program was created as a final project for Basics in Python programming course in 2021 by Rami Ghoniem.

The program's language is Finnish. Functions, variables and comments in the source code written in Finnish aswell.  




# how to use the program
Run the program from file taivoitetaso.py

Data processing and saving is done in file HT_kirjasto.py

Program begins with displaying its menu in the console. 

Select operation by entering its number (1-9), the program ends with command 0 (Lopeta).

Enter 1 to enter the name of the observation station and a year to review, i.e. Kumpula, 2018

Enter 2 (or 5) to read the data into the program's data structures. 

Enter 3 to analyze daily weather information.

Enter 4 to save the result of analysis in selection (3) to a text file. 

Enter 6 to analyze monthly weather data and 7 to save the result in a text file. 

Enter 8 to analyze hourly weather data and 9 to save the result in a text file. 

Enter 0 to end the program.



The project's reposetory contains some text files from the Finnish Meteorological Institute for the user to play with. 
