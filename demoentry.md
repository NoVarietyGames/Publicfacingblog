---
title: ROBLOS Devlogs
publishDate: 2021-05-05 11:06:00
description: 'Offical Place for ROBLOS Updates'
tags:
  - Markdown
# heroImage: { src: './thumbnail.jpg', color: '#B4C6DA' }
language: 'English'
---
<!-- https://help.obsidian.md/Editing+and+formatting/Callouts -->
<!-- https://github.com/Ileriayo/markdown-badges -->
## **ROBLOS Update log**
Newest Update: 8/1/2024 (2.3.2)

![](../../../assets/novarietygames.png)

# Novariety Games

## Hot Fixes
A couple of bug fixes
## Introduction
The only place for official updates or a list of developers for **ROBLOS**
#

 [ROBLOS - GAME LINK](https://www.roblox.com/games/6764327104/ROBLOS-ALPHA)
 [ROBLOS Scripting Documentation](https://docs.novarietygames.com/)
[Novariety Games - Community Server](https://discord.com/invite/ZzT7PxqrGY)

[Novariety Games - Group](https://www.roblox.com/groups/11488629/)

## Key
There are 3 types of updates for the OS
Minor - Regular update mostly a small change
Major - Big massive update. Most likely new apps or an overhaul
Bugfix - Fixes bugs in the game

There are 3 types of updates for Applications
Minor - Fixes bug in the application or just adds quality of life feature
Major - Big Massive Update. Adds new features
Revamp/Overhaul - Revamps entire application


## IMPORTANT READ FIRST
This game is still in development, files may be deleted at any time for a wipe to revamp systems. Please do not save anything important or use regularly until out of development


<div class="callout callout-danger">
  <h4>Images for past updates don't work!</h4>
</div>

## UPDATES
<details>
<summary>BETA 2.3.3 - Website Rework</summary>
In today's update, the Website builder has not only been entirely reworked, along with site querying. But we are not allowing only allowing 8 MB of storage but 1 Gigabyte of storage! With the new backend rework, we decided to host our storage service allowing you guys 1 gigabyte of pure storage.

[Website Builder]
New UI, built inside of the browser instead of new instance. New coding language for the new site system (Documentation coming later). New URL querying and faster searching within the search engine. With the new URL system, you can now have variables instead of your URL! Along with paths and subdomains. There are no limits to how many subdomains or paths you have right now.
![image|255x213](upload://i8orwSk5ywJGdAY3VVfQIH43XLB.png)

To create a path variable you need to use : (Colon) and the variable name. 
The image example is /:x which means to access this variable within the script, you would use window.location.params and your variable name which would be x

Example 2 shows /path/:anyvariablenameatall which again window.location.params.anyvariablenameatall would have access to this variable. 

> Timestamp: October 7th 2024 1:07:00 PM

</details>

<details>
<summary>BETA 2.3.2 - Application (Revamp)</summary>
Browser V2 has just released! What is new?

Browser V2 has added

* Tab System - You can open multiple tabs in Rhodium. You can also check and switch between all your tabs.
* New Home Page Design (Influenced heavily on DuckDuckGo) - Check out Browser V2's new home page! Looking much better than V1
New Home Page
![New Home Page|690x390](upload://e3A4KyZ5sndDwKdtniRgZSm3tHp.png)
Old Home Page
![Old Home Page|690x287, 100%](upload://lfKEIeNyzDLITwEUhNPE77i32UA.png)
* New Results Page - (Again Influenced Heavily) - Check out the new results page for when you search up any website using Rhodium
![Results Page|690x392](upload://6Mgp1rWRNKgSallqV8rEJes2hMd.png)
* Fixed alot of legacy code under the hood for optimization

For Website Developers
* Added Event Dispatching, Event Listening and new Title API. Read more in [Documentation](https://docs.novarietygames.com/websitecreator/luascript/dom/document)
* Web Designer 2.0 is currently in the works! We will improve upon UI, add the new tab methods and make it overall a better experience then currently provided!

**SNEAK PEAK**
Hey! This is a sneak peak of what we are currently working on in ROBLOS. 
![New Game for ROBLOS|690x364](upload://izSi4YmnrewtivqFYkI01rCRORE.jpeg)
:shushing_face: 

We are currently making a 3D game for ROBLOS and *possibly* a 3D game maker engine for ROBLOS. Stay tune for more updates :happy1: 

(These projects are still in it's infant stage. The status is currently unknown and could be scrapped at any time during development)


> Timestamp: August 1st 2024 1:40 AM
</details>
<details>
<summary>BETA 2.3.1 - Minor Update</summary>
Added scripting documentation, [https://docs.novarietygames.com](https://docs.novarietygames.com)
Added a new file extension `.appinstaller`. This file extension can be used to have a user download your [App](https://application.novarietygames.com) from the ROBLOS App Store, create a website and follow the [documentation](https://docs.novarietygames.com) to configure your app installer
![image_2024-04-06_232056360|690x410](upload://wqT8YxWR7BvHAmzCjor5Mn5zdJm.png)

> Timestamp: April 6th 2024 11:21 PM
</details>

<details>
<summary>BETA 2.3 - MAJOR UPDATE</summary>
Been a while huh?
With the new addition of ROBLOS many things have been added, let's explain a few.
New Terminal, new HTML programming language for websites using Rhodium, new documentation for all these new coding features. 
Within Rhodium if you press F9, you can view the logs and the actual code! (If they have)

Screenshotting your OS (Still in development will take up ALOT of space), The ability to see space your folder or file is taking up, you can also see the entire OS space in main page of Xplorer.

New BSOD feature where if a program fails or errors during runtime or kernel loading. The system will BSOD to prevent any damage. Closing any open applications. You can also now Logout, Shut down your machine (aka restarting it) through the taskbar search menu. Which also shows Applications in your C:\\ROBLOS\SysFil64 folder. You can also load into BIOS by pressing backspace 5 times during load up and enter Advance options mode using F8 once during load up.
Although files cannot be deleted. If a core file is deleted, for example let's use Xplorer. If xplorer.exe is deleted or any core files pertaining to Xplorer. Xplorer will fail to launch with a Window (Not Windows) Alert. Last but not least. Their is a new feature in the settings where you can Update your OS files to get any new files that were added in a recent update. Which should fix any Window Alerts you get for new applications installed on the OS.

Well that's all for today's update! Catch you in the next one

TL;DR
* Added Updating System Files
* Added Screenshotting the OS
* Adding more taskbar features
* Added BSOD
* Added BIOS and Advance Options on startup
* Added Terminal and commands you can create
* Added HTML, CSS, and Luascript to Rhodium. 
> Timestamp: March 11th 2024 9:00 PM
</details>
<details>
<summary>BETA 2.2 - MAJOR UPDATE</summary>
New VS code application and ... AN APP STORE!!!
With the attention of coding to the main OS from VS code like creating forms right now or windows apps, the app store works independently from the ROBLOX and uses an external server to hold all the data. Soon the website will be public to allow developers to create applications and will be regularly updated but for now only my testing app is out right now.

The server right now is wonky as it's never always on but that will get fixed soon.



TL;DR
* Added VSCode/Main Coding to the OS and working app store
> Timestamp: August 18 2023 2:05 AM
</details>
<details>
<summary>BETA 2.1 - MAJOR UPDATE</summary>
In this update the website builder gets a new massive upgrade! You can now create code for your website, like javascript the code allows you to querySelect and get the current URL. This code is STILL under development and can result in lag, bugs or unexpected behavior. There are still many steps to improve but right now it seems very nice. It takes a VScode appearance 
* Check out my custom programming language to learn how to use the basics
* https://www.roblox.com/games/14041526119/Custom-Program-Language
TL;DR
* Added coding to browser applications and web builder application
> Timestamp: July 2nd 2023 1:40 AM
</details>
<details>
<summary>BETA 2.0 - MAJOR UPDATE</summary>

Having a lot of projects, I couldn't really update ROBLOS but during my free time I have been remaking the entire OS from scratch. We are pleased to introduce ROBLOS v2 with a whole new file system and notepad system. Allowing for the saving of TXT Files and more with saving to the new Xplorer. You will able to view files and application with saving files as well. Along side we introduced a new BROWSER called Rhodium which is like chromium but doesn't matter. This also comes with a new WEBSITE BUILDER!!! you can now create websites and publish them to the browser using datastores which means your website updates instantly. Now the Builder is in the baby stage, but I been working on it for a while. This builder includes TextLabels, and TextButtons (with onClick actions) I was thinking about making a programming language just for the browser but at a later time. You can also use thepageoflinks.com in the browser to see all new web builder projects URL and ability to click the links to go there. Thank you for watching the development of ROBLOS

This also comes with a new OOBE!
TL;DR
* Revamped entire OS [New OOBE, Taskbar, Desktop Icons, Application, and FileSystem]
* New browser with website builder to allow users to create websites
* All images are posted on ROBLOX
> Timestamp: July 2nd 2023 1:40 AM
</details>
<details>
<summary>BETA 1.7.1 - Minor Update</summary>

Added support for consoles.


> Timestamp: July 27 2021 2:41 PM
</details>

<details>
<summary>BETA 1.7 - Major Update</summary>

Hello everyone! Sorry for not updating! It's been a long time and I have been working on other projects *sneak peek in the community server* I officially added datastores for the background colors and gradients. *Finally!* More will be coming soon! Again sorry for not updating!

We also have a new name! Microblox Studios!
New features that are coming

* Ability to save TXT Files and folders
* More fan suggested features *join community server to suggest!*
> Timestamp: July 27 2021 2:10 AM
</details>


<details>
<summary>BETA 1.6 - Major Update</summary>
 


MAJOR UPDATE!
Datastores are WORKING NOW!!!! I can now sleep at night. 
Datastores save
Pin - No pin does not matter
Username
OOBE Complete 
OS Downloaded
Later datastores will save folders and files :smiley: 

Added OOBE (Out of box experience just like windows)
Added New Installer GUI

More coming soon! Suggest updates or applications on the Community Server

> Timestamp: May 5 2021 11:06 AM
</details>

<details>
<summary>BETA 1.5 - Major/Minor Update</summary>
Added a new standalone game called roleplay city!
This game is a part of Microbloxs corp or something but anyways here is link
[Roleplay City](https://www.roblox.com/games/6968039132/Roleplay-City)
You can find it in TRIBLOX, My profile, or the game link above
Have fun!

 Sorry for not updating in a while I have many things to work on and roleplay city was one of them ever since the old game I was working on got corrupt. :sad:

</details>

<details>
<summary>BETA 1.4 - Major Update</summary>
Added new website to allow fan-made applications/websites to look in the browser for more info
</details>

<details>
<summary>BETA 1.3 - Major Update</summary>
Added another new app 
</details>

<details>
<summary>BETA 1.2- Major Update</summary>
Revamped the main website on the browser check for yourself
Added new app :slight_smile: 
Datastores are still in the works I don't know how to use them :tired_face: 
Revamped the start menu to make it look smaller
</details>

<details>
<summary>BETA 1.1- Minor Update</summary>
Not a Major update but I made this logo. It took some thinking and whether or not this logo was good but please tell me if it is even if you say it's terrible. 
If there are any bugs report them to the community server
</details>

<details>
<summary>BETA 1.0- Minor Update</summary>
Yay! We hit version 1 of the beta!
Anyways just added a new app called notepad, download it at the app store
also you can delete core files :slight_smile: 
If there are any bugs then message them on the community server
</details>
<details>
<summary>BETA 0.1.9 - Minor Update</summary>
Now no pin is officially added
Still working on a way for these datastores to work :tired_face:
</details>
<details>
<summary>BETA 0.1.8 - Major Update</summary>
Added hex color changer to Personalize setting
Added App Store for published downloads with a new category in files
Overhaul on the app frames

 New Update should feature
* Datastores - Save wallpaper, pin, name
* Ability to add txt files won't save right now
* Ability to add folders 
</details>
<details>
<summary>BETA 0.1.7 - Major Update</summary>
A new social media platform has just been published to the browser :slight_smile: 
Triblox changed to a download instead of being on the OS on first start.
The datastores are coming soon where your pin will be saved and wallpaper
Another feature coming as well, creating .txt files and folders
You can suggest features in the community server 
Thank you :cowboy_hat_face:
</details>
<details>
<summary>BETA 0.1.6</summary>
~~A new special freeroam button has been added. The only way to get out of freeroam is to currently rejoin the game but that will be fixed in a later update~~ **SCRAPPED**
</details>
<details>
<summary>BETA 0.1.5</summary>
Blue screen has been added for special files there is a 1 in 100 chance of getting a blue screen so watch out!
</details>
<details>
<summary>BETA 0.1.4</summary>
Messages have finally been added! Im super happy right now for its release. Right now its public with everyone but I am working on it to be player to player
</details>
<details>
<summary>BETA 0.1.3</summary>
Added a new lock screen wallpaper, ability to delete the exe file, added new time and date to OS. 
</details>
<details>
<summary>BETA 0.1.2</summary>
Well there is a new website go ahead and try it out :slight_smile: of course its not complete and Im still working on it
Update may not come out frequently since I'm the only person on this dev team but I will try my best
If you have any suggestions join the community server 
</details>
<details>
<summary>BETA 0.1.1</summary>
Long time no see! Just added a new app called Triblox. It's like Roblox but for the OS. There aren't many games in it right now and the friend's menu is still in the works but of course, test it out for yourself! In future updates, you might be able to see your game on the games list. Tell us your feedback on the community server
</details>
<details>
<summary>BETA 0.1.0</summary>
Yay! We are finally in beta
Added donations still working on that datastore so you can save your pin, username, and background color anyways I hope you enjoy this OS I thought I would give up on it since it would be too hard but I want to complete this! If you have any suggestions join the community server. Thank you!
</details>
<details>
<summary>alpha 0.0.7</summary>
Major Update! 
Added new customization to wallpaper which means the setting customize is working now
Also Finally changed the name of the login user from $name to Account and $name os to ROBLOS
</details>
<details>
<summary>alpha 0.0.6</summary>
Major Update! 
Added a new website to the browser. Of course its not the final version of it there may be some updates to it but I hope you enjoy it!
</details>
<details>
<summary>alpha 0.0.5</summary>
Added new option to shutdown
</details>
<details>
<summary>alpha 0.0.4</summary>
Added login button to log out quickly. Also added ability to change your username check it out in settings :slight_smile: 
</details>
<details>
<summary>alpha 0.0.3</summary>
Added login page and added new button to start menu
</details>
<details>
<summary>alpha 0.0.2</summary>
Added start menu and a secert for you to figure out :slight_smile: 
</details>
<details>
<summary>alpha 0.0.1</summary>
The day Development started
</details>
