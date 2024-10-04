# Task Management Board

## Task Management Board web app that enables task tracking, collaboration, and progress monitoring with the users using Express.js.

#### Tech Stacks: Express.js, HTML, CSS, JavaScript, MongoDB, Socket.io, and Passport.js

Feature: A user(Signed up with Google ID) can create a Team with users. 

The team, can edit the users and create a Project with start&due dates. 

Inside the project, they can assign tasks to the users who were in the team with the start&due dates. 

Passport.js is used for User Authentication and Socket.io is used for friend linking feature.

# Task Management Feature
## Login Page

<img width="1440" alt="login" src="https://github.com/user-attachments/assets/0b8f36df-892d-4ed6-b67c-ef86bab50745">


Users must log in through their Google ID to use this board. When they log in, it will take a username, email, and google ID to create a new profile in the Database.
Passport.js is used.

<img width="496" alt="TMB_GoogleLog" src="https://github.com/liam4806/Task_Management_Board/assets/95008167/1554fdcf-6a20-4037-a908-6a178f4ec1d8">


## Home Page

<img width="1440" alt="home" src="https://github.com/user-attachments/assets/795e7a62-d3ec-4c4b-88e5-fadf8d995909">


This is the Home page that does not have any team. Users can create a team.

### Create Team

<img width="1440" alt="create_team" src="https://github.com/user-attachments/assets/87fcfab6-5d51-48d4-8c23-c7eb291166e6">


Users can decide the name and select the member of the team. Users who are NOT on the team cannot view the team board. They can only view the team board that they are in.

When they create a Team, they can create a Project inside the Team in the same way.

### Create Project

<img width="1440" alt="new_project" src="https://github.com/user-attachments/assets/9f98c691-0779-4868-8883-7ed110b39d6b">


For the Project, users can set the start and due date. 

When users create a project, they can create a task inside the project in the same way. 

### Create Task

<img width="1440" alt="new_task" src="https://github.com/user-attachments/assets/a5ce101a-ba11-4024-928e-f35363620a1d">


For tasks, users can select the progress by To do, In progress, and Done. Also, they can assign users tasks individually.

### Team Dashboard

<img width="1440" alt="dashboard" src="https://github.com/user-attachments/assets/c4f4d273-6617-4cd4-bf1a-a4dc9b58ceaa">


This is the dashboard after the user creates a team and project. They can edit the content or users of the team directly in this dashboard.

### Project Dashboard

<img width="1440" alt="Dashboardwproject" src="https://github.com/user-attachments/assets/82ebca6c-52a8-4efd-84d0-4775063b2b85">


This is the project dashboard after users add the tasks inside. The dashboard will show the tasks that are sorted by the progress for intuitive view and productivity. 

# Friend Request Feature

Feature to link users by friend request to create a team with their friends only for privacy. Socket.io is used.

## Profile

<img width="1440" alt="profile" src="https://github.com/user-attachments/assets/991a0917-c2ee-4e59-ac8f-be2a07c84275">

On the profile page, users can see their information and can search for other users.

### Friend Searching

<img width="1440" alt="add_friend" src="https://github.com/user-attachments/assets/9dd0d6bd-1fc0-423b-88a7-07094c3308c5">

They can search for users and send a friend request.

### Accepting Friend Request

<img width="1440" alt="friend_accept" src="https://github.com/user-attachments/assets/9ee3d870-0736-46f3-b9a4-315f9af7aa35">


This is the view of another user who got the friend request. They can decide to accept or decline. When they accept, both of them will be added to the friend list array. 
