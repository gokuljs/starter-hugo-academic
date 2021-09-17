---
title: How to push large files on GitHub
subtitle: ""
date: 2020-04-01T14:56:18.211Z
summary: >-
  

  # **Let's get started**


  1. Download git extension for large files from <https://git-lfs.github.com/> or**git lfs install**. **Note(** *If you have already committed large files into git then remove those files from the local repository before set tracking of large files***)**

  2. Removing large files from the local repository which you have already committed into your local repository can be done by rolling back to the previous commit this can be done by using git log and git reset **git log** will display a list of all your commits and **git reset** “your commit” will help you to revert to your previous commit.

  3. Once git lfs installed then the next step is to track large files in your project that can be done by using **git lfs track “* your file extension or the file path ”** for ex:- **git lfs track *“*.csv”*** or **git lfs track “*.jpeg”** etc.

  4. Once the tracking of large files is done then you have to make sure that all the files are tracked this can be done **git add .gitattributes**

  5. Then Just commit and push to GitHub as you normally would.
draft: false
featured: false
authors:
  - Gokul JS
lastmod: 2020-12-13T00:00:00Z
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false
  filename: featured.png
---
<!--StartFragment-->

By default in GitHub maximum file size upload limit is 50mb. But when you are working on a project there are chances where you will encounter a file size that is greater than 50mb or it might be video files, data sets, etc. How to commit these files into GitHub?

<!--EndFragment-->