## Summary

1. Project Planning
2. Project Setup
3. Project Workflow
4. Project Development
5. Project Deployment
6. Project Presentation

## 1. Project Panning

In the planning phase, you’ll prepare several documents to help guide your team through the execution of your project.

- [x] Google API - Takuya
- [x] ChatGPT API - Ramic
- [x] Instantly API - Monica

### Deadline:

Today, May 11, 2023 - Monica

#### a. Project Description:

Email marketing app to use the power of AI to personalize the first line of an email. To automate the process of adding leads to email campaign.

#### Project Title:

Title Here
Choices:

1. Lead
2. Fyrst
3. HotMailing
4. From Cold Email to Hot Email
5. emAI

#### Project Description:

- First Line AI Personalized Email Marketing App
- Easily scalable because it automates the process creating personalize first line email to leads of marketing.
- Simplifying the process of uploading and reviewing the process.
- Keeps the cost down because you don't need to hire more people to specifically work on the process.

#### Target Audience:

- All businesses that use email to communicate and get sales lead.

#### Team Members:

- Ramic Laguitan
- Takuya Toyokawa
- Monica Wolfe

#### Deliverable:

Project Description document

#### b. User Stories

User stories allow you to draft the high-level requirements based on the user needs. It should describe the interaction of the user and the app.

#### Deliverable:

User stories document:

- User log in using google auth
- User should be able to select their google sheet and upload it directly to the app.
- User should be able to map the input and map the result to the specific columns they choose.
- User should be able to review the output from AI(ChatGPT) before sending it or post the value to google sheet.
- Get the updated value and send it to an email campaign using instantly.

#### c. Wireframe

#### Deliverable:

Wireframe designs

- [x] Monica

#### d. Entity Relationship Diagram

#### Deliverable:

ERD design:

- [x] Takuya

#### e. Stack Choices

What are the technologies you’re going to use to develop for your app. You need to think about:

Front-End:

- NextJS-13.4, CSS Modules
  Back-End
- NodeJS
- Express, Prisma
  Database
- Postgres

#### Deliverable:

Stack choices document

## 2. Project Setup

To start off on the right foot, you’ll need a good project setup:

#### a. Git repo setup

- Create a repo on GitHub and give access to all team members.
- [x] Takuya

#### b. Project scaffold

If needed, you have to decide which boilerplate code you’re going to use for your project.

- nothing (our own)

#### c. Database setup

You may need to create the database and the initial migration.

- [x] Takuya

#### d. Seed file

You may need to create a seed file since the content of the database should never be part of your repo. Each team member will have to seed their local database.

#### Deliverable:

Setup of your app

## 3. Project Workflow

#### a. Project Communication

We highly recommend that your group implements a daily stand up which will allow better communication and follow-up. You can appoint one member of your team to be the "Stand Up Master", or you can ask a mentor to help lead your stand up meetings. The stand up will allow to review:

What has been accomplished
What will you be working on
What hurdles are you facing

#### Deliverable:

- [x] Daily stand up - Monica

#### b. Project Workflow

You need to take a few key decisions to ensure a smooth project workflow. Ideally, you should think about the following:

What are the project milestones: you need to create a list of the project milestones and specify what are the deadlines.
Git workflow: establish rules about how you’re going to manage your Git workflow. You can discuss it with a mentor if needed.
How to distribute teamwork: before distributing work, you might want to consider working together until you build the core of your app. Afterward, you need to think about how you will distribute the work among your team members.
Coding styles: consider establishing some coding guidelines to ensure consistency between team members.

#### Deliverable:

Project milestones document
Git Workflow:

1. When adding features to the app, please create a new branch first before writing code to ensure that bugs and conflicts can be avoided on the main branch.

2. After writing code and testing functionality to see if it works, please run the command git pull --all in order to get the updated state of the master branch.

3. After git pull --all, git add and git commit, following the convention of present tense rather than past tense. Instead of "Created endpoints..." type "Create endpoints..." instead.

4. Push your code using the command "git push origin <branch-name>", in order to ensure that it shows on the repo before we can merge the changes made to the master branch.

Thanks! This is to ensure that we all keep track of what goes in and out of our master code branch when working on features independently

## 4. Project Development

You should work on the development of your app according to your feature list and project milestones. You should not develop any new features beyond week 11 day 5, since you need to prepare for Demo Day.

### Deadline:

Friday, May 19, 2023

## 5. Project Deployment

You should have a production-ready local version of your app for Demo Day. Optionally, you might want to consider deploying your app on Railway.app (or elsewhere). However, you need to account for the extra time to deploy on Railway.app (or again, elsewhere).

- Vercel

#### a. Testing, bug fixing

Make sure you take time to test the functionalities of your app. You need to think about:

Testing, testing, testing
Fixing bugs
Refactoring your code
Cleaning up your code

### Deadline:

Demo Day minus 2
Monday, May 22, 2023

## 6. Project Presentation

It’s important to take some time to structure the presentation of your app.

Who is the target audience:
You have 2 targets: Employers and the public. For prospective employers you should focus on what you’ve accomplished, highlight - your skills, the technologies you used. For the public, it’s more about the user experience.
You should have a script for the live demo. Optionally, you might want to consider using a power point.
Audio/video setup: it’s important that you check your setup to ensure that everything works.
Presentation practice: It’s important to practice before Demo Day. You should practice in front of a mentor so you can get some feedback.

### Deadline:

- Practice Demo (with mentors): Demo Day minus 1 - Demo Day
- Wednesday, May 24, 2023
