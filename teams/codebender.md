---
layout: page
title: CodeBender
permalink: /teams/codebender/
---
[GitHub organisation](https://github.com/nus-fboa2016-cb)

## Members
 - Thng Kai Yuan ([@thngkaiyuan](http://cs3281-2.blogspot.sg/))
   - Technology Expertise: Information Security
 - Moon Seokmin ([@bsmmoon](http://moonmoon3281.blogspot.sg/))
   - Technology Expertise: Web Crawling
 - Alex Yao ([@alexyaoyang](http://alexyy.com/))
   - Technology Expertise: Web Performance
 - Ma Tanghao ([@harryggg](https://blog.nus.edu.sg/matanghao/))
   - Technology Expertise: Ruby on Rails
 - Jiang Sheng ([@gisonrg](http://blog.gisonrg.me/))
   - Technology Expertise: Node.js

## Workplan for Neuralyzer

* [x] Learn about possible project technologies (not received project details yet) - Week 1
* [x] Understand project requirements - Week 2
* [x] Product Presentation in class with high level understanding - Week 3
* [x] Plan [database details](https://github.com/codebendercc/Neuralyzer/wiki/ORM-Notes) - Week 3
* [x] Plan [front-end pages details](https://github.com/codebendercc/Neuralyzer/wiki/Pages-the-service-should-provide) - Week 3
* [x] Learn more about project background from CEO during Code Sprint - Week 3
* [x] Plan Project specification - Week 3
* [x] Decide on the [Symfony Bundles to use](https://github.com/codebendercc/Neuralyzer/wiki/Symfony-Bundles) - Week 3
* [x] Plan [Analytic and Logging](https://github.com/codebendercc/Neuralyzer/wiki/Types-of-Analytics) for project - Week 3
* [x] Submit first pull request on 1st day of Code Sprint - Week 3
* [x] Have first pull request merged [Pull Request #1](https://github.com/codebendercc/Neuralyzer/pull/1) (Merged) - Week 3
* [x] Create one test and merge into main project [First PHPUnit test](https://github.com/codebendercc/Neuralyzer/pull/12) (Merged) - Week 3
* [x] Setup [Sensiolabs Insight](https://insight.sensiolabs.com/projects/a371effa-c11d-473f-844d-d5f421df79be) for automated push test - Week 3
* [x] Get started with basic prototype - Week 4
* [x] Fix bug related to flashing in iFrame - Week 5
* [ ] Create test case for successful flashing - Week 5
* [x] Refactor code before moving on - Week 6
* [ ] Create landing page - Week 6
* [ ] Create test case for landing page - Week 6
* [ ] Create database for user and tier - Week 6
* [ ] Create test case for user & tier database - Week 7
* [ ] Create registration and login page - Week 7
* [ ] Create test case for login and registration and database linkage - Week 7
* [ ] Create database for firmware - Week 8
* [ ] Create test case to ensure that user and firmware database is linked correctly  - Week 8
* [ ] Create show info page - Week 8
* [ ] Create test case to ensure show info page shows correct info - Week 9
* [ ] Create dashboard page - Week 9
* [ ] Create test case to ensure dashboard page shows correct and links correctly - Week 10
* [ ] Create log/analytics database - Week 10
* [ ] Create Analytics page - Week 11
* [ ] Create test case to ensure Analytic page shows correct analytics - Week 11
* [ ] Create admin page - Week 12
* [ ] Create test case for admin page and features - Week 12

## Workplan for Eratosthenes

* [x] Domain understood - Week 1, Thu
* [x] Product demo - Week 2, Mon
* [x] Project set up - Week 2, Tue
* [x] High-level architecture understanding - Week 3, Mon
* [x] Proposal for feature implementation drafted ([blog post](http://cs3281-2.blogspot.sg/2016/01/planning-for-our-first-feature.html)) - Week 3, Thu
* [x] Feature planned - Week 4
* [x] Minor enhancements - Week 4 & Codesprint
* [x] Feature discussion with the mentor and finalisation - Week 4 & Codesprint
* [x] Working methodology settlement - Week 4 & Codesprint
* [X] **Milestone 1** - Due Week 4, Sun (Fixed in PR [#34](https://github.com/codebendercc/eratosthenes/pull/34))
    * [X] Create 6 new entities
        - [x] Preference
        - [x] Partner
        - [x] Architecture
        - [x] Library
        - [x] Version
        - [x] LibraryExample
    * [X] Create migrations
    * [X] Create 6 fixtures
    * [X] Change example library folder structure to include versions
* [x] **Milestone 2 Part 1** - Due Week 5, Wed
    * [X] Design public APIs: specify request urls and parameters
* [ ] **Milestone 2 Part 2** - Due Week 6, Wed
    * [ ] Create ApiController
    * [ ] Create tests for ApiController
    * [ ] Create ApiHandler
    * [ ] Create tests for ApiController
* [ ] **Milestone 3** - Due Week 6, Sun
    * [ ] Change View Templates to include versions
    * [ ] Change ViewsController
* [ ] **Milestone 4** - Due Week 7, Sun
    * [ ] Component integration
    * [ ] Create integration tests
* [ ] **Milestone 5** - Due Week 8, Sun
    * [ ] Integrate multiple partner functionality into our codebase
    * [ ] Integrate features to remember preferences of partners
    * [ ] Create integration tests for partner and preferences
* Buffer / minor features - Week 9 - 13 

## Workplan for Graphite

* [x] Understand project requirements - Week 1
* [x] Study the current code, understand the limitations and things to be improved - Week 2
* [x] modularize the original code -Week 2
* [x] Product Presentation in class with high level understanding - Week 3
* [x] Learn more about the patterns required to be recognised from CEO during Code Sprint - Week 3
* [x] Plan Project specification - Week 3
* [x] Learn about the detailed user requirement (0-step graph plotting)
* [x] Write tokenizer v0.0 for raw data Week 3
* [x] Write data parser v0.0 for pattern recognizing Week 3
* [x] Write chart plotter v0.0 (based on canvas.js) for plotting chart Week 3
* [x] Self-recovery from incomplete transmission with missing data - Week 4
* [x] Self-recovery from corrupted transmission(happens when transmission rate is too high) - Week 5
* [x] Self-recovery from corrupted negative number - Week 5
* [ ] set up unit test using jasmine (coverage aim:90%) - Week 6
* [ ] refactor the code to improve robustness - Week 7
* [ ] add new pattern: multi-line with X-coordinate - Week 8
* [ ] Create GUI for graph plotting, which can be put into IDE - Week 9
* [ ] Allow user to define coordinates and axis on GUI - Week 10
* [ ] add new pattern: auto-generated timestamp as X-axis - Week 11
* [ ] Documenation (on patterns and user manual) - Week 12

## Contributions

### @thngkaiyuan (Thng Kai Yuan)
* Week 2, Tue - Received project details
* Week 2, Thu - Completed setting up of development environment
* Week 2, Fri - Achieved high-level understanding of Eratosthenes
* Week 2, Sat - Determined the cause of a failing test case (see [blog post on the phantom bug](http://cs3281-2.blogspot.sg/2016/01/catching-phantom-bug.html))
* Week 3, Mon - Presented on Eratosthene's high-level architecture
* Week 3, Thu - Resolved an issue with local tests (see [blog post on "Using Vagrant with Symfony"](http://cs3281-2.blogspot.sg/2016/01/using-vagrant-with-symfony.html))
* Week 3, Sun - [Pull Request #16](https://github.com/codebendercc/eratosthenes/pull/16) (Merged)
* Week 3, Sun - [Pull Request #24](https://github.com/codebendercc/eratosthenes/pull/24)
* Week 4, Wed - [Resolved issue #25](https://github.com/codebendercc/eratosthenes/issues/25)
* Week 4, Wed - [Resolved issue #29](https://github.com/codebendercc/eratosthenes/issues/29)
* Week 4, Sun - [Resolved issue #35](https://github.com/codebendercc/eratosthenes/issues/35)
* Week 4, Sun - [Pull Request #34](https://github.com/codebendercc/eratosthenes/pull/34)
* Week 5, Wed - [Designed the APIs](https://docs.google.com/document/d/1-eUlYzHQypgWRRDwJ7lsj3f8nrbVt7owkldCdUSNKVs/edit?usp=sharing) that are to be implemented
* Week 5, Sat - [Pull Request #38](https://github.com/codebendercc/eratosthenes/pull/38) - A hotfix for the existing codebase
* Week 5, Sat - Implemented the [getVersions API](https://github.com/codebendercc/eratosthenes/commit/c6d8b30a3f567dcecb5bc816977ae91aa96444aa)
* Week 5, Sat - Wrote [tests for the getVersions API](https://github.com/codebendercc/eratosthenes/commit/cc3e92ac8be5db649a9e6f764a2cb863f01abb72)
* Week 5, Sun - Implemented the [getKeywords API](https://github.com/codebendercc/eratosthenes/commit/93d4cdbb995cbaef6a653d3a449938b2dac3e659) (pending clarification from John)
* Week 5, Sun - Created [tests for the getKeywords API](https://github.com/codebendercc/eratosthenes/commit/137dea9adab330167de28d95acc48ee6651967fb) (pending clarification from John)
* Week 5, Sun - Implemented the checkGithubUpdates API ([80b8b38](https://github.com/codebendercc/eratosthenes/commit/80b8b389a0b9c15b0978d83f919b2b2e96fcdc7d) & [52898a0](https://github.com/codebendercc/eratosthenes/commit/52898a0b0f633e1975449dd2d71b4b6ed3f93651)) (pending clarification from John)
* Week 5, Sun - Wrote tests for the checkGithubUpdates API ([75af2f5](https://github.com/codebendercc/eratosthenes/commit/75af2f52e35f700e606cc735b2ee4e72353b5285) & [5d9602a](https://github.com/codebendercc/eratosthenes/commit/5d9602a1bbcfe9ea105106a60b1933216fe0443a)) (pending clarification from John)

#### Contribution to minor project - Teammates
 * 

#### Technology expertise in Information Security
* **Short-Term Plan**: To expose myself to as many aspects of Information Security as possible (e.g. Cryptography, Web Security, Network Security, System Security, Software Security, Pen Testing) and in the process, acquire practical skills that can be applied in the information security industry.
* **Long-Term Plan**: To become an information security professional. To achieve this, I intend to take modules (e.g. CS2107, CS3235, CS4238, CS5331, CS5321) that would allow me to develop a focus area in information security. I am also exposing myself to the industry through my internships (e.g. with FireEye) and external projects (with NUS GreyHats).
* Participated in a discussion of cyber range scenarios with Cyber Test Systems
* Attended 2 training sessions with NUS GreyHats
* Sharing on Cross-Site Request Forgeries ([Blog Post on CSRF](http://cs3281-2.blogspot.sg/2016/01/cross-site-request-forgeries-csrf.html))
* Write-up on my participation in Insomni'hack 2016: ([Blog Post on the Smartcat Challenge](http://cs3281-2.blogspot.sg/2016/01/te-insomnihack-2016-teaser-smartcat-web.html))
* Write-up on [cracking the substitution cipher](http://cs3281-2.blogspot.sg/2016/01/te-cracking-substitution-cipher.html)

### @bsmmoon (Moon Seokmin) (Team Lead - Week 4 - 8)
* Week 2, Sun - Received project details
* Week 3, Mon - Setup and learn project structure and its related technologies such as Symfony.
* Week 3, Thu - Actual implementation detail in preparation of Codesprint.
* Week 3, Sun - Much clearer view on the system. Started as the team lead. Tried to settle the working methodology. Started feature implementation.
* Week 3, Sun - [Pull Request #18](https://github.com/codebendercc/eratosthenes/pull/18) (Merged)
* Week 4, Thu - Resolved [issue #27](https://github.com/codebendercc/eratosthenes/issues/27) (part of [PR #34](https://github.com/codebendercc/eratosthenes/pull/34))
* Week 4, Thu - Resolved [issue #31](https://github.com/codebendercc/eratosthenes/issues/31) (part of [PR #34](https://github.com/codebendercc/eratosthenes/pull/34))
* Week 4, Thu - Resolved [issue #32](https://github.com/codebendercc/eratosthenes/issues/32)
* Week 5, Wed - Discussion on [Eratosthenes API](https://docs.google.com/document/d/1-eUlYzHQypgWRRDwJ7lsj3f8nrbVt7owkldCdUSNKVs/edit?usp=sharing)
* Week 5, Sun - Milestone2 fetch API implemented (branch [api-fetch](https://github.com/codebendercc/eratosthenes/tree/api-fetch))
* Week 5, Sun - Made tests on fetch API
* Week 5, Sun - Milestone2 list API implemented (branch [api-list](https://github.com/codebendercc/eratosthenes/tree/api-list))
* Week 5, Sun - Made tests on list API

#### Contribution to minor project - Teammates
 * 
 
#### Technology expertise in Intelligent Agent

##### Short Term Plan
 * Look for practical application in extension of my education so far
 * Develop agent for simple problem
 * Publish posts / tutorials on blog

##### Long Term Plan
 * Undergo further education: CS4246 (AI Planning and Decision Making), CS5340 (Uncertainty Modelling in AI)
 * Apply skill on real world problem
 * Maintain blog

### @alexyaoyang (Alex Yao)
* Week 1 & 2 - Learn technologies
* Week 2, Sun - Received project details
* Week 3, Mon - Presented on high level architecture of Neuralyzer and what will be
* Week 3, Sat - [Pull Request #1](https://github.com/codebendercc/Neuralyzer/pull/1) (Merged)
* Week 3, Sat - [Pull Request #2](https://github.com/codebendercc/Neuralyzer/pull/2) (Merged)
* Week 3, Sat - [Pull Request #3](https://github.com/codebendercc/Neuralyzer/pull/3) (Merged)
* Week 3, Sat - Learnt more technical details on the why's and how's of Codebender, Neuralyzer and Arduino from the CEO
* Week 3, Sat - Started using SensioLabs' Insight as an automated code quality (also has security, performance, bugrisk, architectural checks) assurance and setup hook for github, such that every push will be reviewed automatically
* Week 3, Sun - Merged 6 more PRs
* Week 3, Sun - [Added first PHPUnit test](https://github.com/codebendercc/Neuralyzer/pull/12) (Merged)
* Week 4, Thu - Created a basic prototype
* Week 5, Thu - [Fixed bug related to flashing](https://github.com/codebendercc/Neuralyzer/pull/20)
* Week 5, Sat - [Refactor existing code + follow good JS practice](https://github.com/codebendercc/Neuralyzer/pull/21)
* Week 5, Sun - [Use Symfony's asset include for HTML importing](https://github.com/codebendercc/Neuralyzer/pull/22)
* Week 6, Mon - Started on landing page

#### Contribution to minor project - Powerpoint Labs
 * 

### @harryggg (Ma Tanghao)
* Week 2, Tues - Received project details
* Week 2, Thurs - Setup development environment
* Week 2, Thurs - Propose alternative solution/protocol (rejected)
* Week 2, Sat - write a simple modularizied tokenizer for the project(stringscanner.js) (https://gist.github.com/harryggg/f37d97d0d470d7d22e63)
* Week 3, Fri - write a raw data parser for the project (dataparser.js)
* Week 3, Sat - Agreed on the common patterns of serial output and the patterns to recognize
* Week 3, Sat - Learned about the design strategy of the project (0-step chart plotting)
* Week 3, Sat - refactor the original code and my own classes
* Week 3, Sat - write a chart plotting class for the project based on canvas.js (chartplotter.js)
* Week 3, Sun - Combine all classes and make the code functional (3 patterns recognized)
* Week 3, Sun - implement self-recovery feature (for incomplete/erronous data in transmission)
* Week 3, Sun - [Pull Request #1](https://github.com/codebendercc/graphic_serial_monitor/pull/6) (Reviewing) (+459 -182)
* Week 4, Thurs - simplified the code, combined two current patterns, change the method of pattern recognition
* Week 4, Fri - rewrite self-recovery for incompelte data transmission

#### Contribution to minor project - Coursemology
 * PR [#797](https://github.com/Coursemology/coursemology2/pull/797) for issue[#681](https://github.com/Coursemology/coursemology2/issues/681) - Week 5, Sun

### @gisonrg (Jiang Sheng)
* Week 2, Tues - Received project details
* Week 2, Thurs - Sun - Setup development environment, learning [Symfony framework](https://symfony.com/) by [tutorial](http://tutorial.symblog.co.uk/)
* Week 2, Sun - Draw system diagrams of codebender.
* Week 3, Thu - Discussion on feature implementation.
* Week 3, Sat - Learn the history and structure of codebender. Discuss about the project planning with mentors. Clarify and understand the feature need to be implemented.
    * Blog post on [Code Sprint Day 1](http://blog.gisonrg.me/2016/CS3281-Code-Sprint-Day-1/)
* Week 3, Sun - Fix code style in the project. Redesign and finalize new database schema of the project.
    * Blog post on [Code Sprint Day 2](http://blog.gisonrg.me/2016/CS3281-Code-Sprint-Day-2/)
* Week 3, Sun - [Pull Request 17](https://github.com/codebendercc/eratosthenes/pull/17)(Merged)
* Week 3, Sun - Fix [Issue 26](https://github.com/codebendercc/eratosthenes/issues/26)
* Week 4, Mon - Fix [Issue 30](https://github.com/codebendercc/eratosthenes/issues/30)
* Week 4, Tue - A discusion [post](http://blog.gisonrg.me/2016/eratosthenes-database-redesign/) about the new database design for Eratosthenes
* Week 4, Fri - Fix [Issue 36](https://github.com/codebendercc/eratosthenes/issues/36)
* Week 4, Sat - Fix [Issue 33](https://github.com/codebendercc/eratosthenes/issues/33)
* Week 5, Wed - Discussion on [Eratosthenes API](https://docs.google.com/document/d/1-eUlYzHQypgWRRDwJ7lsj3f8nrbVt7owkldCdUSNKVs/edit?usp=sharing)
* Week 5, Sat - Implemented the [getExamples API](https://github.com/codebendercc/eratosthenes/commit/9ccd246932832b12b2316f05f90191f8f4a67e05)
* Week 5, Sat - Created [test for getExamples API](https://github.com/codebendercc/eratosthenes/commit/f4e7fc3027270e59e22cc65a0401756dfe4729b3)
* Week 5, Sun - Implemented the [getExampleCode API](https://github.com/codebendercc/eratosthenes/commit/71406c221b926ad94bd14e757ed93093fea984de)
* Week 5, Sun - Created [test for getExampleCode API](https://github.com/codebendercc/eratosthenes/commit/cd56d7d6e820eb10504e9c53dca4017ea2aa18ee)

#### Contribution to minor project Teammates
* 

###### Past Contribution to HubTurbo
* PR [#1242](https://github.com/HubTurbo/HubTurbo/pull/1242) for issue [#1239](https://github.com/HubTurbo/HubTurbo/issues/1239) -Week 4, Sat

#### Technology expertise in Node.js
######Short-term plan:
1. Understand advanced JavaScript topic. [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) is a good place to start.
2. Master Node.js and get familiar with its core APIs. Understand its best practices and its limits.
3. Get familiar with Node's popular frameworks and tools, such as [Express](http://expressjs.com/), [Gulp](http://gulpjs.com/) and [q](https://github.com/kriskowal/q), and be able to use them in personal projects.
4. Learn JavaScript's ES6 standatd.
5. Gain experience by developing simple Node packages and Node applications.
6. Demostrate expertise through side projects, tutorials, and blog posts.

######Long-term plan:
1. Keep myself up-to-date with newest technology in JavaScript and Node.js industry.
2. Participate in some open-source projects that use Node stack
3. Understand Node project structures and workflow, and be able to design the application architecture with my experience.
4. Take modules related to Web Programming, such as CS3216 to keep refining my developing skills.

* [Node.js: what, why, how](http://blog.gisonrg.me/2016/node-js-what-why-how/): a blog post to introduce Node.js
* Leanring Node.js topics by attempting workshops provided on [NodeSchool.io](http://nodeschool.io)
   * [My solutions for nodeschoo.io](https://github.com/Gisonrg/collections/tree/master/nodeschool)
