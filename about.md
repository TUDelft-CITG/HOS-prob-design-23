---
layout: page
title: Unit Information
nav_order: 1
description: >-
    Information about lectures, materials and assignments.
---

<!-- <a href="" target="_blank">link</a> -->
<!-- <a href="https://tudelft-citg.github.io/HOS-prob-design/intro.html" target="_blank">HOS book</a> -->

# Information about this Unit
{:.no_toc}

This unit is is part of three B modules offered in Q4 of the Hydraulic and Offshore Structures (HOS) track in the Civil Engineering MSc program at TU Delft:
- <a href="https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63755" target="_blank">CIEM4210 Marine Renewables</a>
- <a href="https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63756" target="_blank">CIEM4220 Dams, Dikes and Breakwaters</a>
- <a href="https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=63757" target="_blank">CIEM4230 Floating and Submerged Structures</a>

Although each of these B modules look at a wide range of structures, there are a couple important things in common: hydraulic loads govern the design of each system and structure; and failures can lead to significant consequences related to economic damages and loss of life. There is a high level of uncertainty in the hydraulic loads as well as the geotechnical conditions where these systems are operating. This makes probability, risk analysis and reliability-based design key tools for the design, assessment and maintenance of these structures. The purpose of the unit CIEM42X0 Probabilistic Design is to support you in this effort for your system and structure of interest. As such, the unit is built on several key elements:
- Three primary technical topics: 1) extreme value analysis (weeks 1-3), 2) component reliability (weeks 4-6) and 3) system reliability (week 7)
- A series of (online) reading assignments and exercises (homework)
- Weekly workshop-style in-class sessions that will apply concepts covered in the reading and homework

These key elements of the unit are described in the sections below.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Friday In-Class Sessions

Our in-class sessions will typically be Friday mornings (9:45-12:45) in Bouwcampus Hall 1. Most of the time we will try to finish by 12:00. In total there will be 5 sessions: weeks 3, 5, 6, 7, 8. For each session, you will be asked to complete some reading, practice assignments and watch a few short explanatory videos. Some of the assignments will require writing computer code. Although the assignments are not required to be submitted, the equations and code are incorporated directly in the in-class sessions.

The format of the in-class sessions will be workshop-style, where you will work in small groups to solve the assignments, and then share results and questions with classmates and instructors towards the end of the class period. Instructors will give an introduction to the workshop and preview of the upcoming week activities at the beginning and end of each session.

## Assignments

This unit has two types of assignments: homework and workshops, both of which will be shared via the HOS book (introduced below). For all assignments in this unit, you are encouraged to work collaboratively; however, we also encourage you to work out analytic exercises yourself and write your own code, as this is a valuable part of the learning process.
### Homework

Homework assignments are a mix of analytic and coding exercises to prepare you for the Friday workshops, as well as your B module design assignments and exams. In most cases they do not need to be turned in, and solutions will be shared after the due dates indicated in the calendar for you to check your work. We are working on setting up an autograder to help you check whether or not your code is working as expeced, which would be optional. This involves pushing your code to a GitLab repository we create for you, similar to what we did in MUDE; more information will be provided about this in week 3.

The recommended dates for you to start and finish the homework assignments are indicated in the calendar with these buttons: <a href="https://tudelft-citg.github.io/HOS-prob-design/unlisted/assignment.html" target="_blank">Start HW 1</a>{: .label .label-red } and <a href="https://tudelft-citg.github.io/HOS-prob-design/unlisted/assignment.html" target="_blank">HW 1 Due</a>{: .label .label-red }. Note that the buttons contain links that take you to the assignments and solutions in the HOS book (once they are available).

### Workshops

These are meant to be completed in class on Fridays, and build directly on the homework assignments; in some cases you will be asked to use the code from your homework assignment in the workshop. After completing a few calculations, the workshops will emphasize interpreting the results and making decisions to help you in the design of your structure and systems, especially as required for your design projects and exams.

You are not expected to turn in the workshop assignments, and solutions will be provided in the HOS book after the session. Workshops are shown in the calendar with a purple button like this: <a href="https://tudelft-citg.github.io/HOS-prob-design/unlisted/assignment.html" target="_blank">Workshop</a>{: .label .label-purple }

### Design Assignments and Projects

Depending on your B module, you will work on a design-oriented project. Each of them have different scope and requirements, but all of them will have a section that requires you to apply concepts from this unit. Between the design assignments and exams, the probabilistic design component will represent 20% of the total grade you recieve for your B module. Although the assignments and workshops from this unit are not included directly in the grade for the B module, if you are able to complete them you will have no problem getting a good evaluation for the 20% probabilistic design portion of the module.

## Resources

There are two primary resources for this unit, both of which can be accessed online.

### HOS Book

The <a href="https://tudelft-citg.github.io/HOS-prob-design/intro.html" target="_blank">HOS book</a> is an online textbook similar to that used in MUDE for weeks 2.7-2.8. In addition to technical content, it will also be used to share the homework and workshop assignments. It has three main parts:
- **Probabilistic Design**: chapters in this part contain an introduction to the course and various topics related to component and structural reliability that are not covered in the ADK book. Reading from this chapter is listed in the calendar with a link, for example, <a href="https://tudelft-citg.github.io/HOS-prob-design/PD/01_00_intro.html" target="_blank">HOS-PD-1</a> is Chapter 1 of the Probabilistic Design part.
- **Extreme Value Analysis**: chapters in this part provide underlying theory to help understand the EVA procedure that is key for assessing hydraulic loads in HOS projects. Reading from this chapter is listed in the calendar with a link, for example, <a href="https://tudelft-citg.github.io/HOS-prob-design/EVA/01_00_Extreme.html" target="_blank">HOS-EVA-1</a> is Chapter 1 of the Extreme Value Analysis part. The EVA material from MUDE is also included in this part of the HOS book for you to be able to refer to it easily (<a href="https://tudelft-citg.github.io/HOS-prob-design/EVA/MUDE/01_00_MUDE.html" target="_blank">HOS-EVA-5</a>).
- **Homework** and **Workshop** assignments and solutions will be added to the HOS book throughout Q4, as described above.

This book will be actively updated throughout the quarter; primarily with assignments and solutions, but also new technical content may be added, depending on questions and needs from students. The home page of the HOS book will list the updates made throughout the quarter. D epending on the importance or urgency, some (but not all) of these updates may also be communicated via announcements on this website or the Brightspace page for your B module.

### ADK Book

We will use the textbook *Structural and System Reliability* for the component and system reliability part of the course:

{: .note }
Der Kiureghian, A. (2022). Structural and System Reliability. Cambridge: Cambridge University Press. doi:10.1017/9781108991889

<!-- @book{der kiureghian_2022, place={Cambridge}, title={Structural and System Reliability}, DOI={10.1017/9781108991889}, publisher={Cambridge University Press}, author={Der Kiureghian, Armen}, year={2022}} -->

A description of the book can be found at the <a href="https://doi.org/10.1017/9781108991889" target="_blank">book website</a>; note that all the other links on this web page will take you to <a href="https://www-cambridge-org.tudelft.idm.oclc.org/highereducation/books/structural-and-system-reliability/7B7F299239AD41812A0C3E2E93B3CA57#overview" target="_blank">this website</a>, which gives access to the online book and reader, but requires a TU Delft login, as it is offered through the TU Delft Library. In addition, there are a few hard copies on reserve in the TU Delft library, and Robert also has a few copies that he might be able to let you look at while in his office.

<!-- You can only read the texbook online if you are connected to the TU Delft wifi or using a VPN (use the eduVPN software if you are off campus). You can confirm you have access by checking if a green "Access" button appears at the top of the <a href="https://www-cambridge-org.tudelft.idm.oclc.org/highereducation/books/structural-and-system-reliability/7B7F299239AD41812A0C3E2E93B3CA57#overview" target="_blank">book website</a> and a "Read online" button is visible below the book description. -->

<!-- <a href="" target="_blank">link</a> -->

{: .important-title }
> **Important: Online Textbook**
>  
> <a href="https://www-cambridge-org.tudelft.idm.oclc.org/highereducation/books/structural-and-system-reliability/7B7F299239AD41812A0C3E2E93B3CA57#overview" target="_blank">This link</a> is the best way to access the online textbook and requires a TU Delft login. Once clicking "Read online" you can continue with "read only access" (registering for an account does not seem to provide any worthwhile reading benefits). 
> 
> The online textbook loads **very** slowly. It works by loading each chapter one at a time, and sometimes it takes several minutes per chapter. This is obviously annoying, but we have not found a way around it yet. The best strategy is to click on the Chapter you need and wait patiently for it to load. Once it is there, you can view all the contents in that chapter, either by scrolling up and down, or clicking the section links in the Table of Contents. For the required reading listed in the calendar, we will place links to the required chapter to make this process a bit easier (but unfortunately you will still have to wait for it to load). Please let Robert know if you find a better solution! 
> 
> Most links on this website will refer to specific chapters and reading in the textbook; once logged in with your TUD account, you should be able to open these links to the chapters directly. If the link does not work, try starting at the main book page (using the link at the top of this website) and navigating to the necessary chapter using the Table of Contents (and let Robert know about the broken link!). 

For CIE42X0 we will rely most on the following chapters:  
- <a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc10" target="_blank">Chapter 3: Multivariate Distributions</a> 
- <a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc11" target="_blank">Chapter 4: Formulation of Structural Reliability</a>  
- <a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc13" target="_blank">Chapter 6: The First-Order Reliability Method</a>  
- <a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc15/pos_15.0" target="_blank">Chapter 8: System Reliability</a>  

<a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc9" target="_blank">Chapter 2</a> is pre-requisite material for our course, and can be skipped, but may be useful to refer back to as we go, especially to check the notation used throughout the textbook.

Although we will touch on a few topics from <a href="https://ereader.cambridge.org/wr/viewer.html#book/b465a335-deca-4553-b09f-8989cf136370/doc12" target="_blank">Chapter 5</a>, it is not the focus of this course. However, it gives an interesting perspective on a few other reliability methods that are widely used in practice (despite having some well-known issues), so this can be a very useful chapter to refer back to later, especially when trying to understand an unfamiliar reliability technique that may have been used by other engineers or researchers.

### Other Resources

All of the topics we discuss build on what was covered in MUDE, and the <a href="https://tudelft-citg.github.io/MUDE/intro.html" target="_blank">online textbook from Weeks 2.7-2.8</a> is a good resource to understand the basics of risk and reliability analysis.

This unit replaced a 1st-year MSc course CIE4130 Probabilistic Design in the old curriculum. The lecture notes (14MB) can be downloaded <a href="https://surfdrive.surf.nl/files/index.php/s/acbbK9bZ2fAjOx1/download" attributes-list download>here</a>.  In particular, the chapters on structural reliability and system reliability may be interesting.

*Additional material will be added here and organized on an as-needed basis.* 