# Synertek Project Management Portal

> **Project Showcase:** This repository is a public overview of a full-stack web application we developed for Synertek Technologies. The source code is private.

## Overview

For this project, we built a web portal to help manage the commissioning of projects in the commercial building environment. The main goal was to give project owners and admins one place to communicate, track progress, and work through project checklists.

The portal also gives admins, project owners, and users a central place to view and manage project information. Instead of having everything spread across different places, the application keeps project data organized within one system. Systems, equipment, checklists, sections, and tasks can all be managed through the same application.

## Technical Details

### Front End

We built the frontend using React.js and Material UI. React was used to create the interface and manage the different parts of the portal. Material UI helped us keep the design consistent across the application.

### Back End

The backend was built with Node.js and Express.js. We used Express REST API routes to handle things like creating and retrieving project data. Authentication was also added to protect parts of the application that required authorized access.

### Database

MongoDB was used as the main database. Since the project data has a hierarchical structure, MongoDB worked well for storing the different pieces of information used throughout the portal.

## Database Design

The database was organized around several main collections:

- **Users Collection:** Stores user information, roles, and account details.
- **Groups/Companies Collection:** Stores information about organizations involved in projects.
- **Projects Collection:** Stores project information and related project data.
- **Issues Collection:** Stores issues that are identified within projects.
- **Equipment Collection:** Stores equipment information and related project data.
- **Checklists Collection:** Stores checklists connected to equipment and project tasks.

## Architecture

The diagram below shows the portal’s architecture and how requests move between the frontend, backend API, and MongoDB database.

<p align="center">
  <img width="600" alt="Synertek Portal Architecture" src="https://github.com/user-attachments/assets/ad3776e5-7040-4427-80cc-c0bc3ef45528">
</p>

## Version Control

We used Git for version control and GitHub to host the repository. Committing changes regularly helped us keep track of what was being worked on, coordinate changes between team members, and catch problems during development.

## Challenges

One of the harder parts of the project was learning several new technologies while also building software for a real client. At the beginning, there was a learning curve, but the team became much more comfortable with the technology stack as the project went on.

We also had to make sure the application continued to match what the client actually needed. Regular communication and project demonstrations helped us check our progress and make sure we were still moving in the right direction.


