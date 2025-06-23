# CS 499 Computer Science Capstone 
**By: Chetachi Ezikeuzor**

Welcome! This repository contains the final deliverables for my CS 499 Capstone project at Southern New Hampshire University. The focus of this project was to take an existing full-stack web application—Travlr Getaways—and enhance it across three core areas: software engineering and design, algorithms and data structures, and database integration.

Below you’ll find a link to my code review video and the written addendum, which describes existing functionality and explains how each enhancement aligns with course outcomes.

## Contents
- [Professional Self-Assessment](#professional-self-assessment)
- [Code Review Video](#code-review-video)
- [Milestone One Addendum](#milestone-one-addendum)
- [Artifact Enhancements](#artifact-enhancements)
- [Artifact Overview: Travlr Getaways](#artifact-overview-travlr-getaways)
- [Artifact Files](#artifact-files)
- [Repository Structure](#repository-structure)

## Professional Self-Assessment

[Self-Assessment (Word Document)](CS_499_-_Professional_Self_Assessment_-_Chetachi.docx)

This document is the holistic introduction to who I am as a developer. It reflects on my time in the CS program, touches on the core skills I’ve built, and highlights how each artifact in this portfolio ties into my professional goals. I discuss real-world collaboration, stakeholder communication, system design trade-offs, secure development practices, and more.


## Code Review Video

[Milestone One Code Review](https://youtu.be/2PiVOO9qMG8)

This video introduces the original artifact and outlines my planned enhancements. It walks through the existing functionality of my full-stack app (Travlr Getaways), explains the architectural design choices, and identifies areas I targeted for improvement. All enhancements were strategically chosen to align with the five program outcomes.


## Milestone One Addendum

[Addendum (Word Document)](https://github.com/chetachiezikeuzor/CS-499-ePortfolio/blob/9cd9569b7c802d1e6204ada97ceafaa77ee12895/CS%20499%20-%20Milestone%20One%20Addendum%20-%20Chetachi.docx)

This document summarizes the original functionality of the project and explains the rationale behind each enhancement across the three focus areas.


## Artifact Enhancements

### Enhancement 1: Software Engineering and Design

[Milestone Two Narrative](https://github.com/chetachiezikeuzor/CS-499-ePortfolio/blob/9cd9569b7c802d1e6204ada97ceafaa77ee12895/CS%20499%20-%20Milestone%20Two%20Narrative%20-%20Chetachi.docx)
I restructured the backend API for clarity and maintainability. This included breaking down monolithic route files into modular components, adding reusable middleware, and integrating a centralized Winston logger. These changes reflect my understanding of clean architecture and separation of concerns.


### Enhancement 2: Algorithms and Data Structures

[Milestone Three Narrative](https://github.com/chetachiezikeuzor/CS-499-ePortfolio/blob/9cd9569b7c802d1e6204ada97ceafaa77ee12895/CS%20499%20-%20Milestone%20Three%20Narrative%20-%20Chetachi.docx)
Here, I tackled trip sorting logic, implemented helper utilities for time formatting and calculation, and improved data retrieval algorithms using better control structures. I also replaced repetitive logic with reusable functions, demonstrating algorithmic thinking and data manipulation proficiency.


### Enhancement 3: Databases

[Milestone Four Narrative](https://github.com/chetachiezikeuzor/CS-499-ePortfolio/blob/9cd9569b7c802d1e6204ada97ceafaa77ee12895/CS%20499%20-%20Milestone%20Four%20Narrative%20-%20Chetachi.docx)
This enhancement focused on integrating secure user authentication using JWT, updating Mongoose schemas, and restructuring protected endpoints. I also addressed index creation and used more efficient query structures for trip retrieval. These updates demonstrate deeper database design knowledge and security awareness.


## Artifact Overview: Travlr Getaways

The artifact used across all three enhancements is **Travlr Getaways**, a full-stack web app built with:

- **Frontend**: Angular  
- **Backend**: Node.js with Express  
- **Database**: MongoDB using Mongoose  
- **Authentication**: JSON Web Tokens (JWT)  
- **View Engine**: Handlebars  
- **Tools**: Winston Logger, Bootstrap


## Artifact Files

- **[Original Project](https://github.com/chetachiezikeuzor/travlr/tree/module7)** (before enhancements): [travlr_original.zip](travlr_original.zip) 
- **[After Enhancement 1: Software Design & Engineering](https://github.com/chetachiezikeuzor/travlr/tree/enhancement1)**: [travlr_enhanced.zip](travlr_enhanced.zip) 
- **[After Enhancement 2: Algorithms & Data Structures](https://github.com/chetachiezikeuzor/travlr/tree/enhancement2)**: [travlr_enhanced2.zip](travlr_enhanced2.zip)
- **[Final Version](https://github.com/chetachiezikeuzor/travlr/tree/enhancement3)** (all 3 Enhancements): [travlr_enhanced3.zip](travlr_enhanced3.zip) 



## Repository Structure

```plaintext
travlr_enhanced3/
├── app_admin/        # Angular frontend
├── app_api/          # Express API + MongoDB models/controllers
├── app_server/       # Server-rendered views using Handlebars
├── public/           # Static assets
├── data/             # Local data sources
├── index.js          # Main Express entry point
└── README.md         # This file
```

