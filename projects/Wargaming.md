---
layout: project
type: project
image: img/IMG_3549.jpeg
title: "Video Game Development: CompSci-SpeedRun"
date: 2025
published: true
labels:
  - Algorithms 
  - technical
summary: "Game Development for a minigame based video game with different levels based on the year you are currently in university."
---

<img width="200px" class="rounded float-start pe-4" src="../img/classroom.jpg">

---

# CompSci: Speedrun – A Game About Surviving Your CS Degree

Building a video game from scratch has been one of the most challenging (and surprisingly fun) things I’ve done as a computer science student. My current project is called **CompSci: Speedrun**, and it’s a Unity-based visual novel meets simulation-style game that takes players through the journey of earning a computer science degree — one semester at a time.

You play as a first-year CS student just starting your major. The idea is to simulate the experience of being a CS undergrad: the stress, the late-night coding sessions, the professors who can make or break your semester, and of course, the peers who are either helpful... or way too competitive. There’s a bit of narrative storytelling, dialogue-based choices, and some fun mini-games mixed in to break up the story and keep players engaged.

---

## The Goal and Gameplay

The game is structured like a level-based visual novel. Each level represents a semester in college. You make dialogue choices that impact your GPA, social life, and confidence. Along the way, mini-games simulate things like debugging code under pressure, or getting through a group project with flaky teammates (yes, it's as relatable as it sounds).

At its core, **CompSci: Speedrun** is meant to feel like a fast-paced but emotionally grounded look at what it's like to survive — and hopefully thrive — in a CS program. It’s exaggerated for fun, but rooted in real experiences.

---

## Code Behind the Scenes

A lot of the work so far has gone into building a working dialogue system and setting up the intro scene. Here's an example of how the game kicks off using Unity and C#. When the game starts, the main character (you, the player) is dropped into your very first class, with some internal thoughts and narrative setup:

```csharp
using UnityEngine; 
using System.Collections.Generic;

public class StartGame : MonoBehaviour {
    public DialogueManager dialogueManager;

    void Start() {
        Dialogue intro = new Dialogue {
            name = "Player",
            sentences = new List<string> {
                "Wow, this is it. My first class as a CS major... I hope I'm ready.",
                "Who’s that guy over there?"
            }
        };

        dialogueManager.StartDialogue(intro);
    }
}

## What’s happening here is pretty straightforward

The StartGame script sets up the intro dialogue when the level loads. The player character has a short inner monologue, setting the tone of nervous excitement. The DialogueManager handles displaying the lines on screen and advancing the conversation — a key part of the storytelling system.

## Why I’m Building It
As someone who’s currently going through this experience, I wanted to capture what makes studying CS so weirdly unique. It’s not just about learning how to code — it’s about figuring out how to learn, how to stay motivated, and how to balance everything else life throws at you. Making this game is my way of reflecting on all of that while building something creative and technically challenging at the same time.

I’m using Unity for this project because I wanted a tool that gave me control over 2D storytelling and UI while also being flexible enough to support the logic behind dialogue trees, choices, and branching paths. Most of my coding is in C#, which fits nicely with Unity’s structure.

## Next Steps

So far, I’ve implemented the dialogue system and the semester one level. Next, I’ll be adding branching dialogue choices, GPA logic, and a simple minigame that simulates finishing a CS assignment before the deadline (think: a frantic debugging puzzle). Each level will introduce new characters, new challenges, and new emotional beats as the player progresses through sophomore, junior, and senior years.

## Final Thoughts
CompSci: Speedrun is more than just a portfolio project for me — it’s a way of turning my journey as a CS student into something interactive and meaningful. Whether you’re a current student, a grad, or just curious about what it’s like to go through a tech degree, I hope the game feels both relatable and entertaining.


