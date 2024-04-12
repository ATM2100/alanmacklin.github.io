[Back to Portfolio](./)

Horse Whisperer
===============

-   **Class:** System Analysis
-   **Grade:** (pending 100)
-   **Language(s):** PHP, MySQL, HTML
-   **Source Code Repository:** [ATM2100/Horse-whisperer](https://github.com/ATM2100/Horse-whisperer)  
    (Please [email me](mailto:atmacklin@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This is a website built as a team of five, of which I functioned in the role of project lead, and developer. In this project, we wrote out documentation throughout the process, had a living project charter and our own pert/grant charts. We tested it out on both linux and windows, but we chose to make the instructions to set up the server for windows since that is what most of us were using at the time. Our lead developer was also more comfortable on Windows which in the context of a time crunch like a single semester, needed to be taken into consideration. This was a tough project to complete even with the extra people and especially since I had no experience trying to lead programmers at the time. While I may not have done most of the programming for this project, I did learn a lot from generally doing the project with a team. I learned a bit of testing, a bit of coding, and the leadership of programmers that I have used in every competition and group project since this project.
This project features an online website for horse riding lessons complete with a calendar, login system for administrators or users, signing up for and canceling lessons.

## Afore mentioned documents
Test cases are [here](https://docs.google.com/spreadsheets/d/1722IhhqpZohj7tZ947yW0NN-bzVol_lu/edit#gid=59917924)

Charter (includes Pert/Grant charts, and use cases) [here](https://docs.google.com/document/d/1bm3SpEscxj7RXgLrpX0JwO5MbnmIiDItdflP3X-PbHA/edit)

## How to set up the website server

### Setup Instructions
Knowing is the easy part; saying it out loud is the hard part

=======================================================

Downloads:
[php](https://www.php.net/downloads.php) and [mysql](https://dev.mysql.com/downloads/installer/)

======================================================= 

Steps:

1. Install PHP
    - use the link at (1)
    - click "Windows downloads"
    - download the latest **x64 Thread Safe** Zip package

    - create a new php folder 
        - wherever you want, but _save the path_ of where you save it
    - extract the contents of the zip file to the new folder

    - in the folder, find a file named "php.ini"
    - in this file, find a section with a list of "extension="
    - if it does not already exist, add "extension=sqli"

    - click on the Windows Start button and type "environment"
    - click "Edit the system environment variables"
    - go to the "Advanced" tab and click "Environment Variables"
    - click "New" and put in the _saved path_ from before
    - click "OK" until you're out

2. Install MySQL
    - use the link at (2)
    - click the first download (the one with "-web-" in its subtitle)
    - click on the .msi installer file after its downloaded
    - Follow the steps provided by the MySQL Installer to download MySQL Shell and MySQL Server (recommend using latest)
    - 
    - 
3. Download Github repository
    - Download the Source Code from our Release build.
    - Extract the zip file.
    - Run the dump batch file to get all the database information.

## UI Design
We decided on a minimalist green interface where buttons would be in intuitive spots. I believe that this is most clearly shown in the interface for creating your lessons. 
![screenshot](/images/project5/createLesson.png)  
Fig 1. GUI for signing up for a lesson.  
Every button that you could ever want when signing up for a lesson can be found here. If a specific teacher, class type, etc, is wanted then it can be changed in the catagory where it would make sence to change it. 
Registering for classes is also just as simple. as seen in fig 2.
![screenshot](/images/project5/registration.png)  
Fig 2. Registration button.  
Or of you want to schedual a lesson yourself, the calendar is available to you (see fig. 3)
![screenshot](/images/project5/calendar.png)  
Fig 3. Calendar for long time planning  
As you can see on the calendar, we tried to keep as much information together as possible. The calendar can be used for a more customized registration but it is still possible to register for lessons that are preset for a given month long period.

[Back to Portfolio](./)