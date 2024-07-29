## Techevince 10.0 Website 

### Overview
This project aims to create a voting platform for Techevince, an event conducted by the Technical board of IIT Guwahati ( IITG ), enabling users to cast votes for their preferred projects across different domains.

### Core Features

* ***Main Web Page:***           The primary interface for users to access the voting system.
* ***Three Voting Sections:***   Divides projects into distinct categories for targeted voting.
* ***Project Descriptions:***    Provides in-depth details about each project to aid informed voting.
* ***Institute Account Login:*** Requires users to authenticate with their institute account for voting.
* ***Voting Limit:***            Each logged-in user can cast up to 3 votes per domain.

### Technology Stack
* ***Frontend:*** [ReactJS]
* ***Backend:*** [NodeJS, ExpressJs]
* ***Database:*** [MongoDB]
* ***Authentication:*** [Azure AD OAuth2, Passport.js, JWT]

##  The application's key interfaces are outlined below.

***Main page of the web application***

# ![Screenshot (2269)](https://github.com/Deviprasad0815/Techevince-assets/blob/main/Screenshot%20(2269).png)

***Voting Sections: Divided projects into distinct categories for targeted voting.***

# ![Screenshot (2273)](https://github.com/Deviprasad0815/Techevince-assets/blob/main/Screenshot%20(2273).png)

***Business Section: Dedicated section for business-related projects.***

# ![Screenshot (2284)](https://github.com/Deviprasad0815/Techevince-assets/blob/main/Screenshot%20(2284).png)

***Login with Institute Account: Users are redirected to their institute's login page to authenticate.***

# ![Screenshot (2280)](https://github.com/Deviprasad0815/Techevince-assets/blob/main/Screenshot%20(2280).png)

***In-depth project descriptions are available for informed voting.***

# ![Screenshot (2285)](https://github.com/Deviprasad0815/Techevince-assets/blob/main/Screenshot%20(2285).png)

# Development steps

***To get the website up and running, please follow these steps: ( in VS code )***

1. **Clone the repository:**
   - Begin by cloning the repository to your local machine.
   - You will find two main folders: `frontend` and `backend`.

2. **Set up the backend:**
   - Open a terminal and execute the following commands :
     ```
     cd backend
     npm install
     npm start
     ```
   - Confirm that the backend is running.
    
3. **Set up the frontend:**
   - Open a new terminal and run these commands:
     ```
     cd frontend
     npm install
     ```
   - If you encounter any errors, try:
     ```
     npm install --legacy-peer-deps
     ```
   - Then start the frontend:
     ```
     npm run start
     ```
   - Verify that the frontend is running.

Now, the website should be operational on your local computer, and you can proceed with testing.
