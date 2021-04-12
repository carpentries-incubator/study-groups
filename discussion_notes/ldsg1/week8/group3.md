# The Carpentries Lesson Development Study Groups Notes
## Group 3: Friday 9 April 2021 14:00-15:00 UTC

[**This week: Trial Run Debrief**](https://carpentries-incubator.github.io/study-groups/09-reflecting/index.html)

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
- Richard Ostler / He/him/ richardostler / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Alessio Sclocco / he, him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Jannetta Steyn / sher, her/ jsteyn / https://github.com/carpentries-incubator/java-intro
- Sarah Stevens / she, her, hers / sstevens2 / https://github.com/carpentries-incubator/jekyll-pages-novice
- Hanno Spreeuw / he, him / HannoSpreeuw / https://github.com/carpentries-incubator/lesson-gpu-programming
- Shrirang Kulkarni /he,him/ https://github.com/drshrirang
- Annajiat Alim Rasel / hi,him / annajiat
- 
- 
- 
- 
- 
- 
- 
- 
- 
(add more lines as needed)

Apologies: Graeme Grimes

## Roles

**Group Facilitator(s)**: Toby Hodges & Sarah Stevens
**Discussion Lead**: Jannetta Steyn
**Notetaker**: Bailey Harrington

## Agenda

1. Welcome & Icebreaker 
    - If you were a dog, what breed would you be and why?
        - 
        - Toby: [American hairless terrier](https://www.akc.org/dog-breeds/american-hairless-terrier/)
        - Shrirang: Alsacian breed
        - Hanno: labrador
        - Jannetta: Jack russell terrier; they always take on more than they can handle, think they are bigger than they are
        - Bailey: I would not be a dog. Cat?
        - Alessio: stray? no certified breed
        - Richard: something with lots of hair, given the lack of recent haircuts
        - Annajiat: Chow chow, it looks cool

:::info

- How successful was your trial run? Consider this both from the perspective of the learners—how successfully do you think they learned the skills you were aiming to teach?—and your own - how helpful was the trial run as an exercise in gathering feedback about the ongoing development of your lesson?
    - Bailey, Hanno & Alessio, Jannetta, Richard have done their trial runs
    - Hanno was able to get episode review feedback from Toby; the level of expected prior knowledge for participants became more apparent (their material requires some knowledge of NumPy).
        - Brought up questions of whether they want to exclude people who know nothing about Python, by listing it as a prerequisite.
            - Annajiat: Some participant might join not be an expert but may be only to become familiar with it so they can better undertand, may be their teammates. If there is space, I would probably welcome participants with less pre-requisites
        - Additional comments from Toby about adding exercises; for example, GPU concepts relative to CPU spaces—they are in different memory spaces, which currently is not really laid out int he materials.
        - Using Collab; for some of the plots zooming in is really necessary, but the platform doesn't really support it.
    - Bailey: $\LaTeX$ demo
        - ran yesterday evening, think it went well, covered some things about taking a body of text to change from plain text to typeset book, audience was a mixture of people who were completely new and people with a bit more experience, able to get some feedback from both sides.
        - Good feedback - someone suggested adding in a list of all the packages that are used in each episode and a summary of what they are being used for. Latex requries packages for pretty much everything.  I do that in my preamble import statements and comments with why.
        - No setup issues, as Overleaf is very simple to get going.
    - Richard, also yesterday afternoon, mixture of experience levels, frictionless data, also using google colab for the interactive exercises, went well, even people who didn't have python skills were able to follow along, importing google colab worked well.
        - Exercises - general discussion then fill in the blanks for a code sample.
        - Getting feedback was more difficult. General feedback good, but targeted/specfic feedback harder.
        - Learners seem to get more out of it than I learned about the lesson.
        - One person attending who would not be representative of the audience in a real setting. He finished all the exercises very quickly.
    - Jannetta, colleagues who were not java programmers, lesson at an intro level so wanted people with less experience, helper had a conflict but Bailey subbed in, went well, used repl.it platform, so everyone had the same environement.  Didn't run into many issues that needed troubleshooting.  Intro session so not much went wrong.  feedback was good, suggestions were small points - some things I've thought about already - nothing major that I left out.  People thought the pace was good as well.
        - Bailey used repl.it later in the week for a different project

## Those who did the trial run:
- How long did it last?
    * Jannetta: 1 hour
    * Bailey: 90 minutes — the exercises took some time
    * Richard: about an hour +20 min setup
    * Hanno: 45 minutes, but that was without the exercises, which I still have to write.

- How many helpers did you have?
    * Jannetta: 1 helper
    * Bailey: 1 helper
    * Richard: 1 helper
    * Hanno: no helper

- How many episodes did you cover?
    * Jannetta: 3 episodes (short ones)
    * Bailey: 3 episodes (one, of which was very short)
    * Richard: 1 episode
    * Hanno: 1 episode

The amount of time taken for exercises can vary a lot with the specific group in the lesson, making it hard to estimate how long they will take.

- What worked well about the material you have developed?
    - Jannetta: the decision to use repl.it as an environment worked well. The material was very introductory, so there's not much to say there. repl.it might prove problematic in situations where working online is not possible.
    - Richard: Using google colab for the online exercises made things very easy; the Carpentries teaching has shown him new ways to structure exercises that he wouldn't have throught of before. Two types of code examples: method for describing a csv table; previously, he would do one, then have others do a few more; using fill-in-the-blanks is an effective way of doing it that he wouldn't have used before.
    - Hanno: The old GPU course required a lot of setup on remote servers, and other things that using google colab has largely eliminated; however, some libraries still need to be installed and takes some figuring out. The whole episode was set up as a 'teaser': showing the speed-up that is gained using a GPU vs a CPU. That format was appreciated.

- What needs changing before next time? Consider what needs changing about both the lesson and your approach to teaching it.
    - Jannetta: In general, what she did worked very well, so maybe no need to change much.
    - Richard: Needs to add a bit more background to the episodes.
- How well did you estimate how long the episode(s) would take to teach?
    - Jannetta: Did not venture a guess; just stopped at 1 hour.
    - Bailey: I underestimated a bit, mostly because of the exercises.
    - Hanno: It did not take as long as I hoped. Just part of teaching life.
- What do you need help with to improve your lesson?
    - Bailey: I need to know what things people want to do with $\LaTeX$. There are so many things you can do so it is hard to know where to focus.
        - Jannetta: yes you might need to focus on a specific audience e.g. writing papers for journals, writing a thesis. When I was doing my PhD we had some $\LaTeX$ workshops aimed at thesis writing. you could then provide some templates based on what is used at your local university etc.
        - Bailey: yes, aiming for discrete topics that can be mixed and matched.
        - Sarah: maybe have some optional episodes, poll the audience in advance, and cover a set of core episodes and then the optional ones of interest.
    - Richard: The challenge is trying to avoid overload, not putting too much in the lesson.
        - There's always a temptation to put more in and trying to figure out where to draw the line.
        - Sarah: People always suggest to add things to lessons; it's rare that people suggest removing content. Having several maintainers can help with sharing the decision.
            - Toby: I recommend looking back at the objectives you wrote for the lesson at the start of the process. This will help you judge what is essential and what might be superfluous.
            - Sarah: Don't have any recommendations for episode creep off the top of my head but you can always move them to extras later if you decided they aren't needed.
- 
- Now that you have followed the process of backwards design from first steps to teaching the new lesson for the first time
    - what are some benefits of the backwards design approach to lesson development?
    - what are some of the disadvantages?
- What do you wish you had known—or that you had been told—when you began developing this lesson?

- Shrirang: Are there machine learning tools/algorithms to analyse episode or learning materials?
    - Toby: I don't think there are.
    - Shrirang: gauging the number of domain-specific terms being introduced, for instance.
:::

## Discussion

- How did you find the audience for your trial run?
    - Bailey: posted on Slack Lesson Dev channel and invited other people that Bailey knows, including via twitter, identified PhD students, brother - mix of new people and know people. Recieved more replies than could manage in a session. Applied a cut-off on numbers to keep numbers manageable. Scheduling also helped. Lots of interest in the lesson. Possibly identified one person to help with lesson development along with a colleague who acted as helper.
    - I asked my colleagues and Carpentries mentees to join and Bailey offered to be a helper
    - 

- homework (ALL: a task to be done by all collaborators on a lesson; ONE: a task to be done by only one participant per lesson, ideally after discussion with their collaborators)
    - (ALL) Create more issues on your lesson repository, as a way to keep track of outstanding tasks and improvements that could be made.
    - (ALL) Read Section A.3 (Using GitHub Issue Labels) of CDH Appendix A: The Carpentries Incubator.
    - (ONE) Add help-wanted and good-first-issue labels to the issues on your repository as appropriate.
    - (Optionally, ONE) ask Toby to include your lesson in the listing on the Help Wanted page of The Carpentries website.
    - (ALL) Read Chapter 6: Curriculum Development Roles and Chapter 7: Lesson Life Cycle of the Curriculum Development Handbook.
    - (ALL) Open at least one Pull Request to fix an issue on another lesson repository in The Carpentries Incubator.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/3fFaqgBratEv8cU3A
