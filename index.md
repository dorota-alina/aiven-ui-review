---
title: "My impressions on the Create Service screen"
menuTitle: "Create Service screen"
description: "Aiven is a SaaS data platform that offers a suite of managed services to build data pipelines in the
cloud of your choice. This is the “Create Service” screen in our user interface used when our user
wants to create a new managed service on Aiven. What are your first impressions of the UX
writing on this page? How would you go about improving it?"
author: Dorota Wójcik
date: 2022-06-20
---

Here are my thoughts on the Aiven Console UI:

## First impressions

* **+** Joyful, luminous, transparent, well-spaced, readable, comprehensive - space almost fully used for the actually relevant content
* **-** Requires scrolling *deep* down (which deteriorates the visibility and availability of certain relevant config options)

## Coloring

* Theme color (pinkish red?) a bit too flashy, alarming in a way
* Besides the theme color and the logos, the rest seems almost all white - I understand that this is an intentional minimalism but more and more product sites use such an approach nowadays - perhaps it's time to think of something else?
* How about adding two buttons: Turn on the light, Turn off the light (for switching between the light and dark themes)?

## Layout

* When it comes to the central pane of the homepage, instead of one long frame, I would split the configuration steps into separate tabs/ views available from the top bar.
* **+ Create service** button I'd make available in the final view (tab) only, when we can be sure that the user had a chance to see all relevant config options (to prevent the user from selecting this button right after setting up point/ step 1).
* I'd think of extending the left sidebar - there is still plenty of space to use - what else could be relevant and useful from the user's perspective? (money-related stuff excluded :D).

## Availability

* You use the full potential of the page: left sidebar, central pane, right-side, which is great.
* Financial info is easily available, even too visible: **Billing** menu item in the sidebar, credits data in the same sidebar, and a price in the detailed service view on the right - seems a bit too much at once. I'd get rid of all $ from the sidebar at least - let's keep it functional/ technical and about operating a product actually. For me, the best place for this financial data would be **User profile** in the top right corner. First, I'd rename it into **Profile info** and, next, inside I'd add another tab/ view **Billing** next to **Payment options**.
* I'd remove the red blinking triangle next to **Billing** in the sidebar in any case - if someone looks for such stuff, they would find it - no need to draw attention to this one.

## Tooltips

* I'd remove the intro tooltips (walking you through the first steps when creating a service for the first time) - they don't help much (is this help needed at all at this point?) and I believe reorganizing the page into separate tabs/ view would make much more good for user's experience.
* I'd add tooltips for all the services (available upon hovering over specific services) providing short info on what a particular database is mostly recommended for and providing links to its use cases (if any).
* I'd add tooltips for SCPs (available upon hovering) informing why I would select a particular SCP and how it differs from the other ones.
* I'd extend tooltips for Additional Disk Space values (available upon hovering). A the moment, they include the number of GBs only. I'd add short examples for particular values illustrating what a specific additional disk space would allow you to do.

## Miscalenous

* Icon for **Support** (top right corner) could be something more support-associated, e.g. a question mark.
* **+ Create service** button and the chatbot button overlap and are similar colors, which makes the chatbot less visible.
* Is the disclaimer at the bottom really required?
* It'd be good to set some standards for the capitalization of text in the UI. I also have a few editorial remarks/ linguistic improvements to the same.
