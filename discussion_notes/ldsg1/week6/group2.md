# The Carpentries Lesson Development Study Groups
## Group 2: Tuesday 16 March 2021 14:00-15:00 UTC

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

- Tuomas Koskela / he-him / github: tkoskela
- Colin Sauze / he-him / github: colinsauze
- Peter Steinbach / he-him / github: psteinb
- Dan Kerchner / github: kerchner
- Maria Dermit/ github: demar01
- Sue McClatchy / she-her / github: smcclatchy
- 
- 
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Mateusz Kuzak, Toby Hodges
**Discussion Lead**: Colin Sauze
**Notetaker**: Peter Steinbach

## Agenda

1. Welcome & Icebreaker 
    
What is your top tip for remote working?

- Toby: if (like me) you cannot stop look at yourself while on a Zoom call, hide the display of your video feed (if you don't like looking at your own face) or move your video box close to the webcam so it looks like you are making eye contact with the camera (if you do like looking at your own face).
- (Tuomas): **Go easy on yourself**, take breaks, remember we are in a crisis and you can't get as much done as you normally would (if you still remember what normal was like)
- Dan: Don't forget to get outside for walk breaks (**breaks from technology**) - fresh air / sunshine / exercise
    - more breaks for carpentry like workshops
    - Dan: lot of faces staring at you might trigger being intimitated -> pros/con of seeing learners
    - Colin: zoom collapses learner windows
    - Sue: humans read emotions from people's faces (majority of communication is non-verbal)
        - do icebreaker with camera on, ask learners to turn off cameras after that
    - Mateusz: did a workshop without view of the learners -> traumatising experiences
        - at least seeing 2-3 faces is nice
        - even worse in webinar face 
    - Peter: experimenting with the flipped classroom
- Colin: Turn on your webcam if possible. Turn off mute!
- Peter: hackmd pads for notes and decisions are something magnificant that I hope we can keep for the time AFTER the pandemic
    - Colin: have been part of the carpentries before the lockdown
    - Dan: codimd is nice for markdown savvy learners, etherpad was the default
    - Maria: gdoc? 
        - Colin: scalability issues
        - Peter: some (subjective) data security issues
- Maria : doing chunks of work without interruptions and having longish breaks away of desk.    
    - Maria: easily being distracted can become a problem
    - Colin: non-stop switching due to notifications
    - Tuomas: switch off notifications what so ever, read mail only 2x a day
- Mosè: stand up and walk every couple of hours.  Talk with real people if possible
    - Colin: different when having family around
- Mateusz: block time for lunch, make a meal schedule with your partner/girlfriend/wife; Co-working sessions
    - co-working especially beneficial for people alone at home that work on projects
- Sue: [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) for time management
    - helpful for breaking apart large chunks of work (grant/paper writing)
    - Peter: I use pomodoro for changing my pose (sitting, knee'ing, standing, ...)


2. What are some of the advantages of writing exercises before the examples and explanations learners will need to be able to solve them?


- Tuomas: Kind of like test based development. It makes sure that the examples and explanations are relevant to the problems they are meant for.
    - Peter: there are also other approaches, https://youtu.be/qGYGhpwG9iI
        - from my experience: staying flexible and listening to leaner feedback is essential (and acting on it)
        - if you do that, than the method is somewhat irrelevant 
    - Mateusz: tell learners if material is premature
- Mosè: it can help to make sure you get the learning objectives
- Colin: it structures the lesson around the exercises not the explanation
- Dan: Ultimately, the exercises are where the learners apply what they learn from the examples and explanations, so it's like starting with the objectives (exercises) and then writing the content learners will need in order to succeed with the exercises.  Breaking down the exercises helps define the smaller skills that the content will need to teach. 
- Sue: exercises demonstrate whether or not learners understand a new skill or new concept. When you write exercises first, you think about precisely what learners need to learn before you start explaining it to them. This helps to focus your explanation to only that which learners need in order to demonstrate a skill or concept, which is an efficient way to develop a lesson.
- Maria: It forces me to do reverse lesson development. The exercises are the goal and the examples and explanations are what are gonna get learners there
- Peter: it keeps focus and motivates me to think of the conceptual steps that I want to teach; I admit though, it requires substantial practice



3. What are some of the benefits of writing example code blocks before the “connective tissue” text between them?

- Colin: again it structures the lesson around the code examples, not the text. 
- Tuomas: I think it's similar to the excercises, it makes it easier to check that you are describing the right things in the text.
- Dan: Ultimately we are teaching coding skills, so the purpose of the explanatory text IS to explain code, so we would start with the "exhibit" to lead into and explain.
    - Colin: saw lessons with no text, only code. this is tricky to teach, but not impossible.
    - Dan: carpentries style captures the teaching of multiple people, text comprises knowledge of many contributors
- Mosè: I think the text between them is mostly the sorrounding environment, that can also be adapted to different situation 
    - Maria: it may help getting the structure that complies with the 7+2 rule. But it could be the case when connecting the exercises some extra examples may be needed (>7+2). 
- Sue: Depending on the code, the output might change. If you write the text before the code, the text might not reflect the code output.
    - Colin: code tells a story
- Peter: I can test content (helpful when dealing with data) and see if the storyline of my content adds up
    

4. What are some common mistakes and misconceptions you encounter from learners? How can we diagnose and address these?

- Tuomas: People are so used to GUIs that it takes some convincing the shell is representing the same computer as the graphical operating system and the same operations can be performed there. I think it's useful to show the two side by side to demonstrate this.
- Dan: Getting used to the idea that there may be useful informaion in what at first seems like a cryptic error message.  It often takes them time to get used to variables that can contain objects of different structures (single-valued vs. a data frame, etc.).  Case-sensitivity and spacing-sensitivity (or lack thereof) are also something they are not used to having to be careful about -- in an Internet world, a lot of user interfaces are not case sensitive.
    - [name=toby] re: interpreting error messages and making deliberate mistakes as teaching opportunities, we added a couple of "Troubleshooting" exercises into the Jekyll lesson, to force users to make particular mistakes in controlled conditions and become familiar with the "symptoms" associated with different kinds of error (see https://carpentries-incubator.github.io/jekyll-pages-novice/starting-jekyll/index.html#exercise-practice-with-troubleshooting for an example)
- Peter: datatypes in python (diagnose by playing with the +operator); hidden state e.g. with matplotlib configs (deliberate/reproducible errors and asking learners to what just happened)
- Mosè: for the Python lesson, indentation in particular.  In general, sometimes details of the syntax may not be always clear.  Take notes of these issues for future workshops
- Maria: mistakes when learners come from other languages ( for example the need to use or not parenthesis in a python function). 
- Sue: project management - organizing each project the same way so that you always know where the data are, the scripts, the results, etc. Data Carpentry lessons deals with this at the outset, however, learners could be given more practice in differing contexts. Another common mistake is messy code, so more training in how to write clear, well-documented code would be in order.
    - learners in their work tend to produce non-clean code, carpentries' material tries to tackle this
    - Colin: tendency to teach code that works
- Colin: inconsistencies in libraries, for example in pandas dataframes using df.loc("field") and df["field"]. Helpful to have some kind of quick reference in front of you reminding you of common syntax. Also confusing different bracket types and I think communicating these to users is hard, what do you call a ( { and [?
    - [the Library Carpentry "Busting" activity](https://librarycarpentry.org/lc-overview/03-jargon-busting/index.html) is one way to address the communication issue/agree on a common vocabulary
        - run at the beginning at the workshop
        - provides indication of prior knowledge

5. How do you plan to account for your expertise while you write your lesson?


-Homework:
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

- [The Lesson Review Assignment sheet](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing)
- 
- 

[sticky-notes-link]: https://forms.gle/ngPfT3pk8GSscCxB8