# The Carpentries Lesson Development Study Groups Notes
## Group 4: Friday 12 March 2021 23:00-00:00 UTC

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

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice / facilitator
- Jon Wheeler / he/him / jonathanwheeler01 / https://github.com/carpentries-incubator/data-management-pipelines-engineering
- Fan Du / she/her / caifand / https://github.com/carpentries-incubator/citable-software
- James Foster / he/him / jd-foster / https://github.com/carpentries-incubator/julia-data-workflow
- Yuka takemon / she/her / ytakemon / facilitator
- Kate Hertweck / perceived pronouns / k8hertweck / facilitator
- Alex Casper Cline / he/him /alexcasper / discussion lead
- 
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Toby Hodges; Kate Hertweck; Yuka Takemon
**Discussion Lead**: Alex Cline
**Notetaker**: Fan Du

## Agenda

1. Welcome & Icebreaker 
    - (Need an idea for an icebreaker question? Check out [the list of icebreakers from the Instructor Training curriculum](https://carpentries.github.io/instructor-training/icebreakers/index.html).)
    - One thing interesting/exciting that happened in the last week; and one thing you are looking forward to doing for this month
    (Fan lost track of many nice & joyful stories here. Apologies! But people talked about cancer genomics lab work, data analysis, graphic design, reading group, upcoming Easter, fireworks in the wet Australia, inspiring teaching demos in the Carpentries instructor, new hire for the director of mentorship in the Carpentries!)
    
2. Class Discussion: Datasets and different exercises
    - Q1: What potential datasets do people work with in preparing their lessons?
        - easy version: what dataset are you looking at?
        - hard version: In what domain/discipline are you looking for your dataset?
    - Reactions 1:
        - Ronda has been building the dataset for 2 months, questioning herself if she needs to choose between R or Python. In self-debates she confirmed her goal for the dataset, to be clean, integral, and useful for her students
        - Jon points to a training dataset published by UCI about electric power consumption: https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption. The goal is to do a time series analysis with anomaly detection. A public dataset that Jon is building his lesson around. Developing with students and colleagues in Mathematics an analytical workflow.
        - Yuka is not in active lesson development at the moment. But she is a current maintainer for [Data Carpentry R Genomics lesson](https://datacarpentry.org/genomics-r-intro/) using a yeast (?) genomics dataset. They have public datasets from [NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/) for wrangling practices via tidyverse in R.
        - James may not use a dataset for his lesson development in case of the misjudgment of the complexity of datasets being used. He has encountered genomics datasets (of butterflies!) with a publication associated. He was familiar with the datasets being used in the SQL lessons in the Data Carpentries. Each dataset being used in existing Carpentries lessons has their advantages. Quality is helpful (perhaps particularly for learning purposes). [butterfly genomics publication](https://academic.oup.com/sysbio/article/57/2/231/1622699)
        - Alex has a personal dataset of the natural museum in London. He got it by working with students in a field trip. It's amazing but difficult, not the best choice for pedagogical purposes. 
        - Kate would prepare for a wide range of datasets for students to choose from based on their interest. Dataset used for teaching usually needs to be somewhat contrived (e.g., for simplifying the steps). Seems the lesson should be learned here is to curating your teaching resources and do the necessary tweak for teaching.
        - Toby commented on the skills intended to be taught matters for the choice of dataset and its "contrivedness". Take a designed dataset or a realistic dataset for enabling fast moves in reaching your teaching goal. Choosing a narratively attractive dataset may provide strong motivation for learning.
        - Fan, datasets are software code. Catering to python and/or R users. Open source, GitHub codes as datasets. Letting students make their own choice for programming language as it doesn't matter. 
        - 

    - Q2: Effective lesson exercise examples?
    - Reactions 2:
        - James, not a fan of MCQs but a good entry point. MCQs are often written in a way that makes you think about relevant and irrelevant information. Fill-in-the-blanks feels like a better fit to my lesson. Give most of a function definition and ask learner to figure out what objects need to be placed where.
        - Fan, current decusriegenn t design of lesson is first half conceptual, second half more applied/practical. In teh conceptual half, we could design multiple-choice questions and some discussions to keep learners engaged. Present different decisions you could make to make your code more citeable and ask them which fits best and to state their rationale. Fill-in-the-blanks to get audience familiar with the formats I am trying to teach. It might also help to get the learners to write the whole thing. Find out more in a trial.
        - Jon does not have a preference for specific excercise choices. Referring to the Bloom's Taxonomy, the task challenge is the applied step (also possibly include other steps). Considering the COVID-19 situation and Zoom setting, so think practically and pedagogically at the same time.
        - Yuka suggests the approach of starting with MCQ perhaps (simpler questions for scaffolding; and also good entry points for audience). MCQ is also good to make contrasts between choices (so potentially deepening the learning effect). Have more blanks as getting deeper into the lesson content, designing challenges based on the building-up of learning process.
        - James: Simply typing exercises are useful at the certain level.
        - Alex found a regex lesson in the Carpentries where he thought the exercises are good and providing discussion opportunities for learners.
        - Toby shared his recent experience with the [Jekyll page novice course](https://github.com/carpentries-incubator/jekyll-pages-novice): deliberate breaking and experience the symptoms of the problem. This technique has been very successful. As a result, they introduced several exercises with this technique into the lesson.  
        - Ronda thinks about "fill-in-the-blank" exercises to have audiences conceptualizing/thinking about the structure of the dataset.
        - Alex's comment: Not just teaching a particular tool but also a mindset.
        - James's question: How much time do you spend on getting familiar with/adjusting the dataset? This is relevant to assessbility of the learning outcomes too.
        - Fan, teachers or learner persepective? (James clarifies from the learners perspective)
        - James - How much do you assume re: learners knowledge of the  dataset?
        - Jon: information data vs. practice data. How much time would learners spend to get their hands on? Building context seems to be relevant to learners actual levels.
        - Kate picked a dataset from a public database with not abundant documentation. So she had to do some hard thinking on how to have learners understanding the dataset scheme. She alerted in advance about the wierdness in the dataset, and suggested the right place (at the column level) to jump in. 
        

- homework (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
  - (ALL) Recruit one helper for the trial run you scheduled last week.
  - (ALL) Read the [Exercise Types chapter of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:exercises).
  - (ALL) Add exercises of at least three different types to your chosen episode page, to assess whether learners have met the objectives for that episode.
  - (ALL) Read [CDH Chapter 5: Developing Content](https://cdh.carpentries.org/developing-content.html).
  - (ALL) Read the [Expertise and Instruction episode of The Carpentries Instructor Training curriculum](https://carpentries.github.io/instructor-training/03-expertise/).
  - (ALL) Prepare for next week’s homework by reading the [Episode Review](https://carpentries-incubator.github.io/study-groups/05-narrative/06-content#episode-review) callout from the next section.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- [Mine Çetinkaya-Rundel's Keynote Talk from CarpentryConnect Manchester 2019: "Let Them Eat Cake (First)"](https://www.youtube.com/watch?v=fQ4t7p6ZXDg)
- 
- 

[sticky-notes-link]: https://forms.gle/pdmnx7JbzU8RySjx6
