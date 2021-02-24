# The Carpentries Lesson Development Study Groups Notes

## Group 2: Tuesday 23 February 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Aleksandra Nenadic / she. her / gh: anenadic
- Mateusz / he, him / gh: mkuzak
- Dan Kerchner / gh: kerchner
- Peter / he, him / gh:psteinb_ 
- Colin Sauze / he, him/ gh:colinsauze
- Mosè Giordano / he, him / gh:giordano
- Sue McClatchy / she|her / gh:smcclatchy
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Toby Hodges, Mateusz Kuzak, Aleksandra Nenadic, Serah Rono
**Discussion Lead**: Peter Steinbach
**Notetaker**: Daniel Kerchner

# Agenda

## preface

The following agenda is based on the assignments for today. Here is a quick recap:

> ## Homework Tasks
>
> - Read [the Technological Introductions chapter of the CDH][cdh-8]
>   and follow the steps to set up your repository as described in
>   the [template README file][incubator-template-readme].
> - Read [section A.2 of CDH Appendix A: The Carpentries Incubator][cdh-a1],
>   and add topics to your lesson repository.
>   (If you cannot add the complete set of topic tags yet, do not worry:
>   you will be able to add more and remove topics whenever you like.)
> - Note down any questions you have about the lesson template and,
>   if you got stuck, how far you had progressed with the setup beforehand.
> - Add a link to your lesson repository to the Study Group's shared notes document.


## Welcome & Icebreaker

- **Kind reminder**: this session is conducted under the Carpentries Code of Conduct
- **Housekeeping announcement**: lesson template Help Desk session [at 15:00 UTC on Thursday](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Lesson+Template+Help+Desk&iso=20210225T15&p1=%3A&ah=1) in Carpentries Zoom Room 2 (the same place as this call). More Help Desk sessions to be scheduled next week too.

### Icebreaker 1

Please share with use the most astonishing thing, a learner has shared with you during or after a course.

- Colin: a helper who said she really liked the carpentries style of teaching. I suggested she apply to be an instructor and is now qualified as one.
- Aleks: always a bit saddened when people talk about their demotivational experiences inflicted by past teachers
- (Dan) It seems that many courses expect people to learn to code on their own, and they never had a good way to do so, until attending the Carpentries workshop.  (Peter referenced a good talk on Youtube from Mark Guzdial?)
- (Sue) When I first started teaching I was terrified because I don't have a computer science degree, and assumed I had no business teaching R or any other programming language. To my great surprise and delight, participants' difficulties included nothing more than typos. They showed me that I am eminently qualified to teach R to beginners.
- (Mateusz) the person for practicing teaching made a presentation (differential gene expression analysis) as a stop motion style animation with cout out paper graphics
- 
- (Toby) +ive someone wrote me an email some months after a course, to explain how the skills they had learned there had led to them getting a new job :) ; -ive someone arrived at an R course with a keyboard that did not have a working "P" button. It took me 1.5 days to convince them to use one of the prepared backup computers. 
- PS: coding up a complete scipt for doing an analysis on microscopy images on the day after the course
- Tuomas -- a researcher was blown away by the git log --graph option

### Icebreaker 2

As we are talking about git repos today, let us know what you tend to struggle with the most on github/gitlab?

- Colin: I've been using git for over 10 years, but I still find correctly undoing a mistake (either comitted or not) unintutitive and I often have to look it up. In SVN the revert command did this, but git revert is totally different and I still haven't unlearnt SVN fully.
- Tuomas: 
    - I used to struggle with keeping track of multiple remote repositories.
    - Multiple places for information on Github: Issues, Pull Requests, Project Boards
- (Dan) Remembering to keep branches "fresh" when collaborating with other people.  I.e. doing a pull before commencing work on changes.  Also knowing how to gracefully recover from 'detached HEAD'!  Finally, explaining to learners new to git.
- (Mosè): not really a struggle, but I have a lot of gripes with GitHub Actions, in terms of interface and features
- Mateusz: keeping up the fork up to date, I usually delete the repository and fork again
- Aleks: changing interfaces or new features throw me off a bit in a moment until I find my way again and learn new stuff
    - also remembering to refresh with upstream changes
    - also forking when I should do the import and the other way around
- (Toby): small thing I always struggle with is remembering to delete branches after merging. ~~big thing I struggle with is merging upstream changes when working with multiple remotes - I always forget that my fork may contain changes not included in the upstream remote.~~ haha I remember now. merging template updates from the carpentries/styles repository into a lesson repo.
- (PS): trying to NOT have the merging commit message (especially with online commits) 
- (Sue): I mostly have amnesia about the difficulties I used to have with Github - things seems easy now but weren't always. I learned git and github by "bashing my head against a wall", figuratively speaking. I didn't understand the language (push? pull? remote?) but managed to get results even though I had no understanding of what I was doing. 

## Technical Introductions

- breakout rooms, 10 minutes.  Fill out below.

### The devil's advocate

**Split up in break-out rooms. Find arguments against and potentially in favor of the little devils that have their say below.**

1. developing lessons on github? Puhh, that is quite some technology that I am totally reluctant to learn. All this git to and fro and then merge conflicts and what not ... too much hassle: I develop my slides and be done with it.

- Mosè/Dan - Not easy to share openly.  Markdown code for pages is more reproducible - other benefits including ability to use LaTeX.
- Colin/Sue - collaboration not possible w/slides; slides are good for lecture and demonstration, not for live coding so people aren't going to learn skills. they will learn ideas and concepts, but not the means to implement those ideas and concepts. Lesson material in the form of a website is ideal for self-study and review. Git means website might change between taking the course and later referring back to the material.
    - can collaborate w/slides but that collaboration doesn't scale well
    - lecture (i.e. slides) is not a good way to teach skills

2. jekyll? are you serious? why this oldschool website renderer? You should rather use hugo!

- Mosè/Dan - Templates can provide infrastructure for a particular website layout.  (We don't have experience with hugo)
- Colin/Sue - it works! sometimes annoying, but it works! output looks quite nice. Frustraing to fix formatting mistakes and waiting for github pages to update. Running jekyll locally has dependency issues on ubuntu 16.04.

3. why use an engine to convert all content to a HTML website? choose a wiki? Everybody can edit a wiki! It is easy to learn and looks OK.
- Colin/Sue - we're undecided about this: pros and cons to each. Easy editing could be a problem, but can be enforced, wikipedia do this ok.
- Mosè/Dan - Both are markup languages.  Templates can be applied to either(?).
- Peter:  github provides more infrastructure to discuss contributions

4. prose text? All material is written in prose. Why do you bother doing that? I am jotting down my bullet lists and my learners are fine with this. 

- Tuomas + Peter: 
    - con
        - lesson pages not meant as a medium for presentation
        - can be daunting for non-native speakers in the beginning
        - good ideas take time to mature, e.g. https://carpentries.github.io/instructor-training/15-lesson-study/index.html#working-with-learning-objectives is mostly written using bullet points
    - indifferent
        - no publication of a more compiled form of a lesson
    - pro
        - better for convenying context and connections
        - meant for the instructor primarily  
        - good community spirit to invite non-native speakers to submit PRs
        - better for self-study for learners cannot attend
        - hand link to material after course

- Colin/Sue: prose provides a (theatrical) script to teach from and considerably more detail in an easy to follow format; prose is better for self-study, another important way to use a lesson. Bullet points harder to teach from, you need to think on the fly to fill in the extra bits

- Mosè/Dan:  Helps new instructors - preserves and transmits expertise of lesson authors.  Learners can use the material for self-study.

### setting up a github repo (for new lesson) feedback

- share with us something that you liked during the setup :+1: 
    - It worked fine
    - the instructions are very easy to follow and can be found throughout the repo (i.e. in comments)
    - The template github issue (for proposing a new lesson) was very helpful +1
    - there are mature lessons to check if everything went well 

- share with us something that you'd want to be improved during the setup :-1: 
    - its strange seeing all the history from the template development on your newly created lesson. I do wonder if starting from a zip/tarball would be better/cleaner.
        - Or more of a "shallow" clone?  A deep clone also makes the storage size larger.
    - updating new versions of the lesson template (new files, new configs) -> not an impossible task, but it takes time +1
    - we've discussed this in an earlier meeting, so I believe it is a work in progress: a place to include funding agency information, license (e.g. MIT license from source material for lesson), and so on. Acknowledging funders and lesson source material is critical.  

### repo essentials (skipped, but feel free to share something)

When working with matured lesson material of the carpentries such as [shell-novice](https://github.com/swcarpentry/shell-novice) or [python-novice](https://github.com/swcarpentry/python-novice-inflammation), what aspects of these repos do you recall yourself turning back to most of the time? (Feel free to structure your reply, but first sharing which material you refer to and second what aspect you consult the most.)

- the syntax for exercises

### repo necessities (skipped, but feel free to share something)

What aspects of working with a repo do you consider [boilerplate](https://en.wikipedia.org/wiki/Boilerplate_code) or something that you are not clear about why you have to do this?


## Topic Tags (skipped, but feel free to share something)

As documented [here](https://cdh.carpentries.org/the-carpentries-incubator.html#topic-tags), you add (github) tags to your lesson repo. If you follow a specific taxonomy, the Carpentries' Community Developed Lessons page will list your lesson accordingly.

- What are some of the potential benefits of your lesson being listed on the Community Developed Lessons page at this early stage of development?
- What would be the most helpful topic tag for your lesson?


## Until Next Time!

### feedback

**Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]


### homework

- don't forget the following
    - Read [the Working with Learning Objectives section of The Carpentries Instructor Training Curriculum](https://carpentries.github.io/instructor-training/15-lesson-study/index.html#working-with-learning-objectives).
    - Read [the Learning Objectives section of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:process-objectives).
    - Read the [Concept Maps](http://teachtogether.tech/en/index.html#s:memory-concept-maps) and [Seven Plus or Minus Two](http://teachtogether.tech/en/index.html#s:memory-seven-plus-or-minus) sections of Teaching Tech Together.
    - In your Lesson Design Notes, write 2-5 learning objectives for your lesson.
    - Create at least one episode file in your lesson repository and add 2-4 learning objectives in the objectives field for that episode.
    - (optional but recommended) [Set up your computer to build lesson pages locally](https://carpentries.github.io/lesson-example/setup.html#setup-for-local-rendering-of-the-lessons-optional).
        _Note: setting up a local installation of Jekyll is often not straightforward, but is important to ensure you can make good progress with the development of your lesson. If you run into trouble when following the instructions linked above, please post to the lesson-development Slack channel, create an issue on your lesson repository and mention @tobyhodges, email Toby directly, or attend one of the Lesson Template Helpdesk sessions._ Next Help Desk session is this Thursday, 15:00 UTC (this Zoom room)

 
## Resources
Add any relevant resources you found/discussed this week to the list below.

- "Computing Education as a Foundation for 21st Century Literacy" by Mark Guzdial, https://youtu.be/CS3j6Wtdus4


[sticky-notes-link]: https://forms.gle/HEVe3Zc9H5gWD8JW6
