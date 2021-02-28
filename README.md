
<p align="center">
  <img width="480" height="480" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/logos/ProjectHatchetBlk.jpg" >
</p>


# **Project Hatchet Studio** <!-- omit in toc --> 


## **Table of Contents** <!-- omit in toc --> 


- [**About Us**](#about-us)
  - [**Our Culture**](#our-culture)
  - [**Benefits to contributing**](#benefits-to-contributing)
  - [**Donations**](#donations)
  - [Media on our Projects](#media-on-our-projects)
- [**New Members**](#new-members)
  - [Member standards](#member-standards)
  - [Project sync ups](#project-sync-ups)
  - [Creating Documenting](#creating-documenting)
  - [Where to start](#where-to-start)
- [**Developers**](#developers)
  - [ACE coding standards](#ace-coding-standards)
  - [Project standards](#project-standards)
    - [make.py](#makepy)
    - [make.cfg](#makecfg)
    - [Setup.py](#setuppy)
    - [**Workflow File's that need to be Changed when making a new repo**](#workflow-files-that-need-to-be-changed-when-making-a-new-repo)
    - [**Non specific Workflow Automation**](#non-specific-workflow-automation)
  - [Branching](#branching)
- [Releases](#releases)
  - [**Internal Testing**](#internal-testing)
    - [Steps](#steps)
    - [**release_dev.yml will do the following**](#release_devyml-will-do-the-following)
  - [**Release Candidate**](#release-candidate)
    - [**release_rc.yml will do the following**](#release_rcyml-will-do-the-following)
  - [**main release**](#main-release)
    - [**release_main.yml will do the following**](#release_mainyml-will-do-the-following)
- [Setting up a project board with review tracking](#setting-up-a-project-board-with-review-tracking)
- [Setting up a Development Enviorment](#setting-up-a-development-enviorment)



# **About Us**
- A few Arma mod developers got together in 2021 and started the open-source Project Hatchet Studio because we noticed a lack of quality interactive vehicle interiors and a lack of understanding of HUD elements. Arma 3 community. The actual Hatchet Project has been in development since 2018, with the original project the [h-60]( https://forums.bohemia.net/forums/topic/223859-h-60-interactive-blackhawk-pack-public-beta-03-released-development-restarted-join-our-discord/)

- It all started with [ITC AIR]( https://steamcommunity.com/workshop/filedetails/?id=1321663083) and [ITC land]( https://steamcommunity.com/workshop/filedetails/?id=1388192893) with Yax creating Arma’s First IR aircraft pointer, which allowed aircraft to mark targets at night for the infantry. Another Arma first was making the Rover feed allowing ground units to see the Pod feed on fix winged air support assets. After working ITC, AIR/Land  Yax worked on the [F/A-18]( https://steamcommunity.com/sharedfiles/filedetails/?id=743099837) where he made an interactive cockpit and integrated ITC AIR., and wing flex during turning, not to mention numerous real-world and simulated weapon systems.   

- Our vision is to make the most functional aircraft and ground vehicle that has ever been made in Arma, incorporating all of the lessons learned over the years. Our scope is modeling realistic vehicle interior interiors and cockpits that are fully interactive with clickable cockpits. We will focus on quality over mass production. We plan to achieve this by making all of our projects open-source and recruiting developers that share our vision (and are as sick as I am of blowing up randomly in modded helicopters while landing as I am ). We will focus on training and guiding new members through the difficulties of navigating modding in Arma. The end state of our project is educating and spreading knowledge across the multiple projects running simultaneously.
  
  

## **Our Culture**
- Real-life priorities need to take precedence first, Family, School, Work, and Mental Health.

- Project Hatchet is an open-source hobby that we all do on the side of working/going to school full time. First and foremost, no one is getting paid in Project Hatchet Studios, so do not look at this as a job. It may develop into something more in the future; only time will tell.
- The individual developer gets to pick what you want to work on, as long as it is in the scope of the projects currently in progress and an issue is created and approved by a senior member of the studio.
- There are no required work hours per day, per week, or month for that matter. If another developer is waiting on your commit, we ask that you complete it promptly.
- If you need a break, let us know in Discord; it is acceptable to walk away from the project for six months or a year. Take the time you need. Just know someone will be reaching to you via Discord to check up on you and make sure you are okay. 

## **Benefits to contributing**
- Make better assets for the Arma community.  
- Learn a new skill or get better at an existing one.
- Understanding how the development process works, Arma is not an easy to start developing in we - can help you from making beginner mistakes.   
- Use this for you CV and required job experience and build your reputation in your skill set.
- Personal satisfaction 

## **Donations**
- Time is the most valuable asset you can give, so we want to thank you for helping us along with our journey to complete our vision. 

- We accept donations for the operating cost of running a server box that we share with an Arma unit. We use one instance on the server box to conduct private internal testing, and the second instance is used for public MP. 
- We use [US OVScloud](https://us.ovhcloud.com/bare-metal/game/?xtor=CS2-232-[paid-google-nb-public-vpsnonbranded]&gclid=Cj0KCQiA-OeBBhDiARIsADyBcE6UiMtBfF4u50Pf6sfbVFvX6On_HiLStPkcdiyLa0E-im_8ALJ-XhEaAkvUEALw_wcB&gclsrc=aw.ds) and have a [Game-2 server](https://us.ovhcloud.com/bare-metal/game/prices/). We received a discount and pay $99 for the server box and $28 Windows Server 2016 licenses per month.
-  Donations are not required and do not go to the developers. Donations go to a PayPal pool to pay for the server.
-  If you have any suggestions to save us money feel free to let us know. We are looking at the possibility of creating a Patreon account, but we are too early in the process of creating the studio to worry about individual developer donations. 





## Media on our Projects 
1. [Bohemia Post](https://forums.bohemia.net/forums/topic/223859-h-60-interactive-blackhawk-pack-hh-60-pave-hawk-rescue-hoist/)
2. [Helisimmer Article](https://www.helisimmer.com/news/arma-iii-uh-60m-interactive-blackhawk)
3. [Current in-game video](https://www.youtube.com/watch?v=O5s4fXX1zZ0&feature=emb_lo)
   
# **New Members**

## Member standards 
  - Comunication works both ways
  - We can not solve an issue that we do not know about 
  - Every opinion maters in the team from the most senior to newest member.
  - **Focus on finding a something productive to do, find something to improve.**
  - This Team is not for recognition, its to build the best Aircraft Arma has ever seen.
  - **Do not wait to be told what to do seek a task out and do it.**
  - Show results early and often, that is what the dev channel is there for. 
  - Bad news doesn't get better with time. 

## Project sync ups
  - Getting the team together regularly to check progress, ask questions, and address any issues is another good way to keep everyone on track and assure that all team members are aware of their responsibilities in the project.
   
  - Make sure that the entire team knows the scope of the project and that each team member is clear about exactly what is expected of them.
  - No one can effectively complete an assignment if they are unsure what tasks they are responsible for

## Creating Documenting
  - You may  have implemented the most sophisticated system in the in all of arma, if its not documented both for users and developers no one will know about it or how it works.
  
  - Make documentation for each repository, both for users and developers, feel free to steal from this and use as much as possible.
  - Make an end use guide AKA how to use every system and key binding  


## Where to start
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
 




# **Developers**

## ACE coding standards
- We use ACE coding standards which can be [here](https://ace3mod.com/wiki/development/coding-guidelines.html)
- We use ACE development Enviorment for experienced Arma developers [here](https://ace3mod.com/wiki/development/setting-up-the-development-environment.html)
  - For less experienced developers there we will have a through guide further down.  

## Project standards

- Replace the placeholder **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only

### make.py
- project = "@hatchet_PROJECT"
- key_name = "hatchet_PROJECT"
- prefix = "hatchet_PROJECT"
- pbo_name_prefix = "hatchet_PROJECT_"
- MAINPREFIX = "z"
- PREFIX = "hatchet_PROJECT_"
  
### make.cfg
- project = @hatchet_PROJECT
- prefix = z\hatchet_PROJECT\addons
- module_root = P:\z\hatchet_PROJECT\addons
- optionals_root = P:\z\hatchet_PROJECT\optionals
- P:\z\hatchet_PROJECT\release
- pbo_name_prefix = PROJECT_
- -zipPrefix = hatchet_PROJECT
- build_tool = pboproject

### Setup.py
MAINDIR = "z"

PROJECTDIR = "hatchet_PROJECT"

CBA = "P:\\x\\CBA_A3"

ACE = "P:\\z\\ACE3"

### **Workflow File's that need to be Changed when making a new repo** 
 - You need to go through workflow file
 - change **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only
    - release_dev.yml hatchet_PROJECT_dev
    - release_main.yml hatchet_PROJECT_main
    - release_rc.yml hatchet_PROJECT_rc

### **Non specific Workflow Automation**

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


## Branching
**We will follow the branching format**
- **If Something needs to get added let Michael know more types can be added**
  - we may be able to condence the Types  
  
- ### Issues 
  - Issue will be created by prior to a branch getting created
  - Branch will be created off of issues 
  - When a branch is PR is approved and merged intr 


  - **Descriptor**
    - Add a short descriptor of the task
    - This makes the branch name recognizable and easy to **search**
    - In descriptor we will use hyphens - to use instead of white space
      - **Note: This is only git/github and will not be used in code** 

<p align="left" >
  <img width="1000" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/Branching/searching_type_frature.png">
</p>

  - **Types** 
    - This is the type of issue we are working on **all in lowercase**
    - This is diffrent than the labels in Github 
  
    - **Default types**
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
     

  -  **Branch Creation Format**
     - **Type**/**Descriptor**

     - **Good examples**
       - bugfix/dampeners
       - feature/overhaul-flir-system
       - feature/open-inspector

     - **Bad examples**
       - version1-breakpoint1
       - update-electron-comparison

  
# Releases 

## **Internal Testing** 
<img align="center" width="" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/automation_workflow.jpg">

### Steps
- Issue gets created and is assigned an Type: Triage label
- A senior developer Triage's the issue and assigns:
  - Priority 
  - Status
  - Role
  - Experience level 
    - or will not fix and issue gets closed
  


### **release_dev.yml will do the following**
- on push to main branch
- builds addons with HEMTT
- builds addons with HEMTT
- Extracts the mods zip
- Uploads to steam workshop
- Only available to friends of the steam page




## **Release Candidate** 
<img align="center" width="" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/release_candidate.jpg" >




### **release_rc.yml will do the following**
- Build triggered by tag rc-v0.0.0
- uploads public test version to the steam workshop

## **main release**

<img align="center" width="" src="https://raw.githubusercontent.com/Project-Hatchet/developers_hub/main/media/workflow_and_automation/main_release.jpg">



### **release_main.yml will do the following**
- Build triggered by tag v0.0.0
- builds stable version and uploads to steam









# Setting up a project board with review tracking 
- TODO 


# Setting up a Development Enviorment
- TODO 





<!-- This is the code you need to align images to the left:

<img align="left" width="100" height="100" src="http://www.fillmurray.com/100/100">

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

