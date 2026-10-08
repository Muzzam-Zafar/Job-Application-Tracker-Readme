# Job Application Tracker

A practical and responsive web application designed to help job seekers
organize, manage, and track their job applications throughout the hiring
process.

The application brings job details, application status, interviews,
recruiter information, documents, notes, follow ups, and important
deadlines into one organized workspace.

## Preview

The current frontend includes a dashboard, applications table, Kanban
board, and detailed application view.

![Job Application Tracker
Preview](screenshots/job-application-tracker.png)

> Add the screenshot above to the public README repository at
> `screenshots/job-application-tracker.png`.

## Overview

Managing multiple job applications can become difficult when information
is spread across spreadsheets, emails, notes, and different job
platforms.

The Job Application Tracker brings the job search workflow into one
place so users can track progress, manage important information, and
stay organized throughout the hiring process.

## Features

### Application Management

-   Add new job applications
-   Store job title and company information
-   Save job descriptions
-   Add application URLs
-   Record application dates
-   Track application deadlines
-   Assign application priority

### Application Status

Applications can move through different stages:

-   Saved
-   Applied
-   Screening
-   Interview
-   Offer
-   Hired
-   Rejected
-   Withdrawn

### Dashboard

The dashboard provides an overview of the job search, including:

-   Total applications
-   Active applications
-   Upcoming interviews
-   Applications by status
-   Offers received
-   Rejected applications

### Interview Management

-   Add interview dates and times
-   Save meeting links
-   Record interview locations
-   Add interview notes
-   Track interview progress

### Recruiter Management

Store important recruiter information such as:

-   Recruiter name
-   Email address
-   Phone number
-   LinkedIn profile
-   Recruiter notes

### Follow Up Tracking

Create reminders after:

-   Submitting an application
-   Completing an interview
-   Speaking with a recruiter
-   Receiving an update
-   Sending additional documents

### Resume and Cover Letter Tracking

Keep track of documents used for each application:

-   Resume version
-   Cover letter
-   Portfolio link
-   Additional documents

### Search and Filtering

Quickly find applications using:

-   Company
-   Job title
-   Location
-   Status
-   Priority
-   Application date

### Kanban Board

Applications can be managed visually through a Kanban workflow:

``` text
Saved → Applied → Screening → Interview → Offer → Hired
```

Applications can also move to Rejected or Withdrawn when required.

### Calendar View

The calendar can be used to organize:

-   Application deadlines
-   Interviews
-   Follow ups
-   Important job search events

### Salary Tracking

Store compensation information such as:

-   Salary range
-   Expected salary
-   Bonus
-   Benefits
-   Remote, Hybrid, or On site status

### Notes

Add notes to individual applications for:

-   Interview preparation
-   Recruiter conversations
-   Job requirements
-   Technical requirements
-   Follow up information

## Frontend Focus

The project focuses on creating a practical and user friendly frontend
experience.

Key frontend considerations include:

-   Responsive layouts
-   Reusable React components
-   Clear application states
-   Loading states
-   Error handling
-   Empty states
-   Form validation
-   API integration
-   Consistent user experience
-   Maintainable component structure

The goal is to make the application functional while keeping each
interaction clear and predictable for the user.

## Tech Stack

### Frontend

-   React.js
-   JavaScript
-   HTML5
-   CSS3
-   Responsive Web Design

### API and Data

-   REST APIs
-   JSON
-   SQL and database integration

### Development Tools

-   Git
-   GitHub
-   VS Code

## Project Structure

``` text
job-application-tracker/
│
├── src/
│   ├── components/
│   │   ├── Dashboard/
│   │   ├── Applications/
│   │   ├── Interviews/
│   │   ├── Calendar/
│   │   └── Common/
│   │
│   ├── pages/
│   ├── services/
│   │   └── api.js
│   │
│   ├── hooks/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
│
├── public/
├── package.json
├── .gitignore
└── README.md
```

## Getting Started

### 1. Clone the repository

``` bash
git clone https://github.com/your-username/job-application-tracker.git
```

### 2. Open the project

``` bash
cd job-application-tracker
```

### 3. Install dependencies

``` bash
npm install
```

### 4. Start the development server

``` bash
npm run dev
```

The application will be available at the local development URL shown in
the terminal.

## Example Application

``` json
{
  "jobTitle": "Frontend Developer",
  "company": "Example Company",
  "location": "Lahore, Pakistan",
  "status": "Interview",
  "priority": "High",
  "source": "LinkedIn",
  "applicationDate": "2026-10-08",
  "interviewDate": "2026-10-15",
  "salary": "PKR 150,000 - 200,000"
}
```

## Application Workflow

``` text
Saved
  ↓
Applied
  ↓
Screening
  ↓
Interview
  ↓
Offer
  ↓
Hired
```

Applications may also move to Rejected or Withdrawn.

## Development Goals

This project was built with a focus on practical software development
principles:

-   Building reusable frontend components
-   Creating responsive interfaces
-   Integrating REST APIs
-   Handling different application states
-   Validating user input
-   Managing asynchronous data
-   Handling errors gracefully
-   Improving usability
-   Writing maintainable frontend code
-   Designing interfaces around real user workflows

## Future Improvements

Possible future improvements include:

-   AI powered resume analysis
-   Job description and resume matching
-   Resume keyword analysis
-   Automatic job importing
-   LinkedIn job integration
-   Email integration
-   Automated follow up emails
-   Interview preparation assistant
-   Resume version management
-   Advanced application analytics
-   Dark mode
-   Mobile application
-   CSV and PDF export

## Screenshots

### Dashboard

The dashboard provides a high level view of applications, application
status, interviews, and recent activity.

### Applications

The applications page provides a searchable and filterable view of
tracked applications.

### Kanban Board

The Kanban board provides a visual way to manage applications by status.

### Application Details

The application details page brings job information, timeline, recruiter
details, interview information, attachments, notes, and follow up
reminders together.

![Dashboard, Applications, Kanban Board, and Application
Details](screenshots/job-application-tracker.png)

## Author

### Muzzam Zafar

**Associate Software Developer \| Frontend Developer**

Focused on building responsive and practical web applications using
React.js, JavaScript, REST APIs, and modern frontend development
practices.

### Skills

-   React.js
-   JavaScript
-   Frontend Development
-   REST API Integration
-   SQL and Database Fundamentals
-   Git and GitHub
-   Responsive Web Development

## License

This project is licensed under the MIT License.
