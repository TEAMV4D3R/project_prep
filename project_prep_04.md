## Project Description

### Jobs recommendation and application management app

- A concierge service that works across three job sites (LinkedIn, Indeed, Monster).

- Problems solve => save time to the user and provide alerts.

- A react app would allow users to manage the status of their job applications (i.e. pending, interviews scheduled, jobs declined). 

The react app would use a regular CRUD functionality using a django backend app to manage the jobs. 

It would also show a basic statistical graph using D3.js of jobs that the user applied for over time.

It would also recommend jobs by scraping sites like LinkedIn, Indeed, Monster 

The scraper functionality can be on a django backend app that would populate the database.

It would use two models, the user’s jobs model and the recommended app model.

It would use two django apps, one for scraper and the other one for CRUD functionality.

Stretch Goals
The react app would also recommend a job listing using machine learning that would recommend job opening to users.

## User Stories

Start out by creating at least 5 user stories for your approved project. The outline/requirements for user stories can be found HERE

### \#1

As a user, I want to be able to log in
Feature Task: 
Make an api call to the Django server to get json web tokens.
Authenticate username and password
Acceptance criteria
Successfully make an api call to the backend.
Successfully authenticate using json web tokens.

### \#2

As a user, I want to be able to successfully add a job that I applied for to my dashboard
 Feature Task:
                 a.) Add a job with employer, date, status, location, position and job type
 Acceptance criteria:
The form should have 6 input fields (location, status, employer, position and job type, and notes).
Status should have selections of pending, interview, declined.
Job type should have selections of full time, part time, internship, and contract.

### \#3

As a user, I want to be able to successfully update the status or edit  the jobs in my dashboard. 
 Feature Task:
                 a.) Edit the individual jobs data
Acceptance Criteria:
Be able to make a out request to edit existing jobs data
Reflect the new jobs data in the react app

### \#4 

As a user, I want to be able to delete any jobs in my dashboard.
      2.)  Feature Task:
	     a.) Delete a job from the jobs data
      3.)  Acceptance Criteria:
	      a.) Be able to make a delete request to delete a job
	      b.) Reflect the new jobs data in the react app
	
### \#5

As a user, I want to see time series graphs about the jobs in my dashboard
Feature Task:
Use D3.js to display a pie chart
Use Chart.js to display a line chart
Use Chart.js to display a bar chart

### \#6

As a user, I want to see recommended jobs based on job title and location criteria
Feature Task:
Pass information from criteria to Monster, LinkedIn, Indeed
Return Job posting links that match criteria in a clickable way that routes the user to the job postings in another tab


### \#7

Stretch: As a user, I want to be able to communicate with other job searchers
Feature Task:
Implement chat functionality for users on another page in the application.

### \#8

As a user, I want to be able to get to know the team that put together the application
Feature Task:
Implement an about-me page in the application

## Wireframe/Schema

![https://github.com/TEAMV4D3R/project_prep/blob/46842c719d17f908dd4d817e8f136c372702cf23/WireframeplusSchema.png]

