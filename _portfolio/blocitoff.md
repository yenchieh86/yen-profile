---
layout: post
title: Blocitoff
thumbnail-path: "img/blocitoff.png"
short-description: Build an application that allows users to create self-destructing to-do lists.

---

{:.center}
![]({{ site.baseurl }}/img/blocitoff.png)

## Explanation

It's an application that allows users to create self-destructing to-do lists.

Users can create an account in which they add tasks and delete them when completed. The tasks will self-destruct after 7 days if not completed.

## Problem

To-do item will be auto delete after 7 days.

When User create/complete a to-do item, view will changes without reflashing entire page.

## Solution

Use jQuery to hide the target without reflashing page.

Generate a library with a task that will deletes todo-item after 7 days, and use command line to run the task.

