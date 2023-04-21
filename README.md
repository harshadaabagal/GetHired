[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/0wrsx4Jb)
# GetHired

## Project Description

GetHired is a job search and career management portal for university students.

## Features

- Recruiters and Student can login using their valid credentials. Credentials are validated using JWT authentication.
- Students can create their profile and add documents such as resume.
- All documents are uploaded and maintained on Amazon S3
- Recruiters of companies post job openings that students can view and apply for.
  Career Fairs, Networking and Speaker events are posted on the portal and available for student booking
- Recruiters can view the applications and download the student's resumes.
- Used Google maps to display location of the event
- Students can filter on available jobs and events to find ones that interest them.
- Students can search for a job
- Students can post reviews about organizations for other students to peruse
- Students can access their dashboards to view their applications, registered events and job recommendations based on their interests.
- Used Charts.js to display the status of the applications on the student dashboard.


Domain Model
![Domain Model](/assets/images/Domain_model.jpeg)

## Milestones

1 - Setting up the project and Creating UI/UX designs in Figma to get a better idea</br>
2 - Develop and implement Login, Sign up and User authentication,  authorization</br>
3 - User profiles creation for users and recruiters and implementing the APIs</br>
4 - Job Board creation to see all jobs and user should be able to post and apply to jobs</br>
5 - Testing and Deployment</br>


Milestone 1 -
Setting up the project and Creating UI/UX designs in Figma to get a better idea</br>
I should set up the basic project environment by installing required softwares</br>
I should create protypes of how the designs should look</br>
I should get a clear idea of the how the final product should look like</br>


Milestone 2 - 
Develop and implement Login, Sign up , user profiles and User authentication,  authorization</br>
As a user, I want to be able to create an account, so that I can log in to the app.</br>
As a user, I want to be able to log in to the app, so that I can access my profile and other features.</br>
As a user, I want to be able to log out of the app, so that my account is secure.</br>
As a user, I want to be able to reset my password, so that I can regain access to my account if I forget it.As a user, I want to be able to update my password, so that I can keep my account secure.</br>


Milestone 3 - 
User Profiles</br>
As a user, I want to be able to view my own profile, so that I can see my work experience, education, skills, and profile picture.</br>
As a user, I want to be able to edit my profile, so that I can add or update my personal information.As a user, I want to be able to view other users' profiles, so that I can learn more about them.</br>
As a user, I want to be able to search for other users by name, industry, or job title, so that I can find people who I want to connect with</br>

Milestone 4 - 
Job Board</br>
As a user, I want to be able to search for job opportunities by location, industry, and job title.</br>
As a user, I want to be able to apply for jobs with my profile information and resume.</br>
As a company, I want to be able to post job listings and receive applications from interested candidates.</br>


Milestone 5 - 
Testing and Deployment</br>
Perform unit testing and system testing to closely rectify if any bugs in the system</br>
Deploy it on the server</br>
<img width="1440" alt="MicrosoftTeams-image (2)" src="https://user-images.githubusercontent.com/43906676/233677691-10661eed-d2b8-4a15-9d02-35d90431fadd.png">
<img width="1440" alt="MicrosoftTeams-image (3)" src="https://user-images.githubusercontent.com/43906676/233677723-c27ae697-19bb-4c96-a597-43fc76f6aa50.png">
<img width="1440" alt="MicrosoftTeams-image (8)" src="https://user-images.githubusercontent.com/43906676/233677758-d481f1f4-4da2-422b-9ec3-3039b34d01ab.png">


### Instructions to Setup this Project <hr>

#### clone or download
```terminal
$ git clone https://github.com/neu-mis-info6150-spring-2023/final-project-group-get-hired.git
```

Server-side usage(PORT: 5000)
```terminal
$ cd backend   // go to client folder
$ npm i       // npm install pacakges
$ npm start   // run backend

Client-side usage(PORT: 3001)
```terminal
$ cd web-app   // go to client folder
$ npm i       // npm install pacakges
$ npm start // run it locally


