# AR-VRHealth

> **AR/VR For Health (ICS 496 Capstone – Fall 2025)**  
> Authors: Ricki Ace G. Gaborno, Austin Jake C. Villanueva, Justine A. Afaga  
> Sponsor: Dr. Katy Tarrit, Weihao Xin, Samantha Reed

## Table of Contents
- [Overview](#overview)
  - [The Solution](#the-solution)
- [Preview](#preview)
- [User Guide](#user-guide)
- [Community Feedback](#community-feedback)
- [Development History](#development-history--progress)
  - [Milestone 1](#milestone-1)
  - [Milestone 2](#milestone-2)
- [Deployment](#deployment)
- [Enhancements In The Future](#enhancements-in-the-future)
- [Technology Stack](#technology-stack)
- [Acknowledgements](#acknowledgements)
- [Team](#team)

---

## Overview

Alzheimer’s Disease (AD) and Alzheimer’s Disease–Related Dementia (AD/ADRD) affect millions of individuals worldwide and can severely impact **memory, attention, and cognitive function**. Traditional clinical assessments often **lack immersion**, are difficult to standardize, and provide limited insight into how patients interact with **real-world environments**.

This project extends an ongoing effort to build an **AR/VR healthcare environment** by integrating **Electroencephalography (EEG)** with immersive virtual reality tasks. Our goal is to develop an AR/VR software platform that provides **controlled, repeatable, and interactive** cognitive experiences for individuals with AD/ADRD.

By combining **VR stimuli** with **EEG measurements**, this system aims to help researchers better evaluate cognitive processes—supporting more accurate assessments and **earlier detection** of cognitive decline.

### The Solution
**AR-VRHealth** provides:
- **Immersive VR environments** (Apartment, Park, Beach) designed to support cognitive assessment and user engagement.
- An **integrated N-Back cognitive test** (1-back, 2-back, 3-back) using beach-themed objects to create task-specific visual stimuli.
- **Improved scene performance** by fixing inherited bugs and optimizing interactions, visuals, and loading times.
- **Environment-specific audio design** to enhance realism and immersion across all scenes.

---

## Preview

**Poster (latest draft):**

<img width="900px" class="rounded shadow-sm" src="../images/poster_draft.jpg" alt="AR/VR For Health poster">

**In-app screenshots (replace with updated images):**

<img width="900px" class="rounded shadow-sm mb-3" src="../images/preview/scene-park.png" alt="Preview: Park scene">
<img width="900px" class="rounded shadow-sm mb-3" src="../images/preview/scene-apartment.png" alt="Preview: Apartment scene">
<img width="900px" class="rounded shadow-sm mb-3" src="../images/preview/scene-beach-nback.png" alt="Preview: Beach N-Back scene">

---

## User Guide

Keep it classic + easy (update details to match your repo/workflow):

1. **Get the project**
   - Clone/download the repository.
2. **Open in Unity**
   - Open the project folder in Unity (use the same Unity version your team is standardizing on).
3. **Run in Editor**
   - Press Play to test scenes and UI.
4. **Test on Meta Quest**
   - Connect the headset and run a build to validate VR performance, interactions, and UI usability.
5. **Try the N-Back Task**
   - Navigate to the Beach environment and run **1-back / 2-back / 3-back**.

---

## Community Feedback (shall we still add this?)

Things to add for this:
- Who tested (classmates, sponsor team, friends—no personal info needed)
- What they liked (immersion, clarity, fun, realism)
- What they struggled with (UI clarity, instructions, interaction bugs)
- What you changed as a result (1–3 bullets)

*placeholder bullet:*
- “Testers wanted clearer task instructions before starting the N-Back rounds, so we added an on-screen briefing panel.”

---

## Development History / Progress

[View Our Progress Here](https://github.com/orgs/AR-VRHealth/projects/1/views/1)

### How we worked (Methodology)
- **Weekly meetings, live demos, and feedback cycles:** We met weekly to demo VR gameplay, playtest updates, and gather sponsor feedback. We documented flaws/bugs and discussed refinements and next steps to keep development aligned with project goals.
- **Development workflow (Unity + GitHub):** We redesigned/refined scenes (Apartment, Park, Beach) and fixed performance issues in Unity. We used GitHub to track tasks and document progress.
- **Cognitive task implementation:** We expanded the Beach scene into a full environment and developed **1-back / 2-back / 3-back** tests using beach-themed objects as stimuli, continuously testing on **Meta Quest** for smooth interaction and UI usability.

---

### Milestone 1
**Focus (example):** Project setup + inherited scene cleanup (Office/Park) + baseline performance.

The issues that were completed for this include:
- Something..

Screenshots of our progress so far:

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m1-01.png" alt="Milestone 1 screenshot 1">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m1-02.png" alt="Milestone 1 screenshot 2">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m1-03.png" alt="Milestone 1 screenshot 3">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m1-04.png" alt="Milestone 1 screenshot 4">

<div style="clear: both;"></div>

---

### Milestone 2
**Focus (example):** Beach environment expansion + N-Back implementation + XR interaction polishing.

The issues that were completed for this include:
- completed issues 

Screenshots of our progress so far:

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m2-01.png" alt="Milestone 2 screenshot 1">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m2-02.png" alt="Milestone 2 screenshot 2">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m2-03.png" alt="Milestone 2 screenshot 3">

This is a screenshot  
<img width="600px" class="rounded float-start pe-4" src="../images/progress/m2-04.png" alt="Milestone 2 screenshot 4">

<div style="clear: both;"></div>

---

## Deployment

Check out a quick demo here: 

- Demo video: https://(link-here)

---

## Enhancements In The Future

Possible improvements for the future:
- More cognitive tasks beyond N-Back (additional repeatable assessment mini-games)
- Better onboarding/tutorial UI for first-time users
- More environments / more realistic interaction objects
---

## Technology Stack
- Unity
- GitHub (issues/projects/pages)
- SketchUp
- C#
- Meta Quest

---

## Challenges and Learning

**Challenges**
- Setting up the project environment from the previous group, including assigning roles
- Troubleshooting Unity project imports (large file sizes + inconsistent folder structures)
- Implementing the N-Back test on the Beach scene while integrating new assets and maintaining stable VR performance
- Fixing major inherited bugs in the former Office and Park scenes (debugging UI issues, interaction problems, performance slowdowns)

**Learnings**
- Improved collaboration and task division across weekly development goals
- Hands-on experience using VR headsets in Unity, including configuring XR settings, testing interactions, and optimizing performance for Meta Quest
- Practical debugging strategies for large inherited Unity projects, improving scene performance, and managing VR-specific bugs

---

## Acknowledgements

We would like to thank **Dr. Katy Tarrit** for her guidance, feedback, and support throughout the development of this project. We also thank her PhD students, **Weihao Xin** and **Samantha Reed**, for meeting with us weekly, play-testing our VR builds, and providing valuable insights that helped us refine our environments, fix performance issues, and improve overall usability.

---

## Team

**AR-VRHealth** is proudly designed, implemented, and maintained by:
- Ricki Ace G. Gaborno — rg42@hawaii.edu | GitHub: https://github.com/Rickiace
- Austin Jake C. Villanueva — ajcv@hawaii.edu | GitHub: https://github.com/AustinV28
- Justine A. Afaga — afagajus@hawaii.edu | GitHub: https://github.com/Jafaga
