# Survey Buddy

## Part A

#### Front-End Repositiory [here](https://github.com/Survey-Buddy/surveybuddy-client).

#### Back-end Repository here.

#### Presentation here.

#### Project Management Trello Board here.

---

### Application Description

This survey app is designed to make creating and managing surveys effortless. Whether you’re a student collecting data for a project, an individual seeking personal insights, or a business gathering customer feedback, this app provides a simple and intuitive experience for all users.

With just a few clicks, you can design a custom survey tailored to your needs, select recipients from your network, and send it out instantly. The app ensures that managing responses is just as straightforward. Once the survey is completed, the collected data is displayed in an organised and easy-to-understand format, allowing you to gain valuable insights without hassle.

Built with a focus on simplicity and functionality, this app streamlines the process of creating, distributing, and analysing surveys, making it the perfect tool for anyone looking to gather meaningful information quickly and efficiently.

---

### Application Purpose

The purpose of this app is to provide a straightforward and affordable alternative to complicated and feature-heavy survey platforms. Many existing options overwhelm users with unnecessary features and costs. This app focuses on simplicity, ensuring users can quickly create, share, and analyse surveys without distractions or hidden expenses. It's perfect for those who value ease of use and clarity over complexity.

---

### Target Audience

##### Students:

- Ideal for conducting surveys for academic research, gathering peer feedback, or collecting data for projects, assignments, and theses.
- Useful for group work, where students can collaborate on surveys and analyze responses together.

##### Individuals:

- Perfect for personal insights, self-reflection, and hobby-related topics like fitness tracking, lifestyle choices, or creative writing polls.
- Enables individuals to run informal surveys for friends, social media followers, or community groups.

##### Businesses:

- Customer Feedback: Collect insights on customer satisfaction, product preferences, and overall experience.
- Employee Engagement: Run surveys to measure job satisfaction, gather suggestions, and understand team morale.
- Market Research: Conduct surveys to gather insights on market trends, product demand, and consumer behavior.
- Event Planning: Create RSVP forms or post-event feedback surveys to improve future events.

##### Educators and Trainers:

- Useful for creating quizzes, feedback forms, and evaluations for classes or workshops.
- Allows for tracking and analyzing student or trainee progress over time.
  Nonprofits and Community Groups:

- Ideal for collecting input from members, running community feedback polls, or gathering opinions on local issues.
- Enables organizations to track the impact of their initiatives and programs.
  Healthcare Professionals:

- Use for patient satisfaction surveys, pre-appointment checklists, or anonymous feedback on care quality.

##### Freelancers and Creators:

- Collect feedback on services, products, or creative content like art, music, or writing.
- Use as a tool to engage audiences and build community trust through polls or feedback forms.

##### Small and Large Teams:

- Track project progress and gather feedback from team members in real-time.
- Use surveys for retrospectives, brainstorming sessions, or decision-making.

---

### Technology Stack

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

Other technologies include:

- TypeScript

  <img src="./images/Typescript.png" alt="TypeScript logo" width="100" >

  _"TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale."_ - typescript.com

- Boostrap

  <img src="./images/Bootstrap.webp" alt="Bootstrap logo" width="100" >

  _"Powerful, extensible, and feature-packed frontend toolkit. Build and customize with Sass, utilize prebuilt grid system and components, and bring projects to life with powerful JavaScript plugins."_ - bootstrap.com

- Chakra UI

  <img src="./images/chakra.png" alt="Chakra logo" width="200" >

_"Accessible React components for building high-quality web apps and design systems."_ - chakra-ui.com

- Mongoose

  <img src="./images/mongoose.png" alt="Mongoose logo" width="200" >

_"Mongoose is an ODM (Object Data Modeling) library for MongoDB."_ - mongodb.com

- Amazon S3

  <img src="./images/AmazonS3.png" alt="Amazon S3 logo" width="200" >

_"Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance."_ - aws.amazon.com/s3

---

### Functionality / Features

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

#### Mood Board

To analyse competitor applications and gain a deeper understanding of their features and user interfaces, I created a Mood Board showcasing aesthetics and layouts that resonated with me.

![Mood Board](./images/MoodBoard.png)

---

### Crucial Decisions

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

---

### Logo Ideas

1.

![SurveyBuddy Logo idea 1](./images/SB_logo1.png)
![SurveyBuddy Logo idea 1 Green](./images/SB_logo1green.png)

2.

![SurveyBuddy Logo idea 2](./images/SB_logo2.png)

3.

![SurveyBuddy Logo idea 3](./images/SB_logo3.png)

4.

![SurveyBuddy Logo idea 4](./images/SB_logo4.png)

---

### Style Guide

---

### Data Flow Diagram

#### Data Flow Diagram Methods & Symbols

\*For this application, the Yourdon + De Marco convention will be used.

![Data Flow Diagram Methods and Symbols](images/Data-Flow-Diagram-Methods-&-Symbols.webp)
_geeksforgeeks.org_

There are three levels of Data Dlow Diagrams (DFDs), these inlclude:

- Level-0
- Level-1
- Level-2

#### GeeksForGeeks describe 0-level as:

_"... also known as a context diagram. It’s designed to be an abstraction view, showing the system as a single process with its relationship to external entities."_ - geeksforgeeks.com

#### GeeksForGeeks describe 1-level as:

#### GeeksForGeeks describe 2-level as:

![Level 0 and 1 DFD](./images/DFDiagram.jpg)

0-Level Overview of the Survey App:

- _External entities:_

  - Survey Creators: Submit survey details to create surveys.
  - Survey Respondents: Provide responses by filling out surveys.

- _Central system:_

  - Survey Application System processes all user requests.

- _Data flows:_

  - Survey Creators → Submit survey details → Survey Application System.
  - Survey Respondents → Submit survey responses → Survey Application System.
  - Survey Application System → Fetch survey data and results → Survey Creators.

- _Data storage:_

  - All survey data (e.g., questions, responses) is securely stored in MongoDB Atlas.

Breakdown of Processes in the Survey Application:

- _Create Survey:_

  - Survey Creator inputs survey details (title, description, questions).
  - Data is sent via RESTful API to the backend.
  - Backend validates and stores the survey in MongoDB Atlas.

- _Distribute Survey:_

  - A unique link (/survey/{surveyId}) is generated and shared with respondents.
  - Link routes users to a dynamically rendered survey page.

- _Submit Responses:_

  - Respondent answers survey questions.
  - Responses are sent via API to the backend for validation and storage.
  - Stored responses are associated with the respective survey in MongoDB Atlas.

- View Results:

  - Survey Creator requests survey analytics.
  - Backend processes stored responses and generates aggregated data.
  - Data is returned to the frontend and visualised using D3.js charts.

![Level 2 New Survey and Link DFD](./images/DFDLevel2NewSurvey.jpg)

## Flow Charts

\*DFD's were initally made using the flow chart symbols.

**Flow Chart Legend**

![Flow Chart Legend](./images/DataFlow_Legend.jpg)

#### High Level Flow Chart Diagram

![High Level Flow Chart](./images/HL_Flowchart.jpg)

#### Level 1 Flow Chart Diagram

![Level 1 Flow Chart](./images/Level1_FlowChart.jpg)

### Level 2 Flow Chart Diagrams

#### Respondent Survey Retrieval

![Survey Respondent Flow Chart](./images/Flowchart_Respondent.jpg)

#### Respondent Survey Completion

![Survey Completion Flow Chart](./images/Flowchart_SurveyCompletion.jpg)

#### New Survey Creation

![New Survey Flow Chart](./images/Flowchart_NewSurvey.jpg)

---

### Application Architecture Diagram

---

### User Stories

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

---

### High Fidelity Wireframes

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

#### Interactive Wireframe Diagram

![Interactive Wireframe Diagram](./images/InteractiveWF.png)

The UI for the survey app is designed to be simple and logical, ensuring an intuitive user experience. The wireframes above demonstrate exceptional planning of the project’s flow and structure, showcasing thoughtful space distribution, clear content prioritisation, and seamless navigation. They outline the intended actions, core functions, and relationships between screens, providing a comprehensive blueprint for the app’s development and ensuring a cohesive user journey.

---

### Project Management Tracking

#### 13th Nov

The journey begins!

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

![Trello Board 17th Nov](./images/18:11_trello.png)

---

Reference List

---
