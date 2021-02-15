# The Carpentries Lesson Development Study Groups Notes

## Group 1: Monday 8 February 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Jonathan Pelham / he, him / jonititan / https://codimd.carpentries.org/I8vD24QVTSCkQh9duAfoKA?view
- Mateusz Kuzak / he, him / mkuzak / 
- Serah Rono / she, her, hers / serahrono /
- Mike Trizna / he, him, his / MikeTrizna / https://miketrizna.github.io/intro_to_ai_ml/ / [Lesson Development Notes](https://codimd.carpentries.org/DM6o_7hGQJmpJZNGIgkbEA?view) 
- Aleksandra Nenadic / she, her / anenadic
- Nora McGregor / she, her / noramcgregor / [Lesson Development Notes](https://codimd.carpentries.org/DM6o_7hGQJmpJZNGIgkbEA?view) 
- Mark Bell / he/him / mark-bell-tna / [Lesson Development Notes](https://codimd.carpentries.org/DM6o_7hGQJmpJZNGIgkbEA?view) 
- Elnaz Amanzadeh/ she, her/https://github.com/ElnazAmanzadeh
- Batool Almarzouq / she, her / [BatoolMM](https://github.com/BatoolMM) / [Some notes](https://hackmd.io/8HB7UVPpQ36QOFFE7LSiZA)
- Daniel van Strien / he,him/ davanstrien / [Lesson Development Notes](https://codimd.carpentries.org/DM6o_7hGQJmpJZNGIgkbEA?view) 
- Shrirang Kulkarni /he/him /https://github.com/drshrirang

## Roles

**Group Facilitator(s)**: Mateusz Kuzak, Aleksandra Nenadic, Serah Njambi Rono, Toby Hodges
**Discussion Lead**: Toby Hodges
**Notetaker**: Serah Njambi Rono, Aleksandra, Mateusz

## Agenda

1. Welcome & Icebreaker 
    - Please sign in by adding your details to the *Participants* section above.
    - (verbal) Group Facilitator introductions
        - who you are
        - where you are
        - previous experience with lesson development and The Carpentries lesson template
        - Facilitators: 
            - Toby (Curriculum Commmunity Developer, The Carpentries, supporting the community to develop lessons); 
            - Serah (From Kenya currently in Estonia, Director of the Community Development and Engagement, The Carpentries); 
            - Mateusz (Training Programme Lead, Dutch eScience Centre, reusing as much as possible all the templates and resources developed by The Carpentries and the community - running lesson study at a smaller scale); 
            - Aleks Nenadic, works for Software Sustainability Institute in the UK whose goals are aligned wih The Carpentries'. Enables community to develop lessons using their own skills and expertise and adapting best practices that SSI makes available to them.
    - (verbal) Participant introductions
        - who you are
        - where you are
        - about the lesson you will be developing during the program - what is it about? who is it for?
        - previous experience (if any) with lesson development and The Carpentries lesson template
        - Participants: 
            - Batool Almarzouq, Uni of Liverpool, computational biologist, coding in R, and wants to create a lesson for RNASeq analysis, little experience with the lesson template
            - Mike, Washington DC, US, Smithsonian Institute, bioinformatician, experience with with Data Carpentry courses and HPC, but doing ML in his new work and here to work on this
            - Joni, [Safety & Accident Investigation Centre](https://www.cranfield.ac.uk/Centres/Safety-and-Accident-Investigation-Centre), Cranfield University, detection of [EOFDM](https://www.easa.europa.eu/domains/safety-management/safety-promotion/european-operators-flight-data-monitoring-eofdm-forum) in flight precursors, to contribute to engineering content in the Carpentries community, flight data monitoring
            - Nora, London, digital curator at the British Library, they run a training programme in computational skills for digital curators working with cultural heritage data, Library Carpentry focussed - into to ML and AI for librarians 
            - Mark, Wimbledon, National Archives, digital researchers teaching colleagues ML in introductor way, wants to create more materials in this space
            - Elnaz, Iran, molecular biologist, started educational and research group focussed on bioinfomatics, participating in metadata analysis project about neurodegenerative diseases, 1 hour experience in SWC lesson with Konrad Forstner
            - Shrirang, Computer science dept, National Institue of Engeneering, learned python a few years ago, and started using and learning ML as a hobby, Pyton popoular among students and publishers in his country
            - Daniel, London, British Library, works with Nora from this group 
2. Housekeeping notes
    - **Introduction to CodiMD - https://codimd.carpentries.org/features**. You likely will not need all the features described, but quite useful to check in this resource when you have any questions.
    - After each group discussion, notes will be stored in [the study-groups repository](https://github.com/carpentries-incubator/study-groups/tree/gh-pages/discussion_notes), publicly visible. Toby will archive by Tuesday, February 9. Notes **do not need to be exhaustive**, but should note the main points discussed to give a good summary of the conversation - a record of links of useful resources that people found rather than an exact transcript of what each person said. 
    - [Planned schedule for rotating roles](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing)
        - A few days before each call, the assigned Discussion Lead should make a copy of [the shared notes template](https://codimd.carpentries.org/lesson-development-study-groups) and fill in the agenda. They should send a link to the Curriculum Community Developer (Toby), who will fill in the homework tasks, the "sticky notes" survey link, and any logistical points for discussion.
3. Participant questions: What are you unsure about? What would you like more information on? How can we support you during the Study Groups program?
    - Mike: from the assignment spreadsheet it looks like there are other groups meeting at different times and days during the week. On weeks where we cannot make it to the assigned group session, can we join any of the other sessions?
        - Yes. It is better to attend another group's meeting than to miss altogether in any given week. Please let Toby know in advance.
    - Elnaz: how will they split lesson development - who writes what within a lesson?
        - Coordination will be needed within the team working on the lesson. Everyone should do homework tasks themselves though, as the first few weeks you will not be working on the lesson repo yet. Once this starts - each member should ideally be responsible for one episode and practice exercises like writing tasks, exercises, etc. for that lesson. And everyone does the same tasks on a different episode but you need to communicate with the team to make sure everyone in the team is on the same wavelength. 
    - Elnaz: DC Genomics is focussed on Python and there is also R in the lesson - develop a similar lesson using R and also Python and have access to the same lesson in different language? Is this possible?
        - Yes, this is possible. The best thing would be to approach this project afresh and if there is an existing material you could use it to translate into another language but we would like the group to focus on the lesson development process and if you are largely basing your work on an existing lesson you might not get as much from the process as planned. On one hand we want to encourange reuse as much as possible but also to give people an insight into and skills for developing a lesson from scratch.
    - Mike: adding a lesson to the official curriculum and making sure the work is aligned with what the LC, SWC and DC are already working on to avoid repetition and stepping on anyone's toes 
        - LC curriculum advisory committee meets every 2 months, SWC and DC should have curricula advisory committees but the were temporarliry deactivated in pandemic in recognition of people's many obligations. So, we can liaise with LC already.
        - Serah posted a link to a Library Carpentry call for Advisory Group members: https://carpentries.org/blog/2020/12/call-for-new-members-library-carpentry-advisory-group/
    - Shrirang: If this group alone going to advise on curriculum development, or will there be broader guidance on the lesson development.
        - The Carpentries Incubator is the space for people to develop on any topic they want for any aidience they find fitting. Lesson can move to another space after getting the seal of approval from The Carpentres and review process and advisory committees. Resources we share as part of this programme are the main point for guidance and can also get in touch with Toby directly.
    - Nora: can other people contribute to their lessons developed int he next 10 weeks as part of this group
        - They can - it is open source and in theory people can start contributing. However, spontaneous contributions are not really happening at the moment in the Incubator. If this is distruppting for the team - they could talk to Toby and we can try to deal with this. We have not really thought about this a lot. Also, the lesson developers are thr owners of the lesson repos and others cannot directly contrinute but rather via creating issues and PRs. 
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

[sticky-notes-link]: https://forms.gle/JkSbZnjw3uXYE5nr9
