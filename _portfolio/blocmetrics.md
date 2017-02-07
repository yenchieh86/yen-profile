---
layout: post
title: Blocmetrics
thumbnail-path: "https://raw.githubusercontent.com/yenchieh86/Blocmetrics/master/app/assets/images/ss2.png"
short-description: An analytics service and reporting tool that you can be used to track user activity and report results.

---

{:.center}
![](https://raw.githubusercontent.com/yenchieh86/Blocmetrics/master/app/assets/images/ss2.png)

## Explanation

A client-side JavaScript snippet that allows a user to track events on their website.
 
A server-side API that captures and saves those events to a database.
 
A Rails application that displays the captured event data for a user in a chart and line graph form.

## Problem

Application need to have the ability to receive event from those applications. 

Also need to use a graph to show events amount for each registered application.

## Solution

Create a API controller and route for receiving application's events.

Add Groupdate gem to Rails.

