# sre-github-lab

Requirement documentation for a student task



\# Student Task Tracker



\## Overview

Students need a simple way to track coursework tasks and see what remains.

The proposed system will help a student record tasks and mark them complete.

This system improves personal time management and reduces missed deadlines by providing a clean, focused task overview.



\## Scope

In scope: Add a coursework task with a title.

In scope: List saved tasks.

In scope: Mark a task complete.

Out of scope: Fee payments.

Out of scope: Automatic grading.



\## Stakeholders

Student: Records tasks and checks progress.

Instructor: Needs to ensure students track assignment deadlines effectively without cluttering academic portals.

Project maintainer: Needs to manage system stability, review feature documentation, and handle user updates.



\## Functional requirements

FR-01: The system shall let a student create a task with a title.

FR-02: The system shall display the student's saved tasks.

FR-03: The system shall let a student mark a task complete.



\## Nonfunctional requirements

NFR-01: With 100 saved tasks, the task list shall appear within 2 seconds in at least 95 of 100 trials on an agreed test device.

NFR-02: Every task action shall work using only a keyboard, checked against each documented task workflow.



\## Acceptance criteria

FR-01: Given the title "Read Chapter 1", saving a new task makes that title appear in the task list.

FR-02: Given two saved tasks, opening the list shows both titles.

FR-03: Marking an incomplete task complete changes its displayed status to Complete.



\## Assumptions and open questions

Assumption A-01: Students will access the task tracker primarily via modern web browsers on laptop or desktop devices.

Question Q-01: Will task data need to persist across multiple browser sessions using local storage or a backend database?

Question Q-02: Which device will be used to test NFR-01?



\## Project status and viewing

This is a documentation-only project. No application has been built.

Clone the repository and open README.md in Notepad, or read it on GitHub.



\## Author

Laiba Khan - BS Software Engineering, FCIT, University of the Punjab



\## Contributing

Create a documentation branch, edit and review README.md, commit and push the change, then open a pull request for review.

