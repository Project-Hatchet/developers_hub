
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
- [2. **Developers**](#2-developers)
  - [2.1. ACE coding standards](#21-ace-coding-standards)
  - [2.2. Project standards](#22-project-standards)
    - [2.2.1. make.py](#221-makepy)
    - [2.2.2. make.cfg](#222-makecfg)
    - [2.2.3. Setup.py](#223-setuppy)
- [3. **Documenting the automation the workflow**](#3-documenting-the-automation-the-workflow)
    - [3.0.1. **build.yml 1st to run**](#301-buildyml-1st-to-run)
    - [3.0.2. **release_dev.yml**](#302-release_devyml)
    - [3.0.3. **release_rc.yml**](#303-release_rcyml)
    - [3.0.4. **release_main.yml**](#304-release_mainyml)
    - [3.0.5. **release-drafter.yml**](#305-release-drafteryml)
- [4. Release and Automation](#4-release-and-automation)
  - [4.1. Branching](#41-branching)
- [5. Setting up a Development Enviorment](#5-setting-up-a-development-enviorment)



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
   

# 2. **Developers**

## 2.1. ACE coding standards
- We use ACE coding standards which can be [here](https://ace3mod.com/wiki/development/coding-guidelines.html)
- We use ACE development Enviorment for experienced Arma developers [here](https://ace3mod.com/wiki/development/setting-up-the-development-environment.html)
  - For less experienced developers there we will have a through guide farther down.  

## 2.2. Project standards

- Replace **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only

### 2.2.1. make.py
- project = "@hatchet_PROJECT"
- key_name = "hatchet_PROJECT"
- prefix = "hatchet_PROJECT"
- pbo_name_prefix = "hatchet_PROJECT_"
- MAINPREFIX = "z"
- PREFIX = "hatchet_PROJECT_"
  
### 2.2.2. make.cfg
- project = @hatchet_PROJECT
- prefix = z\hatchet_PROJECT\addons
- module_root = P:\z\hatchet_PROJECT\addons
- optionals_root = P:\z\hatchet_PROJECT\optionals
- P:\z\hatchet_PROJECT\release
- pbo_name_prefix = PROJECT_
- -zipPrefix = hatchet_PROJECT
- build_tool = pboproject

### 2.2.3. Setup.py
MAINDIR = "z"

PROJECTDIR = "hatchet_PROJECT"

CBA = "P:\\x\\CBA_A3"

ACE = "P:\\z\\ACE3"


# 3. **Documenting the automation the workflow** 

 - You need to go through workflow file
  
 - change **PROJECT** in each file all in **lower case** and no special char's ie @$%&* only
    - release_dev.yml hatchet_PROJECT_dev
    - release_main.yml hatchet_PROJECT_main
    - release_rc.yml hatchet_PROJECT_rc


### 3.0.1. **build.yml 1st to run**
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

### 3.0.2. **release_dev.yml**
- on push to main branch
- builds addons with HEMTT
- builds addons with HEMTT
- Extracts the mods zip
- Uploads to steam workshop
- Only available to friends of the steam page


### 3.0.3. **release_rc.yml**
- Build triggered by tag rc-v0.0.0
- uploads public test version to the steam workshop

### 3.0.4. **release_main.yml**
- Build triggered by tag v0.0.0
- builds stable version and uploads to steam

### 3.0.5. **release-drafter.yml**
- Updates the change log
- Based on Labels
- Labels description's tell what part the tags update
- Read the issue labels
- relies on a config file located in the root folder called my-config.yml

# 4. Release and Automation

## 4.1. Branching

- ### Issues 
  - Issue will be created by prior to a branch getting created

  - Branch will be created off of issues 
  
  


# 5. Setting up a Development Enviorment 

























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

