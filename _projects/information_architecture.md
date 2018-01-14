---
title: Information Architecture
order: 2
image: /assets/images/iahand.png
layout: project_details
list-subtitle: BrowserStack
list-summary:  Architecture overhaul to accommodate future growth, while balancing user experience and SEO.
---

# Information Architecture

## Context
BrowserStack was originally designed for one product, Live, a manual cross-browser testing product. As BrowserStack grew, it added multiple products but the architecture could not support these while keeping the navigation intact. Multiple adhoc additions made the navigation complex and unweildy. We reached a point where there were multiple problems that impacted new product visibility. Live remained the homepage despite 4 other product additions, even in mobile app testing. This also created a positioning problem where users associated browserstack with only cross-browser testing.

![Bstack Flashback](/assets/images/bs flashback.png)

![current state](/assets/images/current state 01.png)

## Brief

### What was the problem?

1. Users could not find contextual pages in their evaluation/use of the products
- An analysis of 435 queries (Oct - Nov) revealed 43 requested assistance in finding the right product. 
- On an average (Sept - Nov) ~29% of support queries are product questions (eg queuing, device coverage, capability configuration etc)
2. The architecture did not support multiple products
 - Visibility was heavily skewed towards Live (the first product launched!)
 - No real estate to surface product specific resources
 - Enterprise hidden under more 

Current state:

![current state](/assets/images/current state.png)

![current state](/assets/images/current state 2.png)

![current state](/assets/images/current state 3.png)


## Solution

### Solution Guidelines
- Scalability
- Ability to switch between marketing pages and product dasboards
- Feature discovery post login
- Cross-product discovery
- Adhere to standard SaaS product behaviors.

### Key Decisions


### Whiteboarding

![sitemap on whiteboard](/assets/images/IAwhiteboarding.jpg)

![sitemap on whiteboard](/assets/images/IAwhiteboarding2.jpg)

### Page categorisation

### Clustering and Labelling rules

![nearby-locality-search](/assets/images/secondary nav 2.png)
![nearby-locality-search](/assets/images/product dasboard.png)



### Wireframing
![Homepage](/assets/images/1-Global.jpg)

![Product Dropdown](/assets/images/2-Product dropdown.jpg)

![Product Dropdown](/assets/images/3-Developers dropdown.jpg)

![Product Dropdown](/assets/images/4-Global post login.jpg)

![Product Dropdown](/assets/images/5-Secondary nav - automate.jpg)

![Product Dropdown](/assets/images/6-Logged in product dashboard.jpg)

![Product Dropdown](/assets/images/7-Logged in documentation dropdown.jpg)

![Product Dropdown](/assets/images/8-Logged in products dropdown.jpg)

![Product Dropdown](/assets/images/10-Logged in first time product toggle.jpg)

![Product Dropdown](/assets/images/11-Logged in app live dashboard.jpg)




## Final Solution Walk through

<iframe width="854" height="480"
src="https://www.youtube.com/embed/aFt0T90YuH8?vq=hd720&rel=0&autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
