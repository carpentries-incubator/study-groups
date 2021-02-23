# The Carpentries Lesson Development Study Groups Notes

## Group 1: Monday 22 February 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Batool Almarzouq / she, her / [BatoolMM](https://github.com/BatoolMM).
- Jonathan Pelham / jonititan  / [Python EOFDM Precursors](https://github.com/carpentries-incubator/python-EOFDM-precursors)
- Aleks Nenadic/ she, her/ gh: anenadic (apologies - will be ~30 minutes late - coming from another meeting)
- Mike Trizna, he/him/his, MikeTrizna, https://github.com/carpentries-incubator/machine-learning-librarians-archivists
- Mateusz Kuzak / he, him / 
- Mark Bell, he/him, mark-bell-tna
- Daniel van Stirn, he/him, davanstrien
- Shrirang Kulkarni/he,him
-Elnaz Amanzadeh / She/her
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Toby Hodges, Mateusz Kuzak, Aleksandra Nenadic, Serah Rono
**Discussion Lead**: Batool Almarzouq
**Notetaker**: Mark Bell

## Agenda

1. Welcome & Icebreaker 
    - If you could have the power of teleportation right now, where would you go and why?
    -Mateusz: Scotland
    -Shrirang: A carpentry workshop on machine   
    learning in future.
    -Joni: The beach with family
    -Mike: New Zealand

- Can you add a link to your lesson repository in  this shared notes document?
    - Batool, https://github.com/BatoolMM/scRNA-seq/tree/gh-pages
    - Daniel, Mike, Mark, Nora https://github.com/carpentries-incubator/machine-learning-librarians-archivists
    - [Python EOFDM Precursors](https://github.com/carpentries-incubator/python-EOFDM-precursors)
    - 
    - 




- Follow up on last week's homework assignments, What questions do you have after setting up/trying to set up your lesson repository?

    Mike - issues related to Conda installation. De-activating helped solve the problem.
    Batool - working on a new build but still had lots of errors.
    Joni - ruby version higher than available from Mint package manager.  Edited config file to avoid installing ruby seperatly.
    
    - Did you freakout when GHA failed?


    - Did you have an error with `webrick (LoadError)` or with `make serve` or `make check`

    - Do you know why you should not commit the generated HTML files in the `_site` directory? Are we suppose to add it `.gitignore`? 



-  If you could make any improvement to the documentation? What would that be? Think about the most confusing part in the process?

Daniel - possible use of GA to open issues for steps that need to be done to setup a fresh clone of a lesson template
Mateusz - I tend to spend a lot of time getting it to work, then start on another project a couple months later and struggle with the same things all over again
Joni - when writing documentation and lessons it is important to try to avoid "hard-coding" anything relating to information that can change over time and which is used in multiple places - you will need to go manually update these every time something changes.  e.g. version/date

- Was the difference between theses two templates clear? https://github.com/carpentries/styles
https://github.com/carpentries/workshop-template
Mateuz: Briefed about his experiences of workshop template; which is used to set workshop pages; lesson template for setting up lessons and styles for how lessons could look.
Toby: as well as the styles repository, there is the template specific to the Carpentries Incubator- includes a readme file intended to be a good starting point.

Mike: it is better now with the workshop template using being a "template" not having to use the important

Elnaz: I have been keeping track of the stesp I have been taking to set up the local builds. It would be really helpful to see a list of issues others have encountered in the past and how they solved them.

- What are some of the potential benefits of your lesson being listed on the Community Developed Lessons page (https://carpentries.org/community-lessons) at this early stage of development?
Daniel: a lot of discussion around the topic of ML in libraries/archives. Good to let community know it is being worked on.
Joni: Peer pressure to keep working at the repository, so it doesn't get forgotten due to day job.
Shrirang: early comments from community can help, even number of comments indicates popularity.


- What are some of the potential downsides of this?
Toby: adding to list makes it public to large community. Habit of not completing, so then it is out there as a half finished bit of work. But flip side is collaborators can help complete it. [Lost connection again, so missed the rest]


- What topics did you choose to add to your lesson repository? Did you use a strategy to decide what these topics should be?
Toby: add topic tags to repository was homework. Makes them more findable.
Batool: what about design of tags in relation to what we are teaching?
Mateusz: Thinking of and choosing keywords is the hard part.
Shrirang: have a peer discussion with other lesson developers to identify keywords which are most interesting.
Toby: look at topics already being used - think of international spelling variations. Should you use both US/UK spellings to 'double' audience?
Tip - adding topics to your repository also has the advantage that you/others can search for all topics in Github as they're not necessarily in the incubator.

- homework:
    - Read [the Working with Learning Objectives section of The Carpentries Instructor Training Curriculum](https://carpentries.github.io/instructor-training/15-lesson-study/index.html#working-with-learning-objectives).
    - Read [the Learning Objectives section of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:process-objectives).
    - Read the [Concept Maps](http://teachtogether.tech/en/index.html#s:memory-concept-maps) and [Seven Plus or Minus Two](http://teachtogether.tech/en/index.html#s:memory-seven-plus-or-minus) sections of Teaching Tech Together.
    - In your Lesson Design Notes, write 2-5 learning objectives for your lesson.
    - Create at least one episode file in your lesson repository and add 2-4 learning objectives in the objectives field for that episode.
    - (optional but recommended) [Set up your computer to build lesson pages locally](https://carpentries.github.io/lesson-example/setup.html#setup-for-local-rendering-of-the-lessons-optional).
        _Note: setting up a local installation of Jekyll is often not straightforward, but is important to ensure you can make good progress with the development of your lesson. If you run into trouble when following the instructions linked above, please post to the lesson-development Slack channel, create an issue on your lesson repository and mention @tobyhodges, email Toby directly, or attend one of the Lesson Template Helpdesk sessions._

- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [Software Carpentry: lessons learned [version 2; peer review: 3 approved]](https://f1000research.com/articles/3-62/v2#d24110e4249)
- You may find [GitPod](https://www.gitpod.io/about/) useful to provide a cloud-based alternative to the local Jekyll environment setup.
    - see this repository for an example: https://github.com/carpentries-incubator/jekyll-pages-novice
    - the configuration of GitPod is done in these two files:
        - https://github.com/carpentries-incubator/jekyll-pages-novice/blob/gh-pages/.gitpod.Dockerfile
        - https://github.com/carpentries-incubator/jekyll-pages-novice/blob/gh-pages/.gitpod.yml
- Citing software?  https://escience-academy.github.io/lesson-FAIR-software/04-citation/index.html Is this compatible with Carpentries due to CITATION vs CITATION.cff naming schemes?
- Carpentry lessons list https://carpentries.org/community-lessons/

[sticky-notes-link]: https://forms.gle/wZDMRJbbXgyXJTJs8