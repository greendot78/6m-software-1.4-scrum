## Brief

### Preparation

N/A

### Lesson Overview

We will spend the first hour learning about Agile and SCRUM yet keeping in mind with other Agile methodology. We will then learn about the difference between using Object Literal (previous lesson) and Class (today's).

---

### Self studies check-in

Q1: Describe the Waterfall Model.

Q2: Describe the Agile Model.

Q3: Describe the difference between Waterfall and Agile model.

---

## Part 1 - All Agile Methodologies

The most popular Agile Methodology is SCRUM, but it is not the only methodology.

### The Agile Manifesto

<img src="./assets/manifesto.png" />

1. Processes and Tools are not as agile as human beings.
1. Intuitive software is better than excessive documentation.
1. Collaboration ensures product development is aligned with end users' requirement.
1. When business change, the tech team must adapt.

---

### 12 Principles of Agile

<img src="./assets/12-principles.webp" />

The 12 principles applies to every agile methodologies.

### Activity - Research

Choose 3 among the following Agile Methodologies and research how each is conducted:
- Extreme Programming (XP)
  XP is an Agile methodology that aims to produce higher quality software, and higher quality of life for the development team. XP is characterized by:
  **The Planning Game**: Quick determination of the scope of the next release by combining business priorities and technical estimates.
  **Small Releases**: Put a simple system into production quickly, then release new versions on a very short cycle.
  **System Metaphor**: Each project has an organizing metaphor, which provides an easy to remember naming convention.
  **Pair Programming**: All code is written with two programmers at one machine.

- Scrum
- Crystal is a family of Agile methodologies that focuses on people, interactions, community, skills, talents, and communications. It's characterized by several unique features:
  **Cocktail Naming**: Crystal methods are named using colors to signify the 'weight' or 'hardness' of the method. For example, Crystal Clear, Crystal Yellow, Crystal Orange, and Crystal Red.
  **Frequent Delivery**: The primary measure of progress is frequent delivery of usable code to users.
  **Reflective Improvement**: Teams regularly reflect on how to become more effective, then tunes and adjusts its behavior accordingly.
  **Osmotic Communication**: Information is absorbed by team members through overhearing what others are doing.

- Dynamic Systems Development Method (DSDM) is an Agile method that focuses on the full project lifecycle. DSDM mandates that the project stakeholders actively participate to ensure the correct solution is delivered. It's characterized by:
  1. **MoSCoW Prioritization**: Requirements are categorized as Must have, Should have, Could have, and Won't have.
  2. **Timeboxing**: The project is divided into stages and each stage is timeboxed.
  3. **Prototyping**: Prototypes are created to get early feedback from users.


- Lean Development is an Agile methodology that focuses on the creation of value for the end customer and the elimination of wasteful practices. It's characterized by:
  1. **Eliminate Waste**: Anything that does not create value for the customer is considered waste.
  2. **Build Quality In**: Quality is improved by building it into products from the beginning, rather than through inspection at the end.
  3. **Create Knowledge**: Lean development is a learning process that aims to create new knowledge as it progresses.
  4. **Defer Commitment**: Decisions are delayed as long as possible to gather the maximum amount of information and make the best decisions.

- Feature-Driven Development (FDD)
FDD is an iterative and incremental software development process that follows these steps:
1. **Develop an Overall Model**: A high-level walk through of the scope of the system is conducted to identify the key areas.
2. **Build a Feature List**: All the potential features that could be included in the product are listed. These are usually written in the form "action, result, object", such as "Calculate, total cost, of a purchase".
3. **Plan By Feature**: A plan is created for delivering each feature. This includes deciding the order of implementation.
4. **Design By Feature**: Each feature is designed in detail, creating a sequence diagram for each one.
5. **Build By Feature**: Each feature is built and then integrated into the overall model. This includes all testing and documentation.


- Test Driven Development (TDD)
TDD is a software development process where the test is written before the code. It follows these steps:
1. **Write a Test**: Before writing the functional code, a test is written to define what the code will do. At this point, the test will fail because there's no code to test.
2. **Write the Code**: The functional code is written to pass the test. The code should be the simplest possible code to pass the test.
3. **Refactor**: The code is refactored to meet standards and to ensure it's as simple and efficient as possible, while still passing the tests.
4. **Repeat**: The process is repeated for each piece of functionality in the system. The repetition of these steps leads to a cycle known as "Red, Green, Refactor" where Red is writing a failing test, Green is making it pass by writing code, and Refactor is improving the code while keeping it working.

- Kanban

---

## Part 2 - SCRUM

SCRUM is one of the many Agile Methodologies.

<img src="./assets/scrum.webp" style="background-color:white;"/>

SCRUM Theory:
Empricism through:
1. Transparency - Giving visibility to processes 
1. Inspection - Timely checks of progress
1. Adaptation - Adjusting the process as needed

Scrum Values:
1. Courage - We admit we do not know everything 
1. Focus - focus on what is important
1. Commitment - dedicated to delivering quality software
1. Respect - create cross-functional, self-organizing teams
1. Openness - frequently inspecting through delivery

A Scrum team is composed of:
1. Product Owner - Manages the Product Backlog and optimizes the value of the Product
1. Scrum Master - Manages the Scrum process and removes impediments
1. Development Team - Manages itself and create increments based on Definition of Done

In SCRUM, there are four meetings:

1. *Sprint Planning* - Laying out the work to be performed for the sprint. (4 to 8 hours)
1. *Daily Scrum* - Inspect progress toward the Sprint Goal. (15 mins)
1. *Sprint Review* - Inspect the outcome of the Sprint. (1 to 4 hours)
1. *Sprint Retrospective* - Plan ways to increase quality and effectiveness. (1 to 3 hours)

Source: https://www.scrum.org/resources/what-is-scrum

### Activity - Research
What are the use of each Scrum artifacts:
Scrum artifacts are key tools in Agile software development. Here's a brief explanation of each:
1. **Product Backlog**: This is a prioritized list of all the potential features, improvements, and fixes for the product. It's maintained by the Product Owner and it's dynamic, meaning items can be added, removed, or reprioritized as needed.
1. **Sprint Backlog**: This is a subset of the Product Backlog that the team commits to complete during the next Sprint (a time-boxed iteration, typically 2-4 weeks). The team owns the Sprint Backlog and can adjust it during the Sprint as necessary.
1. **Product Increment**: This is the sum of all the Product Backlog items completed during a Sprint and all previous Sprints. At the end of a Sprint, the new Increment must be in a usable condition and meet the Scrum Team’s definition of "Done", regardless of whether the Product Owner decides to actually release it.
---

## Part 3 - Class Activity (What are agile user stories?)

|Action|Duration|Outcome|
|----|--------|-------|
|Learners self Reading for this [link](https://www.atlassian.com/agile/project-management/user-stories).|10 mins|Learners have a brief understanding of what agile user stories are.
|Instructor facilitate students to answer three questions by getting students to type in chat.|20 mins|Summarizes and highlight the good inputs from student.|

Three Questions:
1. **What are user stories?**
User stories are a simple, natural language description of one or more features of a software system, written from the perspective of an end user. They typically follow a simple template: "As a [type of user], I want [an action] so that [a benefit/a value]".
2. **Why user stories?**
User stories are a way to capture product functionality from the user's perspective, ensuring the development team understands the user's needs and expectations. They promote communication, focus on the user's needs, and provide a basis for estimating and prioritizing development tasks.
3. **Example of a user story:**
"As a user, I want to be able to reset my password so that I can regain access to my account if I forget it."

---

## Part 4 - Class Activity (User story creation)

Activity: Choose a Scenario and create at least 10 user stories for your chosen scenario
1. eCommerce website
2. eBanking website
3. eLearning platform
4. Booking management platform (Hotel, Flights)
5. Social media (Facebook, Twitter/X, Instagram, etc.)
6. Video/Music streaming service (Youtube, Spotify)
7. Govtech website

Remember the format of a user story: `As a ____, I want to ____, so that _____`
---

10 user stories for a booking management platform:
1. As a customer, I want to search for hotels in a specific location, so that I can find a place to stay during my trip.
2. As a customer, I want to filter hotel search results by price, so that I can find a hotel within my budget.
3. As a customer, I want to view detailed information about a hotel, including photos and reviews, so that I can make an informed decision.
4. As a customer, I want to book a hotel room for specific dates, so that I can plan my trip.
5. As a customer, I want to receive a confirmation email after booking a hotel, so that I have a record of my booking.
6. As a customer, I want to search for flights by departure and arrival locations and dates, so that I can find a suitable flight.
7. As a customer, I want to select a seat when I book a flight, so that I can choose where I will sit.
8. As a customer, I want to pay for my hotel and flight bookings online, so that I can confirm my bookings immediately.
9. As a customer, I want to cancel my booking and get a refund, so that I can manage changes in my plans.
10. As a hotel owner, I want to list my hotel on the platform, so that I can attract more customers.
