---
author: "Me"
title: "Setting up a Web Site with Hugo and Blonde"
image: "img/hugo-logo.png"
draft: false
date: 2025-09-14
description: "Setting up a Web Site with Hugo and Blonde"
tags: ["content publishing"]
archives: ["2025/09"]
---

Goal: Host a static page website (no server-side processing) on Cloudflare pages. The free trial does not allow any server-side processing, only static pages.

Solution Components:
1) Hugo
Hugo is open-source static site generator (SSG) written in Go (Golang). Content is written in plain text (usually in Markdown).
Markdown is a lightweight markup language used to format text using a plain-text editor. It’s designed to be easy to read and write, and it can be converted into HTML for use on websites.

2) Blonde
Blonde is a theme for Hugo that uses Tailwind CSS. Tailwind CSS is a utility-first CSS framework that helps you build custom designs quickly by using predefined classes directly in your HTML. 

3) Netlify Headless CMS
Netlify CMS is an open-source content management system designed to work seamlessly with static site generators like Hugo, allowing to add content directly in the Netlify CMS UI, which will then be committed to Hugo to re-build the site based on the updated files.

