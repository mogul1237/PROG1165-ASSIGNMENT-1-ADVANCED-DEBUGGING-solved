# PROG1165-ASSIGNMENT-1-ADVANCED-DEBUGGING-solved

Download Here: [PROG1165 ASSIGNMENT 1 ADVANCED DEBUGGING solved](https://jarviscodinghub.com/assignment/prog1165-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

INTRODUCTION Well-designed applications should never “crash”; they should deal with exception or error scenarios in a clean and controlled manner. However, there are times when these exception conditions (even in production) should be noted and reviewed by the development team. A “logger” is often used to record key data when a problem occurs in your code. In the Windows environment, the Event Log is an example of a repository for logged information. Often, a simple text file can be used as well.
In this assignment, you will be implementing a simple logging facility.
REQUIREMENTS Here are the requirements for error logging:
– A function called LogError must write an error message to a text file, to the debug console, or to the program console. This message must contain the following information: o Date and time of occurrence o Error message (passed to the function as a parameter) – Use #define statements to identify: o The output mechanism for the errors (text file, debug console or program console) o The file path for the text file for the error log – Use conditional compile statements in the LogError function to determine where the error message output should go
Write a test program that demonstrates the use of the LogError function. Initially, write a program that does the following WITHOUT the error logging:
– Ask for the user’s age – If the input is non-numeric, you should give the user a friendly message stating that the input is nonnumeric – If the input is null (empty string), you should give the user a friendly message stating that the input cannot be blank – If the input is less than 1 or greater than 110, you should give the user a friendly message stating that the input is out of range – If the age is valid (positive integer), simply say “Thank You” and end the program – If there is any error in the age, the age should be asked for again
Once the program works, add error logging function calls in appropriate places to record where users make errors.
SUBMISSION GUIDELINES
PLEASE READ AND UNDERSTAND THE SUBMISSION GUIDELINES BELOW. FAILURE TO CORRECTLY SUBMIT ANY REQUIRED COMPONENT WILL RESULT IN 10% PENALTY PER MISSING OR INCORRECT COMPONENT.
PAPER SUBMISSION There is no paper submission required for this assignment.
DO NOT SUBMIT THIS ASSIGNMENT SPECIFICATION AS A PART OF YOUR DOCUMENT.
ELECTRONIC SUBMISSION Exactly ONE item will be submitted electronically.
• Upload a single zip file of your COMPLETE, CLEANED source code.
Complete file naming and upload guidelines are provided below.
ELECTRONIC SUBMISSION AND FILE NAMING Often, multiple groups will name their assignment files assignment1.zip (or some other common combination) which results in confusion and complications when downloading and unzipping submitted electronic files.
Please follow the following guidelines for all submissions this term. Failure to follow the electronic submission guidelines may result in a 10% penalty per infraction.
As long as other file naming conventions are followed, you may choose to append an assignment identifier (i.e. “_a1” or something else as appropriate) as the LAST element before the file extension.
ZIPPED SOURCE CODE Unless otherwise requested, you should only ever submit a single zip file containing the source code as specified. Your source code must always be contained WITHIN a top level folder named correctly, so that when it is extracted, it does not lose naming information.
The top level directory should be named with the usernames of all team members as follows:
• Individual assignments: username_src.zip (i.e. jsmith_src.zip) • When working alone: username_src_alone.zip (i.e. jsmith_src_alone.zip) • When working with a partner: username1_username2_src.zip (i.e. jsmith_bjones_src.zip) • When working as a team: username_src_team.zip (i.e. jsmith_src_team.zip – but be certain to include all team members in every code header)
Place your CLEANED project file(s) and / or folder(s) inside this correctly named top level directory before zipping your files.
