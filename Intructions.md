#Development Instructions

##Overview
This document is intended to help the user access the several different functions of the website.


#####To Access the website
To access the website using on of the following: 
* [Public IP: www.blurredlinesbarbershop.com](http://www.blurredlinesbarbershop.com)

#####To Access the server backend
The server is ran through eHost.com and accessed using FileZilla
  1. Open FileZilla or other client
  2. In the Site Manager enter the provided host, username, and password
      * Change Encryption to 'Only use plain FTP' and Logon Type to 'Normal'
      * Transfer settings should be set to 'Passive' and Limited to 2 multiple connections
          - This prevents the server from blocking your IP
  3. Connect through the Site Manager to connect with the server
  4. Updates to the server should be reported to the team and documented

#####To Access PHPMyAdmin
To manage the mySQL/PHPMyAdmin database
  1. When on [eHost.com](www.ehost.com) sign-on using the provided credentials
  2. Access the cPanel where Databases are stored
  3. Select the database and utilize documentation provided from the site for tech specs

#####To Access Code - During Devlopment
Users will be directed to edit code on GitHub
  1. Locate code through GitHub 'awesome/Blurred Lines Web/'
  2. Access to HTML files will be located there
  3. CSS and Fonts are located within their respective folders
  4. Code updates should be made and then saved with description of changes and commit notes
  5. The project team should be updated on any changes to the code files
The project team will upload these files to the server during project development

######**Disclaimer**
Any issues should be passed on to the project team for resolution. These instructions are intended specifically for development purposes. The user should have a basic understanding of server-side languages. eHost.com will be utilized to manage and run the clients webpage and databases. Technical Instructions will continue to develop as new features/instructions are identified.

Additional links can be found through the GitHub Readme.md page.
