---
title: Posts
description: Moore Threads Engineering Documentation
draft: false
updatesBanner: "Welcome NooMTer Ziyang!"
landing:
  height: 300
  image: home/logo.png
  title:
    - EngDoc
  text:
    - Moore Threads' internal Engineering Documentation site, version controlled by Git.
  titleColor:
  textColor:
  spaceBetweenTitleText: 25
  buttons:
    - link: docs
      text: Confluence Wiki
      color: primary
  # backgroundImage:
  #   src: logo-800x246.png
  #   height: 600
footer:
  sections:
    - title: General
      links:
        - title: Confluence
          link: https://confluence.mthreads.com/
        - title: Jira
          link: https://jira.mthreads.com
        - title: MT-Learning
          link: https://mthreads.sharepoint.cn/sites/MT-Learning
    - title: Quick Links
      links:
        - title: Showcase
          link: edu/doc/show
        - title: Edit Guide
          link: edu/doc/guide
        - title: Programming Language @MT
          link: edu/lang
        - title: MT Developer
          link: design/cloud/infra/developer
    - title: News
      links:
        - title: Blog
          link: tags/diagram
  contents:
    align: left
    applySinglePageCss: false
    markdown:
      |
      ## MooreThreads Dev+Infra
      Copyright © 2021. All rights reserved.

sections:
  - bgcolor:
    type: card
    header:
      title: Why EngDoc
      hlcolor: '#283593'
      color: grey
      fontSize: 32
      width: 220
    cards:
      - subtitle: Keep Up to date
        subtitlePosition: center
        description: "Keep documentation up to date with source code. It is highly recommended to update this doc with the final stroke of your project. And don't forget to peer review. Docs are just as important as code."
        image: images/section/keyboard.png
        color: grey
        button: 
          name: Docs
          link: eng/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
      - subtitle: Engineer training
        subtitlePosition: center
        description: "Just join Moore Threads? Start from here. Browse projects, learn tools, follow best practices...\n Our next step is to have engDoc per team, but we have to solve K8s hosting and short_url first."
        image: images/section/processor.png
        color: grey
        button: 
          name: Best Practices
          link: edu/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
      - subtitle: Proud of your works
        subtitlePosition: center
        description: "This is also an internal Medium, spread your knowledge, be proud of your legendary accomplishment last week. Show off your skills and start blogging!"
        image: images/section/root-server.png
        color: grey
        button: 
          name: Blog
          link: blog/
          size: large
          target: _blank
          color: 'white'
          bgcolor: '#283593'
  - bgcolor: DarkSlateBlue
    type: normal
    description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce id eleifend erat. Integer eget mattis augue. Suspendisse semper laoreet tortor sed convallis. Nulla ac euismod lorem"
    header:
      title: Build with Hugo + Mermaid
      hlcolor: DarkKhaki
      color: "#fff"
      fontSize: 32
      width: 500
    body:
      subtitle: Extensible and customizable.
      subtitlePosition: left
      description: "Start contribution to EngDoc by learning [hugo](https://gohugo.io) and Diagram by learning [Mermaid](https://mermaid-js.github.io).\n Yuanfeng is a big fan of them, he draws one mermaid per day!"
      color: white
      image: home/hugo-logo.png
      imagePosition: left
---
