# The Carpentries Lesson Development Study Groups Notes
## Group 3: Friday 26 March 2021 14:00-15:00 UTC

[**This week: Preparing to Teach**](https://carpentries-incubator.github.io/study-groups/07-preparing/index.html)

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
- Sarah Stevens / she/her/hers / sstevens2 / https://github.com/carpentries-incubator/jekyll-pages-novice
- Richard Ostler / he/him /richardostler / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Graeme Grimes /he/him/ ggrimes / https://carpentries-incubator.github.io/workflows-nextflow/
- Jannetta Steyn/ she/her / jsteyn / https://carpentries-incubator.github.io/java-intro/
- Annajiat Alim Rasel / he, =
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Hanno Spreeuw / he, him/ https://github.com/carpentries-incubator/lesson-gpu-programming
- 
(add more lines as needed)

Apologies: Alessio Sclocco

## Roles

**Group Facilitator(s)**: Sarah Stevens, Toby Hodges
**Discussion Lead**: Sarah Stevens
**Notetaker**: Toby Hodges

## Agenda

1. Welcome & Icebreaker 
    - If you could "Matrix-style" become an expert in something overnight, what would you choose, and why?
        - Annajiat: right now, I would love to understand how to make "François-style" magic fixes to a broken lesson template
        - Richard: just speaking another language - any language would do!
        - Jannetta: the ability to think of something under pressure
        - Graeme: I would like to be an expert at MarioKart so I can beat my brothers when we play online.
        - Sarah: Machine learning statistics
        - Toby: German!
        - Bailey: linear algebra
        - Hanno: French. I like the sound of it more than German. Or kite surfing!

2. How are you feeling about teaching soon?

Hanno: episode is completed and awaiting review. we have recruited a number of colleagues to attend the Trial Run. mostly interested to find parts where I did not bridge the expert gap i.e. things that I assumed people would know that they do not.
Richard: on balance I am feeling ok
Bailey: still working on materials but I think the Trial Run will be great(!) It will be late at night, but a good opportunity to gather feedback. 
Graeme: running mine as part of a lab meeting. I am constantly tinkering with it, should probably "freeze" it now and prepare to teach what I currently have.
    Sarah: I would encourage focussing on objectives and exercises, leave polishing text for later. (Toby: +1)

3. What feedback do you plan to collect from your learners during the trial run? Is there a particular aspect of your episode that you hope to gather feedback on?
(The feedback survey template: https://docs.google.com/forms/d/1SJSbCbQG-pO6WaA_QLQFUiXO5kDhr-QvmnRhVphnEpE/template/preview)

Hanno: planning short online check-ins with participants afterwards to find out how they felt about the lesson.
    Sarah: If you know them well, you can usually rely on getting good feedback that way.
    Hanno: I am a bit worried that our colleagues are not representative of the true audience we will get for future workshops with this lesson. The episode will also get reviewed by someone else withing the Study Groups.
    Bailey: likely to get different kind of feedback from reviewer than from someone attending the lesson workshop.
    Sarah: good to have both. Carpentries Instructors probably not representative of target audience either.
Richard: Haven't thought about a structured feedback yet, but would be after feedback on pace, content (too much/too little?), flow amd assumptions on learners prior experience.


4. How will you and your helper(s) work together during and after the trial run?
Richard: I will brief them to monitor the chat, to respond directly to problems there while I can keep teaching.
Sarah: I also ask them to note down issues that come up when they come up. Save you from having to remember them after the trial is over.
Toby: On that note, used to get frusterated when helping because the same problems happened each time and the instructor would notice each time but not fix it.  As the instructor is hard to remember the things that are broken that you notice as you are teaching.  You shouldn't expect yourself to be able to do this.  Have helper to write down this problem occured in this part of the lesson
Sarah: if you have a spare helper, asking them to record timings can be really useful. This is secondary to helping in the chat, troubleshooting etc. You may also want to coordinate who should respond to questions in the chat.
Toby:  Explicit expecation management is really good.  In terms of interruptions, people will ask questions in chat and learners are uncomfortable interruputing. So you might want to empower your helper to interrupt if they notice that a lot of people are getting stuck on something. Sarah: :+1: 
Richard: with that in mind, would it be sensibel to have more planned pauses?
Sarah: Absolutely! Especially ebcause you will lack the non-verbal cues/"reading the room" that you can benefit from in-person. Plan lots of opportunities to check in, use the non-verbal feedback buttons on Zoom. Force yourself to pause! Toby: +100



6. It is preferable not to teach alone. If you are the sole representative of your lesson in the Study Group, how will your preparations for teaching differ compared to what you do as a member of an instructor team?
7. How long do you expect it will take to teach your trial run of a single episode?
8. What are you looking forward to about the trial run?
Hanno: in original classes our lesson is based on, people will have to do a lot to get their system set up to work through the lesson. Now we have direct access to a GPU via Google CoLab, which takes care of all of this.
    Sarah: this sounds like a good thing to ask for feedback on.
    Hanno: yes. We are aiming for a novice-friendly lesson, and this really helps us reduce the amount of new concepts thrown at learners early. Being involved in this program has really helped me think about this process and teaching on a meta-level.
    Richard: for my lesson I want to use Python. In face-to-face setting, everyone would have their laptop in the room. What is the advice for teaching like this online? Everyone has their own setup, or connecting to a prepared instances e.g. CoLab/JupyterLab, etc?
    Sarah: both are possible - useful to keep in mind what will be useful for them after they leave the lesson.
    Hanno: go for a noetbook so they can still run it after the class.
    Bailey: I have taught with Jupyter Notebooks on the local server/JupyterLab but also explored options like CoLab that allow for interactive collaborative editing on a single notebook. I have heard that there can be some lag when used this way. Graeme and I explored another option, CoCalc, which has free options but those may not have the features you need, and paid accounts that provide a lot more customisation. Pricing seemed reasonable. Alternative to CoLab.
    Richard: yes. in the lesson Setup, installaton instructions should be covered. Screen sharing a Jupyter Notebook.
    Bailey: helping with debugging, we used screen sharing and provided an introduction for Helpers to learn how to use multiple screen shares.
    Sarah: brief learners to tell you via the chat the error message *and* what they typed.
    Bailey: we will try out Gitter chat for a workshop next week, to help with support.
    Toby: On the topic of teaching online, with something like a jupyter notebook, main advice from instructors teaching online for the last year is to allow even more time than you would in person.  The management of different windows takes a bit longer.  Need to prepare to repeat yourself for the learners who weren't looking at the right window.  If you can advice the learners that if they have access to a second screen that can be very helpful so they can organize their screen to see everything at the same time.
    Toby: ON the other point about using jupyterlab and other pre-setup space.  Big supporter of having people have it on their own machine so they can use it when they leave.  but for the trial run there is more argument for providing something like binder that is pre-setup.  Big issue with binder is that it times out after about 10 min and you loose the history.  This might not apply for the trial run though since there is not break.  Downside of the trial run is it might be somewhat unsatisfying for the learners because they won't complete a lesson. This might be also be another reason it is okay they don't have it set up after. 
    Jannetta: the last workshop I taught at the University presented a lot fo technical problems. E.g. Anaconda installed on Windows. Second, I don't have access to the details of who has registered and can't contact the learners far in advance - many turn up without their system setup. Used a JupyterHub VM from Docker, and I have run RStudio VM in a similar setup. Pointed learners towards that if they had trouble with their local setup. For my trial run (Java) planning to use repl.it as a backup. Includes an education package that may provide some helpful features e.g. seeing what the learners have written.
        Bailey: another option could be to install a Java kernel for Jupyter.

9. What do you expect will be challenging?
Richard: technical challenges of trying to coach people through problems while teaching online.
    Sarah: depends how big your group is. Helpers will be able to support you in this - can solve some issues in chat. https://carpentries.org/online-workshop-recommendations/ provides some good advice. Also planned breaks give you an opportunity to check in - impromptu breaks if a lot of people seem to be having a problem.
    Toby: Keeping the group small is good for the trial run.  Recommend between 2-8.  If you are doing this on your own, 8 is probably too many people.  In a SWC/DC/LC workshop ~6-8 learners per helper e.g. me+3 helpers = ~24 participants.
Graeme: has anyone tried using OBS to broadcast display and speaker?
    Sarah: I have used it but there is a lot of setup and wouldn't recommend trying to get learners set up to use it. I usually don't like it when live coding - I want the terminal/environment to be the big thing, keeping me small.
Hanno: it is going to be a lot of work.

11.  homework (**Remember there is no call next week.**):
    - (ALL) If you have not already done so, complete a review of the episode you were assigned.
    - (ALL) Coordinate with the helper(s) you recruited for your Trial Run, to ensure they are prepared to support you in teaching and collecting feedback.
    - (ALL) In a scheduled “Trial Run,” teach (at least) one episode of your lesson.
    - (ALL) Open issues on your lesson repository to record the required changes to your lesson that were identified during/after the trial run.
    - (ALL) Before the Study Group next meets, reflect on [the discussion prompts for the next session](https://carpentries-incubator.github.io/study-groups/09-reflecting/).

- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/3fFaqgBratEv8cU3A