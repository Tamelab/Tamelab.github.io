---
layout: essay
type: essay
title: "Reflecting on My Use of AI in ICS 314"
# All dates must be YYYY-MM-DD format!
date: 2026-05-08
published: true
labels:
  - AI
  - Software Engineering
  - Essays
---

# Reflecting on My Use of AI in ICS 314

## I. Introduction

AI has become a normal part of education, especially in classes that involve software engineering. In the past, students had to search through documentation, Stack Overflow posts, class notes, or examples from old assignments to figure out how to solve coding problems. Now, tools like ChatGPT, GitHub Copilot, and Google Gemini can explain concepts, help debug errors, give examples, and help organize ideas much faster. In software engineering, this matters because the field is not only about writing code. It is also about planning, testing, teamwork, documentation, deployment, and understanding how different pieces of a project fit together.

In ICS 314, AI was useful because the course included many different software engineering skills. We worked with JavaScript, TypeScript, React, Next.js, Bootstrap, GitHub, GitHub Projects, Vercel, Prisma, PostgreSQL, Playwright, ESLint, and team project management. I used ChatGPT the most during the semester. I also tried GitHub Copilot, but I did not depend on it as much because sometimes it suggested code that did not match my project structure. I used AI mostly as a helper for explanations, debugging, brainstorming, and checking my work. I did not use it to replace my own learning because many ICS 314 assignments require understanding the code well enough to explain it, fix it, and connect it to the rest of the project.

Overall, AI helped me get unstuck faster, but it also showed me that I still needed to think carefully. AI can give confident answers that are not always correct. Because of that, I learned to treat AI as a support tool, not as the final answer.

## II. Personal Experience with AI

### 1. Experience WODs

For Experience WODs, I used AI mostly when I needed help understanding the goal of the assignment or when I was stuck on syntax. For example, during earlier JavaScript and Underscore practice, I asked ChatGPT, “Give me an example of using Underscore to filter and map an array of objects.” This helped me understand how functions like `_.filter`, `_.map`, and `_.pluck` worked in a simple example before applying them to the actual WOD.

The benefit was that AI made the code easier to understand because it used simple variable names and explained each step. The cost was that the examples were sometimes too generic. They did not always match the exact WOD instructions, so I still had to adjust the logic myself. This helped me learn that AI is useful for starting, but not for blindly copying.

### 2. In class Practice WODs

For in class Practice WODs, I usually did not use AI directly while completing them. I wanted to practice under conditions that were closer to the real WOD environment. Since Practice WODs were meant to help me build speed and confidence, using AI too much would have made it harder to know if I actually understood the material.

However, after finishing a Practice WOD, I sometimes used ChatGPT to review what I did wrong. A prompt I used was, “Explain why this React component is not rendering correctly,” followed by the code. This was helpful because AI could point out small mistakes like a missing return statement, incorrect import, or wrong prop name. The benefit was faster feedback. The cost was that sometimes AI guessed the issue without fully understanding the project setup.

### 3. In class WODs

For actual in class WODs, I did not use AI. I felt that the purpose of those WODs was to test my own understanding and ability to work under time pressure. Even if AI could help, switching tabs and trying to explain the whole problem to ChatGPT would have slowed me down.

Not using AI for in class WODs was useful because it showed me what I actually knew. It also helped me see which topics I needed to review later, such as React state, Bootstrap layout, or form handling.

### 4. Essays

For essays, I used AI as a brainstorming and organization tool. For example, when writing essays about software engineering topics, I asked ChatGPT prompts like, “Help me organize an essay about how software engineering design patterns apply to a class project,” or “Explain Agile project management in simple college student language.”

AI was helpful for getting ideas flowing and making sure I covered the required points. However, I had to rewrite a lot of the wording so it sounded like me. Sometimes AI made the writing sound too formal or too perfect, which did not match my style. The benefit was that it helped me start. The cost was that I had to spend time editing so the essay sounded natural and personal.

### 5. Final Project

AI was very helpful during the final project because our Bow-lletins project had many moving parts. Bow-lletins was a Next.js application for UH Mānoa students to find flyers for jobs, internships, clubs, study groups, events, and other campus opportunities. The project used React, TypeScript, Bootstrap, Prisma, PostgreSQL, NextAuth, and Vercel.

For the final project, I used prompts like, “Why is my Prisma schema causing a P2022 column does not exist error?” and “Help me fix this Next.js build error without changing unrelated code.” AI helped me understand errors related to Prisma migrations, missing database columns, Vercel environment variables, and component import problems.

The biggest benefit was that AI helped me troubleshoot faster. For example, when Vercel showed an error about a missing `rsvpBy` column, AI helped explain that the code expected a field that was not actually in the deployed database yet. The cost was that AI did not know my full project unless I pasted the exact files, so it sometimes suggested general fixes that did not match my setup. I still had to test everything myself.

### 6. Learning a Concept or Tutorial

AI was useful when learning new concepts from tutorials. For example, when learning about Next.js App Router, I asked, “Explain the difference between a server component and a client component in Next.js in simple terms.” This helped me understand why some pages could fetch data directly from the database, while interactive components needed `"use client"`.

I also used AI to understand Prisma better. A prompt I used was, “Explain how Prisma connects a Next.js app to a PostgreSQL database like I am new to databases.” This was helpful because databases were confusing at first. AI helped explain models, tables, fields, migrations, seeds, and how the app reads and writes data.

The benefit was that AI explained concepts in a way that was easier to understand than documentation alone. The cost was that I still had to compare the explanation to the actual ICS 314 template and project code because small version differences matter.

### 7. Answering a Question in Class or in Discord

When answering questions in Discord, I sometimes used AI to double check myself before responding. For example, if someone had a question about a Git command or a React error, I might ask ChatGPT, “Is this explanation of merging main into a branch correct?” This helped me avoid giving someone bad advice.

The benefit was that AI gave me more confidence before answering. The cost was that I had to be careful because AI can sound correct even when it misses context. I learned that if I was not sure, it was better to say what I thought and explain that they should also check the documentation or ask the professor.

### 8. Asking or Answering a Smart Question

AI helped me make my smart questions clearer. Sometimes when I had a bug, my first explanation was too long and included too much background information. I used prompts like, “Rewrite this as a clear smart question for Discord. Include what I tried, what I expected, and the error I got.”

This was useful because it helped me organize my question better. Instead of saying “my page is broken,” I could explain the actual problem, the file involved, the error message, and what I had already tried. The cost was that I had to make sure the final question still sounded like me and included the real details.

### 9. Coding Example

AI was useful for small coding examples. For example, I asked ChatGPT, “Give me a simple example of using `_.pluck` to get names from an array of objects.” This helped me understand the purpose of the function before using it in a WOD.

For the final project, I also used prompts like, “Give me an example of a Bootstrap card layout in React,” or “Show me a simple controlled search input in React.” These examples helped me start building UI pieces for pages like Explore, Dashboard, and Saved Flyers.

The benefit was that AI examples were quick and easy to understand. The cost was that examples were usually simplified and not ready to paste directly into my project.

### 10. Explaining Code

AI was one of the most helpful tools for explaining code. When I did not understand a function or component, I pasted the code and asked, “Explain this code line by line in simple terms.” This was especially useful for server actions, Prisma queries, and React components with props.

For example, in Bow-lletins, I used AI to understand how a server action could save or unsave a flyer by updating an array field in Prisma. AI helped explain how the current user email was checked, how the array was updated, and why `revalidatePath` was needed after changing data.

The benefit was that it made confusing code easier to understand. The cost was that AI sometimes over explained or focused on the wrong part, so I had to ask follow up questions.

### 11. Writing Code

I used AI to help write small pieces of code, but I did not fully trust it for large features. For example, I asked ChatGPT, “Write a simple React component that displays a flyer card with title, date, location, and category.” This helped me create a starting point for UI components.

For bigger features, like the Explore page filters or the Dashboard page, AI was helpful for planning the structure, but I still had to connect everything to my actual project. AI did not always know my file names, imports, CSS classes, or Prisma types. The benefit was that it helped me move faster. The cost was that copy and paste code could break the project if I did not check it carefully.

### 12. Documenting Code

AI helped with documentation for the final project and portfolio pages. For example, I used prompts like, “Write a short user guide section explaining how to save a flyer,” or “Help me describe this feature for a developer guide.”

This was helpful because documentation can take a lot of time, especially when trying to explain a project clearly. AI gave me a draft, but I had to edit it so it matched what the app actually did. The benefit was saving time. The cost was making sure the documentation was accurate and not too wordy.

### 13. Quality Assurance

AI was very helpful for quality assurance. I used it for ESLint errors, TypeScript errors, build errors, and logic checks. A common prompt was, “What is wrong with this code?” followed by the code and the error message.

For example, when working on Bow-lletins, I used AI to help understand errors like “Element type is invalid,” “MissingSecret,” and Prisma schema issues. AI helped explain possible causes, such as a bad import, missing environment variable, or database schema mismatch.

The benefit was that AI helped me narrow down the problem faster. The cost was that AI sometimes listed too many possible causes, and I still had to test which one was true. It worked best when I gave it the exact error message and the exact file.

### 14. Other Uses in ICS 314

Another way I used AI in ICS 314 was for project planning and UI ideas. For Bow-lletins, I asked for ideas to make the dashboard look better without making it too complicated. AI helped me think about sections like saved flyers, my flyers, stats, recent activity, and category cards.

I also used AI to help with Git and deployment questions. For example, I asked about merging main into a branch, checking differences between branches, and understanding Vercel redeploys. These were not always coding problems, but they were still part of software engineering because they involved teamwork, version control, and deployment.

The benefit was that AI helped me understand the workflow better. The cost was that I had to be very careful with Git commands because one wrong command could mess up my branch.

## III. Impact on Learning and Understanding

AI changed my learning experience in ICS 314 by helping me get unstuck faster. Instead of staring at an error for a long time, I could ask AI to explain what it meant. This was especially helpful with TypeScript, Prisma, and Next.js because the error messages were sometimes hard to understand.

At the same time, AI also challenged my learning. If I used it too early, I noticed that I did not remember the solution as well. The best approach for me was to try first, then use AI when I was stuck or needed an explanation. This made AI feel more like a tutor than a shortcut.

AI also helped me build problem solving skills because it showed me how to break errors into smaller parts. For example, with a Vercel build error, I learned to check the error message, identify the file, look at recent changes, check environment variables, and test locally. That process is more important than just getting the answer.

## IV. Practical Applications

Outside of ICS 314, I have used AI for other schoolwork, personal projects, and organizing ideas. For example, I have used AI to help format essays, explain lab calculations, organize study notes, and create simple scripts. These uses are practical because they save time and help me focus on understanding the main task.

In real world software engineering, AI could be useful for prototyping, debugging, writing documentation, and helping teams understand unfamiliar code. For a project like Bow-lletins, AI could help brainstorm features, generate test cases, explain database relationships, or suggest ways to improve user experience.

However, real world use also requires caution. AI does not know the full project context unless the developer provides it. It can also suggest insecure or outdated code. Because of that, AI should be used with testing, code review, and human judgment.

## V. Challenges and Opportunities

The biggest challenge I had with AI was accuracy. Sometimes AI gave an answer that sounded right but did not actually work. This happened most often with newer tools or specific project setups, such as Next.js, Prisma, NextAuth, and Vercel. Small version differences can change the correct answer.

Another challenge was that AI sometimes changed too much code. In a real project, this is risky because one feature can affect another. I learned to ask more specific prompts like, “Do not change anything else,” or “Only update this part of the component.” This made the answers more useful.

There are also many opportunities for AI in software engineering education. AI can help students understand errors, practice concepts, and learn from examples. It could also help students write better documentation and test cases. The key is teaching students how to use AI responsibly instead of pretending it does not exist.

## VI. Comparative Analysis

Traditional teaching methods are still important because they force students to build a real foundation. Reading documentation, watching lectures, doing WODs, and practicing manually help students understand the material deeply. Without that foundation, AI answers can be hard to judge.

AI enhanced learning is different because it gives instant feedback and personalized explanations. If I do not understand something, I can ask AI to explain it another way. That makes learning feel more flexible and less frustrating.

For me, the best learning happened when I combined both approaches. Traditional methods helped me build the skill, and AI helped me get unstuck or see another explanation. AI made the course more manageable, but it did not replace practice. In software engineering, practical skill development still comes from writing code, breaking it, fixing it, testing it, and explaining it.

## VII. Future Considerations

I think AI will continue to become a normal part of software engineering education. Future classes may include more assignments where students are expected to use AI, but also explain how they used it and whether the result was correct. This would be helpful because using AI well is becoming a real skill.

One important future consideration is academic honesty. Students need clear rules about what is allowed and what is not allowed. There is a difference between using AI to explain a concept and using AI to complete an assignment without understanding it.

Another consideration is verification. Students should learn how to check AI answers against documentation, tests, and actual project behavior. In software engineering, a response is not useful just because it sounds good. It has to work, follow the project requirements, and be maintainable.

## VIII. Conclusion

My experience with AI in ICS 314 was mostly positive, but it required balance. AI helped me brainstorm, debug, understand code, write documentation, improve smart questions, and work through final project issues. It was especially useful for Bow-lletins because the project involved many tools working together, including Next.js, React, Prisma, PostgreSQL, NextAuth, Bootstrap, GitHub, and Vercel.

At the same time, AI was not perfect. It sometimes gave wrong answers, suggested code that did not fit my project, or made things sound easier than they were. I learned that AI works best when I give it specific prompts, include the real error message, and still test the answer myself.

For future ICS 314 courses, I think AI should be encouraged as a learning support tool, not as a replacement for learning. Students should be taught how to write good prompts, check AI answers, and reflect on when AI helped or hurt their understanding. Used carefully, AI can make software engineering education more accessible, but students still need to build their own skills through practice, teamwork, and problem solving.
