# SurveyBuddy Application

## Part A - Application Research, Planning, & Analysis

#### ⭐ View Front-End Repository ➡️ [Here](https://github.com/Survey-Buddy/surveybuddy-client).

#### ⭐ View Back-End Repository ➡️ [Here](https://github.com/Survey-Buddy/surveybuddy-backend).

#### ⭐ View Project Management Trello Board ➡️ [Here](https://trello.com/b/5D0KTU38/survey-buddy-part-a).

---

### ▪ Application Table of Contents

**_Due to the header drop downs, the table of contents is inactive. To access the contents, please click on the arrow to the left of "View"._**

<details>
<summary>View</summary>
<br>

**▪ Application Overview** <br>

- [Description](#application-description)
- [Purpose](#application-purpose)
- [Target Audience](#target-audience)
- [Technology Stack](#technology-stack) <br>

**▪ Features & Functionality** <br>

- [Features & Functionality](#functionality--features)
- [Crucial Decisions](#crucial-decisions)
- [Logo Idea Exploration](#logo-idea-exploration)

**▪ Data Flow & Architectural Diagrams** <br>

- [Data Flow Diagrams](#data-flow-diagrams)
- [Application Architecture Diagrams](#application-architecture-diagrams) <br>

**▪ UI/UX Research & Design** <br>

- [User Stories & Personas](#user-stories)
- [Wireframes](#wireframes) <br>

**▪ Project Management & Tracking** <br>

- [Project Management](#project-management)
- [Trello Board Tracking](#trello-board-tracking)

</details>

---

### ▪ Description

<details>
<summary>View</summary>
<br>
This survey app is designed to make creating and managing surveys effortless. Whether you’re a student collecting data for a project, an individual seeking personal insights, or a business gathering customer feedback, this app provides a simple and intuitive experience for all users.

With just a few clicks, you can design a custom survey tailored to your needs, select recipients from your network, and send it out instantly. The app ensures that managing responses is just as straightforward. Once the survey is completed, the collected data is displayed in an organised and easy-to-understand format, allowing you to gain valuable insights without hassle.

Built with a focus on simplicity and functionality, this app streamlines the process of creating, distributing, and analysing surveys, making it the perfect tool for anyone looking to gather meaningful information quickly and efficiently.

## </details>

### ▪ Purpose

<details>
<summary>View</summary>
<br>
The purpose of this app is to provide a straightforward and affordable alternative to complicated and feature-heavy survey platforms. Many existing options overwhelm users with unnecessary features and costs. This app focuses on simplicity, ensuring users can quickly create, share, and analyse surveys without distractions or hidden expenses. It's perfect for those who value ease of use and clarity over complexity.

## </details>

### ▪ Target Audience

<details>
<summary>View</summary>
<br>

##### **Students:**

- Ideal for conducting surveys for academic research, gathering peer feedback, or collecting data for projects, and assignments.
- Useful for group work, where students can collaborate on surveys and analyse responses together.

##### **Individuals:**

- Enables individuals to run informal surveys for friends, social media followers, or community groups.

##### **Businesses:**

- Customer Feedback: Collect insights on customer satisfaction, product preferences, and overall experience.
- Employee Engagement: Run surveys to measure job satisfaction, gather suggestions, and understand team morale.
- Market Research: Conduct surveys to gather insights on market trends, product demand, and consumer behavior.
- Event Planning: Create RSVP forms or post-event feedback surveys to improve future events.

##### **Educators and Trainers:**

- Useful for creating quizzes, feedback forms, and evaluations for classes or workshops.
- Allows for tracking and analysing student or trainee progress over time.

##### **Nonprofits and Community Groups:**

- Ideal for collecting input from members, running community feedback polls, or gathering opinions on local issues.
- Enables organisations to track the impact of their initiatives and programs.

##### **Healthcare Professionals:**

- Use for patient satisfaction surveys, pre-appointment checklists, or anonymous feedback on care quality.

##### **Freelancers and Creators:**

- Collect feedback on services, products, or creative content like art, music, or writing.
- Use as a tool to engage audiences and build community trust through polls or feedback forms.

##### **Small and Large Teams:**

- Track project progress and gather feedback from team members in real-time.
- Use surveys for retrospectives, brainstorming sessions, or decision-making.
</details>

### ▪ Technology Stack

<details>
<summary>View</summary>
<br>
The MERN technology stack was used to build this application.

MongoDB explains a tech stack as…

_‘Tech stacks are sets of technologies that are stacked together to build any application.’_

Since no one software alone allows for the ideal full development of an application, multiple technologies are stacked together to facilitate the building of web applications that are easier to maintain and are scalable _(What Is A Technology Stack? Tech Stacks Explained n.d.)_.

![Tech Stack](./images/TechStack.png)

A popular modern tech stacks used throughout industry is the MERN stack, it uses JavaScript for the front end and server-side technologies, accompanied by MongoDB, a non-relational database management system to perform CRUD operations. These tech stacks use technologies that are JavaScript focused and are known to work well together, they enable a streamlined and unified development process because the technologies are frameworks and libraries of a single language, that allows for code reusability (MongoDB n.d.).

The acronym for these stacks is:

**M** – MongoDB for the database <br>
**E** – Express JS for the API server <br>
**R** – React for the User Interface <br>
**N** – Node JS for the runtime server environment <br>

![MERN logo](./images/mern.webp)

Here is a visual guide of the MERN stack, that displays the overall structure for an app developed using this stack and which technologies interact with each other. The front-end and database operate independently, interacting only with the server-side Express JS and Node JS API environment.

![MERN Architecture](./images/MernArchitecture.png)

### Other main technologies include:

##### **TypeScript**

  <img src="./images/Typescript.png" alt="TypeScript logo" width="100" >

_"TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale."_ - typescript.com

Provides static typing for JavaScript, improving code quality, catching errors early, and making the app easier to maintain and scale.

##### **Boostrap**

  <img src="./images/Bootstrap.webp" alt="Bootstrap logo" width="100" >

_"Powerful, extensible, and feature-packed frontend toolkit. Build and customize with Sass, utilize prebuilt grid system and components, and bring projects to life with powerful JavaScript plugins."_ - bootstrap.com

A CSS framework that simplifies responsive design and styling, helping create a user-friendly and mobile-compatible interface quickly.

##### **Chakra UI**

  <img src="./images/chakra.png" alt="Chakra logo" width="200" >

_"Accessible React components for building high-quality web apps and design systems."_ - chakra-ui.com

##### **Shadcn/UI**

  <img src="./images/shadcn.png" alt="Shadcn logo" width="200" >

_"Beautifully designed components that you can copy and paste into your apps. Made with Tailwind CSS. Open source."_ - ui.shadcn.com

A modern, accessible component library that accelerates the development of elegant, reusable UI elements.

##### **Mongoose**

  <img src="./images/mongoose.png" alt="Mongoose logo" width="200" >

_"Mongoose is an ODM (Object Data Modeling) library for MongoDB."_ - mongodb.com

Simplifies interactions with MongoDB by providing a structured way to define schemas and handle data validation and queries.

##### **Amazon S3** (stretch goal)

  <img src="./images/AmazonS3.png" alt="Amazon S3 logo" width="200" >

_"Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance."_ - aws.amazon.com/s3

A scalable cloud storage solution to manage and serve images efficiently, which would enhance the app's functionality by supporting media uploads.

For a complete list of technologies, please refer to [application architecture](#application-architecture-diagrams).

</details>

---

### ▪ Functionality & Features

<details>
<summary>View</summary>
<br>
A Mind Map was created to explore and document potential application functionality and features.

![Mind Map](./images/MindMap.jpg)

### Minimum Viable Product Features

**User Authorisation:** Ensures that only survey creators can access and manage their own surveys and data, stopping unauthorised access.

**User Authentication:** Verifies user identities through secure login, ensuring only registered users can access their accounts.

**Create a New Survey:** Allows users to design and customise surveys by adding questions, choosing formats, and setting preferences.

**Survey Links:** Automatically generates unique links for each survey, making it easy to share with others for responses.

**Survey Analytics:** Provides survey creators with clear visual insights and summaries of survey results, using charts and graphs.

**Data Display:** Displays survey results in a user-friendly layout, showing individual responses and aggregated data where applicable.

### Stretch Goal Features

**Written Summaries:** Generate detailed written summaries of survey results for easy interpretation.

**Large Language Model Response Summary:** Utilise a large language model (e.g., OpenAI API) to create advanced, natural-language summaries of survey data.

**Targeted Survey:** Allow creators to tailor surveys for specific audiences based on criteria like demographics or behavior.

**Authorisation:** Ensure only authorised respondents can access surveys via unique links to maintain privacy and data integrity.

**Rewards:** Introduce a rewards system for respondents, such as redeemable points or gift cards, to incentivise participation.

**Images:** Add carousel-style image questions to support visual responses and enhance survey engagement.

**Amazon S3 Storage:** Use Amazon S3 to securely store large files, such as images or multimedia responses, for scalable data management.

**Pricing:** Implement flexible pricing plans to accommodate survey creators with different needs, from free basic plans to premium features.

**Interactive Questions:** Add drag-and-drop question types to create a more engaging and user-friendly survey experience.

**Question Translation:** Provide automatic question translations to reach a wider audience and support multilingual respondents.

**Auto Reminder Emails:** Send automated reminders to respondents who haven’t completed the survey to boost response rates.

**QR Code Survey Links:** Generate QR codes for surveys, making it easier for users to share and access surveys via mobile devices.

![Features Board](./images/features.jpg)

### Mood Board

To analyse competitor applications and gain a deeper understanding of their features and user interfaces, I created a Mood Board showcasing aesthetics and layouts that resonated with me.

![Mood Board](./images/MoodBoard.png)

## </details>

### ▪ Crucial Decisions

<details>
<summary>View</summary>
<br>

### Survey Submission options

1. Make API call to store question data after each answered question:

**_Strengths:_**

- Progress Saving
- Real-Time Analytics
- Adaptive Surveys
  - Questions change based on answers

**_Weaknesses:_**

- Increased API Calls
- Increased Backend Complexity
- User Experience
  - Delays between questions

2. Make one API call to store all data at the end of the survey:

**_Strengths:_**

- Reduced API Calls
- Easier Backend Management
- User Experience

**_Weaknesses:_**

- Data Loss
  - If a user were to abandon the survey without submission, or their survey expires, their responses will be lost.
- No Real-Time Updates

### TypeScript

After discovering how TypeScript's interface feature can strengthen understanding when building React components, I decided to deepen my understanding of TypeScript's React functionality to incorporate it into my application. This required additional learning, which I supported by completing an online 'Coding With Mosh' course.

## </details>

### ▪ Logo Idea Exploration

<details>
<summary>View</summary>
<br>
1.

![SurveyBuddy Logo idea 1](./images/SB_logo1.png)
![SurveyBuddy Logo idea 1 Green](./images/SB_logo1green.png)

2.

![SurveyBuddy Logo idea 2](./images/SB_logo2.png)

3.

![SurveyBuddy Logo idea 3](./images/SB_logo3.png)

4.

![SurveyBuddy Logo idea 4](./images/SB_logo4.png)

</details>

---

### ▪ Data Flow Diagrams

<details>
<summary>View</summary>
<br>

### Data Flow Diagram Methods & Symbols

\*For the following diagrams, the **Yourdon + De Marco** diagram convention will be strictly followed, clearly depicting where data is coming from, where it is going, and how it is being stored.

![Data Flow Diagram Methods and Symbols](images/Data-Flow-Diagram-Methods-&-Symbols.webp)
_geeksforgeeks.org_

There are three levels of Data Dlow Diagrams (DFDs), these inlclude:

- Level-0
- Level-1
- Level-2

##### **GeeksForGeeks describe 0-level as:**

_"... also known as a context diagram. It’s designed to be an abstraction view, showing the system as a single process with its relationship to external entities."_

##### **GeeksForGeeks describe 1-level as:**

_"This level provides a more detailed view of the system by breaking down the major processes identified in the level 0 DFD into sub-processes. Each sub-process is depicted as a separate process on the level 1 DFD."_

##### **GeeksForGeeks describe 2-level as:**

_"This level provides an even more detailed view of the system by breaking down the sub-processes identified in the level 1 DFD into further sub-processes."_

\*It is important to note that JSON Web Tokens (JWTs) are generated in the Express backend, not fetched from the database. The database validates the user's credentials, after which the backend generates and issues the active token. While the data flow diagrams below depict the JWT in the path from the data store to the process, it is actually created within the backend itself.

![Level 0 and 1 DFD](./images/DFDiagram.png)

**0-Level Overview of the Survey App:**

- **_External entities:_**

  - Survey Creators: Submit survey details to create surveys.
  - Survey Respondents: Provide responses by filling out surveys.

- **_Central system:_**

  - Survey Application System processes all user requests.

- **_Data flows:_**

  - Survey Creators → Submit survey details → Survey Application System.
  - Survey Respondents → Submit survey responses → Survey Application System.
  - Survey Application System → Fetch survey data and results → Survey Creators.

- **_Data storage:_**

  - All survey data (e.g., questions, responses) is securely stored in MongoDB Atlas.

**Breakdown of Processes in the Survey Application:**

- **_Create Survey:_**

  - Survey Creator inputs survey details (title, description, questions).
  - Data is sent via RESTful API to the backend.
  - Backend validates and stores the survey in MongoDB Atlas.

- **_Distribute Survey:_**

  - A unique link (/survey/{surveyId}) is generated and shared with respondents.
  - Link routes users to a dynamically rendered survey page.

- **_Submit Responses:_**

  - Respondent answers survey questions.
  - Responses are sent via API to the backend for validation and storage.
  - Stored responses are associated with the respective survey in MongoDB Atlas.

- **_View Results:_**

  - Survey Creator requests survey analytics.
  - Backend processes stored responses and generates aggregated data.
  - Data is returned to the frontend and visualised using D3.js charts.

![Level 2 New Survey and Link DFD](./images/DFDLevel2.drawio.png)

### Further Data Flow Diagrams

**High Level Data Flow Chart Diagram**

![High Level Data Flow Diagram](./images/Dataflow_highlevel.jpg)

**Level 1 Flow Chart Diagram**

![Level 1 Flow Chart](./images/Level1_FlowChart.jpg)

### Level 2 Flow Chart Diagrams

**Respondent Survey Retrieval**

![Survey Respondent Flow Chart](./images/Flowchart_Respondent.jpg)

**New Survey Creation**

![New Survey Flow Chart](./images/Flowchart_NewSurvey.jpg)

</details>

### ▪ Application Architecture Diagrams

<details>
<summary>View</summary>
<br>
Server-side architecture refers to the framework that manages the operations and interactions of a web application's backend components. In this model, the server handles the core logic, processes client requests, interacts with databases, and delivers the appropriate responses to the client-side interface. This approach ensures efficient data processing, security, and scalability. <br>

In the context of the **SurveyBuddy** application, the server-side architecture is implemented as follows:

**Backend Framework:** Utilises Express.js to manage server-side logic and handle HTTP requests and responses.

**Database Interaction:** Employs MongoDB Atlas for data storage, with Mongoose serving as the Object Data Modeling (ODM) library to facilitate database operations.

**Authentication:** Implements JSON Web Tokens (JWT) for secure user authentication, ensuring that only authorised users can access specific functionalities.

**API Endpoints:** Defines RESTful API endpoints to enable communication between the frontend and backend, supporting operations such as survey creation, data retrieval, and analytics.

This server-side architecture ensures that your survey application operates efficiently, securely, and is capable of scaling to meet user demands.

![Application Architecture Diagram](./images/architecture.drawio.png)

\*It is important to note that both JWT generation and database connections rely on secret keys, which are essential for secure token creation and authentication. Without these keys, the app cannot function properly.

### **Tech Stack Architecture**

This list breaks down the key technologies used in each architectural component of the app.

#### **Frontend**

- **React**: Framework for building the user interface.
- **useContext API**: For managing global state within the app.
- **React Router DOM**: For routing and navigation between pages.
- **React Forms**: For handling survey inputs and user data.
- **D3.js**: For creating interactive charts and visualising survey analytics.
- **Styling Library** (Bootstrap): For designing the user interface.
- **HTTP Requests** (Fetch or Axios): For communicating with the backend.
- **Validation** (Zod): For client side validation.

#### **Backend (Express)**

- **Express.js**: Framework for building the server and API.
- **JWT**: For secure token-based authentication.
- **bcrypt**: For hashing and securely storing passwords.
- **dotenv**: For managing environment variables securely.
- **Mongoose**: For interacting with the MongoDB database.
- **Middleware**:
- **cors**: For handling cross-origin requests.
- **body-parser**: For parsing incoming request data (built-in for recent Express versions).
- **Node.js**: Runtime environment for executing JavaScript server-side.

#### **Database (MongoDB Atlas)**

- **MongoDB**: Cloud-based database for storing app data.
- **Mongoose**: Object Data Modeling (ODM) library for database communication.
- **Data Validation**: Ensures data integrity using Mongoose schemas.

#### **General Tools**

- **Git**: For version control and source code management.
- **npm**: For package management and dependency handling.
- **Deployment Platforms**: Netlify, and Render for hosting the app.
- **Testing Tools**:
- **Frontend**: Jest or React Testing Library.
- **Backend**: Mocha, Chai, or Supertest.

![Tech Architecture Diagram](./images/TechArchitectureDiagram.drawio.png)

### MERN Stack Architecture

![MERN Stack Architecture High View](./images/mern_architecture.jpeg)

The frontend and backend communicate using **HTTP request** and response calls, exchanging data in **JSON** (JavaScript Object Notation) format. **Express**, a server framework built on **Node.js**, powers the backend, managing these communications efficiently and securely.

The frontend will utilise reusable **React components** wherever possible to align with **DRY** (Don't Repeat Yourself) coding principles. The backend will be structured into **routes**, **controllers**, and **models**, each focusing on a specific task or concern to maintain clear **separation of responsibilities**.

### File System Architecture

```surveybuddy/
├── client/                # Frontend code
  ├── public/              # Static files like index.html
  ├── src/                 # Source files
  │ ├── components/        # Reusable React components
  │ ├── pages/             # Full-page components
  │ ├── context/           # React Context for state management
  │ ├── services/          # API calls and utilities
  │ ├── styles/            # CSS/SCSS files
  │ ├── App.tsx            # Root React component
  │ └── index.tsx          # React entry point
  └── package.json         # Frontend dependencies


├── server/                # Backend code
│ ├── controllers/         # Route controllers (business logic)
│ ├── models/              # Database schemas/models
│ ├── routes/              # API endpoints
│ ├── utils/               # Helper functions/middleware
│ ├── app.js               # Express app setup
│ ├── server.js            # Main server entry point
│ └── package.json         # Backend dependencies
│
├── .env                   # Environment variables
├── README.md              # Project documentation
├── package.json           # Top-level dependencies and scripts
├── tsconfig.json          # TypeScript configuration
└── .gitignore             # Ignored files for Git
```

A robust file system ensures that the application can scale effectively without becoming overly complex. It adheres to the **separation of concerns** principle, grouping related functionalities together while keeping unrelated files and directories separate. This structure enhances maintainability and makes it easier for new developers or team members to navigate and contribute to the project, even if they are unfamiliar with the source code.

Over the past year of the course, I’ve learned that keeping things separated whenever possible is an effective way to reduce frustrating bugs and improve clarity about each file’s purpose.

### Model View Controller Express Architecture

![MVC Diagram](./images/mvc_express.png)

To separate functionality, the system is structured into routes, controllers, models, and services:

- **Routes**: Handle incoming HTTP requests and forward them to the appropriate controllers.
- **Controllers**: Process the request, invoke the necessary business logic or database operations, and generate the HTTP response.
- **Models**: Interact directly with the database to fetch or write data.
- **Services**: Contain reusable business logic, decoupling complex operations from controllers.

This architecture ensures clear separation of concerns, maintainability, and scalability in the application.

</details>

---

### ▪ User Stories

<details>
<summary>View</summary>
<br>
To enlarge user story diagram's please click on image.

#### 1. Sam's User Story

Creating a new survey.

![Sam's User Persona](./images/UP_Sam.png)
![Sam's User Story Diagram](./images/SamsUS.png)

#### 2. Daisy's User Story

Completing an existing survey.

![Daisys User Persona](./images/UP_Daisy.png)
![Daisy's User Story Diagram](./images/DaisysUS.png)

#### 3. Sarah's User Story

Viewing the analytics page.

![Sarah's User Persona](./images/UP_Sarah.png)
![Sarah's User Sotry Diagram](./images/SarahsUS.png)

#### 4. Tim's User Story

Finding a survey link and emailing it to a friend.

![Tim's User Persona](./images/UP_Tim.png)
![Tim's User Story Diagram](./images/Tim'sUS.png)

#### 5. Alice's User Story

Navigating to the account page and logging out.

![Alice's User Persona](./images/UP_Alice.png)
![Alice's User Story Diagram](./images/Alice'sUS.png)

#### 6. John's User Story

Signing up to create a new SurveyBuddy account.

![John's User Persona](./images/UP_John.png)
![John's User Story Diagram](./images/John'sUS.png)

### Evidence of Revision and Refinement

![User Story Refinement](./images/US_refinement.jpg)
![Database in and out](./images/DB-inoutflow.jpg)

</details>

### ▪ Wireframes

<details>
<summary>View</summary>
<br>

Low Fidelity Wireframes Created with Simple Design Asset library.
<br>

**Landing Page**

The landing page is the first page users see when visiting SurveyBuddy, it allows users to learn about the application, view use cases, and to signup or login to their user account. This page should be inviting and simple, with a simple goal of encouraging user to register.

![Landing Page Wireframe](./images/Wireframe1.png)

Intended Actions:

- Sign up
- Login
- View use cases
- Contact
- Register email

**Surveys Page**

The purpose of this page is to allow users to view their created surveys, segregate them by organisation or by tag, perform CRUD operations, and click links to view analytics.

![Surveys Page Wireframe](./images/Wireframe2.png)

Intended Actions:

- View existing user created surveys
- Search for a existing survey
- Perform CRUD operations
- Click link to view analytics

**Login Page**

The purpose of this page is to allow users to login to their account by providing a username or email, and their secret password.

![Login Page Wireframe](./images/Wireframe3.png)

Intended Actions:

- Enter user login details (username or email, and password)

**Survey Page**

The purpose of this page is to allow users, registered or not registered, to answer survey questions and submit their responses.

![Survey Page Wireframe](./images/Wireframe4.png)

Intended Actions:

- Answer survey questions

**Pricing Page**

The purpose of this page is to allow users to learn about what is provided in each payment tier, and links to update their account to a paid monthly subscription service should they desire.

![Pricing Page Wireframe](./images/Wireframe5.png)

Intended Actions:

- Select account tier (free, business and premium)

**Community Page**

The purpose of this page is to allow users to learn about the application, its history and mission statement.

![Community Page Wireframe](./images/Wireframe6.png)

Intended Actions:

- Scroll down the page and read about the applications purpose, history mission etc.

**Interactivity Wireframe Page**

This wireframe overview demonstrates the interactive relationships between screens at a high level.

![Interactivity Wireframe Page](./images/newWFsPrototype.png)

Adhering to the app's mission to provide a simple platform for creating surveys and gathering insightful results, the wireframes above reflect this vision by prioritising MVP functionality, clean and straightforward layout, balanced space distribution, and clear, intuitive intended actions.

### Initial Wireframes Design

#### NavBar

![Nav Bar](./images/NavbarWF.png)

Interactions:

- Click
  - About - navigates to About page
  - Surveys - navigates to Surveys page
  - Recipients - navigates to Recipients page
  - Analytics - navigates to Analytics page

#### Home Page

![Home Page](./images/WF_1.png)

Interactions:

- Click
  - New Survey - navigates to create a new survey page

#### Respondent Survey

![Respondent Survey](./images/WF_2.png)

Interactions:

- Click
  - Submit - Submits survey response data to database
  - Multi Choice - Selects answer to be stored in database on submit

#### Create Survey

![Create Survey](./images/WF_3.png)

Interactions:

- Click
  - Question Type - Select type of question from drop down menu
  - Previous - Returns to previous question input
  - Next - Navigates to next question input
  - Submit - Submit's survey creator data to database

#### Survey Analytics

![Survey Analytics](./images/WF_4.png)

Interactions:

- Click
  - Image - to enlarge image

#### Survey's Page

![Survey's Page](./images/WF_6.png)

Interactions:

- Click
  - Survey - Navigates to analytics page
  - Link - Provides a copiable link to respondent survey

#### User Account

![User Account](./images/WF_5.png)

Interactions

- Click
  - Log Out - Logs user out of account

#### About Page

![About Page](./images/WF_7.png)

Interactions NA

#### Interactive Wireframe Diagram

![Interactive Wireframe Diagram](./images/InteractiveWF.png)

The UI for the survey app is designed to be simple and logical, ensuring an intuitive user experience. The wireframes above demonstrate exceptional planning of the project’s flow and structure, showcasing thoughtful space distribution, clear content prioritisation, and seamless navigation. They outline the intended actions, core functions, and relationships between screens, providing a comprehensive blueprint for the app’s development and ensuring a cohesive user journey.

</details>

---

### ▪ Project Management

<details>
<summary>View</summary>
<br>

### **Project Management Process Evidence**

To manage the development of my survey app, I used a **Trello board** structured with the following columns: **To Do**, **Doing**, **Done**, and **Signed Off**. This workflow aligns with key principles of the **Agile methodology**, ensuring iterative progress and continuous improvement even as a solo developer. Below is a detailed explanation of how my process meets Agile requirements:

#### **1. Sprint Planning**

- Tasks are broken down into manageable and actionable cards within the **To Do** column.
- Each card represents a clear deliverable or functionality, such as implementing wireframes, DFDs, or user personas.
- Tasks in Part-B are prioritised based on user needs, technical dependencies, and project goals.

#### **2. Focused Execution**

- I select tasks from the **To Do** column and move them to **Doing**, focusing on one task, or related tasks, at a time to maintain efficiency and limit time wastage.
- Each sprint focuses on completing a single card or a set of related cards within a short time frame of around 5 days.

#### **3. Iterative Development**

- Completed tasks are moved to the **Done** column, where they remain for a period of self-imposed review.
- This delay allows me to revisit the task after a couple of days with fresh eyes, ensuring quality and identifying potential improvements.

#### **4. Continuous Improvement**

- After review, tasks are either:
  - Improved and refined based on identified gaps or optimisations.
  - Moved to the **Signed Off** column once they meet the required standards and are considered complete, though cards can move back to the doing column at anytime should they require.
- This step mimics the retrospective phase of Agile Methodology, focusing on learning and refining my work iteratively as a predefined process.

#### **5. Transparency and Adaptability**

- The Trello board provides a clear and transparent overview of the project’s progress, from planned tasks to completed features.
- If priorities or requirements change, I adapt the task / card order in the **To Do** column to reflect the new focus areas.
- New cards can be made throughout the project process should they be needed, further providing adaptability to unforeseeable tasks or functionalities.

### **Why This Process Meets Agile Requirements**

- **Iterative Development**: Tasks are completed in small, manageable increments (sprints), allowing for continuous progress.
- **Focus on Quality**: The review process ensures tasks are revisited and refined, aligning with Agile’s emphasis on delivering high-quality, functional software.
- **Adaptability**: The Trello board structure allows for easy reprioritisation of tasks as needed.
- **Self-Reflection**: The review period mimics Agile retrospectives, fostering continuous improvement even as a solo developer.

This process ensures that my development workflow remains organised, iterative, and adaptable while following Agile principles in a manner appropriate for solo work.

</details>

### ▪ Trello Board Tracking

<details>
<summary>View</summary>
<br>

_It is important to note that the **Extra Tech Learning** and **Planning Methodology** cards represent ongoing tasks and are not considered part of sprints. These cards remain in the **Doing** column throughout most of Part A development and planning._

#### 13th Nov - **The Journey Begins!**

Populated the Trello board with initial Part A tasks. Researched app ideas and extra technology.

![Trello Board 13th Nov](./images/13:11_trello.png)

#### 14th Nov

Decided on final app idea - Survey Application - started on wireframes, user stories, mind map and mood board.

Continued with competitor research and learning extra tech - typescript.

![Trello Board 14th Nov](./images/14:11_trello.png)

#### 15th Nov

Completed Mood Board and continued learning TypeScript for React.

![Trello Board 15th Nov](./images/15:11_trello.png)

#### 17th Nov

Completed competitor research and started on Data Flow Diagrams.

![Trello Board 17th Nov](./images/17:11_trello.png)

#### 18th Nov

Completed high fidelity wireframes and user stories, created new low fidelity wireframes and user personas trello cards, decided to use D3.js for data visualisation and analytics, and continued with TypeScript for React online course.

![Trello Board 17th Nov](./images/18:11_trello.png)

#### 19th Nov

After speaking with my lecturer about wireframes, it was decided that basic high fidelity frames without styling would be sufficient, and that low fidelity wireframes would not be required. Therefore, this card was deleted from the project management Trello board.

When creating the data flow diagrams, flow chart symbols were used inplace of data flow diagram convention symbols, the diagrams were recreated using symbols following the Yourdon + De Marco convention in Drawio.

Adding User Persona's to each User Story including a profile picture, bio, goals, motivation, personality and skills sections.

![Trello Board 17th Nov](./images/19:11_trello.png)

#### 20th Nov

Completed Data Flow Diagrams and Application Architecture cards, reviewed cards in **Done** column, and moved to signed off where appropriate.

![Trello Board 20th Nov](./images/20:11_trello.png)

#### 21st Nov

Completed the application architecture diagram card and added a tech architecture diagram to it. Reviewed and made minor changes to wire frames, DFD, user personas and user stories cards and moved to **Signed Off**.

**Part A** of the assignment is almost complete, I now plan to focus my attention on learning TypeScript for React and **Part B** of the assignment.

An **Part A Review** card was added to the Trello Board, to be completed by mid next week.

![Trello Board 21th Nov](./images/21:11_trello.png)

#### 28th Nov

Today I completed a new set of wireframes using Simple Design System components in Figma, and the Part A review card, in relation to the HD requirements in the rubric. I started planning and structuring the final power point presentation, though, after speaking with my lecturer, it was decided that the presentation I was planning will take a more simple approach, so that the application build can take priority.

I am now confident that Part-A rubric points of the assignment are all completed to a level of quality, especially given the application is a solo project, and only minor styling edits will now be necesary before the final submission on Sunday.

![Trello Board 28th Nov](./images/28:11_trello.png)

#### 30th Nov

**Part-A complete! 🎉🎉🎉🎉🎉**

Submitted Part-A of the assignment, continued on with extra tech learning, and building the backend of Part-B.

![Trello Board 30th Nov](./images/30:11_trello.png)

#### November GitHub Contributions

![GitHub Contributions Tracker](./images/githubTracker.png)

</details>

---
