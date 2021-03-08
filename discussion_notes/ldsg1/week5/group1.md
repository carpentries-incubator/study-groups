# The Carpentries Lesson Development Study Group Notes 

## Group 1 (Week 5): Monday 8 March 2021 14:00-15:00 UTC 
***Today's Episode: [Data Sets & Authentic Tasks](https://carpentries-incubator.github.io/study-groups/05-narrative/index.html)***   

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)
1. ["Index" CodiMD for this round](https://codimd.carpentries.org/ldsg1-home#) 


## Participants

Please add your name and preferred pronouns (if any)

- Toby Hodges / he/him 
- Nora McGregor / she/her
- Aleks Nenadic / she, her
- Jonathan Pelham
- Mike Trizna / he, him
- Daniel van Strien/ he, him
- Mateusz Kuzak / he, him / 
- Mark Bell / he, him
- Elnaz she/her
- Shrirang /he, him
Apologies: Batool Almarzouq

## Roles

**Group Facilitator(s)**: Aleks (host), Mateusz (co-host) 
**Discussion Lead**: Nora McGregor
**Notetaker**: Daniel van Strien

## Agenda

**1. Welcome & Icebreaker (10 mins)**
 
Using only emojis, describe how you feel things are going so far with your lesson development? 😀 Head over to https://getemoji.com/ where you can select and copy and paste here:

* Batool: 😅👥🙂🙃🥺😇😭
* Daniel: 😬😀🤡
* Elnaz: 🙂👍😅🧐😂😐😭
* Joni:🤯🥺🥺🥺🤞😅
* Mark: 👍👨‍🎓🎢
* Mike: 🤗😃🤞🤯
* Nora: 🤯🤪⏰👍🤝💡🙂
* Shrirang: 🙋 🙏 😅

* Aleks (I participated a bit of lesson development this week - earlier today): 🤯

*Funny little story: we used favorite emoji as an icebreaker on the old Carpentries EtherPad, which apparently couldn't handle emojis, and crashed the EtherPad for the whole workshop*

**2. Discussion Topic 1: Datasets (20 mins)**
    
>    1. How is your search for an appropriate data set going so far? 
>    2. Describe the dataset you have in mind. Is it noisy realistic dataset or a more contrived and simplified one? Explain your thinking. 
>    3. Do you anticipate your dataset choice having an impact on the way you will approach your lesson (in terms of, say, introducing new complexities, or new concepts you'll need to cover)?

Please consider the above and jot down a sentence or two here first before we discuss (no need to itemise as above, free text notes are perfect). If you have a dataset in mind please link to it here if possible as well:

    * Daniel: We are a little bit akward again here because our lesson is more conceptual and less code heavy. We have gone back and forth a bit on what would be the best way of trying to include some type of data for the lesson without turning it into a heavy hands on course. We currently have the idea of using an example dataset of digitised historic newspapers and using that to frame the lesson examples/discussion points and potentially asking participants to think of their own example to help them engage with the material more actively. 
    * Elnaz: we prefer to have a dataset with a control and 2 test samples including good and high quality and the noisy sample but at the same time dataset shouldnt be very big and we should be able to see the results im 2 days of the workshop. it is the optimistic thought, though searching still is going on and we are trying to get as close as possible to the optimistic one.
    * Joni: We have 16TB of flight data(QAR) from a major european airline but using it is tricky reputationally.  
    Working on anonymising it and reducing risk profile.  
    Legal risk low but it could be taken the wrong way.  
    The aircraft featured within it are still in service.
    It also requires a new parser to make the best use of it as our current tools are error prone and opaque to learners.
    * Mark: The episode I'm working on is about introducing terms and concepts. I would be more likely to point to example projects using data, but if I use any data it would be only to explain/visualise a concept (e.g. decision boundaries) and would therefore need to be small and simple - a very slimmed down version of data used later in the lesson.
    * Mike: Since our lesson is more conceptual than hands-on, I sort of discounted the dataset idea at first. But now, I think I'm interpreting this as 1 example to keep pointing back to for every concept we cover. It seems as if we are settling on historical newspapers as our example, since the combine text (for NLP), images (for Computer Vision), and metadata (for tabular ML).
    * Nora: The episode I'm working on in our main lesson is like Mark, more conceptual (will talk about bias in AI). However I was thinking there could maybe be something in there where people look at a dataset and review it for potential points where bias could make its way in...we'll see!
    * Shrirang: I have worked on prima india diabetes dataset for classification. It needs a little amount of cleaning. I think it a good dataset to explain the machine learning algorithms for classification and also realte to learners as people are aware of medical issues.

General notes: 
- ethical issues in sourcing the data
- finding something that connects to the audience
- idenitfying datasets can be challenging still
- how domain specific to be in what you choose?
- something tractable for the students in the time available

**3. Topic 2: Exercise Formats (20 mins)**

> 1. Which [exercise formats](http://teachtogether.tech/en/index.html#s:exercises) in the reading (or elsewhere) have piqued your interest for use in your lesson? 
> 2. Have you found your exercise format choice might impact your initial approach to your lesson?
 

Please consider the above and jot down a sentence or two here first before we discuss as a group. If you have identified an exercise format not in this week's reading please link to it here if possible as well:

    * Daniel: I think here we/I will use a variety of exercise formats. Finding a multiple choice which isn't too obvious might be a bit tricky. Don't want to have things which aren't engaging but also don't want to include answers as right/wrong in a scenario where it might be less clear cut i.e. there isn't only one way to for example label a dataset as part of an ML pipeline. I also want to include some more 'open ended' exercises that get participants to think more about their own collections/institutions i.e. start to fill out some of the steps they would take for a project, think about who they would involve etc. 
    * Elnaz: i will use various exercises and I will set them for the dataset we are using in the lesson. but I try to not make it much complicated and it will be a variety of the task we do in the session.
    * Joni: Probably a mix of multiple choice, fill in the blanks, and code & run.  Probably only one C&R max each day as an end of day problem.
    * Mark: I have been thinking of multiple choice to test understanding of concepts, although fill in the blanks will probably work too. But I also like the idea of exercises where learners can interact with the data/algorithm and see what happens when they change something.
    * Mike: This section seemed pretty irrelevant to our group, since it is very specific to coding-type exercises. One exercise style that's not mentioned here, but I noticed shows up a bit in the Instructor Training (which is also mostly conceptual) is giving a very barebones intro to a subject, forming breakout groups to discuss their perceptions or ideas about that topic, and then going deeper into the subject and being sure to correct any misconceptions you spot during discussion. Here is an example: https://carpentries.github.io/instructor-training/23-introductions/index.html
    * Nora: The exercises in my episode will be very discussion oriented, I've taken a cue from existing Library Carpentry lessons which do this very well. I will have quizzes for testing recall of jargon/terms as well.
    * Shrirang: The exercises in my discussion will complement theory with incremental codes which will finally lead to the complete submission for verification. However we could verify the small incremental codes and reinforce the learners capbilities in understanding our concepts correctly.

General notes:
- exercises build up on top of each other, incremental coding exericses 
- considerations about how long code/exercises will take to run 
- interaction/exploration options for letting participants explore concepts in a 'hands-on' way. 
- make sure the exercises link back to the motivation that might be driving people to follow the course/lesson
- use of psuedo code as a way of introducing algorithems without becoming 'stuck' in the code part
- if not using pseudocode consider getting students to add comments on each line about what is happening

**4. Homework for Week 6: Monday, 15 March 2021 and Questions for Toby (5-10 mins)**
  - (ALL) Recruit one helper for the trial run you scheduled last week.
  - (ALL) Read the [Exercise Types chapter of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:exercises).
  - (ALL) Add exercises of at least three different types to your chosen episode page, to assess whether learners have met the objectives for that episode.
  - (ALL) Read [CDH Chapter 5: Developing Content](https://cdh.carpentries.org/developing-content.html).
  - (ALL) Read the [Expertise and Instruction episode of The Carpentries Instructor Training curriculum](https://carpentries.github.io/instructor-training/03-expertise/).
  - (ALL) Prepare for next week’s homework by reading the [Episode Review](https://carpentries-incubator.github.io/study-groups/05-narrative/06-content#episode-review) callout from the next section.
  - If you are the [assigned Discussion Lead](https://docs.google.com/spreadsheets/d/1nk6sUI00XGPKL7eNms0VNfcSySpElUDtI3utejXBRC8/edit?usp=sharing) for next meeting, a few days before each call make a copy of the [shared notes template](https://codimd.carpentries.org/ldsg1-home#) and fill in the agenda. Send a link to the Curriculum Community Developer (Toby), who will fill in the homework tasks, the "sticky notes" survey link, and any logistical points for discussion. 

**4.5. Rescheduling Week 8 Call**
Monday 5 April is a public holiday (Easter Monday) in many countries, so we may need to reschedule the call currently planned for that day.
Please place an 'x' next to the times when you would be available.
Monday 5 April 14:00 UTC (i.e. as currently planned): xx
Tuesday 6 April 13:00 UTC: xxxx
Thursday 8 April 13:00 UTC: xxxx
Thursday 8 April 15:00 UTC: xxxxxx
Friday 9 April 13:00 UTC: xxxx
Friday 9 April 15:00 UTC: xxxx

_Apologies from Aleks - I will be on annual leave._

**5. Weekly "Sticky Note" feedback**: Please take a minute to give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Today's Discussion Highlights and Resources
Daniel and all to add any particular useful highlights/resources raised during today's discussion (not covered by individual contributions above).

- [Example of a less code focused exercise format](https://carpentries.github.io/instructor-training/23-introductions/index.html)


[sticky-notes-link]: https://forms.gle/vNhXSJ1nmaVPhb8D9

