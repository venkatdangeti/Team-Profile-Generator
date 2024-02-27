# Team-Profile-Generator

## Description

Task is to take the given starter code and convert it into a working Node.js command-line application. This application will take in information about employees on a software engineering team, then generate an HTML webpage that displays summaries for each person. You have been provided with tests, so make sure every part of your code passes each provided test.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Screenshots](#screenshots)

## User Story

```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```

## Acceptance Criteria

```md
Create a command-line application that accepts user input using the provided starter code.

Create classes for each team member provided and export them. The tests for these classes, which are located in the _tests_ directory, must ALL pass.

The first class is an Employee parent class with the following properties and methods:

name

id

email

getName()

getId()

getEmail()

getRole()—returns 'Employee'

The other three classes will extend Employee.

In addition to Employee's properties and methods, Manager will also have the following:

officeNumber

getRole()—overridden to return 'Manager'

In addition to Employee's properties and methods, Engineer will also have the following:

github—GitHub username

getGithub()

getRole()—overridden to return 'Engineer'

In addition to Employee's properties and methods, Intern will also have the following:

school

getSchool()

getRole()—overridden to return 'Intern'

Finally, although it’s not a requirement, consider adding validation to ensure that user input is in the proper format.

Write code in index.js that uses Inquirer to gather information about the development team members and creates objects for each team member using the correct classes as blueprints.

When a user starts the application, they're prompted to enter the team manager's:

Name

Employee ID

Email address

Office number

When a user enters those requirements, the user is presented with a menu with the option to:

Add an engineer

Add an intern

Finish building the team

When a user selects the engineer option, the user is prompted to enter the following and then taken back to the menu:

Engineer's Name

ID

Email

GitHub username

When a user selects the intern option, the user is prompted to enter the following and then taken back to the menu:

Intern’s name

ID

Email

School

When a user decides to finish building their team, they exit the application and the HTML is generated.

Call the render function (provided for you) and pass in an array containing all employee objects.

The render function will generate and return a block of HTML including templated div elements for each employee.

Create an HTML file using the HTML returned from the render function.

Write it to a file named team.html in the output folder.

You can use the provided variable outputPath to target this location.
```

## Screenshots

These are the final screenshots of the team prfile generator.

Jest Execution Screenshot : ![Alt text](/imgs/Jest_Execution.png)

Inquirer Terminal Inputs Screenshot : ![Alt text](/imgs/Inquirer_inputs.png)

Team Profile Generator HTML Screenshot : ![Alt text](/imgs/Team%20html%20template.png)

Team Profile Generator HTML Webpage Screenshot : ![Alt text](/imgs/Final%20Results.png)

## GitHub page - https://github.com/venkatdangeti/Team-Profile-Generator.git
