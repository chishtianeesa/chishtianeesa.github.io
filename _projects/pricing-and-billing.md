---
title: Pricing & Billing
order: 4
image: /assets/images/pshand.png
layout: project_details
list-subtitle: BrowserStack
list-summary:  Product pricing, packaging, payment rules, subscription management and reporting.
---

# Pricing and Billing systems

## Project #1    :   Revising the homegrown billing system

BrowserStack's business can be split into online vs sales-driven (or inside Sales). I split the whole system into seven main components, and mapped ideal features to each component:  

![pricing-billing-overview](/assets/images/billing-overview.png)

![pricing-billing-overview-2](/assets/images/billing-overview-2.png)

## Problems

![pricing-billing-problems](/assets/images/pricing-billing-problems.png)

## Project #2    :   The Big Pricing Migration

### What was the problem?
We were maintaining three pricing versions to support 22,000 legacy customers. As we experimented with pricing, and launched plans and products, maintenance got increasingly difficult, feature releases slowed down, and new product adoption suffered because new products/plans were visible only to customers on the latest pricing version - so, legacy customers missed out!

### What were the challenges?
- Different value metrics
- Different billing cycles
- a la carte versus bundled/combined plans
- Active, expiring, expired
- Feature access activated by random flags

### What were the risks?
- iMRR loss
- Churn

### What were the success metrics?

- Support tickets
- Customer churn (plan cancellations)
- iMRR loss (incremental monthly recurring revenue). Projected iMRR retention: 65%
- New product adoption (% groups that purchased any of the new products)


### How did we solve it?

The solution is to force migrate all 11,398 V1 groups to equivalent V3 plans without any price increase. The migration will also apply to expired groups. The migration will be handled in-product for all self-service groups and handled via personal involvement for renewal Ops.

We split the migration into four phases:
- V2 to V3 Migration (Online business)
- V1 to V3 migration (Online business)
- 2Checkout to Stripe Migration
- V1, V2 to V3 Migration (Renewals)

Mapping rules for unlimited licenses and multi-products
/add/

### The Communication Plan

Touchpoints
- Subscriptions page
- Plan details in account summary
- First invoice post migration
- Opt-in email
- Cancellation Modal

Modal triggered on subscriptions page:

One previous plan case

![one-previous-plan-modal](/assets/images/one previous plan.jpg)

Two previous plans case

![two-previous-plan-modal](/assets/images/two previous plan.jpg)

Three previous plans case

![three-previous-plan-modal](/assets/images/three previous plan.jpg)


## Project #3    :   Single subscription, to Multiple subscriptions

- Pricing page and checkout experience
- Backend changes
- Salesforce changes

 Why V1 to combined?

- Multiple product confusion
- Low revenue per customer
- Fewer licenses per customer

Why V2 to V3?

Overall increase in revenue due to increase in revenue of ML : Increased ASP for ML plans with more or less same # of deals sold


## Project #4    :   Automate Mobile Plans and Pricing

Introduce browser automate on real mobile devices

Scope:

Real mobile in Browser Automate is a feature within an existing product (browser testing).


Target:

Real mobile in Automate was decided to be a new premium plan.
It will not only serve more advanced and picky users, but also define the "north star" - a plan or a feature-set that everyone should look up to and desire to have.


Key changes:

We are creating a new plan:  Real Mobile in Browser Automate Mobile (real mobile devices in browser automate testing)
We are dropping Automate plan.

-evaluation matrix-
Even though we see option 3 as more attractive naming version, it would  cause potentially high risk of mis-communication issues with existing clients. For example, existing Automate Pro clients would start seeing themselves as Automate account holders and not Pro anymore (even though it's just the naming). The decision is clarified in the main problem solving table (above).
