# Title

## Subtitle

### Project Overview

### Key Features

### Target Audience

## Table of Contents

1. [Features](#features)
   - [Key Features Summary](#key-features-summary)
   - [Additional Features Summary](#additional-features-summary)

2. [User Experience (UX)](#user-experience-ux)
   - [Project Goals](#project-goals)
   - [User Stories](#user-stories)
   - [Design Choices](#design-choices)
   - [Wireframes](#wireframes)

3. [Information Architecture](#information-architecture)
   - [Flowchart](#flowchart)
   - [Database Schema (ERD Diagram)](#database-schema-erd-diagram)
   - [Data Models Description](#data-models-description)

4. [Technologies Used](#technologies-used)
   - [Languages](#languages)
   - [Frameworks & Libraries](#frameworks--libraries)
   - [Databases](#databases)
   - [Other Tools & Services](#other-tools--services)

5. [Agile Methodology](#agile-methodology)

6. [Version Control](#version-control)

7. [Deployment](#deployment)

8. [Forking and Local Setup](#forking-and-local-setup)

9. [Testing](#testing)

10. [Bugs and Fixes](#bugs-and-fixes)

11. [Unsolved Issues and Bugs](#unsolved-issues-and-bugs)

12. [Future Features](#future-features)

13. [Credits](#credits)
    - [Code](#code)
    - [Content](#content)
    - [Media](#media)
    - [Tools](#tools)
    - [Other Resources for Learning and Reference](#other-resources-for-learning-and-reference)
    - [Honourable Mentions](#honourable-mentions)
    - [Note on code used from third-party sources](#note-on-code-used-from-third-party-sources)

## Features

### Key Features Summary

### Additional Features Summary

## User Experience (UX)

### Project Goals

#### Site Owner Goals

#### User Goals

### User Stories

### Design Choices
#### Color Scheme
#### Typography
#### Imagery

### Wireframes
#### Mobile Design
#### Desktop Design

#### Key Pages Wireframed
#### Wireframe to Implementation

## Information Architecture
### Flowchart
### Database Schema (ERD Diagram)

### Data Models Description

### Database Relationships

## Technologies Used
### Languages
### Frameworks & Libraries
### Databases
### Other Tools & Services

## Agile Methodology
### Project Management
### User Stories

User Stories were created as GitHub Issues and managed through the project board. Each user story was assigned a priority label using the MoSCoW method:

- Must Have
- Should Have
- Could Have
- High Complexity
- Won't Have (this time)

### Kanban Board
The Kanban board consisted of the following columns:

1. **Backlog**: Open Issues for MoSCoW prioritizing
2. **MVP**: All Issues for pass criteria
3. **ToDo**: User stories for the current sprint
4. **In Progress**: Stories actively being worked on
5. **In Review**: Stories ready for testing
6. **Done**: Completed stories

### Milestones

- Agile Framework Setup
    - As a project manager, I want to establish the Agile framework so that we can manage the project using Agile methodologies
- Board Management
    - As a project manager, I want to create a board management system so that users can organize their projects effectively
- Card Management
    - As a project manager, I want to develop card management features so that users can create and manage individual tasks
- User Permissions
    - As a project manager, I want to implement a permission system so that board owners can control access to their boards
- Development Environment Setup
    - As a developer I can set up my local development environment so that I can start coding the project efficiently
- UI/UX Development
    - As a project manager, I want to ensure a user-friendly interface so that users can navigate and use the application intuitively
- List Management
    - As a project manager, I want to implement list management features so that users can categorize tasks within their boards
- User Authentication and Profiles
    - As a project manager, I want to implement user authentication and profile management so that users can securely access and manage their accounts
- Design planning
    - As a UX designer, I can create comprehensive design documentation so that the development team has clear guidelines for implementing the Project-Board application
- Project Initialization
    - As a project manager, I want to set up the project infrastructure so that development can begin efficiently
- Deployment
    - As a project manager, I want to deploy the application to a cloud platform so that it is accessible to users online
- Sprint Planning
    - As a project manager, I want to plan and execute sprints so that we can deliver value incrementally and maintain project momentum
- Celebrate Intermediate Successes
    - As a project manager, I want to recognize and celebrate small victories so that team morale and motivation remain high throughout the project
- Continuous Improvement
    - As a project manager, I want to implement processes for continuous improvement so that we can refine our project and methodologies throughout development
- Testing and Documentation
    - As a project manager, I want to ensure comprehensive testing and documentation so that the application is reliable and maintainable

### Agile Approach Benefits

By using Agile methodology, I was able to:

- Respond quickly to changes in requirements
- Deliver working features incrementally
- Maintain a clear overview of project progress
- Prioritize features effectively based on their importance and complexity

[Go to Table of Contents](#table-of-contents)

## Version Control

## Forking and Local Setup

If you'd like to fork this repository and run it locally, follow these steps:

1. **Fork the Repository**:
   - Navigate to the GitHub repository: [Developers Project Board](https://github.com/Lorenz-127/PP4-Project-Board)
   - In the top-right corner of the page, click the "Fork" button.
   - This will create a copy of the repository in your GitHub account.

2. **Clone Your Fork**:
   - On your forked repository page, click the "Code" button and copy the URL.
   - Open your terminal and run:
     ```
     git clone [URL you just copied]
     ```
   - This creates a local copy of the repository on your machine.

3. **Set Up Virtual Environment**:
   - Navigate into the project directory:
     ```
     cd [project directory name]
     ```
   - Create a virtual environment:
     ```
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On Windows: `venv\Scripts\activate`
     - On macOS and Linux: `source venv/bin/activate`

4. **Install Dependencies**:
   - With your virtual environment activated, install the required packages:
     ```
     pip install -r requirements.txt
     ```

5. **Set Up Environment Variables**:
   - Create a `env.py` file in the root directory of the project.
   - Add the following variables (replace with your actual values):
     ```
     SECRET_KEY=your_secret_key
     DATABASE_URL=your_database_url
     CLOUDINARY_URL=your_cloudinary_url
     DEBUG=True
     ```
    Important Notes: 
    - Make sure to set `DEBUG=True` for local development and testing in `env.py`. In `settings.py`, DEBUG mode will be automatically recognized for the development environment based on the presence of the `DEBUG` variable in `env.py`.
    - Remember to never commit the `env.py` file or any sensitive information to version control. If you plan to deploy your fork, make sure to set up the necessary environment variables in your deployment environment.

6. **Apply Migrations**:
   - Run the following commands to apply database migrations:
     ```
     python manage.py makemigrations
     python manage.py migrate
     ```

7. **Run the Development Server**:
   - Start the Django development server:
     ```
     python manage.py runserver
     ```
   - Open a web browser and navigate to `http://127.0.0.1:8000/` to view the application.

[Go to Table of Contents](#table-of-contents)


## Testing

## Bugs and Fixes

## Unsolved Issues and Bugs

## Future Features

## Credits
### Code
### Content
### Media
### Other Resources for Learning and Reference
### Honourable Mentions