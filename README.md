# Student Task Tracker

## Overview
University students often juggle multiple assignments, quizzes, and lab deadlines across different courses. The proposed
Student Task Tracker provides a clean, lightweight checklist where students can record upcoming coursework tasks,
view pending items at a glance, and mark completed tasks as done.

## Scope
- **In scope:** Add a new coursework task with a descriptive title and optional due date.
- **In scope:** View a list of all saved coursework tasks with their completion status.
- **In scope:** Mark an existing incomplete task as complete.
- **In scope:** Filter or distinguish between pending and completed tasks.
- **Out of scope:** University tuition or fee payments.
- **Out of scope:** Automated assignment grading or plagiarism checking.
- **Out of scope:** Live video lectures or instructor file submissions.

## Stakeholders
- **Student:** Primary user who creates coursework tasks, tracks deadlines, and marks finished items complete.
- **Instructor:** Needs visibility into common student workload patterns and clarity on whether course milestones are clearly communicated.
- **Project maintainer:** Responsible for reviewing requirements documentation, managing repository branches, and overseeing future implementation updates.

## Functional requirements
- **FR-01:** The system shall allow a student to create and save a new coursework task with a non-empty title.
- **FR-02:** The system shall display all saved coursework tasks along with their current status (Pending or Complete).
- **FR-03:** The system shall allow a student to mark a pending task as complete and update its status immediately.

## Nonfunctional requirements
- **NFR-01:** With up to 100 saved tasks, the task list shall load and display within 2 seconds in at least 95 out of 100 trials on a standard lab browser.
- **NFR-02:** Every core task action (create, view, mark complete) shall be operable using only keyboard navigation, verified against all documented workflows.

## Acceptance criteria
- **FR-01:** Given a valid task title such as "Complete SRE Lab 04", when the student saves the task, then the new task appears in the task list with a status of Pending.
- **FR-02:** Given two saved tasks in storage, when the student opens the task list view, then both task titles and their respective statuses are displayed.
- **FR-03:** Given an existing task with status Pending, when the student selects the option to mark it complete, then its displayed status changes to Complete.

## Assumptions and open questions
- **Assumption A-01:** Students will access the tracker from a modern desktop or mobile web browser with local or cloud session persistence.
- **Assumption A-02:** each student manages a personal task list without needing multi user team sharing in version 1.
- **Question Q-01:** Should students be able to edit a task title or delete a task after saving it in the initial release?
- **Question Q-02:** Which specific browser and hardware configuration will be used as the standard test device for verifying NFR-01?

## Project status and viewing
This is a documentation-only project for Software Requirement Engineering (SEF25). No application code has been built yet. To view this documentation, open `README.md` directly on GitHub or clone the repository and open `README.md` in Notepad.

## Author
Abdul Haseeb — BSEF25A502 (Course: SEF25)

## Contributing
Create a documentation branch from `main` (such as `doc/feature`), edit and review `README.md`, commit and push the changes to GitHub, and open a pull request for review before merging into `main`.