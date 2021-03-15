# The Carpentries Lesson Development Study Groups Notes

## Group 4: Friday 5 March 2021 23:00-00:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)
1. ["Index" CodiMD for this round](https://codimd.carpentries.org/ldsg1-home#)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Rhonda Jones/lovelybrown
- Jon Wheeler / he/him / jonathanwheeler01 / https://github.com/carpentries-incubator/data-management-pipelines-engineering
- James Foster / he/him / jd-foster / https://github.com/carpentries-incubator/julia-data-workflow/
- Fan Du /she/her / caifand / https://github.com/carpentries-incubator/citable-software
- Alex Casper Cline / he/him /alexcasper
- Yuka Takemon / she/her / ytakemon /
- Kate Hertweck / perceived pronouns / k8hertweck
- Tim Dennis / he/him / jt14den
-
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Tim Dennis, Kate Hertweck, Yuka Takemon
**Discussion Lead**: Rhonda Jones
**Notetaker**: James Foster

## Agenda

1. Welcome & Icebreaker
    - (Need an idea for an icebreaker question? Check out [the list of icebreakers from the Instructor Training curriculum](https://carpentries.github.io/instructor-training/icebreakers/index.html).)



2. What are described as _learning objectives_ in the reading material are sometimes referred to as _learning outcomes_ elsewhere in the literature. Do you prefer one of these terms to the other? Do you think either term is more appropriate to describe the skills a lesson/episode will teach? If so, why?
    - (**note to host: please include this question for discussion** - it will help us decide what changes to make while updating the Instructor Training curriculum. You don't need to devote a lot of time to discussing this, but it would be really helpful to get the thoughts of the participants.)

## Reflection by Rhonda Jones on "Defining Objectives" episode
Chapter 4, designing challenges focuses on the second step of backward design - designing the challenges that l’ll use to help my learners develop these skills. These challenges will also enable me to evaluate my audiences’ skill progression

I'd like to present my lesson, *Designing Relational Databases* at a conference or workshop for genealogists to record, maintain, and query family history.  I intend to use Google Sheets, instead of Excel and SQL. I'm not sure if it would be better to use R or Python.  The tools will operate on multiple platforms (Mac/Windows/Chromebook), and the visualizations will be viewable on laptops, mobile devices, & smartphones.

Use a learner profile to think about someone likely to attend a workshop you will teach.
>Bernice Bennett is a genealogist, nationally recognized speaker, storyteller, and an award-winning author of two publications, Tracing Their Steps: A Memoir and Our Ancestors: Our Stories.  Currently living outside of Washington, D.C. Bernice, a retiree from a 35-year career in domestic and international public health, now works as a research consultant for hire.  Bernice is moderately tech savvy.  Over ten years ago, she created a BlogTalk Radio show entitled, Research at the National Archives and Beyond.  The site focuses on helping individuals interested in history and genealogy to learn about available resources and how to take action.  Bernice also offers consulting services that include: coaching on conducting oral history, maps out strategies for research plan, retrieves records at the National Archives, facilitates group meetings, and offers keynote addresses that target her clients specific needs.  A frequent conference attendee, she is and actively posts on FaceBook and Twitter.  Other target audience members include students, scholars, librarians, archivists, and other researchers engaged in family history and genealogy.

Skill Level:
Beginner.  There are no pre-requisites, attendees do not need to have prior knowledge about digital tools.  Participants will not be taught how to write code or record statistics

Learning objective:
Referencing Bloom’s taxonomy the learning objective is to understand how information is handled and formatted in spreadsheets

I found two similar carpentries lessons, “From a Spreadsheet to a Database” and “sedelmeyer/family-genealogy-database”
•	The lesson’s learning objective focused on using SQL code to create a relational database used to record, maintain, query, and report on personal family genealogical data

I'm in the processing of creating a dataset that has at about 75 rows

Introduction:
Begin with an explanation that a relational database organizes data in tables (or relations). That each table is made up of rows and columns. A row is also called a record (or tuple). A column is also called a field (or attribute). A database table is similar to a spreadsheet. However, the relationships that can be created among the tables enable a relational database to efficiently store huge amount of data, and effectively retrieve selected data.

Step 1: define the purpose of the database
The lesson uses google spreadsheets to design data tables.  I would begin by asking how many people have used spreadsheets in their research?  I would then explain why spreadsheets are useful:
•	data entry
•	organizing data
•	sorting data
Step 2: Gather and organize the data into subject-based tables
Explain that a relational database organizes data in tables that consist of rows (record), columns (field), and cells (value).  The relationships that can be created among the tables enable a relational database to efficiently store huge amount of data, and effectively retrieve selected data.

Choose a single column as the primary key that uniquely identifies each row of the table.  For example, each persons’ name (lastname, firstname) will be assigned a unique number ID as the primary key

Step 3: Create relationships
The power of relational database lies in the relationship that can be defined between tables. The most crucial aspect in designing a relational database is to identify the relationships among tables. 3 3 types of relationships:
•	one-to-many (spouse to spouse; parent child; parent to siblings)
•	many-to-many (each person can have many relatives and also be a relative of many people)
•	one-to-one (parent to child)

Understanding the benefit of good data entry practices:
•	How to structure data cells with relevant information connected to it
•	Common formatting mistakes
•	Basic quality control and data manipulation in spreadsheets
•	Exporting data from spreadsheets
•	Demonstrate how the data cells relate to the relevant information and each other.

By the end of the lesson participants will learn:
•	How to enter variables into columns
•	How to enter observations into its own row
•	How to export the information into a text-based format like CSV.

I'm having an issue with the use of concept maps in the content of the lesson.  I think an explanation of relationships is more effective

Having never created a dataset where I've actually run a query I think it will be difficult to explain how to format the dates as data and making sure I have a well-structured data table that is free of errors. My dataset was incorrect when I entered month and year in one column. I had to make the following corrections: SON-1
SON-2
Daughter-1
Daughter-2
Person ID | FIRSTNAME | LASTNAME
*I would be leery about exporting the database in the workshop.*

## Study Group discussion notes
Initial discussion by Rhonda: objectives for her lesson
-  creating a relational database system that ties into a genealogical research community
-  taking inspiration from conversations with others in the field
-  focussed on the importance of a clean dataset, free of errors
-  accessible and open-source via Carpentries
-  found examples/models in similar lessons
    -  family genealogy related
-  encouraging participatory and community based projects
-  asking questions around how one would encode the complexity of genealogical data into an accessible format
    -  e.g parents and siblings
        -  many-to-one or one-to-one
-  moving forward through trial-and-error in dataset design
-  looking for a programming based solution
-  some of the objective-design tools like multiple choice might not apply in this context
-  keeping the audience in mind while working through the content
-  reflected that it is important to have _working_ queries when presenting to an audience of learners
    - e.g. sorting and querying demonstrations
-  What would the novice want to know or need to know?
-  relation to Bloom's taxononomy
-  enabling a deeper dive into quantity and diversity of the data


- appreciation of the write-up
- Shared link: [Data Science Concept Map](https://docs.google.com/presentation/d/1ForBjP0pVhljBLuqOyYfyHw_1rrwJzpWW1ZHzCqAJpU/edit#slide=id.g8a909fde4e_0_117)
    - compiled by Greg Wilson to help with designing lessons for learners

Question: when discussing lesson design, what is the essential objective are we looking to teach?
- what parts of the lesson description are able to be used to narrow down to a specific objective?
    - For example, learning to read, clean and organise genealogical data; or to go further, utilise the data to map out specific relationships or generate insights between the data-sets.
- Important to the audience to be able to see the concrete outcomes of the lesson
- Backwards-design keeps us honest so participants will get what they expect from the lesson description.
- Alex: Scoping the lesson through this process gave the insight of "biting off more than I can chew". Really defining the concepts succinctly helps.
    - We're not necessarily aiming to get participants to the top of the Bloom hierarchy, but providing an entry point.
    - While we may not need to go further than a developer focussed aspects, the hope is that they will have enough knowledge to go on and share that knowledge in places where they work/participate.

- Jon: Asking questions around the relevance of the concepts to a specific audience (engineering students)
    - Kate: It can be trickier to be constrained by specific audiences, on th other hand it might be helpful to have a well-defined group (compare to the broad expected background in biology etc.)
- Fan Du : spent time exploring Data Carpentry lessons to get a handle on the design
    - Learner profiles led to the realisation that there are more things that could be taught
    - This leads to the question to how we might set up the timeline of the episodes and lessons.
- Kate: timing is often (poorly) determined by e.g. 14 weeks of instruction. At one end of the spectrum is looking to teach a compartmentalised piece of work, while others are looking across a broader set of objectives.
- James: middle of spectrum bewteen comparmentalized, small segments relevant for large audiences, and a small, specific audience with wide-ranging objectives
    - need to generate data and start using it with more specialized scientific software
    - thinking about general materials early, and more specific modules later
- Fan: interesting to think about how to approach Julia as a software solution
- James: language doesn't matter so much when considering larger lessons about coding or performing data analysis. How could a question be expressed independently of the language?
- Kate: choose an early part of the lesson and dig down deeply, while tabling all those other thoughts and ideas about the other parts of the lesson.
- Rhonda: there is a concern about how long the development of the lesson or initial episode will take; is there a particular forum/conference that it could be ready by?
- Alex: this study group process has helped to motivate the development process.
- Kate: for next week, what is needed to get learning objectives well-defined and start moving onto initial episode development?
- Group accountability and making progress are more important that pressuring ourselves to make hard deadlines and trying to manage technical parts
    - lesson repositories in the incubator hold us accountable

- Alex: there is a paralysing aspect to putting out your work publically, including on the Carpentries Incubator, despite agreeing that sharing knowledge publically is a good thing (encouraging students to do so, for example).
- Question: how to use community support for recruiting participants for trialling lessons/episodes?
    - There are resources through Carpentries, including contacting Toby Hodges with a week's notice.
- Jon: often software/data download and setup can be a barrier to getting a lesson started. There is a place for teaching a component with the setup already assumed to be completed.
    - Yuka: this setup aspect is an important part of testing out a lesson and worthwhile to test in "the wild" as integral to the development.
- Kate: it's a tall order to go from workshop inception to teaching a pilot lesson in only a few weeks (e.g., the duration of this study group), but it's also not a ton of material you're expected to teach. This is giving you some space to gain feedback from other folks about your objectives, framing the workshop, and considering how to set up a narrative.
    - also consider leveraging the Study Group office hours to get assistance with whatever logistical help might be useful
- Yuka: keep in mind that the part of the lesson you teach might be dependent on a previous set of knowledge components introduced in earlier episodes; the timing of the whole is then necessary to take into account.


Question to the group
How challenging did you find it to define specific learning objectives for your lesson?


- homework (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
    - (ONE, but discuss with your collaborators first) Create placeholder files for the other episodes in your lesson. Optionally, add learning objectives to these episode files too.
    - (ALL, see link for more info) Schedule an opportunity to teach at least one episode of your new lesson. This trial run should take place between sessions 7 and 8 (26 March 2021 - 9 April 2021). See the info box below for more details.
        - When you have scheduled your trial run, add details to this CodiMD: https://codimd.carpentries.org/ldsg1-trial-runs
    - (ALL) Read [Chapter 4: Designing Challenges of the Curriculum Development Handbook](https://cdh.carpentries.org/designing-challenges.html).
    - (ONE, but discuss with your collaborators first) If your lesson will use an example dataset, in the Data Set section of your Lesson Design Notes briefly describe the features and requirements an ideal dataset would have.
    - (ALL) Identify at least one appropriate example data set/narrative for your lesson, and add a link to the data set in the shared notes document.
    - (ALL) In the Data Set section of your Lesson Design Notes, briefly summarise:
        - why you chose these datasets/examples,
        - what advantages they have as a tool for learning,
        - and what disadvantages/difficulties/complexities they would introduce.

### Trial Run info
::: info
**Why?**
- We include a Trial Run task in the Lesson Development Study Groups program because **teaching content for the first time is not the end of the lesson development process** - it is an important step along the way.

**When?**
- Trial Runs for this round should take place **after your Group Discussion in the week of 22-27 March and before your Discussion in the week of 5-10 April**. (If you cannot schedule the Trial Run in these dates, contact Toby to discuss alternatives.)
- These trial run sessions are expected to take **no more than 60 minutes per episode**.

**What?**
- Think about the dependencies of your episode: **it might be better to trial an episode early in your lesson**, so that your audience do not need to already know what would have been taught earlier.

**How?**
- Your Trial Run can be private (i.e. audience attends by invitation only), open for anyone to register, or anything in between - just make sure you have an audience who can give you feedback on the lesson! You might consider asking for volunteers from your Study Group, or colleagues that you know would have the relevant experience to follow your lesson.
- If you need access to a paid Zoom account for your Trial Run, contact Toby. He can provide you with one of The Carpentries Zoom rooms. He can also help you advertise your trial run, list it on The Carpentries Community Calendar, etc if you want to open up your Trial Run. -> How much lead time is necessary for this?
- Think about the **Code of Conduct** you will follow for your Trial Run - if you do not have your own (e.g. for teaching colleagues at your institution), you can treat the Trial Run as an extension of this Study groups program and use [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html).
- However you choose to do it, please **list the date/time of your Trial Run on https://codimd.carpentries.org/ldsg1-trial-runs when you have scheduled it**.

**For collaborative lessons**
- Where multiple participants are collaborating on a single lesson, each Study Groups participant should **teach one episode of that lesson each** during the Trial Run. Schedules permitting, you should schedule to teach these trial runs together.

Trial Runs are also described in [the Episode Trial Run callout on the "lesson" page](https://carpentries-incubator.github.io/study-groups/04-objectives/#episode-trial-run).
:::

### Feedback

- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [Palladio historic data visualization tool (Stanford)](https://hdlab.stanford.edu/palladio/)
-
-

[sticky-notes-link]: https://forms.gle/2KTkPwqFxdCxFEVC6
