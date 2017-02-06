---
title: Live Style Guide Checklist
permalink: "/share/lsg-checklist/"
layout: page
---

<style>
  .post-content ul{
    list-style: none;
  }
  .post-content li:before {
    content: "\2610";
    margin-right:5px;
  }
</style>
- Demos
  - It is easy for a developer to create a standalone demo using app
  - Demos can be accessed via URLs matching file structure
  - Demos can be built to standalone, fully-contained HTML files
- Generator
  - Style guide can be generated from comments and/or markdown inside
    your code base.
  - Demos are on style guide pages inside an iframe
  - Style guide can be generated, hosted on a local server, and
    watched for changes in a single command
- Deploy
  - Style guide is generated to a single static site folder
  - There is a place to host it (GitHub pages if you don't need security)
  - Style guide is automatically built and deployed with code changes
