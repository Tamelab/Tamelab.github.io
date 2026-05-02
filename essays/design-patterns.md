---
layout: essay
type: essay
title: "Design Patterns"
date: 2026-04-24
published: true
labels:
  - Programming
  - Software Design
  - Next.js
  - Reflection
---


<img width="200px" class="rounded float-start pe-4" src="../img/IMG_3554.jpeg">


# Design Patterns: The Blueprint Behind Bow-lletins

Imagine trying to build something like my final project, *Bow-lletins*, without any structure. At first, it feels manageable. You can throw together pages, connect a database, and get things working. But once features start stacking—user login, posting flyers, saving events, filtering categories—it quickly turns into a mess. Things break in unexpected places, code gets duplicated, and even small changes become stressful.

That’s when I started realizing that writing code isn’t just about making something work—it’s about designing something that *keeps working*. That’s where design patterns came in for me. They’re not strict rules or copy-paste solutions, but more like proven strategies that developers use to solve problems that show up again and again. Kind of like how buildings follow certain structural principles so they don’t collapse, software uses design patterns so it stays stable as it grows.

## Patterns I Didn’t Know I Was Using (At First)

Before I even knew the term “design patterns,” I was already using them. For example, when building authentication in Bow-lletins using NextAuth.js, I naturally structured things so that one central system handled login sessions. Later I realized this follows the idea behind a **Singleton** pattern—making sure there’s only one source of truth managing authentication state.

In my own code, I’ve also used a Singleton-like approach for database access through Prisma. Instead of creating multiple database connections everywhere, I keep one shared instance that everything uses. This prevents conflicts and keeps things efficient.

```ts
import { PrismaClient } from '@prisma/client';

const prisma = global.prisma || new PrismaClient();

if (process.env.NODE_ENV !== 'production') global.prisma = prisma;

export default prisma;
```

At the time, I just thought I was “avoiding bugs,” but in reality, I was applying a well-known pattern.

## Real-Time Features and the Observer Mindset

Another pattern that showed up in my project is something close to the **Observer pattern**. Bow-lletins has features like saving flyers, reacting, or updating posts. When a user interacts with something, different parts of the app need to reflect that change—like updating counts or UI elements.

Instead of constantly refreshing everything, I structured components so they react to changes in state. In React (especially with Next.js), this happens naturally: when data changes, components re-render. That behavior is basically the Observer pattern in action—objects automatically update when the data they depend on changes.

This made the app feel smoother and more interactive without me having to manually sync everything.

## Separating Responsibilities Without Realizing It

One of the biggest improvements in my project came from separating logic into different layers. For example, in Bow-lletins:

- UI components handle display  
- API routes handle requests  
- Database logic is handled through Prisma  

This structure follows ideas from patterns like MVC (Model-View-Controller), even though I didn’t strictly label it that way. The important part is that each piece has a clear role. When something breaks, I know where to look. When I want to add a feature, I don’t have to rewrite everything.

## Why This Actually Matters (Not Just Interview Talk)

Before this class, I thought design patterns were just something interviewers asked about to sound smart. But working on a real project changed that. Without patterns, my code started to feel fragile. With them, everything became more predictable.

Design patterns helped me:

- Avoid repeating the same logic everywhere  
- Keep my code organized as the app grew  
- Make it easier to debug and add features  
- Understand other people’s code faster  

And honestly, the biggest difference is confidence. I’m not just guessing anymore when I structure my code—I have a reason behind it.

## Looking Back at Bow-lletins

By the end of building Bow-lletins, I realized I wasn’t just coding features. I was applying patterns the whole time:

- **Singleton** → managing database and authentication instances  
- **Observer** → UI reacting to state changes in React  
- **Separation of concerns (MVC-like thinking)** → organizing frontend, backend, and database logic  

So if someone asked me now, “What are design patterns?” I wouldn’t just give a textbook definition. I’d say they’re the reason my project didn’t fall apart halfway through development. And if they asked what patterns I’ve used, I could point directly to parts of my own app—not just theory.

That’s what makes them stick.

## AI Use Acknowledgment

I used ChatGPT to help refine the structure, clarity, and wording of this essay. The ideas, examples, and project references are based on my own experience building Bow-lletins.

