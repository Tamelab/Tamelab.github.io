---
layout: essay
type: essay
title: "Building Software That Lasts: Lessons Beyond the Code"
# All dates must be YYYY-MM-DD format!
date: 2026-05-08
published: true
labels:
  - Reflection
  - Software Engineering
  - Essays
---

<img width="450px" class="rounded float-start pe-4" src="../img/difficulty/AI.jpeg">

## Discovering the Bigger Picture

When I first started ICS 314, I thought software engineering was mostly about learning how to build web applications. I expected to work with React, Next.js, Bootstrap, forms, pages, and maybe some databases. I did learn those things, but by the end of the course I realized that web development was only one part of the class. The bigger lesson was learning how to build software in a way that is organized, maintainable, and understandable, especially when working with a team.

This became clear during our final project, Bow-lletins, where our group built a campus bulletin board application for UH Mānoa students. The project included pages for flyers, categories, saved posts, user dashboards, authentication, database storage, and deployment. At first, I thought the hardest part would be writing the code. But the real challenge was keeping the project organized, making sure everyone’s work fit together, and building features that could be changed later without breaking the rest of the app.

Three software engineering topics that stood out to me the most were configuration management, Agile project management, and design patterns. These concepts are not only useful for web applications. They can apply to almost any project where people need to build, organize, improve, or maintain something over time.

## Configuration Management

Configuration management is the process of tracking and controlling changes in a project. In this class, this mostly meant using Git and GitHub to manage our code. Before ICS 314, I understood Git in a simple way. I knew how to push code to GitHub, but I did not fully understand why branches, commits, pull requests, and merges mattered so much.

During Bow-lletins, configuration management became much more important. Each teammate worked on different parts of the app, such as the navbar, dashboard, flyer cards, profile page, database schema, and Explore page. If everyone edited the same files without a system, the project would have become messy very quickly. Branches helped us work separately without immediately changing the main version of the project. Pull requests and merges helped us combine our work more carefully.

I also learned that configuration management is not only about code. It also includes managing environment variables, deployment settings, database changes, and project versions. For example, when our Vercel deployment failed because the database schema did not match the Prisma model, it showed me how important it is to keep the code, database, and deployment environment in sync. A small mismatch, like a missing database column, can break the whole application.

This lesson goes beyond web development. Any project that changes over time needs some form of configuration management. A research team might need to track versions of data files. A game development team might need to manage scripts, art assets, and sound files. Even a writing or design project could benefit from tracking versions so people know what changed and when. Configuration management prevents confusion and protects the project from accidental mistakes.

## Agile Project Management

Agile project management is a way of organizing work into smaller tasks that can be completed, reviewed, and improved over time. Instead of trying to plan every detail at the beginning, Agile focuses on steady progress and adjustment. In ICS 314, we practiced this through Issue Driven Project Management, also called IDPM.

Issue Driven Project Management means breaking the project into specific issues. Each issue describes a task, bug, improvement, or feature. For Bow-lletins, this helped us organize work for different milestones. Instead of saying, “make the app better,” we created smaller tasks like improving the dashboard layout, fixing the navbar, adding flyer categories, updating the Explore page, creating profile settings, or fixing deployment errors. This made the project feel less overwhelming.

At first, I thought creating issues and updating the project board was just extra work. But later, I understood why it mattered. Issues made it clear who was responsible for what. They also helped us show progress during milestones. When a task was finished and closed, it gave the team a record of what had been completed. This was especially helpful because a final project can easily become confusing when everyone is working on different features at the same time.

I can see myself using Issue Driven Project Management outside of web applications. For example, if I were planning an event, I could create issues for booking a room, making flyers, contacting speakers, ordering food, and setting up equipment. If I were working on a game, I could create issues for character design, music, level layout, dialogue, bug fixes, and testing. The main idea is the same: break a large goal into smaller pieces so the team can make steady progress.

Agile project management taught me that software engineering is not only about technical skill. It is also about communication, planning, and teamwork. A good idea can fail if the team is not organized enough to build it.

## Design Patterns

Design patterns are common solutions to common software design problems. They are not finished pieces of code that you copy and paste. Instead, they are ways of organizing code so that a system is easier to understand, reuse, and maintain. Before this class, I usually thought about code in terms of whether it worked or did not work. After learning about design patterns, I started thinking more about whether the code was organized well.

One design idea that stood out to me was separation of concerns. This means different parts of a program should have different responsibilities. In Bow-lletins, this showed up in many ways. The database schema handled how data was stored. React components handled how information appeared on the page. Server actions handled changes like saving a flyer, editing a flyer, or updating user information. CSS handled the visual design, like the corkboard style, sticky notes, buttons, and dashboard layout.

This separation made the project easier to work on. For example, if I wanted to change how a flyer card looked, I could focus on the component and CSS without rewriting the database. If we needed to adjust how flyers were saved or filtered, we could look at the server action or Prisma query instead of changing every page. This made the project more maintainable.

Design patterns matter beyond web development because almost every software system grows more complicated over time. A game, mobile app, data analysis tool, or robotics project can all become hard to manage if everything is mixed together. Patterns help developers build systems that future people can understand. They also help teams work together because the structure of the project is clearer.

## What These Lessons Mean Beyond Web Apps

The biggest thing I learned in ICS 314 is that software engineering is about building software that can survive change. A class exercise can be small enough that messy code still works, but a real project needs structure. Bow-lletins showed me how fast a project can grow once it includes users, pages, data, authentication, styling, testing, and deployment.

Configuration management helps protect the project as it changes. Agile project management helps people stay organized while building it. Design patterns help the code stay understandable after new features are added. These ideas are useful in web development, but they are not limited to it.

I can imagine using these lessons in many future projects. If I build another game, I would use Git branches to separate features, issues to track tasks, and design patterns to organize scenes, characters, and game logic. If I work on a research project, I would use version control to track files and changes. If I work with a team in a job, I will already understand why communication, structure, and planning are just as important as writing code.

## Looking Ahead

Looking back, ICS 314 taught me more than how to build a web application. It taught me how to think like a software engineer. I learned that good software is not only about making something work once. It is about making something that can be tested, changed, shared, deployed, and maintained.

The tools from this class may change over time. Next.js, Prisma, Bootstrap, Vercel, and other technologies will continue to update. But the bigger concepts will still matter. Configuration management, Agile project management, and design patterns are skills I can carry into future classes, personal projects, internships, and real software teams.

By the end of the course, I realized that software engineering is not just about the code on the screen. It is about the process behind the code. It is about how people work together, how changes are managed, and how systems are designed to last. That is the lesson from ICS 314 that I think will stay with me the most.
