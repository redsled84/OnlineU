# Online U

This is a website for free, curated online courses. 

When the site is up (sporadically) it can be viewed at: http://47.32.148.165/

![site image](http://i.imgur.com/FmuC9p0.png)

## Dependencies
* Python 2.x
* [Flask](http://flask.pocoo.org/)
* [SQLAlchemy](http://www.sqlalchemy.org/)


## Initializing the database
`$ python database_setup.py`

## Creating credentials
1. Go to https://console.developers.google.com
2. Create a new project
3. Click "enable and manage APIs"
4. Click "credentials"
5. Create credentials --> OAuth client ID --> Web applications
6. Add your access point to the authorized javascript origins (your public IP, 127.0.0.1, localhost, etc)
7. Add a placeholder site under "Authorized redirect URIs", eg: http://www.example.com
8. Save the credentials file as `client_secrets.json` in the main directory.

## Starting the server
`$ sudo python project.py`

## Todo:
* Majors
  * Automatically enroll user in all courses for a major when the user enrolls in that major
  * Add support for optional and required minors
* Courses
  * Show completed courses on user profile
* Exams
  * Allow admins to edit exams online
  * Add suport for math expressions
  * Add support for multiple choice questions
  * Create server-side grading script
  * Figure out ways to prevent cheating
    * Facial recognition
    * Typing pattern recognition
  * Add support for randomized questions and random question selection
* Misc
  * Add a donation page
  * Add application form for volunteer content curators
  * Add bug reporting
  * Issue verified certificates upon degree completion.
  * SSL/HTTPS
 

## Contributing

Contributions from anyone are welcomed and very appreciated! This is a very big project and it's going to take a lot of people to make it work. Take a look at the todo list above and the issues page for ideas on how to help.
