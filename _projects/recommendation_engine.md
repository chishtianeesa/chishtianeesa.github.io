---
title: Recommendation Engine  
order: 3
image: /assets/images/reccohand.png
layout: project_details
list-subtitle: Housing.com
list-summary:  Discovery product powered by suggestion algorithms to maximize successful searches.
---

# Recommendation Engine

## Summary

In the period of May to July 2015, 35% of the searches for rental properties run on Housing were dead-end searches. Further, only one third of first time users attempted another search after getting 0 listings in the first attempt. To improve the home-finding experience for users, my team introduced Robin, a recommendations engine built using Python, that prodded users to tweak their search and maximize relevant listings. If there was a home on Housing for you, we wanted to make sure you found it. These recommendations took the form of cards, interspersed with search listings. We also built an internal tool to help product managers deploy cards without engineering effort. Over a period of 4 months, we saw dead-end searches drop by 22%. This was of course, the combined result of more supply, and Robin. We isolated data from areas where supply had not significantly increased and still saw a 17% drop in dead-end searches.

## Context

My team managed Housing.com's discovery experience, and more! Here's a visual summary:

![Context](/assets/images/housing.png)

## Problem
35% of the searches for rental properties run on Housing were dead-end searches.

## Approach
We split searches into narrow, normal and broad searches to further understand behaviour for each search type.

1. Narrow searches (<20 listings): When users applied too many filters, search was too specific or supply was low, this meant fewer listings. Typically users looked at at least 7 listings before shortlisting a property.

2. Normal searches (20 - 100 listings): Users applied key filters (location, budget, BHK type) in areas with sufficient supply. Listings were paginated, with 20 properties on each page. Users would typically go up to the 5th page, but engagement on the first 5 of each page would be the highest. So listing #21 would be 5 times as likely to get viewed compared to listing #15. The most relevant properties always took slots of  1 to 5, 21 to 25 and so on.

3. Broad searches (>100 listings): Users applied no filters or ran city wide searches or supply was too high, thus fetching an overwhelming flood of listings which resulted in poor conversion and users abandoning the search altogether.


## Hypothesis
Guiding users through the search/discovery process with contextual recommendations would reduce dead-end/broad searches and improve conversion over time.

## Solution
Keep the user in the search journey, identify non-negotiables and help navigate through those.
- Split filters into hard (BHK, budget, furnished) and soft filters (amenities etc)
- Split cards into static (RA, set Alerts, flatmates)  and dynamic (user specific)
- Create an internal dashboard for product managers to create their own cards as required and deploy without engineering involvement.

### Card families
1. Narrow search
- Single filter
Relax filter (Which filter is restricting search?)
Remove filter (which soft filter is making the search narrow?)
- Multi filter
Relax filter
Remove filter (which soft filter is making the search narrow?)
Single locality
change polygon
- Multi locality
change polygon
2. Broad search
Single filter
Add filter
Single locality
change polygon
Multi locality
change polygon
3. Statics cards
Set Alerts
Flatmates
Rental agreements
See Agents

### Filters

Average filter usage in a 7 day period:
