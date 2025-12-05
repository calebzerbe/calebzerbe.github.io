---
layout: essay
type: essay
title: "Design Patterns are Omnipresent"
# All dates must be YYYY-MM-DD format!
date: 2025-12-04
published: true
labels:
  - Design Patterns
  - Factory
  - Singleton
  - Observer
  - Model-View-Controller
  - FlowController
---

Everywhere you go, you’ll see design patterns. Patterns are the foundation of design in today’s world. Everything is built upon some pattern that was created previously, although generally with some modification to fit the given instance. Such is the same with software engineering. With time, solutions to problems were formed into general methods used to solve commonly occurring problems in software design (though with modifications depending on the situation). In particular, there are object-oriented design patterns, which show relationships and interactions between classes or objects. There are three main types of object-oriented design patterns, which are creation patterns (how to create objects), structural patterns (how to represent collections of objects), and behavioral patterns (how to manage interactions between objects). These kinds of patterns became the foundation of design across the field of computer science, which include but are not limited to: Factory, Singleton, Observer, and Model-View-Controller, among many others.

## Kinds of Design Patterns

Design patterns are quite commonly used and applied to many different situations. Factory, for example, creates objects without exposing underlying logic, which can potentially return objects of different classes, create dependent objects, and return multiple objects. 

<img src=""/>
Factory diagram from Ruslan Dzhafarov (Jan 23, 2023) <a href="https://ruslandzhafarov.medium.com/design-patterns-in-swift-factory-88ab7356544a">[1]</a>

Singleton creates a sort of global variable in an object-oriented language that does not support global variables or provide a global state. 

<img src=""/>
Singleton diagram from Ranjith ramachandran (Jun 22, 2015) <a href="https://www.youtube.com/watch?v=QsBQnFUx388">[3]</a>

Observer is based on the principle that there is a set of objects called the “Observers” that need to be informed when each change in state occurs to another object, called the “Subject”. An example of this would be event handlers.

<img src=""/>
Observer diagram from Wikipedia (Nov 4, 2025) <a href="https://en.wikipedia.org/wiki/Observer_pattern">[4]</a>

Finally, Model-View-Controller, which is widely used in web applications, allows you to decouple the internal representation of information presented to and accepted from a user. The model handles all of the data manipulation and logic, the view is responsible for presenting the data from the model to the user and also responsible for user interaction, and the controller is an intermediary between the model and view, which determines the appropriate view to display information, and takes the user input from the view to update the model.

Model-View-Controller diagram from Robert Eckstein (Mar, 2007) <a href="https://www.oracle.com/technical-resources/articles/javase/mvc.html">[2]</a>

## Implementing of Design Patterns in my own Project

Over this past month, I’ve been working on creating a website for my ICS 314 final project, which is focused on creating an application that allows students at the University of Hawaii to form study sessions with each other for various ICS classes. Because of this, I’ve had to use multiple design patterns, of which I’ve found FrontController and Model-View-Controller to be the most important and two design patterns that I would like to talk about. FrontController is a design pattern that centralizes all client requests in a single component which acts as the application’s entry point, handling authentication, logging, and routing. My site uses this type of pattern with the implementation of the Nextjs app router, which maps each incoming URL to the correct component, layout, or API router handler, manages authentication, error handling, server-side rendering, and data fetching, among other things. This pattern is used in tandem with the Model-View-Controller pattern, which basically forms the skeleton of the entire site. Prisma Postgresql is used as the model, being the database that handles all of the user data and app data. Nextjs would be a type of controller, with its api routers handling HTTP requests, interacting with the data models, and processing input. It is also responsible for handling requests, data fetching, and view selection. Finally, you have the view, which is done using React-Bootstrap, rendering the user interface and presenting the data from the model. These all come together to form the final application.

## Conclusion

To end it off, design patterns are very important and widespread across the internet. Every website and application that you interact with uses some sort of design pattern in its implementation. Therefore, understanding how these patterns work and how to implement them is an important skill to learn and understand fully.

## References

[1] Dzhafarov, R. (2023, January 23). Design Patterns in Swift — Factory. Medium. Retrieved December 4, 2025, from https://ruslandzhafarov.medium.com/design-patterns-in-swift-factory-88ab7356544a

[2] Java SE Application Design with MVC. (2007, March). Retrieved December 4, 2025, from https://www.oracle.com/technical-resources/articles/javase/mvc.html

[3] Ranjith ramachandran. (2015, June 22). Singleton Design Pattern in Java - part I [Video]. YouTube. Retrieved December 4, 2025, from https://www.youtube.com/watch?v=QsBQnFUx388

[4] Wikipedia contributors. (2025, November 4). Observer pattern. Wikipedia. Retrieved December 4, 2025, from https://en.wikipedia.org/wiki/Observer_pattern
