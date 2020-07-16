---
permalink: /
title: "Short Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Sanghoon Jeon has received the B.S. degree in electronic engineering from Kyoungpook National University, Republic of Korea in 2012 and the M.S degree from the Department of Information and Communication Engineering, DGIST, Republic of Korea in 2014. I am currently a Ph.D. candidate at DGIST, advised by Prof. Sang Hyuk Son. My research mainly focuses on developing healthcare applications using Wearable Computing and Cyber Physical Systems.

------

## Research Interests
======
Wearable Computing, Human Computer Interface, Healthcare & IoT Applications, Embedded Systems, and Cyber-Physical Systems

------

## Education
======
>2014/03 - 2020/08

  * Ph.D. Candidate in Department of information and Communication Engineering, DGIST
  * Dissertation: "AI-based Human-in-the-loop Cyber Physical Systems in Healthcare Applications"
  * Advisor: Sang Hyuk Son

>2012/03 - 2014/02

  * M.E. in Department of Information and Communication Engineering, DGIST
  * Master's Thesis: "Development of Rehabilitation Applications by Using Wearable Sensors"
  * Co-Advisors: Taejoon Park and Sang Hyuk Son

>2006/03 - 2012/02

  * B.E. in School of Electronic Engineering College of IT Engineering from Kyoungpook National University
  * Major: Information and Communication Engineering

------

## Publications
======
  1. An Automatic Driving Performance Assessment System for Stroke Drivers by exploiting Pre-trained CNN models 
     Sanghoon Jeon, Joonwoo Son, Myoungouk Park, and Sang Hyuk Son
     IEEE Access, submitted

  2. A Wearable Sleep Position Tracking System Based on Dynamic State Transition Framework [PDF, Link]
     Sanghoon Jeon, Taejoon Park, Anand Paul, Yang-Soo Lee, and Sang Hyuk Son
     IEEE Access, 2019 (SCIE, IF=4.098, Category: Computer Science, Information Systems, JCR Ranking  Top 20%)

  3. Demo: Automatic Assessment Framework for Range of Motion Test using Wearable Device and Smartphone
     Sanghoon Jeon, Yang-Soo Lee, and Sang Hyuk Son
     The 17th Annual International Conference on Mobile Systems, Applications, and Services (MobiSys), Seoul, Republic of Korea, June 2019

  4. Early Detection of Wake-up Stroke using Wearable Sensors: Preliminary Study
     Yang-Soo Lee and Sanghoon Jeon
     The 4th International Brain Technology Conference (BrainTech), Tel Aviv, Israel, March 2019





The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
