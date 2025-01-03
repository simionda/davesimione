---
title: "Getting Started"
date: 2025-01-03T16:43:58+05:30
draft: false
author: "Dave Simione"
tags:
  - Hello World
  - Technology
  - Writing
image: /images/post.jpg
description: "A start to a new year and finally putting words on paper"
toc: 
---
Well, I'm finally doing it.  Starting a blog.  I've wanted to do it for years now, and never have.  What changed?  For one, it's a new year - 2025.  For two, at the end of 2024, I saw a YouTube video from Network Chuck (TODO - link to video) about how to do this.  And three, the past year has been a journey of mental health for me, and my therapist and my newfound guide - Stoicism - both encourage writing and journaling.  With all of those thing, how could I say no?

## Technology
I'll dive into the non-technology in another post, but for now, I wanted to talk about the simplicity of the technology setup.  The ease of this solution is really what is helping me get started - the hurdles to overcoming doing nothing are almost zero.

### Base System - Hugo
I'm using Hugo (TODO, add link to Hugo) as my blogging engine.  Not just that, but for running my whole personal site.  It will be able to do all kinds of things as I add onto it - but I'm starting small and building slowly.

Hugo is extremely simple to setup.  A quick install using your favorite package manager (brew on Mac or choco on Windows for me) and viola, you're ready to go.  There's no database or anything - it is a static site generator.  All of your content lives in markdown files and templates, and Hugo preprocesses it into the actual site that then gets published to the webserver.  To keep things safe and secure, you store everything in git (your choice of provider).  That's all there is to it!

### Theme - Hugo Profile
I selected Hugo Profile as my theme.  It was last committed in 2021 but it's pretty good as is - no glaring bugs and does what I want it to do as a personal website and blog.  It has lots of features I'm not taking advantage of, and the way it is built is easy to read and follow so I know I can extend it if/when I'm ready.

### Hosting - Netlify
I chose this from the Hugo Profile theme, seeing that there were automatic deploy instructions.  I'm still getting used to this but so far, it is very simple and above all, FREE.  I was originally going to use Azure Static Websites for hosting, which I'm much more comfortable with.  If I run into trouble, that will be my backup.