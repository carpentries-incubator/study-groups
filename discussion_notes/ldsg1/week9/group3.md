# The Carpentries Lesson Development Study Groups Notes
## Group 3: Friday 16 April 2021 14:00-15:00 UTC

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
- Graeme Grimes / he/him / ggrimes / https://github.com/carpentries-incubator/workflows-nextflow
- Sarah Stevens / she, her, hers / sstevens2 / https://github.com/carpentries-incubator/jekyll-pages-novice
- Alessio Sclocco / he, him / isazi / https://github.com/carpentries-incubator/lesson-gpu-programming
- Bailey Harrington / she, her / baileythegreen / https://github.com/carpentries-incubator/latex-novice-typesetting
- Jannetta Steyn / she, her/ jsteyn / https://github.com/carpentries-incubator/java-intro
- Richard Ostler / he/him / https://github.com/carpentries-incubator/frictionless-data-agriculture
- Annajiat Alim Rasel / he, him / annajiat / https://github.com/carpentries-incubator/java-novice-inflammation/
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Toby Hodges, Sarah Stevens
**Discussion Lead**: Toby Hodges
**Notetaker**: everyone, Sarah Stevens

## Agenda

1. Welcome & Icebreaker 
    - what is a collaborative project that you really enjoyed working on? can you identify what made it so enjoyable?

* [name=Bailey] [Glosario](https://glosario.carpentries.org): I just kind of randomly 'showed up' in the project last fall, submitted some really big PRs, and very quickly was brought on in a more official capacity as an Editor on the project.
* [name=Jannetta] CarpenPi: HackDay at the SSI CW 2021. It includes all the things that I get very excited about, i.e. Carpentries and Raspberry Pis! Also the fact that there is so much enthusiasm about the project from others. (https://github.com/CarpenPi)
* [name=Sarah] - Cheesey but developing the Jekyll Lesson. A project I was really wanting to work on and it was nice to work with other Carpentries Instructors.
* [name=Richard]: Probably one of the first projects I worked on to develop online mapping for biodiversity data in the early 2000s. This was before Google Earth was really mainstream, so lots of java/geospatial coding and database optimisation work with a good technical team, but also working with the Natural History Museum to get the taxonomies right and various biological recording schemes - some very interesting characters! 
* [name=Graeme] Hopefully the UKRI project, developing data sceince training for the UK bioscience community, I am working on now will be one.
* [name=Alessio] Can't think of anything either. But I participate in online communities and the most important thing is the "community". The feeling of being part of something is (usually) better than the thing itself (even for great projects).
* [name=Annajiat] contributing to HPC lessons. Appreciated contribution, pointed out errors, guided how to correct, encouraged further participation. Got similar responses from some other maintainers. Further meetings were held, in fact there were special sessions which worked somewhat like personalized training. Holds meetings at multiple times to accommodate people from different timezones.

Apologies: Hanno Spreeuw

2. Tips & tricks for collaborating on GitHub
    - [`CONTRIBUTING.md`](https://github.com/carpentries-incubator/jekyll-pages-novice/blob/gh-pages/CONTRIBUTING.md)
        - [Mozilla Open Leaders' guide for how to write a good contributing guide](https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/write-contributor-guidelines/)
        - [an example of a more in-depth contributor's/developer's guide](https://metawards.org/development.html) (hat-tip Natalie Thurlby for the recommendation)
    - keywords to trigger automatic actions
    - reviews
        - requesting a review
        - reviewing a Pull Request
        - suggestions
        - merge policies and branch protection
    - managing notifications
        - repository-level
        - account-level
        - filtering notification emails
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
3. Next steps
    - for you:
        - fill in [the feedback survey](https://forms.gle/AfdaCKjNiV6y6HD39)!
        - join [the Incubator Developers mailing list](https://carpentries.topicbox.com/groups/incubator-developers)
        -  attend a skill-up or community discussion about lesson development
            -  lesson accessibility
            -  lesson reviews
            -  Git for Maintainers
            -  open source project governance
            -  your suggestion here..?
        -  join a Maintainer Co-working Corral
            -  first Wednesday of every month
            -  see [the Community Calendar](https://carpentries.org/community/#community-events)
        -  [attend the ROpenSci community call on fostering community around an open source project](https://ropensci.org/commcalls/apr2021-pkg-community/)
    -  for your lesson:
        -  open issues, label them, opt into the Help Wanted page
        -  [organise a lesson sprint](https://github.com/tobyhodges/lesson-sprint-recommendations)
        -  feature your lesson in [the Incubator Lesson Spotlight](https://docs.carpentries.org/topic_folders/lesson_development/spotlight.html)

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
  - Complete [the Lesson Development Study Groups feeback survey](https://forms.gle/AfdaCKjNiV6y6HD39).
  - (Optionally) write a post for The Carpentries blog, reflecting on your experience in this Study Groups program.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/3fFaqgBratEv8cU3A