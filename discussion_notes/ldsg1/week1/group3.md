# The Carpentries Lesson Development Study Groups Notes 
## Group 3: Friday 12 February 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Serah Rono / she, her, hers / serahrono /
- Annajiat Alim Rasel / he, him, his / annajiat / 
- Richard Ostler / he/him / richardostler
- Graeme Grimes / he/him  / ggrimes / https://github.com/carpentries-incubator/workflows-nextflow
- Alessio Sclocco / he,him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Sarah Stevens / she/her/hers / sstevens2 / https://github.com/carpentries-incubator/docker-introduction
- Aleksandra Nenadic / she, her / anenadic / https://github.com/carpentries-incubator/jekyll-pages-novice
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Martino Sorbaro / he, him / martinosorb
- Hanno Spreeuw/ he, him / HannoSpreeuw
(add more lines as needed)

## Roles

Group Facilitator(s):  Serah Njambi Rono, Sarah Stevens, Aleksandra Nenadic, Toby Hodges
Discussion Lead: Toby Hodges
Notetaker: Serah Njambi Rono, Sarah Stevens



## Agenda

1. Welcome & Icebreaker 
    - Please sign in by adding your details to the *Participants* section above.
    - (verbal) Group Facilitator introductions
        - who you are
        - where you are
        - previous experience with lesson development and The Carpentries lesson template
        - Facilitators ( have experience with the Carpentries lesson template and in developing lessons): 
            - Toby Hodges, curriculum development community developer, overseer of these study groups. In this call, we will cover logistics, and take any questions to clarify how the study groups will work. This is the third meeting this week. There are four separate study groups
            - Serah Rono, calling from Tallinn, Estonia. Director of Community Development and Engagement at The Carpentries. Used the lesson template when developing material for [the Community Facilitators Program](https://carpentries.github.io/community-facilitators-program/). Program set up to prepare and train community members to take on leadership roles within the community.
            - Sarah Stevens (she/her/hers) from the University of Madison. Has several lessons in development - text analysis in Python, Docker, Jekyll and others.
            - Aleks Nenadic from SSI in the UK, Carpentries Instructor Trainer, collaborated with Toby and Sarah on lesson development in the recent past
     - (verbal) Participant introductions
        - who you are
        - where you are
        - about the lesson you will be developing during the program - what is it about? who is it for?
        - previous experience (if any) with lesson development and The Carpentries lesson template
            -  Annajiat, lecturer, part of community facilitators program as a feedback facilitator, maintainer for the python for social science lesson, not much experience with the lesson template but sometimes have used it and am learning, would like to make a java based lesson
            -  Richard, UK agricultural research, data science team, bioinformatics/stats courses for phd students, based on ecological DC, would like to embrace carpentries style, lesson on [frictionless data](https://frictionlessdata.io).
            -  Graeme,  bioinformatician, Carpentries trained instructor, organize the new Phd Intake program, running several carpentries courses, creating lesson bioinfomratics workflows with nextflow in genomics, extends unix scripting to make it reuseable, benefits of nextflow is there is a big community and lots of training and there are people who would be interested in contributing
            -  Alessio, netherlands escience, phd in comp sci, hpc pilot program, been teaching gpu programming for 8-9 years, last year decided to start dev materials in carpentries style and started gpu lesson but overwhelmed, then learned about this group and joined to learn how to do it better
            -   Bailey, currently transition from phd to postdoc, Edinburgh workshops organizing and teaching, lesson on typesetting in latex, geared towards beginners and going to a mid-level; some experience working with the lesson template by contributing to existing lessons, but not so much actual lesson development itself.
            -   Martino, currently postdoc in Zürich, used to be at Edinburgh, carpentries instructor, recently jumped into developing latex lesson with Bailey, orginally at UK carpentries meeting was interested in Machine Learning Lesson development which is becoming more active and would like to contribute to that.
            -   Hanno, astronomer and colleague of Alessio at the Netherlands escience institute, background in efficient computing from previous employer, the netherlands cancer institute


2. Housekeeping notes
    - **Introduction to CodiMD - https://codimd.carpentries.org/features**. You likely will not need all the features described, but quite useful to check in this resource when you have any questions.
    - After each group discussion, notes will be stored in [the study-groups repository](https://github.com/carpentries-incubator/study-groups/tree/gh-pages/discussion_notes), publicly visible. Toby will archive by Thursday, February 18. Notes **do not need to be exhaustive**, but should note the main points discussed to give a good summary of the conversation - a record of links of useful resources that people found rather than an exact transcript of what each person said. 
    - [Planned schedule for rotating roles](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing)
        - A few days before each call, the assigned Discussion Lead should make a copy of [the shared notes template](https://codimd.carpentries.org/lesson-development-study-groups) and fill in the agenda. They should send a link to the Curriculum Community Developer (Toby), who will fill in the homework tasks, the "sticky notes" survey link, and any logistical points for discussion.
    - Zoom meeting link will be different (carpentriesroom2) for most calls, but the meeting password is the same for both rooms. Check the calendar invitations to see which room we are meeting in.
3. Participant questions: What are you unsure about? What would you like more information on? How can we support you during the Study Groups program?

    - Annajiat: NLP lesson in topic box, wanting to try it out.  What is the process because some people have expressed interest but it doesn't seem to be active.
        -  Toby: someone [sent a proposal in Discuss mailing list](https://carpentries.topicbox.com/groups/discuss/T2ea133f901f7eda2/introductory-internet-web-material) and [opened an issue in the Incubator repository](https://github.com/carpentries-incubator/proposals/issues/86) inviting people interested to collaborate to contact them. This is an approach you can take so people interested in co-developing the NLP lesson with you can contact you and join the collaborators team.  
        -  Sarah: interested in covering NLP and teach some of NLP material using `nltk` in the [python text analysis lesson](https://github.com/carpentries-incubator/python-text-analysis) and welcomes Annajiat to be a part of this work  - Annajiat is interested and will join.
    - Graeme: learners environment, when developing this lesson students used to install locally for lessons, more and more using cloud environments.  Should we still require everything be able to run on someone's laptop?  Minimum specs?
        - Toby: Min specs need to think more about.  Don't think all the lessons have to run on someone's laptop.  Some of the offical Carpentries lessons run in cloud.  Carpentries not sure how to support cloud instances for new lessons.  Potentially support in the future for this.  HPC intro lesson in incubator requires an HPC env and they've found ways to provide learning environments.  Also success in the past setting up sandbox clusters in the cloud for teaching a lesson like that.  No easy answers.  GPU lesson has specific technical requirements for examples.  [Send an email to Toby](mailto:tobyhodges@carpentries.org) and you can discuss what could be done for this lesson.  Then you can expect that the learners have environments are available after.
        - Follow-up on if lessons need to run on a laptop to be official
        - Toby: lessons don't have to run on laptop to become official.  Eventually lessons theoretically can move into the [Carpentries Lab](https://carpentries.org/community-lessons/) or into one of the [existing lesson programs (Software/Library/Data Carpentry)](https://carpentries.org/workshops/#workshop-curriculum).  If a lesson fits well into one of the lesson programs, then the curriculum advisory committee for that program can discuss and decide if that should go into the lesson. That is the point that the advisory committee might have requirements on if it needs to be run on a laptop or use open sources software.
    - Bailey: Lesson template is being reworked.  Will it be possible to port an existing lesson to the new template easily?
        - Toby: New one coming in Global North's summer but we are using the current.  One of the main priorities is that there is tooling to make it easier to transfer from the current lesson template.  The exception to this might be any customizations to the template in individual lessons which might break when ported to the new template.  If you are concerned about this, avoid making too many customizations to your lesson.
    - Richard: Example data and name of lesson.  Name submitted was Frictionless Data for (Agricultural) Ecology. Should the title and focus be briader or is the current approack ok - how targeted to a specific audience should a lesson be?
        - Toby: Will discuss this more in a later week.  two main principles we follow, meeting learners where they are and the other is management of cognitive load. For both specificity is good but then if someone joins who is not in that domain can be difficult.  Looking forward to this group's discussion in later weeks. Advice for now: if you know for sure that you will be teaching this lesson to a specific audience then plan for that community then you can expand later.
        - Aleks: can be hard to strike a good balance between focussing on your community and reaching more people. Targetting for a specific domain makes content and resources in your lesson more approachable
        - Richard: agrees with this, it can be hard to pursue a specific direction when one is aware of more applications in the Frictionless Data community outside the domain chosen, but important to approach this way and hopefully others will find ways to adopt it for their domains
        - Sarah: [DC Ecology lesson](https://datacarpentry.org/lessons/#ecology-workshop) is a good example, has been adapted for many different audiences by swapping out the tabular data used.  We've customized by swapping in a health sciences data set and I think [Social sciences DC lesson](https://datacarpentry.org/lessons/#social-science-curriculum) was developed based of DC Ecology too
        - Aleks: and when there is no domain-specific tabular data to swap in, we resort to teaching the DC Ecology lesson as is as canonocal DC lesson, but sometimes people find it hard to take it to their specific problems ( and use cases) +1 from Sarah
        - Graeme: have customized the conda lesson have swapped out examples for the bioinformatics community.
5. What are some of the advantages of developing an open source lesson? What are some of the disadvantages?
6. Which of the seven principles of learning, defined by Ambrose et al. and summarised in CDH Chapter 1, are particularly relevant to The Carpentries lesson design and development? Are there any that you think are less relevant?
    - Students’ prior knowledge can help or hinder learning
    - How students organize knowledge influences how they learn and apply what they know
    - Students’ motivation determines, directs, and sustains what they do to learn
    - To develop mastery, students must acquire component skills, practice integrating them, and know when to apply what they have learned
    - Goal-directed practice coupled with targeted feedback enhances the quality of students’ learning
    - Students’ current level of development interacts with the social, emotional, and intellectual climate of the course to impact learning
    - To become self-directed learners, students must learn to monitor and adjust their approaches to learning
7. Homework:
    - Work with the Curriculum Community Developer (Toby) to ensure your lesson repository is created in The Carpentries Incubator. Step 1, if you haven't done it already, is to open an issue in the Proposals repository: https://github.com/carpentries-incubator/proposals/issues/new?assignees=&labels=&template=issue_proposal.md
    - Read Chapter 3: _Deciding what to teach_ of the Curriculum Development Handbook.
    - Make a copy of the [Lesson Design Notes Template](https://codimd.carpentries.org/HPwUE3FnTeSQJ9-_5EfU7Q?edit) in your preferred format. You can use this page to record important decisions made about the design of your lesson during and after the Study Groups Program.
    - Add a link to your Lesson Design Notes next to where you signed in on this shared notes document.
    - Write at least one **learner profile** for your lesson and add it to your Lesson Design Notes, making sure your profile(s) answer the questions listed in the chapter.
8. **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [The CodiMD Features example page](https://codimd.carpentries.org/features)
- 
- 

[sticky-notes-link]: https://forms.gle/741W5pL4CHd9MGGE6
