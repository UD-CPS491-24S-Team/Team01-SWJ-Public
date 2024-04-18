---
name: The Society of Women Journalists
tools: [Django, Python, PostgreSQL]
image: /Team01-SWJ-Public/images/swj.png
description: Django web application for sharing information on the Society of Women Journalists.
---

# The Society of Women Journalists Website

## Table of Contents

1. [Overview](#overview)
2. [Month 1](#month-1)
3. [Month 2](#month-2)
3. [Month 3](#month-3)

## Overview

The Society of Women Writers and Journalists is a British learned society for professional women writers founded in 1894. 

Our sponsor, Dr. Laura Vorachek is an English Professor at the University of Dayton. She has been researched and collected information on this society from primary materials, and desires a web application to store this data. Our task is to continue development on the existing web application, improve aesthetics, and implement additional features. 

This is project has been ongoing for Capstone groups before us, and our goal is to redesign and complete the application. 

## The Project's Development Timeline

<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/Timeline.png" alt="SWJ Timeline" width="80%">
    </div>
</div>

As is described on the current SWJ website, the site is a research database of membership in the Society of Women Journalists between 1894 and 1914. It is a searchable, free online resource that currently offers the ability to:

- Search by member name & penname
- Search by leadership position

This project was created in order to:

- Recover the identities of women working as journalists at the turn of the twentieth century
- Map networks of social and professional support among female journalists
- Recover a more detailed history of the early years of the SWJ
- Centralize and make more widely accessible SWJ membership lists.

## Month 1

_1/24/2024 to 2/14/2024_

Our semester is broken up into three milestones, or months, where we follow an agile methodology for continuous development.

In Month 1, we focused on getting acquainted with the application, Django, and completing simpler tasks. We began this month with a "Django bootcamp" where each team member created a simple blog application. This allowed us to get familiar with Django prior to actual development. 

The SWJ site is a Django application, which is structured as follows:

<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/django-structure.png" alt="SWJ Structure" width="80%">
    </div>
</div>

<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/django-diagram.png" alt="SWJ Diagram" width="80%">
    </div>
</div>

The following tasks were implemented:

- Added country/county fields to the Member model on the admin site
- Improved member search results
- Added a nested model to the Member model to allow for photos
- Fixed the alphabetical search bar
- Fixed the image disappearing issue with base64
- Added logo to pages (favicon)
- Added delete button on admin site for ranges and orgs
- Removed References in navigation bar
- Improved printing / added print button
- Created website design templates
- Added Password Reset on Admin side
- Penname linking

<p class="text-center">
{% include elements/button.html link="https://docs.google.com/presentation/d/1EGnuGD51gIvJnRHyoBwTa1VtlUYzV6q5NqsDf-wu8-o/edit?usp=sharing" text="Month 1 Presentation" %}
</p>

## Month 2

_2/14/2024 to 3/13/2024_

In Month 2, having become well acquainted with Django, we began development on the more advanced, longer term features. 

These features included:

- Begin Advanced Search
- Finalize Aesthetics Plan
- Add Honorary Members <sup>1</sup>
- Implement data analytics <sup>2</sup>
- Secure admin side
- Import/Export

[1] Added a new page listing honorary members.
<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/honorary.png" alt="SWJ Honorary Members" width="80%">
    </div>
</div>

<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/honorary-page.png" alt="SWJ Honorary Members" width="80%">
    </div>
</div>

[2] Connected the SWJ site to Google Analytics.
<div class="container">
    <div class="row">
        <img src="/Team01-SWJ-Public/images/analytics.png" alt="SWJ Analytics" width="80%">
    </div>
</div>

<p class="text-center">
{% include elements/button.html link="https://docs.google.com/presentation/d/1cZbe8YgmGbh2qDJjJX4EqZuG9xk95C0z7x1Dtb8VtC8/edit?usp=sharing" text="Month 2 Presentation" %}
</p>

## Month 3

_3/13/2024 to 4/10/2024_

In Month 3, we finished up the tasks we began in Month 2 and completely changed the aesthetics of the site to match the design plan we created with our client. Additionally, we fixed the site's buggy search algorithm. 

Our tasks included:
- Finish Aesthetics
- Finish Data analytics
- Add advanced search functionality

Demo video:

<video width="320" height="240" controls>
  <source src="/Team01-SWJ-Public/images/swj-demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<p class="text-center">
{% include elements/button.html link="https://docs.google.com/presentation/d/1wy-521T7Lvqmq4tuTkfRE6-Ttu-G0Xh_dKNM562meLQ/edit?usp=sharing" text="Final Presentation" %}
</p>

<p class="text-center">
{% include elements/button.html link="https://www.swj1894.org/" text="Visit the SWJ Site" %}
</p>
