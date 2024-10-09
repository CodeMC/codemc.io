---
title: Welcome to CodeMC
permalink: /
layout: splash
description: >
  CodeMC is an organization that provides free, public Jenkins CI Services for Open Source projects.<br>
  We are primarily focused on Minecraft-related projects, but also welcome projects of any other kind.<br><br>

  We also offer public Nexus Repositories, allowing you to distribute your code to others with ease.

excerpt: Public CI and Nexus Services for the Open-Source Community.
header:
  overlay_image: /assets/banner.png

getting_started:
  - excerpt: |-
      ### Discord
      
      Our Discord Server is the main place to request being added to our Jenkins and Nexus services.  
      It is also the ideal place for receiving support with our Services, should you have questions.
    btn_label: Join our Discord
    btn_class: btn--light-outline
    url: https://discord.gg/AGcFMu6
  - excerpt: |-
      ### Documentation
      
      Our Documentation is the best place for obtaining information on how to do specific things.  
      Wanna know how to make a Webhook from your Jenkos Job to Discord? Wanna know how to integrate building from Pull requests? Our Docs have you covered!
    btn_label: Visit our Docs
    btn_class: btn--light-outline
    url: https://docs.codemc.io

resources:
  - image_path: ./assets/logos/jenkins.png
    excerpt: |-
      ### Jenkins
      
      Our public Jenkins instance is available for anyone who wants to use it and has successfully applied for it.  
      We strive to provide the best Jenkins experience possible for you.
    btn_label: Visit CI instance
    btn_class: btn--light-outline
    url: https://ci.codemc.io
  - image_path: ./assets/logos/sonatype_nexus.png
    excerpt: |-
      ### Nexus
      
      Our public Nexus instance allows you to publish your resources for others to include in their own project.
    btn_label: Browse our Nexus
    btn_class: btn--light-outline
    url: https://repo.codemc.io
  - image_path: ./assets/logos/github.png
    excerpt: |-
      ### GitHub
      
      Our GitHub Organization contains the source of various open source projects under the CodeMC Umbrella, be it our Discord bot, our Documentation or even this website.
    btn_label: Visit GitHub
    btn_class: btn--light-outline
    url: https://github.com/CodeMC

team:
  - image_path: https://github.com/sgdc3.png
    excerpt: |-
      ### sgdc3 (aka Gabrielle C.)
      
      Administrator
    btn_label: Visit GitHub
    btn_class: btn--light-outline
    url: https://github.com/sgdc3
  - image_path: https://github.com/Andre601.png
    excerpt: |-
      ### Andre601
      
      Administrator  
      Documentation-Manager  
      Bot-Developer
    btn_label: Visit Website
    btn_class: btn--light-outline
    url: https://andre601.ch
  - image_path: https://github.com/gmitch215.png
    excerpt: |-
      ### gmitch215
        
      Moderator  
      API-Developer
    btn_label: Visit Website
    btn_class: btn--light-outline
    url: https://gmitch215.xyz
---
# CodeMC
CodeMC is home of countless open source projects of all kinds. While we started as a free Jenkins and Nexus service aimed at Minecraft-related projects, are we now accepting projects beyond these sections.

## Getting Started
To get started with joining the CodeMC community, you first need to join our Discord Server and apply with an Open-Source project that fits our Project Standards.

{% include feature_row id="getting_started" %}

## Resources
We offer various resources for you to use.

{% include feature_row id="resources" %}

## Meet the Team
CodeMC is managed by a team of individuals with various experiences in different fields.  
Below can you find some of our most important staff members.

{% include feature_row id="team" %}