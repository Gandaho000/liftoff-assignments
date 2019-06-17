# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
I would like to create a web app for an accounting firm in St. Louis. I will update the current website to have a more robust frontend using javascript and bootstrap. I will implement a backend system that allows admins to update information about workflows, client billing, and other important tasks at the company. 

The current website is outdated and is not responsive. Mobile users have a terrible experience on the site. This company is in need of an update. 

### Features
Admin login: Admins will be able to login to access important informtation regarding the firm.

Client Info Database (Name of Company, Company Contact 1, Company Contact 2, Company Contact 3, Address, Phone Number, Phone Number 1, Phone Number 2, Phone Number 3, Phone Number 4, Email Address, Email Address 1, Email Address 2, Email Address 3, Email Address 4)

There is going to be a form that clients can use to enter all of the information. Once they submit the form they will be added to the database. Admins can later assign customers to tasks they create. 

Worflow Tasks (Admins will be able to create a name of a workflow and add tasks that need to be completed. Once completed the admins will be able to delete the task. Once deleted the system will display the task with a strike, the date and time it was striked, and the name of the user who deleted the task)

New clients added to the database will be put in a list so the staff will know to send them a thank you card

All new clients will be put into a list that will be accessible to admins. There are some onboarding tasks that each new client will have to go through before being removed from the new client list. 

Clients will have tags associated with them that shows what kind of client they are. Accounting, Consulting, Tax, Payroll, etc

The company uses Quickbooks to manage invoices. Quickbooks offers an API that allows devs to utilize information from the local app. I would like to display open balances for clients in the database.

Taks - To make it easier I would like to have workflow/task templates for processes that are done regularly. So instead of an admin adding one task. They can add a task template to a client that automatically adds a list of tasks to that client. 

Client Emailing System - I would like there to be a way for admins to send templated emails through the admin system. This could be a link that opens Outlook, with prefilled content tailored for that client

### Technologies
- Java
- Javascript
- SQL database
- Hibernate
- Spring
- Thymeleaf
- Quickbooks Desktop API


### What I'll Have to Learn
Javascript

Quickbooks API

I am going to have to learn how to associate the company contact with the correct phone number. I'm going to have to learn to learn how to correctly map clients information in the databases. 