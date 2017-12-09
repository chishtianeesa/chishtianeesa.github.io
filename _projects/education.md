---
title: Education  
order: 8
image: /assets/images/polygons.png
layout: project_details
list-subtitle: BrowserStack, Jun 2017 to Dec 2017
list-summary:  Internal product that determines product pricing, packaging, payment rules, post transaction scenarios such as refunds, and revenue recognition.
---

# Polygon Crawler

## Gathered fids and polygon geo-data

Polygon data allows for efficient address-based representation of geographical data, e.g. apartments in a locality. Categorization of the polygons would be a major task, but the hierarchical address structure Google uses can be crawled using the fid data. This allows us to build a polygon tree for easy clustering and matching, e.g. nearby locality search

![nearby-locality-search](/assets/images/polygons.png)

## State-aware and distributed

The crawler was state-aware, which allowed for resuming on faults, including arbitrary timeouts from Google servers. The independent query design of the system allowed for multiple instances to be run parallely without overlap. This increased throughput time directly by number of cores.
