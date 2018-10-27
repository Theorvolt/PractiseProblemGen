# PractiseProblemGen
A practise problem generator coded in the wolfram language.

## Synopsis
This practise problem generator uses the Wolfram language to generate worded problems that can be solved automatically by Mathematica. The problem generator was originally designed to help practise hard questions where knowledge of multiple concepts was needed as opposed to randomly generated problems with different numbers, e.g find the derivative of 3e^x + 4x as opposed to x^2. 

## The repository file
Mathematica can generate mx files which can contain expressions when loaded into a session. Using this, questions and their answers can be saved in a database that can be called into Mathematica with the Get function, calling the mx file.

## How do I use this?
Upon loading the file, there are 5 sections which divide the file. For the time being, ignore the Management for the repository section and the Creation of the data file section. 

To define all the functions, open the Required custom functions and datasets file and execute the code inside by shift entering the cell. 

After this, head to the Workspace section and run the loadFile[]; function that is there.

Finally, head to The user interface section and run the session[] function. Scroll down and the program will appear. To change topics or difficulty, go to options and change it accordingly.

## How do I create questions?
TBD, will post at a later date.
