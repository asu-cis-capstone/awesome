#Development Instructions

##Overview
This document is intended to help the user access the several different functions of the website.


#####To Access the website
To access the website using on of the following: 
* [Public IP: 54.172.207.252](http://54.172.207.252)
* [Public IP: http://ec2-54-172-207-252.compute-1.amazonaws.com/](http://ec2-54-172-207-252.compute-1.amazonaws.com/)
  - The homepage is a directory called HTML5UP-zerofour; index.html

#####To Access the server backend
To edit the backend of the website
  1. Request access by submitting a pull request on GitHub
  2. A public key will be sent to the user, when received change format from .txt to .pem
  3. In the command line run the following command: 
    - ' chomd 400 CIS440.pem '
  4. cd to the pem file directory 
    - ' cd downloads '
    - type: ' ssh -i "CIS440.pem" ec2-user@54.172.207.252 '
  * If an error or permission settings will not allow you to access the site contact the team

#####To Access PHPMyAdmin
To manage the mySQL database
  1. Go to [http://54.172.207.252/phpmyadmin](http://54.172.207.252/phpmyadmin)
  2. Enter username and password provided
  3. Access project 'Blurred Lines' and update information contained

#####To Access Code - During Devlopment
Users will be directed to edit code on GitHub
  1. Locate code through GitHub 'awesome/html5up-zerofour/'
  2. Access to HTML files will be located there
  3. CSS and Fonts are located within their respective folders
  4. Code updates should be made and then saved with description of changes and commit notes
  5. The project team should be updated on any changes to the code files
The project team will upload these files to the server during project development

######**Disclaimer**
Any issues should be passed on to the project team for resolution. These instructions are intended specifically for development purposes. The user should have a basic understanding of server-side languages. A host site will be utilized prior to completion for easier access to web development. A new set of instructions will be released when this has been established. 
Links can be found through the GitHub Readme.md page.
