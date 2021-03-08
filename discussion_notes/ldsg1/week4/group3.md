# The Carpentries Lesson Development Study Groups Notes

## ## Group 3: Friday 5 March 2021 14:00-15:00 UTC

This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups &#34;lesson&#34; pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)
1. [&#34;Index&#34; CodiMD for this round](https://codimd.carpentries.org/ldsg1-home#) 

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice - watching the notes but on childcare duty this afternoon :)
- Jannetta Steyn / she, her/ jsteyn
- Alessio Sclocco / he, him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Sarah Stevens / she, her, hers / sstevens2 / https://github.com/carpentries-incubator/jekyll-pages-novice
- Richard Ostler / he/him / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Graeme Grimes / he/him  / ggrimes / https://github.com/carpentries-incubator/workflows-nextflow
- Hanno Spreeuw /he, him/ https://github.com/carpentries-incubator/lesson-gpu-programming
- Bailey Harrington / she, her / https://github.com/carpentries-incubator/latex-novice-typesetting
- Annajiat Alim Rasel / he, him, his / https://github.com/carpentries-incubator/java-novice-inflammation
- Shrirang Kulkarni /he,him/https://github.com/drshrirang
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Aleks Nenadic, Serah Rono, Sarah Stevens
**Discussion Lead**: Richard Ostler
**Notetaker**: Hanno Spreeuw

## Agenda

1. Welcome &amp; Icebreaker 
    
2. What are described as _learning objectives_ in the reading material are sometimes referred to as _learning outcomes_ elsewhere in the literature. Do you prefer one of these terms to the other? Do you think either term is more appropriate to describe the skills a lesson/episode will teach? If so, why? 
    - (**note to host: please include this question for discussion** - it will help us decide what changes to make while updating the Instructor Training curriculum. You don&#39;t need to devote a lot of time to discussing this, but it would be really helpful to get the thoughts of the participants.)
    - :+1: for **learning objectives**: :+1: :+1: :+1: :+1:
    - :+1: for **learning outcomes**: :+1: 
    - :+1: consider them to be different concepts: :+1: :+1: :+1: :+1: :+1: :+1:
3. Did anyone try to set-up local development (please add below if you did, which OS and how you found it - easy; OK; difficult; impossible!). Did anyone use R?
    - [name=Bailey]: Have not yet set up local build for this, but have done so previously for my own sites.
    - [name=Alessio] haven&#39;t had time to test the local setup because I have been fighting with FPGAs :) So far I have been pushing to github for rendering.
    - [name=Graeme] Setup localy on Mac OSX catalina , but have edit my content using the web browser.
    - [name=Jannetta] I have set it up. I&#39;m using Linux. But I did it October last year so I can&#39;t remember how easy or difficult it was.
    - [name=Hanno] Seemed very straightforward on my Manjaro Linux machine.
    - [name=Richard] straight forward on WSL2/Unbuntu
    - [name=Annajiat] WSL2 isn&#39;t supported on my machine. Not sure about WSL1. Does any know if WSL1 or git bash would work for the setup and execution?
        - [name=toby]: according to [the setup instructions](https://carpentries.github.io/lesson-example/setup.html#option-2---using-windows-built-in-applications) it should be possible to set it up with native Windows tools... I have no direct experience of this I&#39;m afraid.
    -
    a. **Question for Toby**: will local development practice change with new lesson template or will it still be Ruby/Jekyll?
        - [name=toby] **the new template is being designed to run on RMarkdown, which means local builds of the lesson will require R &amp; RMarkdown. Jekyll, Ruby, GNU Make, and Python will no longer be required. (You may need to install other kernels for RMarkdown where you are writing a lesson with a different programming language than Python or R.)**
        - Follow-up: Will the formatting of the lesson in markdown change with the new template?
            - [name=toby]: yes, a little. e.g. the exercise and solution blocks will not need to be written as blockquotes anymore. but there willa lso be tools to convert existing lessons to the new format. One other thing you might _want_ to change after the switch: the use of RMarkdown will allow you to write code blocks that are executed when the lesson is built, meaning you no longer need to manually write the output of commands into your lessons, and remember to update that output whenever the code changes...
4. How did you find writing _learning objectives_? 
    a. Was it difficult or easy? 
    b. Has it helped to make it clearer what you want your lesson to teach or change what you want to teach? 
    c. Did you evaluate your learning objectives using **Blooms Taxonomy**
    (each person please put one thought below).
    - .
    - Shrirang: Outcome perhaps more appropriate than objective.
    - [name=Alessio] not exactly difficult, but tricky to be right. Working on this we ended up deciding on adding another episode in between the two episodes we had already planned :)
    -
    - Discussion of what level of blooms taxonomy is apporpriate for your lesson 
    - [name=Sarah]They feel core to the reverse instructional design approach to me.  Where you think carefully ahead of time about the learning objectives/outcomes and then it helps you to integrate them well into your exercises and eventually your lesson content
    -
    -
    -
5. Did you use concept maps to develop the lesson structure?
    a. Is concept mapping a familiar idea to you? 
        - :+1: Familiar to me:
        - :+1: New to me:
    b. Did it help or did you use a different method?- 
    - Mixed views on concept maps, some people  like but some strong opinions against. 
    - [name=Bailey] :-1:
    - [name=Alessio] we have not tried it yet, but we will try to sketch something next week
    - Shrirang - can be useful for drawing the overall lesson plan, but use objectives to express the detail
    - - Graeme - can be useful for sharing ideas, but not sure if doing it right.
    - Sarah: I also don&#39;t love concept maps either but have used them a few instances and can see how they can be useful for various tasks.  Communicating with others, and limiting conecepts and splitting episodes. do not worry about doing right, so much as making it useful for you and the other lesson developers you are working with.
6. How did you find the infrastructure for developing a lesson? Did the episode template and instructions make sense? 
    a. What was good/helpful?
    - [name=Alessio] The episode template is simple enough to work with. Not much overhead except text editing.
    b. What could be improved?
    - Including template files for episodes instead of just one for the introduction to be edited. :+1:
    - .


9. 
- homework (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
    - (ONE, but discuss with your collaborators first) Create placeholder files for the other episodes in your lesson. Optionally, add learning objectives to these episode files too.
    - (ALL, see link for more info) Schedule an opportunity to teach at least one episode of your new lesson. This trial run should take place between sessions 7 and 8 (26 March 2021 - 9 April 2021). See [the Episode Trial Run callout on the &#34;lesson&#34; page](https://carpentries-incubator.github.io/study-groups/04-objectives/#episode-trial-run) for more details.
        - When you have scheduled your trial run, add details to this CodiMD: https://codimd.carpentries.org/ldsg1-trial-runs
    - (ALL) Read [Chapter 4: Designing Challenges of the Curriculum Development Handbook](https://cdh.carpentries.org/designing-challenges.html).
    - (ONE, but discuss with your collaborators first) If your lesson will use an example dataset, in the Data Set section of your Lesson Design Notes briefly describe the features and requirements an ideal dataset would have.
    - (ALL) Identify at least one appropriate example data set/narrative for your lesson, and add a link to the data set in the shared notes document.
    - (ALL) In the Data Set section of your Lesson Design Notes, briefly summarise:
        - why you chose these datasets/examples,
        - what advantages they have as a tool for learning,
        - and what disadvantages/difficulties/complexities they would introduce.

### Trial Run info
::: info
**Why?**
- We include a Trial Run task in the Lesson Development Study Groups program because **teaching content for the first time is not the end of the lesson development process** - it is an important step along the way.

**When?**
- Trial Runs for this round should take place **after your Group Discussion in the week of 22-27 March and before your Discussion in the week of 5-10 April**. (If you cannot schedule the Trial Run in these dates, contact Toby to discuss alternatives.)
- These trial run sessions are expected to take **no more than 60 minutes per episode**.

**What?**
- Think about the dependencies of your episode: **it might be better to trial an episode early in your lesson**, so that your audience do not need to already know what would have been taught earlier.

**How?**
- Your Trial Run can be private (i.e. audience attends by invitation only), open for anyone to register, or anything in between - just make sure you have an audience who can give you feedback on the lesson! You might consider asking for volunteers from your Study Group, or colleagues that you know would have the relevant experience to follow your lesson.
- If you need access to a paid Zoom account for your Trial Run, contact Toby. He can provide you with one of The Carpentries Zoom rooms. He can also help you advertise your trial run, list it on The Carpentries Community Calendar, etc if you want to open up your Trial Run.
- Think about the **Code of Conduct** you will follow for your Trial Run - if you do not have your own (e.g. for teaching colleagues at your institution), you can treat the Trial Run as an extension of this Study groups program and use [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html).
- However you choose to do it, please **list the date/time of your Trial Run on https://codimd.carpentries.org/ldsg1-trial-runs when you have scheduled it**.

**For collaborative lessons**
- Where multiple participants are collaborating on a single lesson, each Stduy Groups participant should **teach one episode of that lesson each** during the Trial Run. Schedules permitting, you should schedule to teach these trial runs together.

Trial Runs are also described in [the Episode Trial Run callout on the &#34;lesson&#34; page](https://carpentries-incubator.github.io/study-groups/04-objectives/#episode-trial-run).
:::

### Feedback

- **Weekly &#34;Sticky Note&#34; feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/2KTkPwqFxdCxFEVC6


