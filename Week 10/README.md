# Research & Reflection Journal – MV* Architectural Patterns

## Overview

During this research, I explored the concept of **MV* architectural patterns**, which are commonly used in web and mobile application development. The term MV* represents a family of related patterns that organize the structure of an application. These include patterns such as **Model-View-Controller (MVC)**, **Model-View-ViewModel (MVVM)**, and **Model-View-Presenter (MVP)**.

Unlike design patterns such as Singleton or Observer, which solve specific programming problems, MV* patterns focus on the **overall architecture of an application**. They help developers organize code into clear layers, making applications easier to maintain, scale, and understand.

## Architectural Patterns vs Design Patterns

Through this research, I learned that there is an important distinction between **design patterns** and **architectural patterns**.

Design patterns are usually solutions to specific problems in object-oriented programming. Examples include Singleton, Factory, Strategy, and Observer patterns. These patterns focus on improving small pieces of code or solving specific technical challenges.

Architectural patterns such as MV* patterns, on the other hand, define the **overall structure of an entire software project**. They determine how different parts of the application communicate and how responsibilities are separated within the system.

This separation of responsibilities helps developers manage complex projects more effectively and ensures that different parts of the application remain organized.

## MVC (Model–View–Controller)

MVC is one of the earliest and most widely used MV* patterns. It divides an application into three main components:

- **Model** – Manages the application's data and business logic.
- **View** – Represents the user interface and displays data to the user.
- **Controller** – Handles user input and updates the model or view accordingly.

Frameworks such as **Ruby on Rails** commonly use the MVC architecture. By separating these responsibilities, MVC helps maintain clean code and improves maintainability in larger applications.

## MVVM (Model–View–ViewModel)

MVVM is another variation of the MV* architecture that is widely used in modern mobile development. It introduces the **ViewModel** component, which acts as a bridge between the Model and the View.

In MVVM:
- The **Model** manages the application data.
- The **View** displays the user interface.
- The **ViewModel** handles presentation logic and prepares data for the view.

Modern frameworks such as **SwiftUI for iOS** and **Jetpack Compose for Android** often use the MVVM pattern because it works well with reactive and declarative UI development.

## MVP (Model–View–Presenter)

The MVP architecture is another variation of the MV* approach. In this pattern:

- The **Model** handles data and business logic.
- The **View** displays the interface.
- The **Presenter** manages the communication between the model and the view.

The presenter contains most of the application logic and directly updates the view. This pattern is often used in environments where stronger separation between the user interface and business logic is required.

## Reflection

Through this research, I learned that MV* patterns are important for structuring complex applications. While design patterns help solve smaller programming problems, architectural patterns such as MVC, MVVM, and MVP define how the entire system is organized.

Understanding these architectural patterns helps developers build applications that are easier to maintain, test, and expand. I also learned that the choice of MV* pattern often depends on the development framework being used. For example, MVC is commonly used in traditional web frameworks, while MVVM is widely adopted in modern mobile development.

Overall, learning about MV* patterns helped me better understand how large applications are structured and how developers organize responsibilities between data, logic, and user interface components.

# Assessing External Community Contribution Guidelines

## Repository Reviewed
https://github.com/jump-dev/JuMP.jl

## Overview

For my external open-source community, I explored the **JuMP.jl** repository on GitHub. JuMP is an open-source mathematical optimization modeling language written in the **Julia programming language**. It is commonly used by researchers, engineers, and developers to model and solve optimization problems.

To understand how contributors participate in the project, I carefully reviewed the **README.md** file and other documentation related to contributing.

## Contributing Documentation

The JuMP repository provides several documents that help contributors understand the project and the contribution process. These include:

- **README.md** – Provides an overview of the project, installation instructions, and general information about the JuMP optimization framework.
- **CONTRIBUTING.md** – Explains how contributors can submit improvements or fixes to the project.
- **Code of Conduct** – Defines the expected behavior for community members to ensure respectful and inclusive collaboration.

These documents help create a structured environment for contributors and make it easier for new developers to understand how to participate.

## Contribution Process

Based on the documentation provided in the repository, the typical contribution process includes the following steps:

1. Identify an open issue or discuss a potential improvement.
2. Fork the repository to a personal GitHub account.
3. Clone the forked repository to a local development environment.
4. Create a new branch for the proposed changes.
5. Implement the changes or improvements.
6. Run the project’s tests to ensure that the changes work correctly.
7. Submit a **Pull Request** for review by the project maintainers.

Contributors are also encouraged to update documentation and tests when making changes to the codebase.

## Community Interaction

The JuMP project encourages contributors to interact with the community before making contributions. Questions, bug reports, and feature ideas can be discussed on the **JuMP Community Forum**. Developers may also communicate with maintainers through the project’s developer chat channels.

This type of communication helps contributors better understand the project and ensures that proposed changes align with the project’s goals.

## Reflection

From reviewing the JuMP repository and its contribution guidelines, I learned that open-source projects usually provide clear instructions that help contributors participate effectively. The JuMP project offers well-structured documentation, testing requirements, and communication channels that support collaboration between contributors and maintainers.

These guidelines help ensure that contributions follow the project’s standards and make it easier for new contributors to understand the development workflow.

## Planned Contribution

Based on the contribution guidelines provided by the JuMP project, I would begin by identifying an open issue that I could potentially work on. I would then fork the repository to my own GitHub account and clone the forked repository to my local machine.

After creating a new branch, I would implement the changes related to the selected issue. Before submitting any contribution, I would run the project’s tests to confirm that my changes do not introduce errors. Finally, I would document the work completed in my personal fork of the repository and prepare the changes in a pull request following the JuMP contribution guidelines.

## Mattermost Summary – Contributing to the JuMP.jl Community

For my external open-source community, I explored the JuMP.jl repository on GitHub and reviewed the README.md and contributing documentation. JuMP is an open-source mathematical optimization modeling language written in Julia.

From the documentation, I learned that contributors are encouraged to interact with the community before contributing. Users can discuss questions, bugs, and feature ideas on the JuMP Community Forum, and developers can communicate with maintainers through the developer chatroom.

The contribution process involves finding or discussing an issue, forking the repository, creating a new branch, making changes, running tests, and submitting a pull request. Contributors are also expected to follow the Code of Conduct and update tests or documentation when needed.

Overall, the JuMP project provides clear guidelines and helpful resources that make it easier for new contributors to understand how to participate in the community.

## External Community Contribution

As part of this project, I explored an external open-source community and identified a potential issue that I could contribute to. The detailed plan for contributing to the external repository, including the selected issue, repository links, contribution workflow, and development notes, is documented in the **CONTRIBUTING.md** file.

Please refer to the following document for more information:

[CONTRIBUTING.md](CONTRIBUTING.md)

## Follow-Up Questions and Reflections

### What was the most challenging task this week?

The most challenging task for me this week in DGL 104 was understanding how to contribute to an external open-source project. This included finding a suitable repository, reviewing the project documentation, and understanding the contribution guidelines such as the README, CONTRIBUTING files, and Code of Conduct. Since every open-source project has its own structure and workflow, it initially felt confusing to understand how the contribution process works.

### How did I overcome this challenge?

I overcame this challenge by carefully reading the documentation provided in the repository and following the recommended steps for contributors. I also spent time exploring the project's issues and community resources to better understand how contributors interact with maintainers. Breaking the process into smaller steps, such as identifying an issue, reviewing the guidelines, and planning the contribution, helped me better understand the workflow. This process improved my understanding of how open-source collaboration works and how developers contribute to community-driven projects.



 