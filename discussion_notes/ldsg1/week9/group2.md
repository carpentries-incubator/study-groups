# The Carpentries Lesson Development Study Groups Notes
## Group 2: Tuesday 13 April 2021 14:00-15:00 UTC

[**This week: Collaborative Lesson Development**](https://carpentries-incubator.github.io/study-groups/10-collaborating/index.html)

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
- Peter Steinbach / he/him / psteinb
- Colin Sauze / he/him / colinsauze
- Mose Giordano / he/him / giordano
- Sue McClatchy / she/her / smcclatchy
- Mateusz Kuzak / he, him / mkuzak
- Tuomas Koskela / he, him / tkoskela
- 
- 
(add more lines as needed)

Apologies: Maria Dermit

## Roles

**Group Facilitator(s)**: Toby Hodges, Mateusz Kuzak, Aleksandra Nenadic
**Discussion Lead**: Toby Hodges
**Notetaker**: 

## Agenda

1. Welcome & Icebreaker 
    - what is a collaborative project that you really enjoyed working on? can you identify what made it so enjoyable?

* Mateusz: Four simple recommendations for Open Source Software (4OSS): good team, it helped that we mostly knew each other already,
* Colin: My first postdoc project, building a robot boat for surveying glaciers in Greenland. Very multidisciplinary, interesting to watch all of these different skills come together to produce something. There was a great moment when we got some plans from an engineer and over a few weeks these emerged first into a printout, then some pieces of wood and then got assembled into a full hull.
    * all different disciplines coming together, they have not met before, they may not even had a video call, all collaboration was via email
* Dan:  leading a jazz quintet.  Helping members develop original compositions, new arrangements of existing music.  Enjoyed how each person contributes to the creative process and how the result is the result of everyone's creativity combined.  It's truly a collaboration where each person is critical.
* Sue: I went door-to-door with my elderly neighbor to ask our neighborhood for funds for a neighbor who is terminally ill and whose family is getting food from the food bank. We raised over $1,000 USD and delivered it to her that night. It felt like something meaningful, something important, and something well-received. We all pitched in to help out a family.
* Mose: contributing to AUCTeX.  It was my first contribution to a large open-source project, I got great mentoring.  What I enjoyed most?  Gratitude of users :+1: for mentoring
* Tuomas: I developed a Monte Carlo simulation during my PhD with a group of students who were all using it for parts of their research. I enjoyed working with a lot of people who were in a similar situation but had very different skills.Toby: it's nice that each person in the project can contribute the parts they like to work on, so that you dont have to work on the parts that are not interesting to you.
* Peter: Submitting our proposal for a "Teching ML" workshop at ECMLPKDD for 2020; it was 3 of us and each and everyone knew github as a tool and henceforth was ready to go; distribution of tasks was super open as we were dedicated; we did it within 10-14 days aside our day jobs and we go the workshop in the end!

Toby: we should provide the oprtunities for people to contribute to things they may find valuable

What is the value of investing so much time in making your lesson welcoming and easy to contribute to?


2. Tips & tricks for collaborating on GitHub
    - [`CONTRIBUTING.md`](https://github.com/carpentries-incubator/jekyll-pages-novice/blob/gh-pages/CONTRIBUTING.md)
        - [Mozilla Open Leaders' guide for how to write a good contributing guide](https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/write-contributor-guidelines/)
        - [an example of a more in-depth contributor's/developer's guide](https://metawards.org/development.html) (hat-tip Natalie Thurlby for the recommendation)
        - we use standard `CONTRIBUTNG` file that contains: how to contribute, where to contribute (which are the right repositories and files), what to contribute (it is good to specify what kind of contributins are welcome, lessons are usually already full, you may have a preference on which parts of the lesson would take most advantage from the contributions)
    - keywords to trigger automatic actions
        - closing issues with the "closes" or "fixes" keywords followed by the issue number.
    - reviews
        - requesting a review
        - reviewing a Pull Request
            - comment on a line
        - suggestions
            - Fix any mistakes yourself but they'll be suggested back to the creator of the request.
            - You can't usually make changes to somebody else's fork, so either it has to go back to the submitter of the pull request or you can make the change yourself on the main branch after accepting the pull request.
        - merge policies and branch protection
            - Policies can be set to require tests to pass or multiple reviewers to approve a change.
    - managing notifications
        - repository-level
        - account-level
        - filtering notification emails
            - github fixes within the CC address of notification, what the purpose/type of the notification is
    - [tagging a maintainer team](https://github.blog/2012-05-09-introducing-team-mentions/)
        - your lesson should have a Team associated with it, containing you, Toby, and any other people you have been collaborating with on the project. You can mention (@carpentries-incubator/team-name) this Team any time you want to attract the attention of all lesson maintainers at once.
    - [pinned issues](https://github.com/carpentries-incubator/docker-introduction/issues)
        - keep an issue pinned to the top of the issue listing, so that it is easily noticeable for visitors.
        - useful if there is an important discussion that you want people to contribute to, or a problem that you really need help with
        - see link above for an example
    - issue labels and issue templates
        - label your issues to help others understand the type and progress/status of an issue.
        - remember that issues labelled `help-wanted` can be automatically listed on [the Help Wanted page](https://carpentries.org/help-wanted-issues/) if you opt in (contact Toby)
    - projects
        - the Projects tab of your GitHub repository provides an interface for organising and managing issues. If you are familiar with "Agile" project management, you can use this as a "kanban" board to organise tasks. It can also be used over a longer period to keep track of which issues are a priority and which can be left for later e.g. we have used a Project board to identify all the issues that need to be addressed before a lesson can be taught.
        - documentation here: https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards
    - [discussion boards](https://docs.github.com/en/discussions)
        - discussion forum for your github project. 
        - see an example: https://github.com/carpentries-incubator/docker-introduction/discussions
        - if you cannot activate this for your lesson repsoitory, contact me to give you the appropriate permissions.
    - topic tags
        - keep the topics on your lesson repository up-to-date! this will ensure your lesson is listed appropriately on The Carpentries website.
        - go to your repository homepage, click the gear symbol next to "About" and add/edit topics there.
        - Reminder: more about which topics to include here: https://cdh.carpentries.org/the-carpentries-incubator.html#topic-tags
    - Learn more about Git
        - [A list of resources from Paula Andrea Martinez](https://orchid00.github.io/git_for_humans/007_resources.html)
        - [Code Refinery's _Collaborative Version Control with Git_ lesson](https://coderefinery.github.io/git-collaborative/)
    - [Glosario](https://glosario.carpentries.org/)
        - whenever you introduce a new term from your lesson topic, add a link to the definition
        - you can also write your own glossary in the `reference.md` file of your lesson repository
        - contributions in languages other than English wanted to help translate lessons
3. Next steps
    - for you:
        - fill in [the feedback survey](https://forms.gle/AfdaCKjNiV6y6HD39)!
        - join [the Incubator Developers mailing list](https://carpentries.topicbox.com/groups/incubator-developers)
        - attend a skill-up or community discussion about lesson development
            -  lesson accessibility
            -  lesson reviews
            -  Git for Maintainers
            -  open source project governance :+1:
            -  your suggestion here..?
        -  join a Maintainer Co-working Corral
            -  first Wednesday of every month
            -  see [the Community Calendar](https://carpentries.org/community/#community-events)
        -  [attend the ROpenSci community call on fostering community around an open source project](https://ropensci.org/commcalls/apr2021-pkg-community/)
    -  for your lesson:
        -  open issues, label them, opt into the Help Wanted page
        -  [organise a lesson sprint](https://github.com/tobyhodges/lesson-sprint-recommendations)
        -  feature your lesson in [the Incubator Lesson Spotlight](https://docs.carpentries.org/topic_folders/lesson_development/spotlight.html)

- 
**Your questions and suggestions:**
- _add your questions here_
    - 
    - 
    - 
    - 
    - 
- _add your resources and tips below_
    - 
    - 
    - 
    -
    - 



4. homework:
  - Complete [the Lesson Development Study Groups feedback survey](https://forms.gle/AfdaCKjNiV6y6HD39).
  - (Optionally) write a post for The Carpentries blog, reflecting on your experience in this Study Groups program.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/ngPfT3pk8GSscCxB8