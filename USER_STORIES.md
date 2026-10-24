# Lab 03 — Agile Lab Scenarios

## Group Information

- **Group Number:** G05
- **Project Name:** Course Registration System
- **Module:** Course Registration
- **Repository:** CourseRegistrationSystem
- **Project Board:** G05 - Course Registration Board

## Project Overview

The Course Registration System helps students view offered courses, check prerequisites, register for eligible courses, drop registered courses, and view their course timetable.

## User Stories

### [G05-CR] US-01 - View Offered Courses

**User Story:**  
As a student, I want to view the courses offered by the university so that I can choose suitable courses for registration.

**Acceptance Criteria:**
- [ ] The system displays courses offered for the current semester.
- [ ] Each course displays its code, title, credit hours, and instructor.
- [ ] If no courses are available, the system displays an appropriate message.

**Technical Tasks:**
- [ ] Design the offered courses screen.
- [ ] Create a course data structure.
- [ ] Implement the function to display available courses.
- [ ] Test the course list and empty-list message.

### [G05-CR] US-02 - Check Course Prerequisites

**User Story:**  
As a student, I want to check course prerequisites so that I can confirm my eligibility before registering.

**Acceptance Criteria:**
- [ ] The system displays prerequisites for each course, if applicable.
- [ ] The system indicates whether the student has completed the required prerequisites.
- [ ] If prerequisites are not met, the system explains that the student is not eligible.

**Technical Tasks:**
- [ ] Add prerequisite information to the course data.
- [ ] Implement prerequisite validation.
- [ ] Display eligibility status to the student.
- [ ] Test eligible and ineligible cases.

### [G05-CR] US-03 - Register for a Course

**User Story:**  
As a student, I want to register for an eligible course so that I can enroll in courses required for my semester.

**Acceptance Criteria:**
- [ ] The system allows registration when the student meets the prerequisites.
- [ ] The system displays a confirmation message after successful registration.
- [ ] The system prevents registration when prerequisites are not met.
- [ ] The system prevents duplicate registration in the same course.

**Technical Tasks:**
- [ ] Design the course registration interface.
- [ ] Implement course registration validation.
- [ ] Save the student's registered courses.
- [ ] Test successful and invalid registration attempts.

### [G05-CR] US-04 - Drop a Registered Course

**User Story:**  
As a student, I want to drop a registered course so that I can update my semester course selection when needed.

**Acceptance Criteria:**
- [ ] The system displays the courses in which the student is registered.
- [ ] The system allows the student to drop a registered course.
- [ ] The system displays a confirmation message after the course is dropped.
- [ ] The system displays an appropriate message if the student is not registered in that course.

**Technical Tasks:**
- [ ] Design the registered courses screen.
- [ ] Implement the drop-course function.
- [ ] Update the student's course registration record.
- [ ] Test successful and invalid drop requests.

### [G05-CR] US-05 - View Course Timetable

**User Story:**  
As a student, I want to view my course timetable so that I can check the days and times of my registered classes.

**Acceptance Criteria:**
- [ ] The system displays the timetable for the student's registered courses.
- [ ] Each timetable entry displays the course title, day, time, and location.
- [ ] If the student has no registered courses, the system displays an appropriate message.

**Technical Tasks:**
- [ ] Design the course timetable screen.
- [ ] Store course schedule information.
- [ ] Implement the timetable display function.
- [ ] Test timetable display for registered courses and empty schedules.

## Change Challenge

**Group Challenge:** To be confirmed from the Lab 03 instructions.

**Proposed response:** The system should validate course registration before confirming it. It should prevent registration when prerequisites are not met or when the student is already registered in the same course.

**Note:** Replace this proposed response with the exact Group 5 change challenge from the lab manual and document how the system addresses it.

## Peer Review

**Peer Review Comment:** The user stories are clearly written and include testable acceptance criteria. The technical tasks provide a practical implementation plan. The team should verify prerequisite validation and test successful and unsuccessful registration cases.

**Peer Reviewer:** [Enter a group member's name]

## Definition of Done

A user story is considered complete when:
- All technical tasks have been completed.
- Acceptance criteria have been checked.
- The implementation has been tested.
- A peer review has been completed.
- The relevant issue has been moved to Done.
