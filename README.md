Original App Design Project - README Template
===

# Lang

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview

### Description
Welcome to Lang, a competitive team-based learning app. Teams are tasked with identifying images in their target languages to score more points than the opposing team in a fast paced learning environment. 

### App Evaluation
- **Category:** Education
- **Mobile:** 
    - **Real-time**: Gameplay is real-time with and against other players, giving a sense of social pressure.
- **Story:**
    - It is difficult to learn axiomatic vocabulary (e.g. cat or door) without memorizing. There are flashcards, Anki, and other platforms to learn this vocabulary, but these are lonely experiences. Lang provides a gamified and sociable platform for vocabulary learning at your target language.
    - Anyone who has learned or attempted to learn a language knows that vocabulary is vast. They will complain that it is boring or even forgetful. 
- **Market:**
    - The user base of Lang is targeted to language learners. Language learners would find the Lang to be a fun language learning alternative.
- **Habit:**
    - The gamifying and social factor of language learning is the most gravitating aspect of the app. Lang may have a ranking system to keep language learners motivated.
    - The average user mainly consumes the app rather than creating.
- **Scope:**
    - The main challenge are the networking and UI aspects.
    - How do I implement match placement? How do I allow users to create rooms for others to join? How do I make sure the UI looks clean and polished?
    - The core of the app is to learn language collaboratively. It does not necessary have to be a battle against other teams; it could be some type of leaderboard. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Login
* Logout
* Sign Up
* Database Synch
* Main Menu
* Team Match Making
* Core Gameplay - Type Words In, Highlight Image, Recieve Points
* Post Gameplay - Leaderboard

**Optional Nice-to-have Stories**

* Upload a profile picture
* Create your own match for people you know to join.
* Voice Input Support
* Match history
* Search for profiles
* View profile details
* Additional Language Support

### 2. Screen Archetypes

* Login / Regiter
   * Login
   * Logout
   * Sign Up
* Stream
   * Main Menu
   * Team Match Making
* Creation
    * Core Gameplay - Type Words In, Highlight Image, Recieve Points
* Other
    * Database Synch
    * Post Gameplay - Leaderboard

### 3. Navigation

**Flow Navigation** (Screen to Screen)

* Login
  -> Main Menu
* Logout 
  -> Login
* Sign Up
  -> Main Menu
* Main Menu
  -> Logout
  -> Team Match Making
* Team Match Making
  -> Core Gameplay
* Core Gameplay
  -> Post Gameplay
* Post Gameplay 
  -> Team Match Making
  -> Main Menu
  -> Logout

## Wireframes

<img src="https://github.com/darrylkid/Lang/blob/main/thumbnail_Lang%20P1.png"/>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
