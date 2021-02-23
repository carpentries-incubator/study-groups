# The Carpentries Lesson Development Study Groups Notes

## Group 4: Friday 19 February 2021 23:00-00:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Kate Hertweck / perceived pronouns / k8hertweck / facilitator
- Jon Wheeler / he/him / jonathanwheeler01 / https://github.com/carpentries-incubator/data-management-pipelines-engineering
- Yuka Takemon / she/her / ytakemon / facilitator
- Fan Du / she/her / caifand / [Lesson Design Notes](https://codimd.carpentries.org/3_0Znrp-SQmLAjx_HGLjWw?both)
- James Foster / he/him / jd-foster / [Lesson Repository](https://github.com/carpentries-incubator/julia-data-workflow/) / [Lesson Design Notes](https://codimd.carpentries.org/IMY4Cu3ZR6Oabrr87ZV6XQ?both)
- Tim Dennis / he/him / jt14den / facilitator Tim
- Alex Casper Cline / he/him / alexcasper / [notes](https://codimd.carpentries.org/03Wg6JS6S2qP4bpTpjt4WQ?edit)


## Roles

**Group Facilitator(s)**: Kate Hertweck, Tim Dennis
**Discussion Lead**: James Foster
**Notetaker**: Jon Wheeler

## Agenda

Instructions for registering an account on this CodiMD server:
    - "log in" with your preferred username and password - this will create your account
    - you can then log in again with these credentials
1. Welcome & Icebreaker 
    - Coffee or tea, and how do you take it? If neither, preferred beverage?
        - Jon: Coffee black.
        - Kate: coffee, with peppermint mocha creamer
        - James: Coffee in the morning (milk not sugar), tea in the afternoon (also milk no sugar).
        - Fan: Black coffee all day 
        - Yuka: Coffee black always
        - Tim: Coffee b/f noon, tea in the afternoon, coffee with oatmilk, tea with nothing 
        -  Rhonda: Coffee (black, no sugar)
        -  Alex Casper (should say tea as I'm in the UK, but I prefer terrible instant coffee)

2. Welcome to Tim Dennis, UCLA. Library data science center, support for reseachers doing data intensive work. Maintainer of Library Carpentry lessons (shell, R).

3. Identifying the audience discussion
    * Learner profiles, the range of experiences that people bring.
    * Three parts to thinking about learners
        * Target audience
        * Skills
        * Developing learner profiles
    * Challenges to writing learner profiles? Understanding what learners want or need. Or, challenges we have faced as teachers and learners?
        * Difficult subject areas - physics for example
        * RNA sequencing - actually matching learner profiles to expectations of audience; working with/within mindset of stakeholders
        * How to frame and narrow down the lesson?
        * Working with some colleagues: after receiving data dump, determining how to teach statistical modeling: sometimes coworkers have great ideas! Challenge is in getting stakeholder involvement to connect content to skills
        * Data/code publishing and citation - imagining the kinds of use scenarios the learners are likely to face/engage with. When there is a real life need to address, that can provide an understanding of entry points for designing material
        * Defining scope for curriculum - the learner profile is a scoping tool; scope can change
        * Utility of an anti-learner profile? That is, people who are not part of the audience - they may already know or have a skill; helps to narrow question when we may not know who the audience is to think about who it is not
        * Challenging to design things for others than ourselves, and also to design for tools other than the ones we are familiar with.
        * Developing RDBMS for geneaologists and offering it as a service with 1:1 consultation - people may be experts in the subject area and need help organizing data, visualizing. User could be a generalist and/or comfortable with technology and creating data out of text.
            * This is a specific interest/outcome but the backgrounds of the users/learners are broad
        * How many learner profiles? Good to have multiple. Different profiles will align with different parts and aspects of the lesson. Develop strategies within the lesson to accommodate those different levels and outcomes.
        * Where are lessons aimed at - novices? Domain specialists who are technical novices? Thoughts:
            * Jon: technical novices, STEM undergrads (3rd or 4th year) for this particular lesson

            * James: technical novices, some university learning experience
            * Casper : With this lesson, I'd say upper intermediates who've done Software Carpentry or have some programming experience. Would like to develop some more introductory lessons later, but think that would be a bigger project
            * Kate: researchers who are already experts at working in a wet lab, clinic, or with computation, but haven't worked with genomic data. They may have minimal experience with coding, and probably not any experience with research software engineering
            * Tim: librarians who have to clean library data (bibliograhic stuff, usage stats, etc.) and want to also make some graphs. For the R lesson, we think they'll be novices who understand the domain and how to use excel to tasks manually but the goal will to teach them how to more programmatic & less manual processes. 
            * Rhonda:high school and undergrads, experienced genealogists, community organizations. Limited programming experience
            * Fan: researchers who hope to publish their software, or have the needs to release their software. They may be working at different skill levels in terms of programming.


        * Defining/finding a balance between the technical and conceptual outcomes/skills. Learner profiles can be targeted at different points of these dual hierarchies.
        * Challenge of writing lessons that target a broad range of learners. Traditionally SWC targets novice programmers while DC targets domain specialists.
        * Difficult to answer question about the pain points.
        * Learners may only want to learn one thing - difficult to manage expectations around other (necessary) concepts/skills.
            * How you advertise your course can help to manage expectations. Target learners who may benefit the most.
            * Identify loose prerequisites, point to other workshops or resources that may be helpful
        * Profile examples:
            * Fan: https://codimd.carpentries.org/3_0Znrp-SQmLAjx_HGLjWw?both#
            * James: https://codimd.carpentries.org/IMY4Cu3ZR6Oabrr87ZV6XQ?both#
            * Jonathan: https://github.com/nmcarpentries/lesson_design
            * Kate: https://github.com/fredhutchio/rnaseq/blob/gh-pages/instructors.md
            * Tim: https://github.com/LibraryCarpentry/lc-overview/blob/gh-pages/files/learner-profiles.md
        * Identifying skills that surface in learner profiles is a challenge. Concrete goals that learners will take from the lesson.
        * Jonathan: dealing with pandemic (which challenges infrastructure) means needing to include these considerations in learner profiles. How do you do technical work without strong technical infrastructure?
        * Challenge of choosing a topic in terms of difficulty - developing a lesson is a good way to reinforce and consolidate understanding.
            * Helpful to look at the other lessons in the incubator to find similar, aligned topics.
        * Profiles make good documentation for assessing lesson development and actual outcomes. We will be teaching our lessons, so we'll have a chance to revisit our profiles based on experience.


3. Housekeeping

    * Some have reported issues creating an account with CodiMD. Create an account at https://codimd.carpentries.org/. Instructions provided above.
        * Necessary to have an account for pushing notes to GitHub when it's each persons' turn to take notes and publish.
    * Process of setting up a lesson template is another challenge to address. More info on this next week.

- Homework:
  - Read the [Technological Introductions chapter of the CDH](https://cdh.carpentries.org/technological-introductions.html) and follow the steps to set up your repository as described in the template README file.
  - Read [section A.2 of CDH Appendix A: The Carpentries Incubator](https://cdh.carpentries.org/the-carpentries-incubator.html), and add topics to your lesson repository. (If you cannot add the complete set of topic tags yet, do not worry: you will be able to add more and remove topics whenever you like.)
  - Note down any questions you have about the lesson template and, if you got stuck, how far you had progressed with the setup beforehand.
  - Add a link to your lesson repository to the Study Group’s shared notes (this) document.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/DCMSDeWCxwU45Q246
