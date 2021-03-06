---
title: "Europython 2019 Talk - Rewriting the Django autoreloader"
date: 2019-09-22T20:38:42+01:00
tags: ["django"]
slug: europython-2019-talk-writing-a-python-autoreloader
---

Over two years ago I set out to try and improve Django's autoreloader implementation. My 
[PR was merged](https://github.com/django/django/pull/8819/) and the feature released in Django 2.2, and I thought I 
should at least mention it on my blog.

The role of an autoreloader is conceptually pretty simple: When a developer changes a file your software should detect 
this and make those changes visible to the developer. Autoreloaders are pretty ubiquitious - most development tools and 
frameworks ship with one and for the most part they give a great speed boost while you are working. 

A good autoreloader is also surprisingly hard to implement and suffers from a fairly unique set of problems. The 
implementation can differ signficantly between languages - some languages make auto-reloading easier to implement and 
some, like Python, make it harder. 

I was waiting for my EuroPython talk on the subject to be uploaded to YouTube before I wrote anything about this.
And now that it's up I can be lazy and just embed it below rather than writing a whole post on the subject!

{{< youtube id="IghyoR6ld60" >}}
