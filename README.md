# Magento 2 Expert (formerly Professional) Developer Certification

**Note that the Magento version included in this project (2.2.5) is broken and cannot be upgraded. Therefore, use a separate installation of Magento 2.3.x instead.**

## Introduction

This exam is for a Magento 2 developer with a recommended experience level of 1.5 years in customizing different areas of the Magento platform. By passing this exam the developer earns a Magento 2 Certified Expert (formerly Professional) Developer
certification.

This exam validates the skills and knowledge needed to customize Magento 2 in the areas of 
- UI modifications; 
- database changes; 
- admin modifications; 
- checkout process customizations; 
- order management integrations and customizations; and
- catalog structure and functionality changes.

## Rubric

* 60 Multiple Choice items
* 120 minutes to complete the exam
* A score of 68% or higher is needed to pass the Magento 2 Certified Expert (formerly Professional) Developer exam
* This exam consists primarily of scenario-based questions in a multiple-choice format.
* Based on Magento Open Source (2.3) and Magento Commerce (2.3), but applicable to those using any version of Magento 2.

## Study plan

### Do the Swift Otter mock exam

* Noting which areas you are weakest on
* Repeat the Swift Otter exam every month, to gauge your progress (but if you notice yourself memorising the right answers, do it more infrequently).

#### Swift Otter Mock Exam scores

Work through Swift Otter (and other learning resources) in this order:

| Topic                                             | Proportion of Questions | 2021-01-11                  | 2021-02-10 | 2021-02-17 | 2021-03-03 |
|---------------------------------------------------|-------------------------|-----------------------------|------------|------------|------------|
| Overall                                           | 100%                    | 75% (45% chance of passing) | 66% (47%)  | 68% (51%)  |            |
| Customizing the Catalog                           | 12%                     | 69%                         | 37.5%      | 66.67%           |            |
| Customizing the Checkout Process                  | 13%                     | 75%                         | 25%        | 66.67%           |            |
| Working with Databases in Magento                 | 7%                      | 67%                         | 61.11%     | 33.33%           |            |
| Request Flow Processing                           | 12%                     | 70%                         | 70%        | 100%           |            |
| Magento Architecture and Customization Techniques | 18%                     | 100%                        | 75%        | 50%           |            |
| Customizing the Magento UI                        | 10%                     | 100%                        | 83.33%     | 75%           |            |
| Customer Management                               | 5%                      | 100%                        | 83.33%     | 75%           |            |
| Developing with Adminhtml                         | 10%                     | 69%                         | 91.67%     | 54.17%           |            |
| Using the Entity-Attribute-Value (EAV) Model      | 8%                      | 50%                         | 100%       | 100%           |            |
| Sales Operations                                  | 5%                      | 100%                        | 100%       | 66.67%           |            |

### Study framework

* Work through the guide, prioritising areas you are weakest on (from the mock exam) and also areas which have the highest proportion of questions (according to the official Magento Study Guide).
* Review Swift Otter guide for each of these sections
* Review notes for matching section in https://github.com/magento-notes/magento2-exam-notes
* Consult the DevDocs before and during EVERY topic below
* Consult the core for examples of each topic below
* Make your best effort to understand the 'what/where/when/why/how' of the core codebase to understand the effects that your code will have, e.g.
    * What options are there in the config which can affect the logic?
    * How can you customise the operation of the logic?
      * Events
      * Plugins
      * `di.xml` (preferences)
      * `di.xml` (virtual types)
      * `di.xml` (argument injection)
* Document everything in your own DevDocs - build up your own archive of documentation. Perhaps we could even sell it/use it as a base for a book at some point.
* Produce example module demonstrating how to achieve points in section
  * Include examples of how to achieve said functionality:
    * Programmatically; Either via a command or using a resource script
    * Manually; via the admin
* Add points for further research to [Magento Research Topics](https://github.com/ProcessEight/hydrogen/projects/8) project

### Then

* Work through lower-priority areas of study guide using framework above
* Work through tasks in [Certification](https://github.com/ProcessEight/hydrogen/projects/3) project

## Resources

### Documents

* (PDF) MAGENTO 2 CERTIFIED PROFESSIONAL DEVELOPER EXAM PREPARATION EBOOK: Swift, Joseph. Swift Otter.
    * Location: 
        * UKFast cloud-shaped USB key drive: `/HAR/Magento/2/Training`,
        * zone8-aurora: `/data/hydrogen/magento-resources/magento-2/documentation/certification/swift-otter/Magento 2 Certified Professional Developer Study Guide` 
 
* (PDF) MagentoU - Magento 2 Certified Associate Developer Exam Study Guide: Magento.
    * Locations: 
        * UKFast cloud-shaped USB key drive: `/HAR/Magento/2/Training`, 
        * zone8-aurora: `/data/hydrogen/magento-resources/magento-2/documentation/certification/magento-u/Study guides`

### Magento.com

* Magento U Courses (past and present)
    * Magento Certification Moderator Kit (For M1, but could still be useful in M2): `/data/hydrogen/magento-resources/magento-1/documentation/training/magento-u/Magento Certification/Magento Moderators Kit/magento-moderators-kit`
    * Magento Developer Certification Prep Study Group Participant Guide v. 1.2: `file:///data/hydrogen/magento-resources/magento-1/documentation/training/magento-u/Magento Certification/Magento Moderators Kit/magento-moderators-kit/MDC_Prep_Study_Group_Participant_Guide_v1.2.pdf`
    * Fundamentals of Magento 2 Development v2.1 Exercises & Solutions Guide: `file:///data/hydrogen/magento-resources/magento-2/documentation/training/magento-u/Fundamentals of Magento 2 Development v2.1/FMDv2.1_AllUnits_ExercisesAndSolutions_20170915.pdf`
* Magento U Free videos
* Continuous Learning as a Developer https://community.magento.com/t5/Magento-DevBlog/Continuous-Learning-as-a-Developer/ba-p/94044
* DevDocs: http://devdocs.magento.com/
* DevBlog: http://community.magento.com/devblog/

### Gists

Becoming Certified by Vinai Kopp

https://gist.github.com/ProcessEight/91bb00ac508ffe978bc0f309fae3f51f#becoming-certified-by-vinai-kopp

Fundamentals of Magento 2 Development (v2.1): Unit One: Magento 2 Platform and architecture (With notes explaining what has changed in Magento 2.2.0)

https://gist.github.com/ProcessEight/f51886fe5aa2ff7761c697e5b401cf72

Fundamentals of Magento 2 Development (v2.1): Unit Two: Request Flow (With notes explaining what has changed in Magento 2.2.0)

https://gist.github.com/ProcessEight/bc4d0fe36ad28f60ca3a9126f5ab5d53

Fundamentals of Magento 2 Development (v2.1): Unit Three: Rendering (With notes explaining what has changed in Magento 2.2.0)

https://gist.github.com/ProcessEight/b2357ea923ccd85369c1020c901081ed

Fundamentals of Magento 2 Development (v2.1): End of Unit Quizzes (with answers)

https://gist.github.com/ProcessEight/5e57863d6b8b4bdd9671a19b95266e17

Anatomy of Magento 2: Service Contracts

https://gist.github.com/ProcessEight/a14e6512616353917bfe9e1fbfc90802

Anatomy of Magento 2: Extension Attributes

https://gist.github.com/ProcessEight/da06d767a400a62d76faaa791ed3d0ca

Anatomy of Magento 2: API

https://gist.github.com/ProcessEight/74cd880994cff8fe2604e79da44b52f3

Anatomy of Magento 2: Price Indexing

https://gist.github.com/ProcessEight/e161d4dc7a744d2727bbf4360ecda615

Anatomy of Magento 2: Price Generation

https://gist.github.com/ProcessEight/640aac60b9711b8a6a1e68049ee00fdf

### Repositories

Magento 2 study guides in Markdown format

https://github.com/df2k2/m2cert

Magento 2 Certified Expert (formerly Professional) Developer notes

https://github.com/magento-notes/magento2-exam-notes

### Agency blogs

* Swift Otter
    * Course notes eBook: https://swiftotter.com/technical/certifications/magento-2-certified-developer-study-guide
    * Practice exam
* integer_net
    * Magento 2 Certified Professional Developer: About the Exam: https://www.integer-net.com/magento-2-certified-professional-developer-about-the-exam/
* netz98: 
    * ???Magento 2 Certified Professional Developer???: Profi-Tipps zur Zertifizierung (de_DE) https://www.netz98.de/blog/magento-howto/profi-tipps-zur-zertifizierung-magento-2-certified-professional-developer/
    * Infos zur Zertifizierung zum Magento 2 Certified Professional Developer (de_DE) https://www.netz98.de/magento/magento-2-certified-professional-developer/   
* BelVG:
    * Links to detailed articles expanding on points from the official study guide: https://belvg.com/blog/plus-two-magento-2-certified-professional-developer-at-belvg.html#step_7
* Mage Module:
    * A suprisingly insightful article discussing the methodology of preparing for the exam (especially the 'Specific things I did to prepare' section): https://www.magemodule.com/all-things-magento/professional-life/magento-2-certified-professional-developer-plus/

### Videos

* Mage Talk: https://www.youtube.com/watch?v=1WHxZH60AvU
* Nomad Mage
* Mage2.tv
* Mage2Katas
* M.Academy
* Swift Otter video courses

### Other Resource Lists

https://github.com/aleron75/mageres

https://github.com/DavidLambauer/awesome-magento2