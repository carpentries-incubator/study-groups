# The Carpentries Lesson Development Study Groups Notes

## Group 4: Friday 26 February 2021 23:00-00:00 UTC


This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Kate Hertweck / perceived pronouns / k8hertweck / facilitator
- Jon Wheeler / he/him/ jonathanwheeler01 / https://github.com/carpentries-incubator/data-management-pipelines-engineering
- Fan Du / she/her / caifand / https://github.com/carpentries-incubator/citable-software
- Tim Dennis / he-him / jt14den / facilitator 
- Alex Casper Cline / he/him / alexcasper
- 
- 
- _Absent apology_: James Foster (see you next week!)
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Kate
**Discussion Lead**: Fan Du
**Notetaker**: Kate

## Agenda

1. Welcome & Icebreaker 
    - (Need an idea for an icebreaker question? Check out [the list of icebreakers from the Instructor Training curriculum](https://carpentries.github.io/instructor-training/icebreakers/index.html).)
    - Today's icebreaker: Cat or dog? Do you live with them? Or some other living creatures you live with or prefer?
        - Fan: Dreaming of a chicken coop
        - Jon: Cats and dogs, have two dogs now and a lizard. Had cats in the past.
        - Tim: We lost our cat over the winter break :(

2. Week 3 Discussion Agenda: Lesson Infrastructure
    - This week is very technical, so our discussion will be focused on problem solving
    1. Have you set up your lesson repository? Any issues/challenges/questions?
        - repositories have been created!
        - the process seems opaque, and very complex
        - review checklist below to get started modifying your template
    3. Lesson Template Checklist:
        * Lesson homepage
        * Episodes
            * Introduction
            * Motivating questions
            * Learning objectives
            * Key points
        * Extras
            * Reference
            * Setup
            * Instructor's Guide
        * Things we can move around:
            * Timing assignment for episodes
            * Code blocks
            * Pop-ups: Callouts, Challenges, Discussion questions, Challenge solutions.
        * Don't forget to set up:
            * `_config.yml`
            * `CONTRIBUTING.md`
            * `CITATION` file
            * `AUTHORS` file
    4. Technical setup: 
    - walk through of making first edits to lesson template (config, README, AUTHORS)
    - what are the other files we'll be modifying most often? episodes!
        * Use Markdown/RMarkdown to develop your content 
            * Which one do you prefer?
        * Use GitHub to share and synchronize your course content, and to contribute to others' Lessons
        * Install Jekyll & Ruby on your computer
        * **Discussion Question**: What do you find most confusing about Markdown/GitHub/Jekyll/Lesson Template?
    5. **Reflection moment** (Type your response :smiley:)
        * What surprised you so far?
        * What do you find challenging?
    6. Hang around the Carpentries Incubator
        * On GitHub: The [carpentries-incubator/proposals](https://github.com/carpentries-incubator/proposals/) repository
        * On the Carpentries website: [Community Developed Lessons](https://carpentries.org/community-lessons/)
        [Lesson topic tags](https://docs.google.com/spreadsheets/d/1KkmBtCu4PaNb5nzJAD82UHcfHQlaPY84qPVxw8WO8es/edit#gid=1895634731)
    1. Maintaining and contributing to Lesson repositories
        * Label issues or help with labeled issues
        [How to label issues](https://docs.carpentries.org/topic_folders/maintainers/github_labels.html)
        [`help wanted` issues in the Carpentries Lesson repositories](https://carpentries.org/help-wanted-issues/#for-maintainers)
        [Make your repository visible on the Carpentries website](https://carpentries.org/help-wanted-issues/#for-maintainers)
        * **Discussion Question 1**: What are the potential benefits and downsides of having your lesson listed on the Community Developed Lesson page at this early stage of development?
            - good to have lessons there, encourages adding more content to materials!
            - peer review is good, but it can be confusing when there's not a lot of content already included
            - see incubator: lots of other repos from new lessons!
            - being able to track evidence of work put into lessons
            - a sweet spot for people to be able to make meaningful contributions
            - be able to look into other lessons and learn things
        * **Discussion Question 2**: What topic tag(s) do you add/plan to add to your lesson?

3. Housekeeping notes
    - Useful links
    [Lesson Template](https://carpentries.github.io/lesson-example/setup.html)
    [Lesson example](https://carpentries.github.io/lesson-example/)
    [Markdown help](https://commonmark.org/help/)
    [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
    [GitHub flow](https://guides.github.com/introduction/flow/)
    [CodiMD Intro](https://codimd.carpentries.org/features)
    [Role rotating schedule](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing)

4. Homework (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
    - (ALL) Read [the Working with Learning Objectives section of The Carpentries Instructor Training Curriculum](https://carpentries.github.io/instructor-training/15-lesson-study/index.html#working-with-learning-objectives).
    - (ALL) Read [the Learning Objectives section of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:process-objectives).
    - (ALL) Read the [Concept Maps](http://teachtogether.tech/en/index.html#s:memory-concept-maps) and [Seven Plus or Minus Two](http://teachtogether.tech/en/index.html#s:memory-seven-plus-or-minus) sections of Teaching Tech Together.
    - (ALL) In your Lesson Design Notes, write 2-5 learning objectives for your lesson.
    - (ALL) Create at least one episode file in your lesson repository and add 2-4 learning objectives in the objectives field for that episode.
    - (ALL, optional but recommended) [Set up your computer to build lesson pages locally](https://carpentries.github.io/lesson-example/setup.html#setup-for-local-rendering-of-the-lessons-optional).
        _Note: setting up a local installation of Jekyll is often not straightforward, but is important to ensure you can make good progress with the development of your lesson. If you run into trouble when following the instructions linked above, please post to the lesson-development Slack channel, create an issue on your lesson repository and mention @tobyhodges, email Toby directly, or attend one of the Lesson Template Helpdesk sessions._

- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- https://carpentries-incubator.github.io/jekyll-pages-novice/ SO META!

[sticky-notes-link]: https://forms.gle/DCMSDeWCxwU45Q246