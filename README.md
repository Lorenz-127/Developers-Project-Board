# Title
Developers Project Board

## Table of Contents

01. [**Project Rationale**](#project-rationale)
    - [Key Project Goals](#key-project-goals)
    - [Target Audience](#target-audience)
    - [User Stories](#user-stories)

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


## Project Rationale

Developers Project Board is a full-stack web application designed to provide a powerful, intuitive task management solution specifically tailored for developers. This project aims to combine the visual simplicity of a kanban-style interface with advanced features typically found in professional project management tools, offering a unique platform for individuals and teams to boost their productivity in software development projects.

### Key Project Goals

1. Develop a responsive and user-friendly web application that can handle complex task management efficiently for software development projects.
2. Implement advanced features such as board customization, task prioritization, and team collaboration while maintaining an intuitive user interface.
3. Create a flexible data model that allows for future scalability and potential integration with other development tools.

#### Site Owner Goals

- Create a user-friendly agile management platform for developers
- Provide a secure and reliable service
- Encourage user engagement and retention
- Establish a foundation for future feature expansion

#### User Goals

- Easily organize and manage tasks and software development projects
- Collaborate with team members efficiently
- Access task information from any device
- Customize boards and lists to fit specific development workflow needs

### User Stories

1. Emma - The Tech Project Manager

    - Demographics:
        - Age: 32
        - Occupation: Project Manager at a software development company
        - Location: Urban area, manages a hybrid team (remote and in-office)

    - Background:
        - Experienced in using various project management tools
        - Manages multiple software development projects simultaneously
        - Values visual organization and clear communication in project tracking

    - Motivations and Goals:
        - Wants to streamline development workflows and improve team collaboration
        - Needs to categorize tasks by project phase, assign team members, and set priorities
        - Aims to improve project visibility and track team productivity

    - Detailed User Journey:
        Emma starts her day by logging into Developers Project Board. She quickly creates a new board for an upcoming software project, setting up lists for different development phases (e.g., Backlog, In Progress, Testing, Done). Throughout the day, she adds new tasks, assigns them to team members, and sets due dates. She uses the board's customization features to color-code tasks by priority. During team meetings, Emma shares the board to discuss progress and adjust workflows as needed.

    - User Benefits:
        - Visual representation of development workflows enhances team understanding
        - Easy task assignment and priority setting improves project management
        - Real-time updates and collaboration features keep the development team aligned

2. Alex - The Freelance Developer

    - Demographics:
        - Age: 28
        - Occupation: Fulltime freelance web developer
        - Location: Works remotely, frequently travels

    - Background:
        - Comfortable with various development tools and project management software
        - Juggles multiple client projects with personal development goals
        - Prefers flexible, accessible tools that work across devices

    - Motivations and Goals:
        - Needs a system to manage both client work and personal coding projects efficiently
        - Wants to prioritize tasks effectively to balance multiple responsibilities
        - Aims to improve time management and maintain a clear overview of all ongoing development projects

    - Detailed User Journey:
        Alex begins his week by reviewing his Developers Project Board dashboard. He has separate boards for each client project and one for personal development goals. He adds new tasks related to ongoing projects, sets due dates, and prioritizes his workload for the week. Throughout the day, he uses the mobile version of Developers Project Board to quickly add or modify tasks as new ideas or client requests come in. He regularly uses the filtering and search features to focus on the most critical tasks across all his development boards.

    - User Benefits:
        - Centralized platform for managing both client and personal development projects
        - Flexibility to access and update tasks from any device
        - Visual organization helps maintain a clear overview of multiple ongoing coding projects

[Back to Top](#table-of-contents)

### Design Choices
#### Color Scheme

![Developers Project Board Color Palette](/assets/readme/PP4-Colors.png)

The color palette is designed to create a professional, calming, and easy-to-use interface:

- Slate Gray (#708090) serves as the main background color, providing a neutral base for the application.
- Dark Slate Gray (#2F4F4F) is used for the header and primary interactive elements, offering a strong contrast.
- Dark Slate Gray variants with different opacities (#2F4F4F6E at 43% and #2F4F4F94 at 58%) are used for list backgrounds and board tiles, creating depth and hierarchy.
- Very Dark Blue (#091E4240, 25% opacity) is used for card backgrounds, adding subtle depth to the interface.
- Light Gray (#F5F5F5B5, 71% opacity) is used for text and icons to ensure readability against darker backgrounds.

This color scheme creates a balanced, professional look while ensuring good contrast and readability throughout the application. \
The use of opacity in several colors allows for a layered design that adds visual interest without compromising usability.

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
### Issues

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