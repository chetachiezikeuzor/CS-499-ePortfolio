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

[Self-Assessment (Word Document)](https://github.com/chetachiezikeuzor/CS-499-ePortfolio/blob/d6f2ec5103bad2b4cd8c7e79fc96e538d8094945/CS%20499%20-%20Professional%20Self%20Assessment%20-%20Chetachi.docx)

<details>
<summary>Click to expand full self-assessment</summary>

As I look back on my journey through the Computer Science program at Southern New Hampshire University, I see more than just a collection of assignments and code—I see growth. I see a clearer sense of direction, a stronger technical foundation, and the shaping of values that now define how I approach problems as a developer. Completing this program and building this portfolio have been a huge part of that. It gave me the chance to revisit older work with new eyes and level up those artifacts in ways that reflect the skills I’ve gained along the way.

This program helped me build a solid understanding of the core areas of computer science, but it also made me more intentional about how I approach my career. I’ve always been curious, and this major gave me the space to explore different topics—everything from software engineering to cybersecurity to mobile development. More importantly, it helped me figure out where I thrive. I realized I’m drawn to work that combines clean architecture, thoughtful design decisions, and clear user experiences. That discovery didn’t happen all at once. It evolved as I tackled projects, received feedback, and pushed myself through the tougher parts of the curriculum.

One of the most valuable aspects of the program was learning how to collaborate effectively. I’ve worked in team settings before, but courses like CS 250 (Software Development Lifecycle) and CS 405 (Secure Coding) taught me how to contribute meaningfully in technical environments. I learned how to ask better questions, give actionable feedback, and adapt my communication depending on who I was talking to—whether it was a peer, stakeholder, or project lead. I’ve carried that forward into my professional experiences at T-Mobile and Verizon, where I supported teams with automation and application monitoring tasks. Sometimes, that meant shifting between technical operations and broader communication with non-technical teammates, which challenged me to be more flexible in how I explain and justify my work.

When it comes to communication, I’ve grown a lot. Early in the program, I focused mostly on whether my code worked. Now, I put just as much effort into clarity and documentation. Through assignments like the code review video and narrative writing, I’ve learned how to explain the why behind my work, not just the what. That skill has proven incredibly valuable, especially when justifying design trade-offs, walking others through architecture, or presenting enhancements that improve scalability or security.

In terms of technical growth, this capstone is where everything started to click. For the software engineering enhancement, I applied clean architecture principles to reorganize the backend of my full-stack app, breaking up monolithic logic into modular routes and middleware. That was a direct result of what I learned in CS 320 (Software Testing and QA) and CS 340 (Software Engineering). For the algorithms enhancement, I refined backend utilities by writing more efficient data sorting and filtering logic. I leaned on skills from CS 260 (Data Structures and Algorithms) and practiced making trade-offs between readability and performance. And for the database enhancement, I implemented JWT authentication and optimized MongoDB queries—an area I explored further in CS 405 and CS 350 (Computer Architecture and Operating Systems), where I started thinking more critically about data flow and security from the ground up.

Security is something I’ve developed a much stronger mindset around. Earlier in the program, I saw it as something separate, something you “add on” after building the main functionality. But through courses like CS 405 and the security-focused work I did during this capstone, I realized that security starts at the architecture level. Thinking about data validation, access control, and user authentication as part of the initial design process has made my applications more resilient and user aware. Even when using third-party libraries or frameworks, I now approach them more critically, asking: How does this handle user data? What vulnerabilities does this open?

This capstone project ties all those lessons together. I chose to enhance a full-stack travel planning app that I originally built in a previous course. Each enhancement—software design, algorithms, and databases—builds on the last. Together, they demonstrate not just a wider range of technical skills, but also a more mature perspective on how to maintain and scale an application over time. My goal with this portfolio wasn’t just to check boxes. I wanted to produce work I’d be proud to show to a hiring manager, recruiter, or engineering peer.

Ultimately, this program helped me bridge the gap between learning and doing. It taught me to think like a developer, not just a student. And while there’s still so much I want to learn and explore (especially in full-stack development and cloud infrastructure), I feel more confident stepping into roles that require not just technical ability, but also thoughtful communication, collaboration, and decision-making. My ePortfolio is the best reflection of that growth.

</details>

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
