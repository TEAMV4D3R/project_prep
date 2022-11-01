# Project Requirements

1. Vision
 - The vision of this product is to have an application that lets the user save information about their job search process.
 - Saved information will include jobs applied to and allow users to input information about job statuses.
 - The pain point this solves is keeping track of jobs applied to and job statuses.
 - People should care about this product because it provides a centralized location for job searchers to manage their job applications.

2. Scope (In/Out)
 - IN - What will your product do:
 - This application will allow users to track their applied jobs.
 - This app will allow user to search for jobs in the database.
 - This job will allow users to edit their profile.
 - This application will allow users to see their job statuses in graphical form.
 - OUT - What your product will not do
 - Will not allow users to apply to jobs directly through this application.

3. Minimum Viable Product
 - React Application with login capabilities
 - Users can input jobs applied to, update job statuses, delete jobs from their database.
 - Inputs can include company, status, and notes (for company mission/vision/culture notes etc), interview information ie. time, who was involved, notes from the interview etc.
 - Show a graph (pie chart or visual) with application status etc
 - Deployed Django Application with AWS or Vercel (Plan to spend extra time here)
 
4. Stretch Goals
 - Lets the users chat with other job applicants (perhaps through socket io/node.js pysocket, django)
 - Scrape data from LinkedIn, Indeed, and Monster and recommend similar jobs based on user behavior.
  
5. Functional Requirements
 -  List the functionality of your product.
 - This will consist of tasks such as the following:
 - An admin can create and delete user accounts.
 - A user can update their profile information with jobs applied to, job statuses, and company specific information
 - A user will get recommended jobs based on search criteria they provide
 
6. Data Flow
 - The user will start by creating a profile with their username, password, and email.
 - They will then be directed to the login page where they will log in. Once the user is logged in, they will be directed to the user profile menu which includes job status, user information, and user guide which will link to the My Jobs page.
 - There will be a menu on all pages that allows the user to route through the pages on the site.
 - In the My Jobs page, the user can add information about jobs they have applied to including the position, job description, location, employer, notes, and input date.
 - The user can also choose to look at the job board where they can input their location and the job type they are looking for to see a listing of jobs that match their search criteria.
 - The users can also potentially visit the chat board where they can write messages to other users of the application which would be stored for up to three days on the site.
 - Finally, the user has the option of visiting the page on the developers.
 
7. Non-Functional Requirements (301 & 401 only)
 - Two key non-functional requirements of this application will be testability and documentation.
 - This application will aim to have 80% test coverage.
 - Tests will be written through pytest for the backend of the application to ensure consistent functionality and partner site scraping.
 - Furthermore, we aim to have documentation that takes the user through the full happy path of the application so all features are clear and readily available for users. 
