# TDT4250 - Advanced Software Engineering - Assignment 1
## Content
Case description, study plan with semesters, courses and groups of courses to select among for electives.
A program includes multilpe semesters with optional specializations (single or multiple).
Every courses included in a semester can be mandatory or elective.

## Constraints
- Each semester can contain courses summarizing in a total of 30 credits (validated using OCL).
- Each course need to be at least 5 credits (manually written validation).

## Model structure
![plant UML model](https://i.imgur.com/2qp510p.png)

## Sample
The Sample.xmi file includes an example of a studyprogram with a specialization, 2 semesters and 7 courses. Some of the courses are mandatory and some are elective.

- Program: 2 year Msc Computer Science
  - Specialization: Software Development
    - Semester: Semester 1
      - SemesterCourse: ELECTIVE
        - Course: Advanced Software Design
      - SemesterCourse: ELECTIVE
        - Course: Graphical User Interface
      - SemesterCourse: MANDATORY
        - Course: Introduction to Artificial Intelligence
      - SemesterCourse: MANDATORY
        - Course: Information Systems
    - Semester: Semester 2
      - SemesterCourse: ELECTIVE
        - Course: Information Security
      - SemesterCourse: ELECTIVE
        - Course: Advanced Software Enginering
      - SemesterCourse: ELECTIVE
        - Course: Software Architecture
