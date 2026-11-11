
# Student Task Tracker

## Overview

The Student Task Tracker is a proposed system designed to help students organize and manage their academic coursework. Students can create tasks, view their saved tasks, and mark completed tasks.

The main objective is to improve time management keep track responsibilities and help students monitor their progress.

## Scope

### In Scope
- Add a coursework task with a title.
- Display all saved coursework tasks.
- Mark a task as complete.
- View the completion status of each task.

### Out of Scope
- Fee payments and financial transactions.
- Automatic grading of assignments.
- Online examination management.

## Stakeholders

- **Student:** Creates coursework tasks, views pending work, and tracks academic progress.
- **Instructor:** Needs visibility into the proposed system's capabilities and how it supports students in managing coursework.
- **Project Maintainer:** Manages project documentation, maintains requirements, and handles future updates.
- **University Administration:** Is interested in improving students' academic organization and productivity.

## Functional Requirements

- **FR-01:** The system shall allow a student to create a coursework task by entering a task title.
- **FR-02:** The system shall display all coursework tasks saved by the student.
- **FR-03:** The system shall allow a student to mark an incomplete task as complete.
- **FR-04:** The system shall display the completion status of each saved task.

## Nonfunctional Requirements

- **NFR-01:** When the student has 100 saved tasks, the task list shall appear within 2 seconds in at least 95 out of 100 trials on an agreed test device.
- **NFR-02:** Every task management workflow shall be operable using only a keyboard, verified against all documented task workflows.
- **NFR-03:** The system shall display task titles and completion statuses clearly and consistently.

## Acceptance Criteria

- **FR-01:** Given the title "Complete Database Assignment", when a student saves a new task, the task shall appear in the saved task list with the exact entered title.
- **FR-02:** Given two previously saved tasks, when the student opens the task list, both task titles shall be displayed.
- **FR-03:** Given an incomplete task, when the student marks it as complete, its displayed status shall change to "Complete".
- **FR-04:** Given saved tasks with different completion states, when the student views the task list, each task shall show its correct completion status.

## Assumptions and Open Questions

### Assumptions
- **A-01:** Each student will manage their own coursework tasks.
- **A-02:** Every task will have at least one title.

### Open Questions
- **Q-01:** Should students be able to assign deadlines to their coursework tasks?
- **Q-02:** Which device will be used to test the performance requirement NFR-01?
- **Q-03:** Should students be able to edit or delete previously saved tasks?

## Project Status and Viewing

This is a documentation-only project. No application has been developed.

To view the project documentation, clone the GitHub repository and open README.md in Notepad, or view it directly on GitHub under the doc/feature branch.

## Author

Ubaid Ahmad Raza  
Course: Software Requirement Engineering 

## Contributing

1. Create a separate documentation branch.
2. Edit and review README.md.

