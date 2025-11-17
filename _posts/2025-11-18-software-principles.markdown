---
layout: post
title:  "Why another useless blog?"
date:   2025-11-18 01:24:12 +0530
categories: Personal 
---

To this I answer why not? Why not share my opinion on things which doesnt matter in the long run, and we will just figth tooth and nail to prove our point. Which again is pointless. In any case, If I need to taunt my expertise on matter, this will be my bible. Put all my brain dump here so I can be of clean.

And, to the other point. I need to have a place to store my points related to the work/project/research I am doing. I am too lazy to put it in a book, and even lazier to store it safely and revise. So, I will use this to store and access my stuff. Pretty neat.

Lets start with my opinion on how to write a good software. 
In my opinion, any piece of software should solve one problem, and only one problem and keep it working for atleast 2 years. There is no point in coming up with solution which wont even last in 2 months. So considering this, I came up with a plan.

### Steps for building good software 


1. Stability
    
    Why do we need stability? because we are not primates. We need accountability, and the things we are building need to run for a long time. If not, why are we doing this band-aid work. This we can only achieve by choosing the right framework, and clear definition of expectation. We dont need software that doesnt work, nor piece of product that is expected to be working in _future_

    To put in clear words : 
    - We need the software to run atleast 5-10 years without any issue. To do that, we need to chose the right framework which has great support for long term usage, and has minimal changes throughout. 
    - We also need to include the security aspect here. For the system to run for long time, we need to use as little external libraries as possible. This safeguards us from security threats, and actually learn what is going on behind the scenes. 

2. Flexible 
    
    Iterate fast and quick. The only thing that is different from good and bad software is the amount of testing and handling failure scenarios. If we are able to add any piece of code, with proper testing and future proof logic then the good outcome is inevitable. 

    - Absoulte minimal effort is required to add any new feature/page/element to the existing system
    - We need to be able to run the software in one machine. Software should accomate any and all hardware by default (not a fan of monolith architectures here). If we need multiple machines to test anything, might as well throw it in another (dust)bin.

3. Robust 
  
   "Anything that can go wrong will go wrong" . The system should be recover itself from any failure. The NASA system have a robust failure strategies in case of emergencies. Have similar standards when handling or coming up with an algorithm. All systems will break, It is a matter of when not if.
    
   - *ASSUME FAILURE SCENARIOS EVERYWHERE*. Consider the user as 5 year old, that have access to any/all files in system. 
   - Good engineering lies in simplifying. Rewrite the system in as less lines as possible. This ensures code is efficient, scalable, and mainly readable. 


> It takes atleast 3 attempts to understand anything. Software is the no different. 
