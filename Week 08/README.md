# Functional User Requirements and User Stories

## Introduction

To develop useful apps, developers must understand user needs. However, software is often created by people who are not the exact target end-users, which makes structured requirement methods essential. While developers tend to focus on user interface (UI) and user experience (UX), it is equally important to consider how an app works from a technical computer science standpoint.

## User Stories

A **user story** is a short statement written from the user’s perspective, typically beginning with:

> "As a user, I can..."
> 
> or
> 
> "As a user, I want..."

User stories help developers empathize with users, clarify expectations, and improve team communication. They are written in natural language and focus on user-facing behavior rather than technical detail.

However, user stories are rarely technical and may overlook important aspects such as performance, security, or other non-functional requirements.

## Functional User Requirements

To address these limitations, user stories are translated into **functional user requirements**.

Functional requirements provide clear technical specifications of software features, usually described in terms of **input and output**. Similar to a function in programming, they define:

- **Input** – Data provided by the user or system  
- **Output** – The resulting system behavior or response  

This creates a stronger technical foundation for development.

## Technical Design Document (TDD)

In many projects, functional requirements are organized within a **Technical Design Document (TDD)**.

A TDD typically includes:

- Software architecture  
- Technologies to be used  
- Feature implementation details  
- Testing plans  
- Performance criteria  

The TDD serves as a guiding document in the early stages of development. Once implementation begins, the working code or Minimum Viable Product (MVP) often becomes the primary source of truth.

## Conclusion

User stories help identify user needs.  
Functional requirements translate those needs into technical specifications.  
Technical design documents organize the architecture and implementation plan.

Together, these tools ensure that an application is both user-centered and technically well-structured.

# Research & Reflection: Processing Programming Language

## 1. What is the language used for?

Processing is a creative coding language and development environment that works like a **software sketchbook**. It is mainly used to learn programming through visual output. 

It is commonly used for:
- Creating digital art and generative visuals  
- Making animations and interactive graphics  
- Building simple games  
- Data visualization  
- Prototyping interactive media projects  

Processing allows users to see immediate visual results, which makes it especially helpful for creative experimentation and learning.

## 2. Who uses the language?

Processing is used by:
- Visual designers  
- Digital artists  
- Creative coders  
- Students and educators  
- Architects and media creators  

It is popular among artists and designers who want to generate visuals for exhibitions, music videos, films, and interactive installations. It is also widely used in classrooms to teach programming in a more visual and engaging way.

## 3. What are some useful resources?

Some useful resources for learning Processing include:

- Processing.org (Official Website)
- Processing Reference Documentation
- Getting Started Tutorials on Processing.org
- The Coding Train (YouTube Channel)
- OpenProcessing (Community Sketch Sharing Platform)
- Processing Community Forum
- Processing (Second Edition) – MIT Press Book

## 4. Why are these specific resources useful?

The official website and documentation are useful because they provide accurate explanations of syntax, built-in functions, and installation instructions.

The Processing Reference is helpful for understanding commands related to shapes, color, animation, and interaction.

The Getting Started tutorials provide step-by-step beginner guidance.

The Coding Train YouTube channel explains concepts visually and practically, making it easier to understand creative coding.

OpenProcessing allows users to explore real projects and learn from community examples.

The Processing Community Forum helps users solve errors and learn from other developers’ experiences.

The MIT Press book provides structured and in-depth learning for serious study.

# Mattermost Response

Processing is often used beyond screen-based graphics, particularly in interactive installations and physical computing projects when combined with tools like Arduino. Because Processing can communicate through serial connections, artists and developers use it to visualize real-time sensor data (such as motion, light, or sound input) and transform that data into dynamic visual feedback.

This capability makes Processing popular in media art exhibitions and experimental design labs, where interactive systems are central to the creative experience. The official Processing website (processing.org) provides example sketches and documentation that demonstrate how to manage serial communication and perform live rendering within the `draw()` loop. These resources are especially valuable for rapid experimentation and prototyping of interactive systems.

# User Story Activity

App Chosen: K’ómoks Community Connect (MIT App Inventor Project)
Feature: Cultural Information & Quiz Section

## General User Story

As a user, I can learn about K’ómoks First Nation culture through the app.

## More Specific User Stories

As a user, I can open the Culture screen from the home page.

As a user, I can read information about traditions, history, and community values.

As a user, I can scroll through content clearly without confusion.

As a user, I can take a quiz to test my understanding of the cultural information.

As a user, I can see my quiz results immediately after submission.

As a user, I can retake the quiz to improve my score.

## Different Contexts / Motivations

As a newcomer to the Comox Valley, I want to learn about the K’ómoks Nation so I can better understand the local community.

As a student at NIC, I want to use the quiz feature to reinforce my learning.

As a visitor, I want quick and clear information without reading long academic text.

## Acceptance Criteria (Checklist)

- The Home screen clearly displays a button for the Culture section.
- The Culture screen loads without errors.
- Text is readable and properly formatted.
- Users can scroll smoothly through content.
- The Quiz button is visible and functional.
- Quiz questions display one at a time clearly.
- The app calculates and displays the score correctly.
- Users can retake the quiz without restarting the app.
- The app stores quiz results (if TinyDB is used).

# Follow-Up Questions and Reflections

## 1. What is one interesting thing that you’ve learned from researching about programming languages and from reading other students’ posts?

One interesting thing I learned is that programming languages are designed with very different goals and audiences in mind. For example, Processing focuses on creativity and visual output, making it ideal for artists and designers, while other languages like Haskell focus more on mathematical logic and functional programming concepts. This helped me understand that programming languages are not just technical tools — they reflect different philosophies and purposes. Reading other students’ posts also showed me how each language solves problems differently depending on what it is designed for.

## 2. What other programming languages might you consider working with for DGL 104? What are your second choices, and why?

Besides Processing, I would consider working with Lua as a second choice because it is lightweight and often used in game development and scripting. It would be useful for interactive projects.

Another language I would consider is JavaScript because it is widely used in web development and interactive design. Since DGL 104 involves digital and interactive work, JavaScript would be very practical for building websites and user interfaces.