# CprE 308 Final Project

## Overview
The goal of this project is to allow students the chance to familiarize themselves with additional topics relating to operating systems.
To do so, students will study a topic relating to operating systems and write a report detailing their findings.
The goal is to focus on practical aspects, and not simply theoretical.

Students will first submit a project proposal outlining the topic they choose to study.  The final report will be due near the end of the semester.  

Students can work individually, or in pairs (no more than 2).

## Timeline

 - **Final Due Date** The final project will be due the Friday before deadweek, or April 25th (at 11:59pm)
 - **Project Proposal** The project proposal will be due the Friday after Spring Break, or March 28th (at 11:59pm)

## Requirements

### Content
 - Students should choose a subject area to study and provide a report detailing their findings.
 - The report should clearly articulate their understanding of the topic.
 - The report should be separated into clear sections.  A possible outline may be:
    - Introduction: What is the topic.
    - Background: Brief background of the topic.  This may include history and related issues.
    - Discussion of Topic: Bulk of content.
    - Conclusion: Summary of topic, and what you learned.

### Formatting
 - Students should submit their document as a single column, double spaced PDF, in 10pt font.
 - The report should be at least 5 pages for an individual, or 8 pages for a pair.
 - Students are encouraged to use \LaTeX. The IEEE provides good templates here: [http://www.ieee.org/conferences_events/conferences/publishing/templates.html](http://www.ieee.org/conferences_events/conferences/publishing/templates.html). 

### Submission
 - The proposal will be submitted to BlackBoard by the deadline as simple text.
 - The completed report will be submitted to BlackBoard by the deadline as a PDF.

## Grading
Overall, this project will be worth 5% of the semester grade (as per the syllabus).

The grading rubric will be:

 - 5% - Proposal
 - 10% - Formatting (Following instructions)
 - 20% - Structure/Coherency - Does the paper follow a comprehensible pattern?  Is the flow of thought easy to follow?
 - 65% - Content - Is the content correct?  Is the topic clearly explained, and the findings clearly detailed?  Do the students show that they have gained a reasonable understanding of the topic?

Additionally, a **2% Bonus** will be awarded for each week early the project is turned in.  For instance, turning the project in by April 11th will be worth an extra 4%.

## Suggested Topics
There are a number of topics to choose from.
The purpose of the proposal is to ensure that your topic is neither too difficult nor too easy.

The following is a list of possible topics.  You can certainly choose something not lited here.

 - Monolithic versus microkernel operating systems.
 - Scheduling algorithms: which are actually used in modern OSes?
 - Memory issues: how caching is implemented
 - File Systems: which ones are used?
 - Process Creation: How does the `do_fork()` function actually work?
 - Kernel modules: how are they created and used by a kernel
 - Any kernel subsystem: what does it do, how does it work?
 - Anything from: [https://www.apple.com/osx/advanced-technologies/](https://www.apple.com/osx/advanced-technologies/)

The focus of your study should be on practical issues, not theoretical.

## Additional Option - Working with Kernel Code
As another option to complete the objective of the project, students may modify existing Linux Kernel code in a productive manner.
For instance, you may choose to implement some new feature or fix an existing but in the current kernel.
For some help getting started, you might check out: [http://kernelnewbies.org/](http://kernelnewbies.org/).

If you choose this option, please submit your changed code:

 - Mention the kernel used as a base
 - Include the whole source files which you modified
 - Include a diff/patch of your changes (git works great)
 
For a report, include an introduction/background/conclusion (why your changes are important).
The bulk of the report should also describe the changes you made.
The page count for these reports should be 3 pages (solo) and 6 pages (pair).

Grading will be slightly altered from the above rubric, with most of the content score going toward the code.


