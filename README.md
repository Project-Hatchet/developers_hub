
<p align="center">
  <img width="480" height="480" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/logos/ProjectHatchetBlk.jpg" >
</p>


# **Project Hatchet Studio** <!-- omit in toc --> 


## **Table of Contents** <!-- omit in toc --> 


- [1. **About Us**](#1-about-us)
  - [1.1. **Our Culture**](#11-our-culture)
  - [1.2. **Benefits to contributing**](#12-benefits-to-contributing)
  - [1.3. **Donations**](#13-donations)
  - [1.4. Media on our Projects](#14-media-on-our-projects)
- [2. **New Members**](#2-new-members)
  - [2.1. Member standards](#21-member-standards)
  - [2.2. Project sync ups](#22-project-sync-ups)
  - [2.3. Creating Documenting](#23-creating-documenting)
  - [2.4. Where to start](#24-where-to-start)
- [3. **Developers**](#3-developers)
  - [3.1. ACE coding standards](#31-ace-coding-standards)
  - [3.2. Project standards](#32-project-standards)
    - [3.2.1. make.py](#321-makepy)
    - [3.2.2. make.cfg](#322-makecfg)
    - [3.2.3. Setup.py](#323-setuppy)
    - [3.2.4. **Workflow File's that need to be Changed when making a new repo**](#324-workflow-files-that-need-to-be-changed-when-making-a-new-repo)
    - [3.2.5. **Non specific Workflow Automation**](#325-non-specific-workflow-automation)
  - [3.3. Branching](#33-branching)
    - [3.3.1. **Issues**](#331-issues)
    - [3.3.2. **Descriptor**](#332-descriptor)
    - [3.3.3. **Types**](#333-types)
    - [3.3.4. **Default types**](#334-default-types)
    - [3.3.5. **Branch Creation Format**](#335-branch-creation-format)
    - [3.3.6. **Merging**](#336-merging)
- [4. Releases](#4-releases)
  - [4.1. **Internal Testing**](#41-internal-testing)
  - [4.2. **All issues will be tracked by a automated project board**](#42-all-issues-will-be-tracked-by-a-automated-project-board)
    - [4.2.1. Steps](#421-steps)
    - [4.2.2. **release_dev.yml will do the following**](#422-release_devyml-will-do-the-following)
  - [4.3. **Release Candidate**](#43-release-candidate)
    - [4.3.1. **release_rc.yml will do the following**](#431-release_rcyml-will-do-the-following)
  - [4.4. **main release**](#44-main-release)
    - [4.4.1. **release_main.yml will do the following**](#441-release_mainyml-will-do-the-following)
- [5. Setting up a project board with review tracking](#5-setting-up-a-project-board-with-review-tracking)
  - [5.1. Automation](#51-automation)
  - [5.2. Whole Board Overview](#52-whole-board-overview)
  - [5.3. Issues that need to be reviewed (triage)](#53-issues-that-need-to-be-reviewed-triage)
  - [5.4. TODO/Ready to be assigned to a dev, Dev is Working AKA DOING](#54-todoready-to-be-assigned-to-a-dev-dev-is-working-aka-doing)
  - [5.5. Pull request Submitted](#55-pull-request-submitted)
  - [5.6. Pull request in progress](#56-pull-request-in-progress)
  - [5.7. Review approved](#57-review-approved)
  - [5.8. Done/merged into main](#58-donemerged-into-main)
- [6. Setting up a Development Enviorment](#6-setting-up-a-development-enviorment)



# 1. **About Us**
- A few Arma mod developers got together in 2021 and started the open-source Project Hatchet Studio because we noticed a lack of quality interactive vehicle interiors and a lack of understanding of HUD elements. Arma 3 community. The actual Hatchet Project has been in development since 2018, with the original project the [h-60]( https://forums.bohemia.net/forums/topic/223859-h-60-interactive-blackhawk-pack-public-beta-03-released-development-restarted-join-our-discord/)

- It all started with [ITC AIR]( https://steamcommunity.com/workshop/filedetails/?id=1321663083) and [ITC land]( https://steamcommunity.com/workshop/filedetails/?id=1388192893) with Yax creating Arma’s First IR aircraft pointer, which allowed aircraft to mark targets at night for the infantry. Another Arma first was making the Rover feed allowing ground units to see the Pod feed on fix winged air support assets. After working ITC, AIR/Land  Yax worked on the [F/A-18]( https://steamcommunity.com/sharedfiles/filedetails/?id=743099837) where he made an interactive cockpit and integrated ITC AIR., and wing flex during turning, not to mention numerous real-world and simulated weapon systems.   

- Our vision is to make the most functional aircraft and ground vehicle that has ever been made in Arma, incorporating all of the lessons learned over the years. Our scope is modeling realistic vehicle interior interiors and cockpits that are fully interactive with clickable cockpits. We will focus on quality over mass production. We plan to achieve this by making all of our projects open-source and recruiting developers that share our vision (and are as sick as I am of blowing up randomly in modded helicopters while landing as I am ). We will focus on training and guiding new members through the difficulties of navigating modding in Arma. The end state of our project is educating and spreading knowledge across the multiple projects running simultaneously.
  
  

## 1.1. **Our Culture**
- Real-life priorities need to take precedence first, Family, School, Work, and Mental Health.

- Project Hatchet is an open-source hobby that we all do on the side of working/going to school full time. First and foremost, no one is getting paid in Project Hatchet Studios, so do not look at this as a job. It may develop into something more in the future; only time will tell.
- The individual developer gets to pick what you want to work on, as long as it is in the scope of the projects currently in progress and an issue is created and approved by a senior member of the studio.
- There are no required work hours per day, per week, or month for that matter. If another developer is waiting on your commit, we ask that you complete it promptly.
- If you need a break, let us know in Discord; it is acceptable to walk away from the project for six months or a year. Take the time you need. Just know someone will be reaching to you via Discord to check up on you and make sure you are okay. 

## 1.2. **Benefits to contributing**
- Make better assets for the Arma community.  
- Learn a new skill or get better at an existing one.
- Understanding how the development process works, Arma is not an easy to start developing in we - can help you from making beginner mistakes.   
- Use this for you CV and required job experience and build your reputation in your skill set.
- Personal satisfaction 

## 1.3. **Donations**
- Time is the most valuable asset you can give, so we want to thank you for helping us along with our journey to complete our vision. 

- We accept donations for the operating cost of running a server box that we share with an Arma unit. We use one instance on the server box to conduct private internal testing, and the second instance is used for public MP. 
- We use [US OVScloud](https://us.ovhcloud.com/bare-metal/game/?xtor=CS2-232-[paid-google-nb-public-vpsnonbranded]&gclid=Cj0KCQiA-OeBBhDiARIsADyBcE6UiMtBfF4u50Pf6sfbVFvX6On_HiLStPkcdiyLa0E-im_8ALJ-XhEaAkvUEALw_wcB&gclsrc=aw.ds) and have a [Game-2 server](https://us.ovhcloud.com/bare-metal/game/prices/). We received a discount and pay $99 for the server box and $28 Windows Server 2016 licenses per month.
-  Donations are not required and do not go to the developers. Donations go to a PayPal pool to pay for the server.
-  If you have any suggestions to save us money feel free to let us know. We are looking at the possibility of creating a Patreon account, but we are too early in the process of creating the studio to worry about individual developer donations. 





## 1.4. Media on our Projects 
1. [Bohemia Post](https://forums.bohemia.net/forums/topic/223859-h-60-interactive-blackhawk-pack-hh-60-pave-hawk-rescue-hoist/)
2. [Helisimmer Article](https://www.helisimmer.com/news/arma-iii-uh-60m-interactive-blackhawk)
3. [Current in-game video](https://www.youtube.com/watch?v=O5s4fXX1zZ0&feature=emb_lo)
   
# 2. **New Members**

## 2.1. Member standards 
  - Comunication works both ways
  - We can not solve an issue that we do not know about 
  - Every opinion maters in the team from the most senior to newest member.
  - **Focus on finding a something productive to do, find something to improve.**
  - This Team is not for recognition, its to build the best Aircraft Arma has ever seen.
  - **Do not wait to be told what to do seek a task out and do it.**
  - Show results early and often, that is what the dev channel is there for. 
  - Bad news doesn't get better with time. 

## 2.2. Project sync ups
  - Getting the team together regularly to check progress, ask questions, and address any issues is another good way to keep everyone on track and assure that all team members are aware of their responsibilities in the project.
   
  - Make sure that the entire team knows the scope of the project and that each team member is clear about exactly what is expected of them.
  - No one can effectively complete an assignment if they are unsure what tasks they are responsible for

## 2.3. Creating Documenting
  - You may  have implemented the most sophisticated system in the in all of arma, if its not documented both for users and developers no one will know about it or how it works.
  
  - Make documentation for each repository, both for users and developers, feel free to steal from this and use as much as possible.
  - Make an end use guide AKA how to use every system and key binding  


## 2.4. Where to start
- Read this documentation 
- Figure out how you want to contribute and communicate this in the discord under the developer chat.
  - **3D Modeling**
    - Vehicle Creation
    - Vehicle Editing
    - ordnance Creation
    - Additional Vehicle parts
    - Getting Game ready
    - Baking 
    - Encoding (Object builder, Blender )
    - UV Unwrapping 

  - **Scripting** 
    - Scripting new functionality 
    - Writing configs
    - Model Encoding (Object builder)
    - Rvmat Expert
   
  - **Grapic designing**
    - Designing logos
    - Branding
    - 3D Texture work  
    - Substance Painter 
    - 2D Texturing (Rvmat)
  
  - **Animating** 
    - Parts of models 
    - Animation of Character Positions Inside Vehicles
  
  - **Programming**
    - Internal tools for development 
    - CI/CD
    - .DLL creation
    - PhysX Expert 

  - **Video Content Creators**
    - Video Encoding
    - YouTube Content Creators
    - Streamers

  - **Documentation** ( everybody's least favorite topic)
    - Creating
    - Maintaining
    - validating   
  
  - **Future roles**
    - Leadership roles
    - Marketing
 




# 3. **Developers**

## 3.1. ACE coding standards
- We use ACE coding standards which can be [here](https://ace3mod.com/wiki/development/coding-guidelines.html)
- We use ACE development Enviorment for experienced Arma developers [here](https://ace3mod.com/wiki/development/setting-up-the-development-environment.html)
  - For less experienced developers there we will have a through guide further down.  

## 3.2. Project standards

- Replace the placeholder **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only

### 3.2.1. make.py
- project = "@hatchet_PROJECT"
- key_name = "hatchet_PROJECT"
- prefix = "hatchet_PROJECT"
- pbo_name_prefix = "hatchet_PROJECT_"
- MAINPREFIX = "z"
- PREFIX = "hatchet_PROJECT_"
  
### 3.2.2. make.cfg
- project = @hatchet_PROJECT
- prefix = z\hatchet_PROJECT\addons
- module_root = P:\z\hatchet_PROJECT\addons
- optionals_root = P:\z\hatchet_PROJECT\optionals
- P:\z\hatchet_PROJECT\release
- pbo_name_prefix = PROJECT_
- -zipPrefix = hatchet_PROJECT
- build_tool = pboproject

### 3.2.3. Setup.py
MAINDIR = "z"

PROJECTDIR = "hatchet_PROJECT"

CBA = "P:\\x\\CBA_A3"

ACE = "P:\\z\\ACE3"

### 3.2.4. **Workflow File's that need to be Changed when making a new repo** 
 - You need to go through workflow file
 - change **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only
    - release_dev.yml hatchet_PROJECT_dev
    - release_main.yml hatchet_PROJECT_main
    - release_rc.yml hatchet_PROJECT_rc

### 3.2.5. **Non specific Workflow Automation**

- **build.yml 1st to run**
  - runs when pull requests to main branch
  - it does a lint check
     - Checkout the source code
     - Validate SQF
     - Validate Config
     - Validate Stringtables
        - We currently don't have
     - Validate Return Types
     - Check for BOM ?
        - No one knows what this means
  3. builds the project
     1. Build with HEMTT
     2. Releases zip file

- **release-drafter.yml**
- Updates the change log
- Based on Labels
- Labels description's tell what part the tags update
- Read the issue labels
- relies on a config file located in the root folder called my-config.yml


## 3.3. Branching
**We will follow the branching format**
- **If Something needs to get added let Michael know more types can be added**
- we may be able to condense the Types  

### 3.3.1. **Issues** 
  - Issue will be created by prior to a branch getting created
  - Branch will be created off of issues 
  - When a branch is PR is approved and merged intr 


### 3.3.2. **Descriptor**
  - Add a short descriptor of the task
  - This makes the branch name recognizable and easy to **search**
  - In descriptor we will use hyphens - to use instead of white space
  - **Note: This is only git/github and will not be used in code** 

<p  >
  <img width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Branching/feature_search.png">
</p>

### 3.3.3. **Types** 
  - This is the type of issue we are working on **all in lowercase**
  - This is diffrent than the labels in Github 

### 3.3.4. **Default types**
  - **feature**
    - Adding a new feature
  - **bugfix**
    - A fix for a bug 
  - **documentation**
    - Adding or updating documentation
  - **hotfix**
    - critical bug fix
  - **devops**
    - updating a tool or workflow not related to 
  - **model**
    - an update to a model
  - **texture**
    - update to texture or rvmat
  - **refactor**
    - refactor of code to improve
  - **release**
    - Need to ask about this  could be useful   
   
### 3.3.5. **Branch Creation Format**

   - **Type**/**Descriptor**

   - **Good examples**
     - bugfix/dampeners
     - feature/overhaul-flir-system
     - feature/open-inspector

   - **Bad examples**
     - version1-breakpoint1
     - update-electron-comparison

### 3.3.6. **Merging** 
  - There are two options when merging **rebase** and **Squash Merge**
    - Squash Merge is better when you commit frequent to a branch and want to clean up the history to show a single branch being added 
    - Rebase is used to merge all of the commit and keep the commit history
    - More can be read about types of merges ob the Github [Docs](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-merges)  

  
# 4. Releases 

## 4.1. **Internal Testing** 
## 4.2. **All issues will be tracked by a automated project board** 
<img  width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/automation_workflow.jpg">

### 4.2.1. Steps
- Issue gets created and is assigned an Type: Triage label
  
- A senior developer Triage's the issue and assigns:
  - **To a Project board** 
  - Priority 
  - Status
  - Role
  
  - Experience level 
    - or will not fix and issue gets closed
  - A developer will assign themselves a task and create a branch 
  - Developer will work on the issue until is is complete and submit for a PR
  - A code review will happen by a senior developer
    - If Failed the developer will get notified
    - IF passed the PR will be merged
    - The PR will trigger an automated build process and release to steam
    - the developer will be free to take a new task  
  
### 4.2.2. **release_dev.yml will do the following**
- on push to main branch
- builds addons with HEMTT
- builds addons with HEMTT
- Extracts the mods zip
- Uploads to steam workshop
- Only available to friends of the steam page




## 4.3. **Release Candidate** 
<img  width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/release_candidate.jpg" >




### 4.3.1. **release_rc.yml will do the following**
- Build triggered by tag rc-v0.0.0
- uploads public test version to the steam workshop

## 4.4. **main release**

<img  width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/main_release.jpg">



### 4.4.1. **release_main.yml will do the following**
- Build triggered by tag v0.0.0
- builds stable version and uploads to steam

# 5. Setting up a project board with review tracking 

## 5.1. Automation
- The following images will show the whole board and the automation
- Project boards will be built for each release
- There is no standard board that meets our need so feel free to pick the one that matches 
  - Change the template to match the our standard 

 ## 5.2. Whole Board Overview 
<img width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/Whole%20Board.png">
 
 ## 5.3. Issues that need to be reviewed (triage)
 <img width="500"  src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/Issues_to_be_reviewed.png">

 ## 5.4. TODO/Ready to be assigned to a dev, Dev is Working AKA DOING
- **No Automation**

 <img  width="500" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/Branch_created%20.png">

 ## 5.5. Pull request Submitted 

 <img width="500"  src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/PR_inprogress.png">

 ## 5.6. Pull request in progress 

 <img width="500"  src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/PR_review.png">

 ## 5.7. Review approved 

 <img width="500"  src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/PR_approved%20png.png">

 ## 5.8. Done/merged into main   

 <img width="500"  src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Project_board_standards/Done_Merged.png">


# 6. Setting up a Development Enviorment
- TODO 





<!-- This is the code you need to align images to the left:

<img  width="100" height="100" src="http://www.fillmurray.com/100/100">

This is the code you need to align images to the right:

<img align="right" width="100" height="100" src="http://www.fillmurray.com/100/100">

This is the code you need to align images to the right:

<p align="center">
  <img width="460" height="300" src="http://www.fillmurray.com/460/300">
</p>

 -->

<div class="footer" align="center">
    &copy; 2021 PROJECT HATCHET STUDIO
</div>

