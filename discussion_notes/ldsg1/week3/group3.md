# The Carpentries Lesson Development Study Groups Notes

## ## Group 3: Friday 26 February 2021 14:00-15:00 UTC


This document can be used for note-taking and resource sharing during Study Group discussions.

## Important Links

1. [The Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html)
1. [Study Groups "lesson" pages](https://carpentries-incubator.github.io/study-groups/index.html)
1. [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
1. [Teaching Tech Together](https://teachtogether.tech/)

## Participants

Please add your name, preferred pronouns (if any), GitHub username, and (when you have it) a link to your lesson repository below. See first line for an example.

- Toby Hodges / he/him / tobyhodges / https://github.com/carpentries-incubator/jekyll-pages-novice
- Graeme Grimes / he/him / ggrimes / https://carpentries-incubator.github.io/workflows-nextflow
- Jannetta Steyn / she, her / jsteyn
- Alessio Sclocco / he, him / [GitHub](https://github.com/isazi) / https://github.com/carpentries-incubator/lesson-gpu-programming
- Annajiat Alim Rasel / he,him,his / annajiat / https://carpentries-incubator.github.io/java-novice-inflammation
- Sarah Stevens / she, her, hers / sstevens2 / https://github.com/carpentries-incubator/docker-introduction
- Serah Rono / she, her, hers / serahrono / https://carpentries.github.io/community-facilitators-program/
- Richard Ostler / he/him/ richardostler / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Hanno Spreeuw / he, him/ [GitHub](https://github.com/isazi) / https://github.com/carpentries-incubator/lesson-gpu-programming
- Bailey Harrington / she, her / g: baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting

## Roles

**Group Facilitator(s)**: Toby Hodges, Aleksandra Nenadic, Serah Njambi Rono, Sarah Stevens
**Discussion Lead**: Graeme Grimes
**Notetaker**: Annajiat Alim Rasel

## Agenda

1. Welcome & Icebreaker 5 mins
    - Please sign in by adding your details to the Participants section above.
    - What carpentries lesson would you like someone-else to develop and why? Add suggestion below:
    - Majority voted to a no icebreaker.

1. What questions do you have after setting up/trying to set up your lesson repository? 10 mins
 
    * Alessio: set up without following documentation first, might be useful to point people to documentation if it exists. 
    * Bailey agrees that a directory mapping would additionally help to show people what to expect.
    * Bailey and Sarah would sit after to talk about the workshop website repo
    * Toby: added lesson examples and other resources, GitHub pages, Jekyll at the bottom of the page in the resources section. Agrees with Bailey's observation and will work to improve documentation around what each is in each folder and the content of each file
    * Richard: it is not clear what some of the tags in each file's content is set up to do, so would appreciate documentation to make it less confusing
    * Graeme: how did people setup the repo, cloning repo, having a local copy? Bailey's one was setup with the help of Toby but she had prior experience. Alessio made use of local repo.
    * Serah: templates are missing some of the expected functionalities, will share later.
3. What was confusing about the process? 10 mins
    * Serah: styles vs incubator template: was not sure which was the right one to work with. Toby helped to figure it out
    * Toby: happy to elaborate on the difference between the two if that is helpful
    * Hanno: found it straightforward
    * Graeme: found CDH content presentation very dense, and felt it would have benefitted from diagrams/visuals breaking up the text. Annajiat agrees
    * Jannetta: finds template format overwhelming. 
    * Toby: which ones specially are found to be confusing. 
    * Jannetta: started on a private repository last year, worked on the lesson alone for a while but didn't get much further. Currently unsure about where to start, repeated the process, went through the provided material and struggled with the decision to either create one, or try to use the one I created. I should have all the requirements in the Linux machines but found a lot have changed since last October. Toby will follow up after the call.



5. What are some of the potential benefits of your lesson being listed on [the Community Developed Lessons page](https://carpentries.org/community-lessons/) at this early stage of development? 5 mins
    * [name=Bailey]: New collaborators can discover it
    * [name=Alessio]: Letting other people know as soon as possible that there is some development in one "area"
    * [name=Annajiat]: Getting more helping hands and feedback. Avoid duplication of efforts 
    * [name=Richard]: Others in the Frictionless Data community are aware of what I'm doing and can see progress (no offers to collaborate yet though!). 
    * [name=Serah]: potential collaborators on the lesson get to share bits of the lesson they may be interested in collaborating on, early day questions and suggestions to help shape the lesson
    * [name=Sarah]: letting your potential audience (learners and instructors) know a lesson is in development
    * [name=Toby]: having  lesson listed bring in spontaneous contributions. Mailing to mailing list was useful to gain attention. 
6. What are some of the potential downsides of this? 5 mins
    * [name=Annajiat]: I'm sure pros will outweigh any downsides. :+1:
    * [name=Alessio]: Cannot really think about real downsides, maybe just having material that is so draft to be not usable but it's not a real downside if explained (and tags I believe are used for this)
    
    * [name=Serah]: early-day discussions about incomplete sections / works-in-progress may paint an inaccurate picture of the complete lesson and get us caught in heated and time-consuming / potentially draining discussion about where the work is going / investing time in convincing people vs working on the lesson, ++ :+1::+1:
    * [name=Richard]: everything is draft, so quality can be variable :+1:
    * [name=Greame]: did anybody approach to volunteer as a reviewer or helper
    * [name=Sarah]: People may suggest topics which are out of scope for your lesson
    * [name=Toby]: if you have only limited time, then getting people onboarded early on might be inconvenient to collaborate, taking up more time in the long run compared to finishing the work on own. 
        * Bailey: how do we opt-in? Send an email to Toby or team@carpentries.org. It is not an automated process in GitHub
        * Annajiat: is it ok to cross-post to cp-discuss mailing list and to Slack?
            * Serah: it is ok to post to both channels, but try to space out those messages by a week or so.

8. List the  topics you choose to add to your lesson repository below alongside your name? Did you use a strategy to decide what these topics should be? 10 mins
    * Graeme Grimes/ workflows-nextflow / English, lesson, rna-seq-analysis, workflow-management, pre-alpha, bulk-rna-seq, carpentries-incubator, 
    * Alessio Sclocco / gpu-programming-lesson / python, programming, GPU, English, lesson, pre-alpha, parallel-programming, carpentries-incubator, lesson-gpu-programming
        * Somewhere already there, so I guess it was Toby :)
        * was confused about where to add topics in the beginning - was looking at the repo files for things to edit before realising this was a separate ask in a spreadsheet.
    * [name=Bailey]: Toby listed [latex, typesetting, english, lesson, pre-alpha, carpentries-incubator]
    * [name=Jannetta]: In the repository that I created, I added: lesson, carpentries, carpentries-incubator, English, Java, programming-language, alpha
    * [name=Annajiat]: I'm trying to follow existing inflammation flavor to make a resource people can choose from based on the programming language they use in their institution, English, Java. People already can choose from python and r. Adding Java to the list of programming languages to choose from might be helpful.
    * [name=Richard]: Data, Frictionless, Agriculture
    * Toby: what strategy did people have in choosing topics?
        * Sarah: thought of words that would be great to add to titles (albeit with no space) and fitted those in as topics
        * Graeme: Had no specific strategy. How does the choice of topics affect the classification of lessons?
        * Toby: we are aiming to make the lessons more discoverable if they are interested in it. Working on a better searching and filtering system to make it easier for people to discover these lessons
        * Annajiat: how do we find lessons easier using Incubator labels? tried and chanced upon a barebones one.
            *  see the 'List of Lesson Topics' on the right side of the [community lessons page on The Carpentries website](https://carpentries.org/community-lessons/). 
            *  eventually, it should be possible to see which lessons are in what stage of lesson development - alpha, beta, etc.
            *  alternative way is to use GitHub search on the [Incubator organisation on GitHub](https://github.com/carpentries-incubator)
        * Annajiat: curriculum vs lesson development. Which should take precedence?
            * Toby: worked with someone who was making several lessons and wondered whether to make separate repositories or use one repository and have a really long resource. Settled on the first option as the best way to go
        * Alessio: read the topics in the spreadsheet and picked the most appropriate ones (according to me)
    * Bailey: it might take 20 minutes for the changes to show up
        * Annajiat: frequent referesh might lead to the page being unavailable for a while, have to wait it out.
    * Sarah: Gitpod allows rending on web which uses docker on the backend. Example: docker example that toby entioned, yaml needed. can be edited online. 
 
- homework (ALL=a task to be done by all collaborators on a lesson; ONE=a task to be done by only one collaborator per lesson):
    - (ALL) Read [the Working with Learning Objectives section of The Carpentries Instructor Training Curriculum](https://carpentries.github.io/instructor-training/15-lesson-study/index.html#working-with-learning-objectives).
    - (ALL) Read [the Learning Objectives section of Teaching Tech Together](http://teachtogether.tech/en/index.html#s:process-objectives).
    - (ALL) Read the [Concept Maps](http://teachtogether.tech/en/index.html#s:memory-concept-maps) and [Seven Plus or Minus Two](http://teachtogether.tech/en/index.html#s:memory-seven-plus-or-minus) sections of Teaching Tech Together.
    - (ALL) In your Lesson Design Notes, write 2-5 learning objectives for your lesson.
    - (ALL) Create at least one episode file in your lesson repository and add 2-4 learning objectives in the objectives field for that episode.
    - (ALL, optional but recommended) [Set up your computer to build lesson pages locally](https://carpentries.github.io/lesson-example/setup.html#setup-for-local-rendering-of-the-lessons-optional).
        _Note: setting up a local installation of Jekyll is often not straightforward, but is important to ensure you can make good progress with the development of your lesson. If you run into trouble when following the instructions linked above, please post to the lesson-development Slack channel, create an issue on your lesson repository and mention @tobyhodges, email Toby directly, or attend one of the Lesson Template Helpdesk sessions._

- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- The Lesson Example: https://carpentries.github.io/lesson-example/
- A breakdown of a lesson repository: https://carpentries-incubator.github.io/jekyll-pages-novice/repo_contents/index.html
- Incubator lesson tags: https://docs.google.com/spreadsheets/d/1KkmBtCu4PaNb5nzJAD82UHcfHQlaPY84qPVxw8WO8es/edit#gid=1895634731
- [GitPod](https://www.gitpod.io/about/)
    - see an example repo configured with GitPod here: https://github.com/jekyll-pages-novice

[sticky-notes-link]: https://forms.gle/JkSbZnjw3uXYE5nr9
