# The Carpentries Lesson Development Study Groups
## Group 3: Friday 19 March 2021 14:00-15:00 UTC

[**This week: Writing Explanatory Content**](https://carpentries-incubator.github.io/study-groups/06-content/index.html)

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
- Jannetta Steyn / sher/her/ jsteyn / https://github.com/orgs/carpentries-incubator/teams/java-intro-maintainers
- Richard Ostler / he/him / richardostler / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Hanno Spreeuw/ he/him / GH: HannoSpreeuw/ https://github.com/carpentries-incubator/lesson-gpu-programming
- Alessio Sclocco / he, him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Mateusz Kuzak / he, him / mkuzak / 
- Graeme Grimes / he/him / ggrimes / https://github.com/carpentries-incubator/workflows-nextflow
- Annajiat Alim Rasel / he, him / annajiat / https://github.com/carpentries-incubator/java-novice-inflammation/
(add more lines as needed)


## Roles

**Group Facilitator(s)**: Toby Hodges, Mateusz Kuzak
**Discussion Lead**: Hanno Spreeuw
**Notetaker**: Jannetta Steyn, Toby Hodges, Mateusz Kuzak

## Agenda

1. Welcome & Icebreaker 
    - (Need an idea for an icebreaker question? Check out [the list of icebreakers from the Instructor Training curriculum](https://carpentries.github.io/instructor-training/icebreakers/index.html).)

:::info

What questions do you have about writing your lesson?
* Alessio: I wanted to write exercises but couldn't find the template for how to do this so they would be formatted correctly in the built webpage. Would be nice to have a template for episode pages that includes placeholders for these kinds of blocks.
    * Toby: this is the page to refer to for formatting in the episode pages: https://carpentries.github.io/lesson-example/04-formatting/index.html but I agree these special blockquotes are a bit of a pain to write.
        * Alessio: thanks!
* Richard: How much should people be directed away from the lesson towards the specification. Would it be good exercise to refer learners to take 15 minutes to read the specification?
    * Annajiat: other lessons link out to more complete references/courses, give recognition to inspriration, include links to recommended reading.
    * Toby suggests to link to external materials. Remember Rule 6 of Teaching Tech Together: "never hesitate to sacrifice truth for clarity." Better to keep things brief/leave things out to keep people interested/to avoid confusing them.
    * Bailey: linking to resources for finding out more is a good thing, can help them find something if they get stuck or want to find out more. :+1:
    * Mateusz: Put the resources at the bottom of the notes
    * Graeme: is there a way to share slides/code blocks and diagrams of best practices
    * Toby: not built into the lesson template. There have been discussions around doing this in the new template but it is unlikely to be a priority.

Example of including figures in the lesson as the reference for instructors: https://swcarpentry.github.io/shell-novice/figures/index.html

* Richard: discussion exercises, where I am trying to get learners to start thinking about something. Is this approrpiate?
    * Annajiat: this is established practice in e.g. the DC Ecology spreadsheets lesson
    * Bailey: good for a breakout rooms exercise
    * Graeme: can be difficult to get learners talking in breakout rooms
    * Bailey: yes, depends on the group of students in each room
    * Mateusz: this kind of exercise works well to "set the scene" and get them focussing on the right things at the start of the day.
    * Hanno: look at it the other way and consider what would happen if they were not aware of what was important to know about e.g. the structure of the file and what could happen then.
    * Richard: format of the exercise: I want them to think about what you need to describe data, then move on from there to introduce the structure to describe the data. Helping them understand why you want to do this in the first place.
    * Bailey: you're talking about higher-level properties of data sets? 
    * Richard: yes, at that level it is fairly generic
    * Toby: follow it up with a question (e.g. multiple choice) that will give the Instructor much more specific information about how well the learners have got what you wanted them to get from the discussion question.
    * Jannetta: similar to the kind of data clean-up exercise in DC spreadsheet/OpenRefine lessons? Better to give them unstructured data and ask them to structure it?
    * Richard: not really about structuring data, but about describing it. 
    * Jannetta: give them something that will make them think about potential solutions, and guidance on whether or not they are on the right track.
    * Bailey: give them a description and ask them to identify what the data looks like based on that description?

What are some of the advantages of writing exercises before the examples and explanations learners will need to be able to solve them?
* Alessio: writing exercises first makes it easier to decide what to teach without overloading the learner
    * "what is necessary to be able to solve this exercise?""
    * Hanno: very focussed approach to design exercises first.
* Jannetta: a bit like Test-Driven Development: write the test first then write the code. Makes you think of what you want to assess, before explanations of how to get there.
* Bailey: I have been using idea of smaller concepts I want to teach to help me choose examples to use in the lesson. At the moment it looks like it won't be a single example text—which was probably always ridiculous, anyway. I have some examples of prose-like (Irish Fairy Tales) text organised into 'chapters' that can provide the feel of a larger document, without being large (and to which I will have them add illustrations); and some other bits that have text along with accompanying formulæ and tables for more technical stuff.
* Toby: did anyone find that designing exercises made you realise something was missing from your objectives?
* Richard: I found this a useful approach and really validated the objectives for an episode - it made me finesse the objectives, but not radically change them.

What are some of the benefits of writing example code blocks before the “connective tissue” text between them?
How do you plan to account for your expertise while you write your lesson? "expert awareness gap" (AKA "expert blind spot")
* Hanno: "we therefore have to make sure everything we teach is useful right away and conversely that we do not teach anything just because it is fundamental." Learning things because they are fundamental was how I learned in school/college, but it doesn't apply here! Alessio and I looked at the old version of the GPU Programming lessons and found that it starts with GPU Fundamentals. You may lose a lot of students along the way while teaching them about the five different types of memory etc.
* Alessio: exercises can be useful to avoid covering too much fundamental material. Review by other people who are not experts would be helpful to guard against this too.
* Graeme: I am teaching something that I am not an expert on yet. Learning along the way. I hope that will help me not to get bogged down in fundamentals, understand the difficult parts to learn etc
* Annajiat: Teaching is a good way to learn. It seems that lesson development is also a good way to learn.
    * Going through a new experience, it is going to take some time to sink in. After first pass, this should get easier and faster. I saw a recent funding call that estimated a year to develop a lesson, trial runs, etc.
* Richard: with these lessons we are aiming to make people competent practitioners, not experts. e.g. DC Ecology SQL & databases lesson, which does not mention any of the expert language (normalisation etc) around databases. Teaching them that "through the back door" even if they are not learning the formal language.
* Hanno: really a different perspective than you might think in the first place.
* Graeme: I wonder sometimes whether we should be teaching in the historical context. Whether that would help people better understand the necessity of different aspects of what we are trying to teach.
* Toby: better to focus on the skills people have signed up to learn but often historical context can help with explaining those.
* Bailey: some historical context can often help e.g. reduce frustration around ludicrous short names for UNIX commands

:::

- homework:
    - (ALL) Complete (at least) the episode you plan to teach in your trial run, and request review when it is ready.
        - You should request a review by opening a new issue on your lesson repository and tagging the assigned reviewer (@reviewer_username), telling them where to find the material that you would like them to review.
        - Find the name & GitHub username for the person assigned to review your episode in this sheet: https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing
    - (ALL, if you have time this week) Complete a review of the episode you were assigned. See the callout below for more details about how you should approach the review.
    - (ALL) In preparation for your Trial Run of an episode, read the two Carpentries Instructor Training bonus modules on online training: 
        - [Know Your Tools](https://carpentries-incubator.github.io/instructor-training-bonus-modules/01-online-workshops-module-1/index.html)
        - [Making the Dream Work](https://carpentries-incubator.github.io/instructor-training-bonus-modules/02-online-workshops-module-2/index.html)
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/3fFaqgBratEv8cU3A
