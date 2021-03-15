# The Carpentries Lesson Development Study Groups Notes
## Group 3: Friday 12 March 2021 14:00-15:00 UTC

[**This week: Data Sets & Authentic Tasks**](https://carpentries-incubator.github.io/study-groups/05-narrative/index.html)

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
- Jannetta Steyn / she, her / jsteyn / 
- Sarah Stevens (she/her/hers) / sstevens2 / https://github.com/carpentries-incubator/jekyll-pages-novice
- Graeme Grimes / he/him / ggrimes / https://carpentries-incubator.github.io/workflows-nextflow
- Alessio Sclocco / he, him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Annajiat Alim Rase / he, him / annajiat / 
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Hanno Spreeuw / he, him/ HannoSpreeuw / https://github.com/carpentries-incubator/lesson-gpu-programming
- 
(add more lines as needed)

Apologies: Richard Ostler

## Roles

**Group Facilitator(s)**: Sarah Stevens, Toby Hodges
**Discussion Lead**: Bailey
**Notetaker**: Sarah Stevens, Toby Hodges

## Agenda

1. Welcome & Icebreaker 

### Icebreaker:  What is your favourite dinosaur?
- Annajiat: T-Rex
- Graeme: T-Rex
- Bailey: pterodactyl / Ducky from The Land Before Time
- Toby: Styracosaurus
- Alessio: Triceratops
- Jannetta: Velociraptor
- Sarah: Tri*cera*tops
- Hanno: Ankylosaurus?
- 


## Discussion
#### Identifying datasets
* Has anyone run into trouble identifying a potential dataset for their lesson? (I have.)
    * Graeme: adapting lesson, the dataset works but doesn't fit the biology well
    * Hanno: Discussing with Alessio, maybe don't need dataset, GPU programming, something compute intensive, something embarassingly paralell, looking at old GPU programming lessons - lots of things that don't fit the Carpentries recommendations, Image as an input dataset - bit cliche maybe? not very exciting example
    * Jannetta: still thinking about it, haven't decided what would work and what wouldn't
    * Bailey: challenge identifying a good example dataset/text for a lesson on typesetting. Struggling to find a text example that will include tables, etc to use as examples of what I want to teach.
        * Sarah: could you try including "pretend" scientific observations into tables and equations? Whale observations w/Moby Dick as a off the cuff example
* Have you gone for an authentic dataset, or a more contrived example?
    * Graeme: Is there a place where all the datasets used in the carpentries are listed so they can be reused? Might be useful. 
    * Sarah: I think that's a great idea, especially for more generic datasets. (Toby: +1) In my experience, we usually start looking for an authentic data set but end up "contriving it" to prepare it for the examples of the points we want to teach. E.g. we downsample the data, remove some of the variables, etc to reduce dimensions.
    * Bailey: I would expect the process of modifying a data set to involve more removing of problems than adding them in.
* Why?
* Would your choice change if you were doing another topic?

#### Order of topics
* Did the search for a dataset lead to a change in the (order of) topics you plan to cover?
    * Graeme: In the example they use a lot of hello world/foobar examples, so planning to rewrite the examles that follow a narrative.
    * Bailey: Like moving away from that as it confuses beginners making them think there is inherent meaning in those topics when there is none.
    * 
#### Exercise formats
(Multiple-choice, Parson's, fill-in-the-blank or faded examples, new context application)
* What exercise formats do you think work well with your material?
    * Alessio: didn't design exercise yet but in looking at the formats found that parson's problems might not work for us - maybe because we aren't used to them / haven't seen them in other related materials.  Multiple choice can be useful, fill in the blank too.  Wondering if new context type exercises should be at the end since they are longer?
    * Sarah: a good point - having extra exercises for people to do is a good idea. In the Jekyll lesson there are a lot of examples of where we add something new to the website, then we ask the learners to do the same thing in a different page. We also introduce some basics of e.g. Markdown then provide a cheat sheet and ask them to refer to that to write more MD content.
    * Toby: Example of md and cheatsheet is a good example of that approach to the lesson.  Thinking about the concept, we aren't asking them to understand how the specific formatting works but rather that when you use the formatting it changes how the page is rendered.  With the cheatsheet we are making sure they understand that larger concept of markdown rather than the specifics of what we have shown them.  If you have examples of that in your lesson, where you are trying to get them to understand the broader concepts, then this can be a good assessment.
    * Bailey: Didn't think about giving them the Latex cheatsheet
    * Toby: Giving them the cheatsheet early on means they don't need to think about the syntax as much but rather the concepts and error messages.
    * Bailey: Re Error messages - sometimes it is good at recognizing where the error is, othertimes it isn't good at that. But good point in that I'm use the cheatsheet to remember specific things.
* Are there any you think are incompatible?
    * Graeme: Some of the exercises I'd like them to do are workflow using nextflow syntax, stuff that isn't important seems to get in the way (exiting a program for example).  Want to use an editor but not get stuck in those issues instead of the actual exercise. 
    * Sarah: in the SWC Git lesson we use nano because it at least gives some hints. In other lessons, I have used Jupyter Notebooks as a text editor, despite running the code on the command line.
    * Graeme: I use RStudio a lot and that could be used here too, just need to hide all the R-specific stuff.
    * Sarah: Spend some time at the beginning to demonstrate how to minimise pains in that interface.
    * Toby: On incompatible exercises, worked on a lesson on another workflow lang where the files are often yaml and parson's problems are a bit of a problem.  Some of the yaml lines are nicer for readablility to have in that order but aren't important.  Also the ones that are hierarchaical would be difficult to reorder.
    * Bailey: Value in teaching that sometimes the order of the lines doesn't matter and sometimes they do.  So maybe a chunk based parson's problems would be helpful.  Dictionaries with keyvalue pairs are inherently unordered for example.
    * Toby: In some parts of the lesson it might really work.  Parts that describe the input and output.
    * Bailey: A Parson's Problem could be beneficial to illustrate that order doesn't matter (or only matters in chunks)
    * Toby: In what circiumstances would you choose a Parson's problem as a paricularlly relelvent exercise format?
    * Graeme: Example with pipe in R works well, in workflows the order is useful to understand
    * Bailey: For loop where you are manually incrementing the loop variable, when you do that can really matter.
    * Toby: setting where you are trying to assess that your learners get the logic of what happens when and why that is important.
    * Alessio: Examples from Toby and Bailey have helped me find where I could use them.  Problems with syncronization point and it is relevent where you do them in your code.
* Are there types of exercises you would like to include, but have struggled with?
    * Toby: multiple choice questions.  Really hard to do well and really easy to do badly
    * Sarah: strikes me every time I teach Instructor Training - every MCQ answers should have _diagnostic power_. Learners in those workshops have often never seen/noticed that in the MCQs they have encountered. Reminds me of chemistry classes in college, where one lecturer loved to ask questions with multiple answer that could be true or false and would ask for combinations of which ones could be true or false, etc. Have thought back to try to figure out if those had diagnostic power or not.
    * Bailey: In course, 5 questions on a page and they would all follow-on from each other, so if you got the first one wrong you got all of them wrong
    * Sarah: weshould include assessment in lessons to help us find out whether the learners are following. We do not need/want to test them and grade them. Think about how you might address the things people get wrong as part of the lesson down the line.
    * Toby: Idea where centrally instructors can report where their learners commonly get the exercise wrong, and if it is consistent, it is a problem with the lesson and it would be helpful to get this large scale data of what needs to be changed.  Maintainers could use that info to update the lesson.
    * Toby: other purpose of the exercise int he lesson is to give them a chance to practice the skills as well. So it is fine to include exercises that are easy but don't give you much diagnostic info.  Need to be easy though.
    * Bailey: in the jekyll lesson do they render the websites locally? 
    * Toby: Early on in the design of the lesson we chose to use the web interface for good reasons but has implications for other issues as part of the lessons. Sometimes you can't separate the choice of topic from the platform that is commonly used.

## Homework
ALL: a task to be done by all collaborators on a lesson;
ONE: a task to be done by only one collaborator per lesson:
  - **ALL** Recruit one helper for the trial run you scheduled last week.
  - **ALL** Read the [Exercise Types chapter of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:exercises).
  - **ALL** Add exercises of at least three different types to your chosen episode page, to assess whether learners have met the objectives for that episode.
  - **ALL** Read [CDH Chapter 5: Developing Content](https://cdh.carpentries.org/developing-content.html).
  - **ALL** Read the [Expertise and Instruction episode of The Carpentries Instructor Training curriculum](https://carpentries.github.io/instructor-training/03-expertise/).
  - **ALL** Prepare for next week’s homework by reading the [Episode Review](https://carpentries-incubator.github.io/study-groups/05-narrative/06-content#episode-review) callout from the next section.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [Mine Çetinkaya-Rundel's Keynote Talk from CarpentryConnect Manchester 2019: "Let Them Eat Cake (First)"](https://www.youtube.com/watch?v=fQ4t7p6ZXDg)


[sticky-notes-link]: https://forms.gle/3fFaqgBratEv8cU3A
