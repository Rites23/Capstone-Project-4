Capstone-Project-4

Poised Project

Project Details:

Description

The Poised Project is a program written in the Java language that was created to fulfill the level 2 task requirements for the Hyperion Development Software Engineering Bootcamp. The program is designed to be a project management system for a small structural engineering firm called 'Poised'. The company Poised works on various buildings in an engineering capacity to ensure structural integrity. The Java program was written to assist the company in keeping track of the many projects that they work on.

Functionality

The plan was to create a main 'Menu' Java class, which will call on methods from the other sub-classes, depending on what action the user chooses from the displayed menu. Once the project is finished it will be able to capture all the necessary information about new projects, update information on existing projects, finalise existing projects, view a list of projects that are incomplete or overdue, as well as find and select a project by number or name. This project is still a work in progress. So far, the functionality of the Java program is as follows:

It consists of a 'New Person' Java class that contains certain variables, a constructor, and a method to display all the person information. So it basically creates a person object (for example a contractor) with all their necessary details (e.g. name, number, address etc.) and displays their information in an easy-to-read format.

There is also a 'New Project' Java class which also contains variables, constructor and a method to display all information related to a new project. It therefore works to create a new project object with all the related details (e.g. project number, project name, building type, deadline etc.) and displays the new project in an easy-to-read format.

Then there is the main 'Poised Menu' class, which is where the actual program is executed. This program displays a welcome message to the user and then allows them to add a new project. The user is prompted with a series of questions, which gather information to create a new project object. Once all the information is gathered, a successful message is displayed, as well as the project information.

The program then displays a short menu to the user with the options to edit existing projects, update contractor details, finalise a project, or to exit the program. The user types in a number corresponding to the menu choice displayed to go to their desired option. If they choose to edit an existing project, they are given further options to edit the project due date or edit the total amount paid to date. If they choose to update contractor details, they are asked a series of questions to gather new contractor information. If they choose to finalise a project, an invoice is generated (if there is money outstanding) and they are asked to enter a completion date for the project. The project status is then finalised too. After each menu option, the edited project object is displayed for the user to view. If they choose to exit the program, a successful 'Logged out' message is displayed.
