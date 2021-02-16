# The Carpentries Lesson Development Study Groups Notes

## Group 2: Tuesday 9 February 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Peter Steinbach / he/him / twitter:@psteinb_, github:@psteinb / https://github.com/carpentries-incubator/deep-learning-intro
- Tuomas Koskela / he/him / github:[@tkoskela](https://github.com/tkoskela) / https://github.com/carpentries-incubator/julia-novice/
- Colin Sauze / he/him / github:@colinsauze / 
- Maria Dermit / she/her /[github:@demar01](https://github.com/demar01)
- Dan Kerchner / github:[@kerchner](https://github.com/kerchner)
- Mateusz Kuzak / he, him / gh: [mkuzak](https://github.com/mkuzak)
- Aleksandra Nenadic / she, her / gh: [https://github.com/anenadic](https://github.com/anenadic)
- Sue McClatchy / she|her / github: [@smcclatchy](https://github.com/smcclatchy)
- Mosè Giordano / he/him / gh: [@giordano](https://github.com/giordano)


## Roles

**Group Facilitator(s)**: Mateusz Kuzak, Aleksandra Nenadic, Toby Hodges
**Discussion Lead**: Toby Hodges
**Notetaker**: Aleksandra Nenadic

## Actions
- Action on Toby to delete week 8 entry when we have an interval for trial runs and collecting feedback for people's lessons (March 30 for this group)

## Agenda

1. Welcome & Icebreaker 
    - Please sign in by adding your details to the *Participants* section above.
    - (verbal) Group Facilitator introductions
        - who you are
        - where you are
        - previous experience with lesson development and The Carpentries lesson template
        - Toby, Curriculum Development Lead, from The Carpentries core team, before this working as bioinformatics community manager at EMBL, Heidelberg, Germany
        - Mateusz, Training Programme Lead at the Dutch eScience Centre, bioinformatitian, worked as researcher, then RSE, now coordinating training 
        - Aleks, Training Lead at UK SSI, doing loads of community engagement & policy around better research software. Carpentries Trainer
    - (verbal) Participant introductions
        - who you are
        - where you are
        - about the lesson you will be developing during the program - what is it about? who is it for?
        - previous experience (if any) with lesson development and The Carpentries lesson template
        - Peter, based in Dresden, Germany, did some lesson development but without guidance, Carpentry Instructor, working on deep learning lesson and consulting some people already on this, some past involvement in HPC and trying to establish HPC Carpentry
        - Dan, librarian + software developer, George Washington Uni, Washington DC + graduate student in Biostatistics, curriculum for data analysis and stats for life science with Sue, already collaborated on such lessons so a good example for how past experiece can help or hinder
        - Colin, RSE at Super Computing Wales, Aberystwyth, past experience in ML and HPC lessons - trying to align with the Carpentries recommendations, saw some previous lessons as a guide for how to develop his, but no formal training on this, also developed some lessons in ML not in Incubator at the moment
        - Maria, postdoc in London, Cancer Institute, proteomics, lesson to develop is intro to proteomics data analysis with R and BioConductor packages, previous informal experience in lesson development 
        - Sue, Jackson Lab, Maine, US, various lessons in various states, most developed genetic mapping lesson. Will work with Dan on lesson. Offered ML lesson to people at JL but realised that they need some background in stats, some foundational knowledge is needed, audience biomedical researchers
        - Tuomas, RSE at UCL, London, background: physics and  HPC, with Mose wishes to work on Julia introductory lesson 
        - Mosè, RSE at UCL, London, no experience with lesson development so keen on learning the process and wishes to develop the lesson in Julia with Tuomas and transfer his knowledge to students. 
2. Housekeeping notes
    - Introduction to CodiMD - https://codimd.carpentries.org/features
    - After each group discussion, notes will be stored in the study-groups repository, publicly visible. Notes do not need to be exhaustive, but should note the main points discussed to give a good summary of the conversation.
    - [Planned schedule for rotating roles](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing)
        - A few days before each call, the assigned Discussion Lead should make a copy of [the shared notes template](https://codimd.carpentries.org/lesson-development-study-groups) and fill in the agenda. They should send a link to the Curriculum Community Developer (Toby), who will fill in the homework tasks, the "sticky notes" survey link, and any logistical points for discussion.
            - When acting as a notetaker, summarise discussions when taking the notes over the coming weeks, rather than full transcript of the call, to retain enough anonimity while catching the essence of disucssions
            - If you know you cannot attend on a given week or are not comfortable taking one of the roles - please contact Toby in advance but we think you will benefit the most from the programme if you do take these rotating roles
            - Also refer to Code of Conduct if you need to report anything and are not comfortable reporting to Toby
3. Participant questions: What are you unsure about? What would you like more information on? How can we support you during the Study Groups program?
    - Sue: once a lesson is in the Incubator - it is opened up to the community - and people want the lesson to be perfect before submitting - who retains control in the Incubator?
        - Once the lesson is in the Incubator (either from scratch of transferred from eleswhere) - the person submitting it has full control and can rename, delete, do anything to the repo as they wish. There is a process for moving to official Lesson Programmes or the Lab (to be launched next month) where reviewed, approved, mature and tested lessons will go. While they are in the Incubator - no one is vouching for them being complete/mature or ready to go elsehwere.
    - Sue: her lessons are in her personal GH, but once moved to the Incubator, how can her contributions be tracked by her and her employers, to show activity and contributions.
        - Lessons can have DOI and a record in Zenodo, with the authors list in the order according to the number of commits in the lesson repo. [Journal of Open Source Education](https://jose.theoj.org/) - Carpentries can help fast track lesson to undergo peer review and move to the Lab - so an actual journal entry to cite alongside the Zenodo DOI. Carpentries are working on the new lesson template with a much clearer contributions page with a better history of contributions and development efforts (e.g. initial efforts at a hackathon). New lesson template will be ready in summer 2021. 
        - You can have a fork of a lesson in your own account or organisational account together with the version in the Incubator - you have to sync the former with the latter but it may help with tracking who is contributing what.
        - GH have a contributions page for your account where you can see all your contributions to various different projects
    - Colin: process of moving to the new lesson template, e.g. loads of copy+pasting and lost history?
        - There is a remote theme for Jekyll with a link in the lesson. The new lesson template won't use Jekyll so there will be loads more work to migrate and break customisations people did locally to current lesson template. But coding 'code' and examples should be much easier in the new template. MD files will remain the same but the infrastructure around them will change - people should be able to reuse episode MD files in the new template.
    - Is this a good point to beta test the new lesson template?
        - In theory yes, but not just yet.
    - Dan: break in week 8 - would this be reflected in the calendar entries? *Action on Toby to delete this entry*
        - Yes, Toby will fix - there is going to be a 2 weeks' interval around that time to give people chance to teach their lesson and collect some feedback
5. What are some of the advantages of developing an open source lesson? What are some of the disadvantages? 
    - Developing a lesson open source publicly from the very beginning so anyone can in theory come and contribute
    - Advantages: 
        - pick up someone's lesson and use it, better than doing something on your own on a short notice
        - can improve on someone's lesson
        - you can cite it to a certain extent
        - collaborating with people to finish things off - you get a bit of a push
        - second pair of eyes and second perspective
        - you need how to govern an open source project - with the Incubator such a process already exists
        - disagreements and forks can be realised early on and youc and decide to go separate ways and doing backward lesson design can enable people to detect these things earlier
        - it gets you to learn and become an open source project contributor

    - Disadvantages:
        - lesson may not be finished
        - you do not agree 100% with the lesson content, you do not have controle over someone else's lesson
        - infrastructure is missing to see/count citation e.g. in Google Scholar
        - habit of starting a project and never finishing it and no one never sees it - that's better than showing your never-finished work
        - process of handling ideas and contributions from different people can slow you down, especially early on, you have to review them and decide what to do with them
        - you may feel you have to have all the answers ready before you open it up
        - less editorial control, compromises are key and meeting people half way

7. Which of the seven principles of learning, defined by Ambrose et al. and summarised in CDH Chapter 1, are particularly relevant to The Carpentries lesson design and development? Are there any that you think are less relevant?
    - Students’ prior knowledge can help or hinder learning
    - How students organize knowledge influences how they learn and apply what they know
    - Students’ motivation determines, directs, and sustains what they do to learn
    - To develop mastery, students must acquire component skills, practice integrating them, and know when to apply what they have learned
    - Goal-directed practice coupled with targeted feedback enhances the quality of students’ learning
    - Students’ current level of development interacts with the social, emotional, and intellectual climate of the course to impact learning
    - To become self-directed learners, students must learn to monitor and adjust their approaches to learning
8. Homework:
    - Work with the Curriculum Community Developer (Toby) to ensure your lesson repository is created in The Carpentries Incubator. Step 1, if you haven't done it already, is to open an issue in the Proposals repository: https://github.com/carpentries-incubator/proposals/issues/new?assignees=&labels=&template=issue_proposal.md
    - Read Chapter 3: _Deciding what to teach_ of the Curriculum Development Handbook.
    - Make a copy of the [Lesson Design Notes Template](https://codimd.carpentries.org/HPwUE3FnTeSQJ9-_5EfU7Q?edit) in your preferred format. You can use this page to record important decisions made about the design of your lesson during and after the Study Groups Program.
    - Add a link to your Lesson Design Notes next to where you signed in on this shared notes document.
    - Write at least one **learner profile** for your lesson and add it to your Lesson Design Notes, making sure your profile(s) answer the questions listed in the chapter.
9. **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [The CodiMD Features example page](https://codimd.carpentries.org/features)
- [Carpentries Incubator](https://github.com/carpentries-incubator/proposals)
- [Carpentries Lab](https://github.com/carpentrieslab/proposals)


[sticky-notes-link]: https://forms.gle/k4CiZJNAJRbv7ZLm6
