# The Carpentries Lesson Development Study Groups Notes
## Group 1: Monday 12 April 2021 14:00-15:00 UTC

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
- Mateusz Kuzak / he, him / mkuzak 4 
- Mark Bell / he/him / https://github.com/carpentries-incubator/machine-learning-librarians-archivists
- Mike Trizna / he,him / MikeTrizna
- Daniel van Strien / he,him/ davanstrien
- Batool Almarzouq / she,her/ [BatoolMM](https://github.com/BatoolMM)
- Jonathan Pelham / jonititan / [Python EOFDM Precursors](https://github.com/carpentries-incubator/python-EOFDM-precursors)
- Nora McGregor / she, her / noramcgegor
- 
(add more lines as needed)

## Roles

**Group Facilitator(s)**: Toby Hodges, Mateusz Kuzak, Aleksandra Nenadic
**Discussion Lead**: Toby Hodges
**Notetaker**: 

## Agenda

1. Welcome & Icebreaker 
    - what is a collaborative project that you really enjoyed working on? can you identify what made it so enjoyable?

* Mike: I helped work on an overhaul of outdated documentation for a bioinformatics workflow my team used to use. We set aside 4 hours, ordered pizza, and plowed through all of the issues at once, rather than a lot of deferred maintenance.
* Mateusz: 4OSS, 4 simple recommendations for open source software, amazing group of people, that helped wtih enjoyable work together, also many oprtunities to work in person in short sprints
* Joni: Hackathon challenge regarding aircraft multi party through life maintenance collaboration.  Required a distributed architecture.  Was paired up with people I didn't know but we bounced ideas around and iterated quickly on them over the time we had.  The back and forth with quick and well signposted changes in direction was very plesant.  Always knew where I stodd, what the next challenges were, and felt that I had a meaningfull role in steering and delivering.  [Hack Hercules](https://www.gov.uk/government/publications/dasa-defence-logistics-hackathon-information-sheet/defence-logistics-hackathon-information-sheet)
* Nora: I worked on a project to develop ground truth for automatic transcription of historical arabic scientific manuscripts and that was absolutely wonderful, primarily because it was *completely* new to me in all aspects so I learned a ton. I think that's why I've enjoyed this collaboration so much as well. My partners are fab and dedicated and I've learned loads from the experience!
* Daniel: This one! I think for a few main reasons. It was a good sized group to work with. I work on a project with 20+ people and often decisions are made in 3hour meetings with 20 people which crushes my spirit. This was a size that allowed for good discussion. Another reason was that it had a clear focus as an outcome and the people I worked with are super nice :) 
* Mark: The project that brought me to my current job. It was experimental and we had a good team who worked together and helped each other out. There was a also a developer who had liked to work in different, modern, ways so I learned about new ways of working.
* Elnaz: How we enter into a round and we put all the energy and we get to know some other people from another country or university with thee the similar thoughts and try to solve the issue. I am recently working on the starting of a Department called Neuroinformatics with my colleagues. There are physicians, geneticians , etc, and we are trying to find common areas and move through them.
* Batool: Bookdash event with the turing way last November. It was the first enjoyable virtual event. I think it's because the size of the group was manageable. I loved meeting other contributors, discuss different ideas and experiences.
* Toby: developing the Jekyll lesson has been really fun - it has helped to have a group of collaborators with a clear, shared vision for what we want the lesson to look like in the end, and who know each other well enough to be able to communicate effectively.

2. Tips & tricks for collaborating on GitHub
    - [`CONTRIBUTING.md`](https://github.com/carpentries-incubator/jekyll-pages-novice/blob/gh-pages/CONTRIBUTING.md)
        - [Mozilla Open Leaders' guide for how to write a good contributing guide](https://mozilla.github.io/open-leadership-training-series/articles/building-communities-of-contributors/write-contributor-guidelines/)
        - [an example of a more in-depth contributor's/developer's guide](https://metawards.org/development.html) (hat-tip Natalie Thurlby for the recommendation)
    - [tagging a maintainer team](https://github.blog/2012-05-09-introducing-team-mentions/)
    - [pinned issues](https://github.com/carpentries-incubator/docker-introduction/issues)
    - issue labels and issue templates
    - [the Help Wanted page](https://carpentries.org/help-wanted-issues/)
    - keywords to trigger automatic actions
    - reviews
        - requesting a review
        - reviewing a Pull Request
        - suggestions
        - merge policies and branch protection
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
    - managing notifications
        - repository-level -> click on Watch/Unwatch at the top of the repository homepage for a dropdown of notification level choices
        - account-level -> go to your GitHub profile settings, where you can choose which notifications are sent where for each repository/organisation that you are a member of
        - filtering notification emails -> the notification emails from GitHub include "cc'd" addresses describing what kind of notification it is e.g. review_requested@noreply.github.com, subscribed@noreply.github.com and mention@noreply.github.com. Use these to set up filtering rules in your email client, to create folders for different kinds of notifications e.g. one folder for "subscribed" level notifications, which are less likely to require any action or your part.
    - Learn more about Git
        - [A list of resources from Paula Andrea Martinez](https://orchid00.github.io/git_for_humans/007_resources.html)
        - [Code Refinery's _Collaborative Version Control with Git_ lesson](https://coderefinery.github.io/git-collaborative/)
    - [Glosario](https://glosario.carpentries.org/)
        - whenever you introduce a new term from your lesson topic, add a link to the definition
        - you can also write your own glossary in the `reference.md` file of your lesson repository
3. Next steps
    - for you:
        - fill in the feedback survey!
        - join [the Incubator Developers mailing list](https://carpentries.topicbox.com/groups/incubator-developers)
        -  attend a skill-up or community discussion about lesson development
            -  lesson accessibility
            -  lesson reviews
            -  Git for Maintainers
            -  open source project governance
            -  your suggestion here..?
        -  join a Maintainer Co-working Corral
            -  Maintainers of official Carpentries lessons meet monthly to work through issues/pull requests on their lesson repositories. you might find this helpful as a way to make regular progress and build connections with other maintainers
            -  first Wednesday of every month
            -  see [the Community Calendar](https://carpentries.org/community/#community-events)
        -  [attend the ROpenSci community call on fostering community around an open source project](https://ropensci.org/commcalls/apr2021-pkg-community/)
    -  for your lesson:
        -  open issues, label them, opt into the Help Wanted page
            -  guidance on how to use The Carpentries' standard set of issue labels: https://docs.carpentries.org/topic_folders/maintainers/github_labels.html
            -  and how to populate a repo with these labels if you want to use them: https://docs.carpentries.org/topic_folders/maintainers/github_labels.html#how-to-populate-a-github-repository-with-these-labels
        -  [organise a lesson sprint](https://github.com/tobyhodges/lesson-sprint-recommendations)
        -  feature your lesson in [the Incubator Lesson Spotlight](https://docs.carpentries.org/topic_folders/lesson_development/spotlight.html)

** tips and tricks notes
CONTRIBUTING file, the one in the incubator is the standard, you are welcome to adjust it to your own project,lists: how to cntribute, where to contribute, what to contribute, it also contains: 'what not to contribute', this is very important for the mature lessons, because if something is giong to go in, something will need to go out, otherwise the lesson would grow to someting larger than could be covered in the workshop. THere is also a pointer to the guide to how to contribute to the project.

Issues:
- tags: you can tag people ion the issue using `@` for exampe @mkuzak, when you type `@` there will be a dropdown, showing a list of teams, you can tag the whole team. Good for internal communication in the team.
- pinned issues: the issue you want every one to see, eg. you collect feedback in this issue
- pull requests:
- issue templates: templates live in the .github directory in the root of the repository, you can have multiple issue templates
- you can label issues (eg. help wanted)
- keywards: every issue have a number starting with `#` you can use it to refer to issues, if you include "fixes #5" in the commit message, GH will close an issue



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
  - [Complete the Lesson Development Study Groups feeback survey](https://forms.gle/AfdaCKjNiV6y6HD39).
  - (Optionally) write a post for The Carpentries blog, reflecting on your experience in this Study Groups program.
- **Weekly "Sticky Note" feedback**: please give us your feedback about this week by [filling out this two-question form][sticky-notes-link]

## Resources
Add any relevant resources you found/discussed this week to the list below.

- 
- 
- 

[sticky-notes-link]: https://forms.gle/vNhXSJ1nmaVPhb8D9