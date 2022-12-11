# TP-Generator-
Command-line application that takes in information about employees on a software engineering team and generates an HTMl webpage that displays summaries for each person. 

## Project Description
Run in Node, this command line application  requests information from the user about employees of a team. The positions listed are employee, intern, engineer. It requests the employee's name, employee ID, and email to generate a HTML page with employee information listed on cards. The intern role has additional information about school; the engineer role has additional information about GitHub page; the manager role has additional information about office number.  

# Installation
 The user must enter "npm i", and "npm i inquirer" to install the modules before running the applicaiton. 

 After the application is launced, the user must build the team by entering the team member's name, employee number, email, and select the team member's role("engineer", "intern" and "manager"). 
 
 If the " engineer" role is selected, the app asks the user for the Github username. 

 If the " intern" role is selected, the school information must be entered. 

 If the " manager" role is selected, the user is prompted to enter the  manager's office number. 



A screenshot showing an example user input is shown below:

![Screenshot of user input]

When the information about the employees are entered, the user is asked whether there are more employees to add. 
If yes, the user is provided with the same prompts again. 
If no, then the HTMl file is created with cards displaying the information about the employees informations entered in the " output" folder titled " team.html". 

A screenshot of the team profile is shown below. 


# Techniques and Technologies Used
The app was created using Visual Studios, Node.js, NPM modules default modules, the " inquirer", and " fs" module. 

This app uses test-driven development. Jest is used to perform tests on all class constructors. The FS node module is used to generate and edit files from strings written in Javascript.