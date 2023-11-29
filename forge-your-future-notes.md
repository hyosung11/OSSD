# Forge Your Future with Open Source - Book Notes

## 1. The Foundations and Philosophies of Free and Open Source

## 2. What Free and Open Source Can Do for You

### FOSS Benefits to Your Skillset

#### Communication

#### Collaboration

**Bus Factor** is a number equal to the number of team members who, if run over by a bus, will put the project in jeopardy.

#### Tools

- issue tracking
- version control
  - commit messages
    - provide details of what is changed
    - why it was necessary
    - what problems the commit fixes
- mailing lists

#### Best Practices

learn how best practices work, why they're important and see firsthand the difference they make to a successful software project.

- version control
- feature branches
- unit and integration tests
- continuous integration and deployment (CI/CD)
- design patterns

#### Technologies

- technologies change
- people skills can serve you far better than the technological skills
- The Next Big Thing

### FOSS Benefits to Your Career

FOSS offers you endless options for technologies and architectures. Once you determine your goals, you can turn to FOSS to see which projects will help you reach them.

#### Public Portfolio

- start a log or portfolio for tracking all your contributions
- maintain your own portfolio to track contributions
- maintain your own record of all types of contributions so that you can easily share your contribution portfolio with prospective employers

#### Portfolio as Resume

- portfolio supplements a resume; it does not replace it
- a CV or resume shows prospective employers two things
    1. What you have done for past professional positions and
    2. What difference you've made with those actions
- Prospective employers what someone who made a difference
- resume = what you've done
- portfolio = how you did it
- You need both to share with specific data (numbers)

### FOSS Benefits to Your Personal Network

- Human networking is simply people communicating with other people.
- Communicating while requires practice, intention, and attention.
- "It's not what you know, it's whom you know."
- The most important benefits of these relationships are the discussions, introductions, and information sharing that happens in them.
- More than any technology you will ever use or create, the relationships you foster will help you thrive in your career.
- The relationships formed through contributing to free and open source projects may be the most valuable and lasting benefit.

### Benefit from Preparation

- learn the lay of the land
- know what files and social structures to look for

## 3. Prepare to Contribute

Steps

1. Realize you want to contribute
2. Find a project
3. Find a task (issue)
4. Set up your environment
5. Work on your contribution
6. Submit your contribution
7. Receive feedback and iterate on your contribution
8. Contribution accepted!
9. Goto step 1

### Ways to Contribute

- code, user interface, user experience design, documentation
- testing leads to bug reports
- organizing and managing the entire process

![FOSS-tasks](FOSS-tasks.png)

- hardware expertise
- subject matter expertise
  - e.g., strong pedagogical background to write and review lesson plans for an education project

### Common Project and Community Roles

![onion-metaphor](onion-metaphor.png)

Roles

1. Leadership - Benevolent Dictator For Life (BDFL)
2. Core Contributors
   1. commit bit - authority to approve a contribution
   2. heed the advice and feedback of a core contributor
3. Non-Core Contributors
   1. make regular contributions
   2. can provide advice and mentoring for newer contributors
   3. lifeblood of project
4. New Contributors
   1. apprenticeship phase
   2. projects that pay attention to this role have strong communities which are worth seeking out
5. Users
   1. need people to use the project
   2. provide feedback, bug reports and feature ideas
   3. users the most important layer/role of all because (meet user needs and solve their problems)

Know these most common roles in FOSS to navigate the hierarchy in most projects as you enter the world of FOSS contributing.

### Files You Should Know About Before You Start

Familiarize yourself with what files and features you may see. Not all files mentioned here exist in all projects. Locate most files in the root directory of a project, but not always. Look for a `docs` or similarly named documentation directory.

#### README

- typically first thing you see for a project
- project's face to the world
- make the README file the first stop when visiting any project
- it gives a sense of what the project is about and where to look for more information about the project

#### LICENSE (also COPYING)

- declares the terms under which folks are permitted to use, modify, and distribute the project
- sometimes called `COPYING` particularly for projects that use a version of the GNU Public License (GPL)
- "open source" projects must have an OSI-approved license
- no license means not open source; it is merely "source available"
- `LICENSE` file determines whether a project is open source

#### CONTRIBUTING

- `CONTRIBUTING` file
  - how the project prefers to receive contributions
  - the requirements and parameters a contribution must meet to be accepted into the project

- Apache HTTPD web patches has separate guidelines
  - reporting bugs
  - contributing code
  - contributing documentation

- The Public Speaking Resource project has one file
  - [Public_Speaking](https://github.com/vmbrasseur/Public_Speaking)
  - resources for presenting at technical conferences

- No `CONTRIBUTING` File scenario
  - look at past contributions
  - ask the community for process verification
  - once you have verified the process with the community and made your first contribution, be a community **superhero** by writing it up in the first version of the project's `CONTRIBUTING` file

- Communication is the most important thing (note to myself)

#### Code of Conduct

- Contributor Covenant created by Coraline Ada Ehmke
  - copied into this directory as `contributor-code-of-conduct.md`
  - [Coraline Ada Ehmke](https://where.coraline.codes)

- Code of Conduct (CoC)
  - CoC sign that community wiling to do the right thing
  - enforcement in an effective and empathetic way paramount

#### Styleguides

- Very Strong Opinions
- Always read and follow style guidelines if they exist
- Examples
  - [Google Styleguides](https://github.com/google/styleguide)
  - OpenStack family of projects => IBM
- if no guidelines, not any stylistic preferences the project maintainers express
  - write up the project's stylistic preferences in their very first styleguide and then link to it in the `CONTRIBUTING` file.

#### Other Handy Files

- `INSTALL` or `INSTALLATION` file
  - [`make`](https://www.gnu.org/software/make/)
- `CHANGES` or `CHANGELOG` file
  - use to determine whether the version of the software you're using includes a certain bug fix
  - see the development trajectory of a project
- `AUTHORS` file
  - not as common anymore

### Issue Tracking

- issue tracking, bug tracking, ticketing system - same concept
- uses range
  - bug tracking
  - feature requests
  - support questions
  - design discussions
  - team conversations
  - debates
- always ask the community if you have questions and to verify your assumptions

### Common Communication Routes

1. entirely asynchronous
2. semi-asynchronous
3. synchronous

- Seek out documentation and advice before participating in project discussions.
- Email mailing lists are a common communication method
- real-time chat platforms used as well
  - Internet Relay Chat (IRC)
  - Matrix
  - RocketChat
  - Mattermost
- respect the chosen communication routes used by the project

### Contributor License Agreement (CLA) / Developer Certificate of Origin (DCO)

- Contributor License Agreement (CLA)
  - right to share your contribution
  - agree that the project has a license to alter, distribute, and administer those contributions
  - you agree that you will never revoke that license

- Developer Certificate of Origin (DCO)
  - recently a more popular alternative to CLA
  - DCO relies upon a contributor signing their contribution using the `-s` or `--signoff` flags of the git version control system
    - denotes the right to distribute the contribution under the same conditions as the project license
  - only applies to git projects (not Subversion, CVS, or other systems)

### You're Ready to Find a Project

- equipped with guideposts to navigate FOSS projects
- Find a project and make your first contribution

## 4. Find a Project

- wanting to contribute to a project is the first milestone
- finding the project that's right for you is the second milestone
- take the time to find a project that matches your goals and values.
- defining your goals and requirements and finding the right first project can take some time to do properly, but it's a very good investment.

### Set Your Goals

Why do I want to contribute to open source software?

- goals must be specific and actionable
- collect your thoughts and write them down
  - get a snapshot of your current mind
  - snapshot gives you something to which you can refer later

Brainstorming Session

What do I want to get out of this? Why am I doing this?

1. to get a job as a professional software engineer
2. to learn how software is developed in an actual profitable company
3. to make meaningful connections with other software engineers
4. to find a mentor
5. to make a valuable contribution to a project I love
6. to feel part of a team
7. to get out of toy project hell
8. to bridge the skills gap
9. to contribute to a project that advances human health and fitness

Take the thoughts and organize, consolidate and focus them into a list of goals. Expand on the thoughts until they are specific. Collect similar thoughts together.

What is the why behind every thought? Iteratively refine and collect your thoughts into categories until you've consolidated them into a few core things you would like to achieve by contributing to free and open source software.

Each goal must be specific, concise, and actionable.

My Goals

1. Get an interview at a company where I make an open source contribution.
2. Learn best practices for choosing an issue, making a code contribution, and writing a pull request
3. Practice right speech in communication and collaboration with professional software engineers
4. Master git commands and the GitHub platform for open source software development
5. Find an open source software development mentor
6. Add at least one new piece to my portfolio

Own your goals, take responsibility for meeting them, and you are much more likely to be successful in your FOSS contributions.

Change the goals as necessary.

### Collect Your Requirements

What are your personal requirements for the project you select? What criteria must the project meet to be a good fit for you?

#### Skills

What are your skills? What can you offer to a project?

- great writer or editor
- translation
- graphic design
- user experience specialist
- know certain programming languages
- have experience with electronics
- experience managing people
- writing technical specification or grants
- organizing events

Skills I bring to the party

1. good writer and editor
2. understanding of learning pedagogy
3. advanced JavaScript skills
4. intermediate SQL skills
5. knowledge of scrum/agile/kanban and project management
6. legal background as former litigation lawyer

#### Interests

- domain knowledge

Interests! Hobbies! Curious About!

1. soccer
2. basketball
3. strength training
4. speed training
5. sprinting
6. mobility
7. diet
8. longevity
9. biomarkers
10. reading
11. writing
12. wealth creation
13. family
14. child-raising
15. Buddhism
16. meditation
17. Stoicism
18. Shamanism
19. alternative healing modalities
20. acupuncture
21. dogs
22. nature
23. Korean farmer's band music
24. Bruce Lee

#### Time Availability

- assess how much time you can devote to contributing to a project
- consider that some projects have steeper learning curves

#### Goals

- skills, interests, time availability, and goals = specific requirements
- impermanent and can change over time

### Collect Candidate Projects

- limit the pool of candidates
- start with projects you already use and enjoy
  - Linux user examples
    - Blender, GIMP, KDE, GNOME
  - FOSS Projects are everywhere
    - Drupal, Moodle, Visual Studio Code, iTerm
  - smaller satellite projects such as libraries, plugins, extensions
- inspect your software and its ecosystems for FOSS projects
- Open your favorite web browser, fire up your favorite search engine, and type in an interest name followed by the words "open source" into the search field
- browse popular version control service providers
  - GitHub
  - GitLab
  - BitBucket
- ask network and local community
  - friends
  - social network contacts on Twitter, LinkedIn, etc.

**Invest an hour or two to collect a nice pool of candidate projects and to familiarize yourself with the landscape of free and open source projects that exist in the world.**

#### Candidate Projects List

1. Visual Studio Code
2. freeCodeCamp
3. dev.to
4. GroupSpot
5. Glofox
6. TrainHeroic
7. ATG
8. Forza Football
9. Insight Timer
10. StatSports APEX
11. Garmin
12. Notion
13. Evernote
14. ZebraWeb
15. Node
16. Express
17. OpenSpiel (<https://github.com/deepmind/open_spiel>) - Framework for developing research environments and algorithms for games, including simple soccer game environments. Good option to contribute environments, visualization, or algorithm implementations.
18. Google Research Football (<https://github.com/google-research/football>) - Research project for developing reinforcement learning agents for football/soccer games. Potential areas to contribute include new training scenarios, opponent AI bots, or visualizations. Requires Python/Tensorflow skills.

#### Select a Project

1. Compare the list of projects you've built with your list of requirements.
   1. Of course, matching your requirements is a very important feature for any potential project.
2. Consider how easy it will be for you to contribute
   1. Give yourself the best possible chance for success.
   2. Choose a project that makes contributing more straightforward
   3. Start with an easy win
   4. Increase motivation to continue down the path of contributing elsewhere

### Select a Task

### What is "Success"?
