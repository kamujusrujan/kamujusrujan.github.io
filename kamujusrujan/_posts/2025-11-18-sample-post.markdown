---
layout: post
title:  "Why another blog?"
date:   2025-11-17 00:18:15 +0530
categories: personal
---
This is purely for fun website. I am too lazy to note down my points in a note taking app. Hence, I thought it'd better if I do it this way. 
I wont have to remember the passwords, or install any app.

### Steps for building good software 

We need to come up with the philosophy for software engineering. 

1. Stability 
    - We need the software to run atleast 5-10 years without any issue. To do that, we need to chose the right framework which has great support for long term usage, and has minimal changes throughout. 
    - We also need to include the security aspect here. For the system to run for 10 years, we need to use as little external libraries as possible. This safeguards us from security threats, and also makes sure what is going in the system
2. Flexible 
    - Absoulte minimal effort is required to add any new feature/page/element to the existing system
    - The friction between the development and the deployment needs to be as minimal as possible. 
        - **Bonus** : If we dont need any CICD action for deployment.
    - We need to be able to run the system in one instance of any machine. This check makes sure the system is independent of the infrastructure and also reduces the complexity between the inter dependent services. 
        - for example, we need to make sure the system works fine without the celery service, database service, ARM architecture dependent services etc,. 
3. Robust 
   - "Anything that can go wrong will go wrong" . The system should be recover itself from any failure. The downtime of more than a [PARTICULAR THRESHOLD] 
   - *ASSUME FAILURE SCENARIOS EVERYWHERE*. Consider the user as 5 year old, that have access to any/all files in system. 
   - Good engineering lies in simplifying. Rewrite the system in as many less lines as possible. This ensures code is efficient, scalable, and mainly readable. 

> It takes atleast 3 attempts to understand anything. Software is the no different. 