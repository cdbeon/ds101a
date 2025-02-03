---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Course syllabus. Conatins policies and information about the course.
---

# Syllabus
{:.no_toc}

{: .note }
> This syllabus is a living document, meaning that it can be updated at any time throughout the course. Check back periodically to see any changes that have been made to the course.
> 
> <i> Last Updated: February 2, 2025</i>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

<hr>


## About DS 101A?

Data Science (DS) 101A is the first course of a two-part series that teaches the foundations of conducting an independent research project using data science applications. DS 101A, which spans over the course of 15 weeks, covers a combination of basic coding principles and skills required to explore and analyze datasets. Students will learn how to use a dataset to conduct exploratory data analysis and create visualizations to help convey their results to a proper audience.

Below are the main units covered throughout the course and their learning objectives. After each unit, students will be able to:
- <b>Unit 1: Basic Programming Principles in Python</b>
    - Understand Python syntax
    - Create user-defined functions to solve specific problems
    - Create a custom class object to structurer an entity 
    - Become comfortable with working in a Jupyter environment
- <b>Unit 2: Dataset Analysis and Manipulation using Pandas</b>
    - Read in a dataset into a Pandas dataframe
    - Select columns and filter rows in a dataframe
    - Calculate aggregate statistics 
    - Clean the dataset via manipulation
- <b>Unit 3: Creating Visualizations</b>
    - Create simple (sub)plots from a Pandas dataframe
    - Customize the plots with proper labels and titles
    - Select the proper visualization for a specific question
- <b>Unit 4: Statistics and Inference</b>
    - Describe the dataset using statistical terms
    - Understand the difference between parametric and non-parametric tests
    - Conduct hypothesis testing with one-sample and two-sample datasets
    - Select the proper test to use depending on the question

Please note that this class is modeled similarly to a university-level course, meaning that the pace may be faster than what students are normally used to. 

<hr>

## About DS 101B

Data Science 101B: Research with Data Science, the second part of the course, will cover fundamentals of conducting an independent research project. This course will be offered during Summer/Fall 2025. Some of the topics that will be covered include creating a research proposal, conducting a literature review, and understanding the anatomy of an academic paper. Unlike DS 101A, DS 101B is has an emphasis on independent work and will require more effort from the student to meet assignment deadlines. 

A more comprehensive syllabus of the course will be released closer to the start of its offering date. The course will be offered in the summer/fall of 2025.

<hr>

## Course Components

### Lecture

There will be a synchronous, online weekly lecture every Thursday from 8:00 – 9:30 PM PT. Please refer to the course calendar for dates and additional details.

Lecture is mandatory, and students are expected to attend every week. <b><u>If a student has three unexcused absences, they will be automatically dropped from the course.</u></b> If you have a concern about not being able to make a future lecture due to prior engagements or are facing an emergency situation, please contact the instructor as soon as possible. 

### Office Hours
Office hours are dedicated sessions where students can ask questions or request additional help from instructors. Although office hours are optional, they are highly recommended if you require any additional help with any of the content or assignments.

Dedicated office hours are weekly on Wednesday from 8:00 – 9:30 PM PT. If you cannot make this time, please contact the instructor to schedule an alternative time.

### Homework
Homeworks are week-long assignments that are designed to help students develop an in-depth understanding of both the theoretical and practical aspects of ideas presented in lecture. Homeworks will be graded on a completion-basis, meaning that students will receive credit as long as they complete the entirety of the assignment with ample effort. Homework solutions will be posted shortly after the following lecture.

Assignments will be released promptly after lecture and are due by 11:59 PM PT on Wednesday of the following week, unless otherwise stated. Deadlines are subject to change.

### Final Project
For Data Science 101A, there will be a final project towards the end of the semester. This project is meant to be a culmination of everything that was covered in Data Science 101A, in lieu of exams. Details of the final project will be released at a later date.

<hr>

## Course Grading
The grading criteria for the course is as follows:

| Criterion | Grading |
|-----------|---------:|
| Lecture Attendance	| 50% |
| Lecture Participation	| 10% |
| Homework Assignment	| 15% |
| Final Project	        | 25% |

<hr>

## Advancing to DS 101B

Data 101A has a grading system to ensure that students are keeping up with the course material. Students are required to at least score a 75% or higher in order to advance to DS 101B. 

The instruction has the final discretion as to whether or not a student qualifies to advance to DS 101B. 

<hr>

## Resources

Resources will be provided as the course progresses. If you want to get ahead, I highly recommend looking through [UC Berkeley's Data 8](https://www.data8.org/sp25/index.html) course. 

{: .note }
> Data 8 uses their own Python library called `datascience` that's meant to be a more intro-friendly way to introduce students to coding. We will not be using this library. Instead, we will be using current industry-standard libraries that will be more relevant and compatible with other libraries (e.g. visualization libraries such as `matplotlib` or `seaborn`). 


<hr>

## Additional Policies and Notes

### Late Policy 
Late work will not be accepted under any circumstances. Please make sure to start assignments as early as possible to avoid any last-minute submissions.

### Academic Integrity and Collaboration Policy 
Collaboration is heavily encouraged in research to promote sharing ideas and perspectives. However, when it comes to learning, there is a fine line between collaboration and cheating. You are encouraged to talk to other classmates about methods to solutions, but sharing code and answers is considered academic misconduct. Evidence of academic misconduct will result in immediate removal from the course. Please make sure your solutions are your own – besides, the best way to learn something is to go through the whole mile of understanding and learning!

### Wellness Policy 
Understandably, juggling this course and your many other responsibilities can get overwhelming. If you ever feel like you are struggling to keep up, please contact the instructor as soon as possible! We want you to succeed and move on to DS 101B so that you can have something substantial when you apply for college 😊 

### Course Flexibility 
Please be advised that this is the first iteration of the course, meaning that there’s a lot of changes that can happen throughout the semester. I will do my best to plan everything ahead, but I appreciate your understanding if there are any last-minute changes. I will also do my best to communicate any changes well ahead in time!
