# The Carpentries Lesson Development Study Groups Notes

## Group 2: Tuesday 9 March 2021 14:00-15:00 UTC

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
- Sue McClatchy / she/her / smcclatchy / https://github.com/smcclatchy/statistical-inference-for-biology
- Peter Steinbach / he/him / github:@psteinb twitter:@psteinb_ 
- Colin Sauze / he/him / github:@colinsauze
- Mosè Giordano / he/him / github:@giordano
- Maria Dermit/ she /her/ github: @demar01
- Tuomas Koskela / he/him / github:@tkoskela

## Roles

**Group Facilitator(s)**: Mateusz Kuzak
**Discussion Lead**: Maria Dermit
**Notetaker**:  Sue McClatchy 

# Agenda

## preface

The following agenda is based on the assignments for today. Here is a quick recap:

> ## Homework Tasks
> 
> -  Create placeholder files for the other episodes in your lesson. Optionally, add learning objectives to these episode files too.
> - Schedule an opportunity to teach at least one episode of your new lesson. This trial run should take place between sessions 7 and 8 (26 March 2021 - 9 April 2021).
> - Read [Chapter 4: Designing Challenges of the Curriculum Development Handbook](https://cdh.carpentries.org/designing-challenges.html)
> In the Data Set section of your Lesson Design Notes briefly describe the features and requirements an ideal dataset would have.
> Add a link to the data set in the shared notes document.
> In the Data Set section of your Lesson Design Notes, briefly summarise:
        - why you chose these datasets/examples,
        - what advantages they have as a tool for learning,
        - and what disadvantages/difficulties/complexities they would introduce.

1. Welcome & Icebreaker 

What is a mythical creature from where you grew up? Describe this mythical creature below, state it verbally to the group, or do both as you prefer.
- (Tuomas) In Finland there are a lot of [elves](https://en.wikipedia.org/wiki/Haltija) everywhere. They are sort of spirits that look after many inanimate objects, such as houses, saunas, wells and so on. I use the word "elf" because the name is the same as the creatures who help Santa Claus, but it's a bit hard to translate.
- I come from Kraków, there used to be a dragon, living next to the castle, the dragon was killed by the shoemaker, who made a fake sheep, filled with sulfur. The dragon ate the sheep, then drunk water from Wisła river and "exploded". 
- (Colin) In Wales it has to be dragons. Symbols of them are everywhere, including our flag but the stories are much more vague. More recently there are stories of "the beast" which looks like a big cat, probably escaped from a zoo or kept as a pet which got too big. 
- (Dan) Hmm maybe the Headless Horseman, from the Legend of Sleepy Hollow, a short story published in 1820 by American author Washington Irving.  Maybe this is like a headless browser!
- (Mosè) I come from a city in Italy called Lecce.  We have a creature called "scarcagnulu", or "laurieddhu", a small ugly and hairy man who can visit you during the night, jump on your belly and aks for money
- (Maria) In the basque country there are quite a lot of. interesting mytical creatures. One of them is this guy called Olentzero, who is basically basque Santa Claus. The only difference is that he works as a coal miner, and gives coal as presents if kids have been naughty. 
- (Sue) In the U.S. [Bigfoot](https://en.wikipedia.org/wiki/Bigfoot) is a popular mythical creature with occasional sightings that include very grainy, nondescript photographs, or a picture of a gorilla at the zoo. 
- (Peter) [Rübezahl](https://en.wikipedia.org/wiki/R%C3%BCbezahl) - a mighty giant that is said to roam the mountains where my grandparents lived, similar to other creatures, he can also cast magic if different sorts; he punishes the bad and serves the poor in need
    - [name=toby]: I think this is my favourite ice breaker. All of these answers are so good!

### _Designing challenges_

1. Which of these two would you prioritise to select a dataset for your lesson, and why?
a) presenting learners with a realistic data set, containing noise and artefacts that may be difficult to account for or remove, or
b) using a simplistic or contrived example to provide a sequenced, hierarchical introduction of concepts to manage cognitive load
- Dan: suggestions for finding data sets with the right license and can be used for training? Is there a strategy?
- Peter: has used penguins data set, however, this is a tricky question since many open data sets are often not ready for teaching and require considerable effort to understand (seaborn)
- Colin: scikit-learn also has built-in data sets
- Mateusz: dplyr (tidyverse) has flights data set in R; also likes gapminder data, though this is not necessarily useful for every case
- Colin: list of interesting data sets/APIs https://github.com/public-apis/public-apis #thank you Colin!
    - [name=toby]: [Dryad](https://datadryad.org/search) is also a good option for finding openly-licensed data sets for re-use in lessons etc.
    - Dan:  I have sometimes also looked on https://datasetsearch.research.google.com/ (although haven't yet used one of these sets in teaching) .  Also Kaggle, although the quality of the data sets (e.g. metadata and provenance) is inconsistent.
    - [name=toby]: important to make sure the data is licensed for re-use without restriction e.g. CC0 - Google Data Set Search can be really powerful but you will need to double-check you are allowed to re-use and modify the data.
- Dan: Usually even with a realistic data set, it's possible to derive simple enough examples (for example by focusing on a limited number of variables).  And/or, you can derive a subset that is more appropriate for the lesson.
- Colin: Ideally I want a mix of both, at least if I want to teach something about data cleaning/wrangling. Perhaps using a partially pre-prepared dataset that i've removed some of the worst and most time consuming issues from but still leaving some issues for the learners to tackle. A good example, in the Python with gapminder lesson all the GDP fields begin (GDP_year) instead of just year (e.g. GDP_1952). Later in the lesson these get cleaned up. Or in the Unix lesson all of Nelle's pipline data is supposed to have an A or B indicating which machine processed it, but some has Z instead and there's a section on filtering the right data out and rejecting invalid data.
- Tuomas: Depends a bit on what you want to teach and the skill level of the audience, but in general I would prefer simplistic data sets to focus more on the concepts you want to teach and have less chance of random problems.
- Mosè: I prefer (b), adding the effort to clean the data can be distracting and time-consuming for the purpose of teaching some basic concepts
-  Maria : For my lesson I am going ot use a proteomics dataset, that is as realistic as possible to the kind of input data set I think learners of my lessons would have in their routine analysis. 
- [name=peter]: clearly b! but that entails, that the dataset is easy to grasp (one downside of the iris dataset btw)
- Sue: if I were teaching data wrangling, I would use a raw data set so that learners could go through the process of preparing data for analysis. This is a special case though. More often, the learning goals don't include data wrangling, so I would want a processed, clean data set to build upon.

- Dan: not mutually exclusive; you can start with a partly cleaned subset of data.
- Colin: sometimes you want to teach both data wrangling and data processing (e.g. Software Carpentry Python or Unix shell lessons)
- Tuomas: it depends on what you want to teach - if you are teaching programming, you would want clean data; if you are teaching data analysis, you would want some filtering or sorting
- Mosè: I prefer something simple because it is easier to adapt to learners from different backgrounds, though in some cases you might want to teach data cleaning
- Mateusz: it also depends on how you are using your data set in your lesson - are you using it only in a few examples, or throughout the entire lesson (e.g. Data Carpentry)
- Maria: question - the penguins data set is great, it has missing values for example. Do you know of other widely used data sets?
- Peter: metadata is sparse for many data sets, so it can be tricky to determine how they might be used
- Maria: lesson I'm planning to do is method-dependent, and I would like to present something that is more realistic
- Sue: a fan of Mine Cetinkaya Rundel (spelling?) and "let them eat cake first" approach, which requires clean data at the outset.

2. Did the search for an appropriate data set or example affect the order and/or set of concepts you plan to cover in your lesson?

- Colin: A bit of a mixture, I usually have an idea of what I want people to learn, and find data to help with that, but restrictions of the data can alter it.
- Dan: I generally try to lay out the concepts first, based off of the lesson objectives and episode objectives, but adjust if needed based on the dataset.  Sometimes this has resulted in overly "realistic" results, for example regression on two variables where the scatterplot looks like a blob rather than a line.
    - on teaching regression, I found [this website](http://sustainabilitymath.org/statistics-materials/) nice for linear regression as a starter
- (Peter) generally searching for a good dataset takes an immense amount of time, just experienced this myself; at the end, I stayed with something simple, even at the expense of through ML at 400 rows of penguins data (which is unrealistic, but works perfectly)
- Mosè: I'm still not sure about what data set to use (or if?), but this kind of search will certainly slightly influence the concepts to cover in the lesson
- not really - in my case the data already came with lesson content and exercises (Data Analysis for the Life Sciences by Irizarry & Love). I am only adapting their work and placing it into the Carpentries lesson format
- Tuomas: Roughly the concepts come first. You may always want to tailor the data set to the audience. 
- Maria: I normally aim to cover the concepts first and then search for a dataset that would work. Of course sometimes that dataset doesnt exits, so lessons may need some changes.


- Colin: I don't have the data drive what I teach, however, the data do have influence or refine what or how a lesson can be taught; still searching for the perfect data set for my lesson
- Dan: if designing lessons around objectives, you can find multiple data sets that work for an objective; however, at some point in lesson development a data set might not be the best for each objective
- Peter: stayed with penguins data to teach machine learning, which is fine because it reduces cognitive load
- Mosé: still haven't found a suitable data set, not sure whether to use a real data set or contrived; agrees with Dan - concepts come first, then adapt the rest
- Tuomas: agree - ideally concepts should be clear first, then depending on audience change data set if concepts taught are general enough


3. What kind of challenges (e.g. MCQ, Parson’s problems, fading exercises) are you planning to use in your lessons? Are there any that would work poorly? Explain your reasoning.

- (Peter) too many MCQs tend to become boring; I thought that finding bugs exercises is nice as it encourages people to insert asserts or similar constructs (if this line provides x,y,z; then the next line should give abc); I've desinged fill-in-the-blanks too as they align well with the content
    - [name=toby]: in our Jekyll lesson, we have flipped the "find the bug" format, telling them to deliberately insert errors of different kinds to get familiar with what the behaviour will be when a particular error is present. (This is most helpful for tools that do not have good error reporting...)
    - [name=peter]: check the 4th exercise [here](https://deeplearning540.github.io/lesson03/content.html) that I used as __find-the-bug__ exercise
- Colin: I think a mixture works well. But I do find learners often try and paste in and run code from exercises where this isn't required of them, e.g. faded examples of parsons problems. 
- (Mosè): I tend to prefer MCQs, it's easier to plan them, but probably a mixture of different types is the best choice
- Maria: I am planing to have few MCQs along each chapter. But I do agree with Peter that too many question turn the lesson boring. 
- (Dan) Reading the lesson development handbook reminded me of more typyes I can use (e.g. Parson's, etc.) so it gave me more ideas for challenges -- plus the guideline to intersperse challenges throughout the lesson, not just at the end.  For programming type lessons, I would use less of the Discussion type, and more of MCQ, Parson's, fading, etc.
    - [name=toby]: then you're _really_ going to like one of the homework tasks for this week, which is to read the Exercise Types chapter of Teaching Tech Together, which is more comprehensive than the list in the CDH (with more formats appropriate for learners who are not novices)
- Sue: much of what I plan to teach is conceptual, so often I prefer to have discussion questions for groups of 2-3 (think-pair-share). Peer learning and teaching can be powerful. I'm also moving away from teaching programming per se in favor of teaching data analysis. Discussion questions are easier to write than MCQ, Parson's problems, or faded examples, and they provide a way for people to get to know one another. An overarching goal of my teaching is to break down walls between people in different lab groups at my instituion, so opportunities to work in small groups and discuss ideas are very valuable.
- Tuomas: We try to use MCQs for discussion between the students, make them explain to each other why they chose different answers. Sometimes it works very well in identifying misconceptions. I haven't really used other types much, I worry that they end up taking too much time.

- Peter: even though these are good vehicles to assess progress, MCQs become boring so I have started to mix in other kinds of challenges. I introduce bugs into code and have them find them. I also use fill-in-the-blanks, though these are difficult to write.
- Colin: I like a mixture of different kinds, so that if someone doesn't do well on one type they'll have other opportunities.
- Mosé: generally prefer MCQ because I already know alternatives to present to students
- Maria: planning to use MCQ, though I find fill-in-the-blanks more motivating
- Dan: homework reading for today very helpful because it lists different choices; sometimes I forget to evenly space them throughout lesson rather than presenting all at end.

4. Do you adapt your challenges depending on the dataset, or format the datasets to adapt them to your challenges?




- homework:
- (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
    - (ALL) Recruit one helper for the Trial Run you scheduled last week.
    - (ALL) Read the Exercise Types chapter of Teaching Tech Together.
    - (ALL) Add exercises of at least three different types to your chosen episode page, to assess whether learners have met the objectives for that episode.
    - (ALL) Read CDH Chapter 5: Developing Content.
    - (ALL) Read the Expertise and Instruction episode of The Carpentries Instructor Training curriculum.
    - (ALL) Prepare for next week’s homework by reading the Episode Review callout from the next section.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/dM5NX9yqMb58uCMw5