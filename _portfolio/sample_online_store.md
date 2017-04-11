---
layout: post
title: Sample Online Store
thumbnail-path: "https://raw.githubusercontent.com/yenchieh86/yen-profile/master/img/online_store.png"
short-description: Build an online store.

---

{:.center}
![](https://raw.githubusercontent.com/yenchieh86/yen-profile/master/img/online_store.png)

## Explanation

An online store that allow admin to sell products.

Has infinite scrolling, admin can upload image, shopping cart, shipping and payment system

Use friendly id to show user name in URL instead of user id.

Has search engine allow user to seach product by type keyword in search form.

## Problem

It takes too long to load home page, and product list. 

## Solution

Use Kaminari gem and jQuery to create infinite scrolling system, and also use Ajax, allow browser no need to load every thing at once.
Browser only will load a part of data at first, then will load rest of data after user scroll down the page or click a button.