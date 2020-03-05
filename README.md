# JOB LISTING

## PROJECT  4 :  FULL STACK FRAMEWORKS WITH DJANGO MILESTONE PROJECT 
The website is a prototype for employers to create their own account and add/edit/delete job listings. Potentially bring jobs to many job seekers and connect them to the employers. Potentially the website can generate revenue from job hosting and advertisement by companies. Future development includes having company profile, job seeker account and profile and more job information.

## SCOPE
The website is a job portal for employee to find job and employer to post new job posting
_LOGIN / REGISTER / LOGOUT_
- user can create an account to post a job listing 

_CREATE_ - user can enter the new job opening. 

_EDIT_ - user can edit their job listing

_READ (DISPLAY)_ - able to show all listing from databases

_DELETE_ - user can delete the job posting

## Demo
A live demo can be found here. https://proj4-job-listing.herokuapp.com/

## UX
Easy to use and navigate and post on the website

## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)
4. Django 2.2.4
5. Python 3
6. JinJa
7. Postgres SQL

## Features
The page will show the full listing from the database by default

User can perform CRUD and create own login account.

_Limitations & Future development:_
Many bugs are not fixed due to time. Not able to update user when changes done

*No* | *Steps* | *Expected Results* | *Observations*
--- | --- | --- | ---
1 | `On the Landing Page, click on the "Assign Me a Talent Hunter"`| `Link to the Company listing page and display all job listings`| **Pass** 
2a | `Under the Company tab, Click on 'New Listing' yellow button located on top right` | `Display a new entry form for entering new listing information` | **Pass** 
2b | `Enter the details in form and submit`|`Return to listing page (under Company tab) and new listing is added` | **Pass** 
3a | `Under the Company tab, Click on 'Edit Listing' on right of each listing`|`Show a form to allow user to edit existing car details with current data pre-entered in field` | **Pass** 
3b | `Edit the changes and click submit`|`Return to listing page (under Company tab) and the selected listing is updated` | **Pass** 
4a | `Under the Company tab, Click on 'Remove Listing' on right of each listing` | `Information of the listing is retrieve and displayed, will prompt user to confirm the removal` | **Pass** 
4b | `Click on 'Confirm Remove' on right of each listing` | `Return to listing page (under Company tab) and the selected listing has been removed` | **Pass** 
5a | `From Home Page - Click on 'Companies' tab` | `Switch to Employer Page with hyperlink 'https://proj3-job-listing.herokuapp.com/employer' and display database listing with New Listing / Edit / Remove Button` | **Pass** 
5a | `From Home Page  - Click on 'Job Seekers' tab` | `Switch to Job Seeker Page with hyperlink 'https://proj3-job-listing.herokuapp.com/employee' and display database listing only` | **Pass** 
5b | `From Job Seeker Page - Click on 'Home' or 'JTE Recruit' tab` | `Switch to Landing Page with hyperlink 'https://proj3-job-listing.herokuapp.com'` | **Pass** 
5b | `From Job Seeker Page  - Click on 'Companies' tab` | `Switch to Employer Page with hyperlink 'https://proj3-job-listing.herokuapp.com/employer' and display database listing with New Listing / Edit / Remove Button` | **Pass** 
5c | `From Employer Page - Click on 'Home' tab` | `Switch to Landing Page with hyperlink 'https://proj3-job-listing.herokuapp.com'` | **Pass** 
5c | `From Employer Page  - Click on 'Job Seekers' tab` | `Switch to Job Seeker Page with hyperlink 'https://proj3-job-listing.herokuapp.com/employee' and display database listing only` | **Pass** 
6a | `Test Login Button` | `Show a login page for user to enter login id and password'` | **Pass** 
6b | `Test Click on 'Submit' in Login Page` | `Go to Landing page and show 'You have successfully logged in' and username` | **Pass** 
7a | `Test Register Button` | `Show a register page for user to enter email, login id and password (twice)` | **Pass** 
7b | `Test Click on 'Submit' Register Button` | `Go to Landing page and show 'You have successfully logged in' and username'` | **Pass** 
7 | `Test Logout Button` | `Logout and return to landing page and show Login & Register option` | **Pass** 


#### Deployment
This site is hosted using Heroku App Link : 
_https://proj4-job-listing.herokuapp.com/_

All codes are uploaded to GitHub and links are made to Heroku by installing in bash terminal in projects.

Regular commits are push to the Github subsequently push to heroku to deploy.
.gitignore file is added to remove files that are not required or files that we do not wish to be uploaded to Github

_Deploy Heroku:_

* i) Install Heroku using bash
* ii) Login to Heroku
* iii) Install gunicorn
* iv) Create Procfile and requirements.txt
* v) Commit and push to Heroku 
* vi) Set up the Environment Vasriables
* vii) Update Dependencies

## Credits

Uses W3School for many reference (https://www.w3schools.com/) Uses fontawesome for the social media icons (https://fontawesome.com/) Uses Bootstrap for templates (https://getbootstrap.com/) 
