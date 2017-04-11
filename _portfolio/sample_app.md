---
layout: post
title: Sample Twitter App
thumbnail-path: "https://raw.githubusercontent.com/yenchieh86/Blocmetrics/master/app/assets/images/ss2.png"
short-description: Build a website like Twitter.

---

{:.center}
![](https://raw.githubusercontent.com/yenchieh86/Blocmetrics/master/app/assets/images/ss2.png)

## Explanation

A website like Twitter that allow user to create posts, follow other users.

Build User model and mailing system without using Devise gem.

Users need to confirm thier email address before they can log in.

Write test code to make sure there's no mistake when I doing code refactoring

Using AWS S3 to save image file.

## Problem

First time use AWS to store image file.

Need to confirm user's email address before useer log in

## Solution

Use fog gem to upload image file to AWS if application is running in production environment

Create an controller for user to active their account, and sent the link to user by email 