---
date: "2019-05-05T00:00:00+01:00"
draft: false
linktitle: "BasicBasics 1"
menu:
  ryouwithme:
    parent: BasicBasics
    weight: 2
title: BasicBasics 1 
toc: true
type: docs
weight: 2
---

# An opinionated tour of RStudio

Welcome to the first lesson of [Basic Basics](../01-BasicBasics-0/)! Here at R-Ladies Sydney, we're a pretty opinionated bunch. In this lesson, we're going to impart our opinions^[Because these are opinions, you can probably find people who disagree. To each her own and all that!] on navigating RStudio and setting up your workflow. This forms the foundation of all future RYouWithMe lessons - so be sure to follow along carefully!

## Lesson Outcomes
By the end of the lesson, you should:

* 1.1. Have R and RStudio installed on your machine
* 1.2  Know your way around RStudio 
    + Know how to create a Project file and a script in RStudio
    + Understand the idea of a working directory and where your RYouWithMe files live
    serve
    + Understand what happens in the "four quadrants" of RStudio
* 1.3. Have adjusted your settings to make your RStudio life a little less painful [trust us on this one!]

## 1.1 Install R and RStudio

The first step is pretty straigforward. First, install [R](https://cloud.r-project.org/) then install [RStudio](https://www.rstudio.com/products/rstudio/download/#download). 

For this lesson (and likely the rest of RYouWithMe), we'll be using R v.3.5.1 (2018-07-02) -- "Feather Spray" and RStudio Version 1.1.463. So, if you already had R and/or RStudio installed, **best to check for version updates!** It probably won't make that much of a difference if you have an older version, but very occasionally it does matter. Also, note that our screenshots and screencasts will be use a Mac, but the instructions should broadly apply to PC users!

## 1.2 Creating files and a tour of the studio

In this screencast, we'll review:  

  * The overall layout of the default RStudio interface
  * How to create a project and organise your files
  * How to create a script
  * The four main quadrants of the RStudio interface and what you can expect to do in each.

<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/kfcX5DEMAp4?rel=0&modestbranding=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Watch the video and then carry out the following steps:

1. Create a new project and save it to an "RYouWithMe"" folder somewhere you'll be able to access it again. This can be your Desktop, in Dropbox, or anywhere else sensible. You'll be coming back to this for all your RYouWithMe lessons - so just be sure to remember where you put it!
2. Create a "scripts" and "data" folder within that folder.
3. Play around with expanding and reducing the components of the interface.
4. Create a script file and save it (to your scripts folder within RYouWithMe of course!)

For quick reference, here's a screenshot of the quadrants and a brief explanation

![](/img/quadrants.jpg)


  * Q1 - contains: script, data, command to run script
  * Q2 - contains: console
  * Q3 - contains: environment
  * Q4 - contains: files, plots, packages, help

## 1.3 Settings

Some people like Rstudio to remember stuff from session to session. We think this is dangerous. So to avoid future hassle, we recommend that you change two settings. 

Locate Preferences (on Mac, this is in the RStudio menu). In the General tab, uncheck "Restore .RData..."  and select "never" for "Save workspace..."

![](/img/settings.jpg)

Tada! 

Now onto [Lesson 2: Installing and Loading Packages!](../01-BasicBasics-2/)

