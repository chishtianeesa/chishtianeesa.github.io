---
title: SaaS Enterprise
order: 1
image: /assets/images/gear_vr.jpg
layout: project_details
list-subtitle: BrowserStack, Oct 2016 to Apr 2017
list-summary: Led an engineering team of 5 to build BrowserStack's enterprise edition.
---

# BrowserStack for Enterprise

## Context

BrowserStack is a cloud based website and mobile app testing product. It started out with a predominantly self-service SaaS model which led to exponential organic growth, particularly among freelance developers. The product also gained popularity among enterprises, but missing features and services prevented adoption at scale. To address this problem, and thus increase retention and revenue per account, my team built BrowserStack’s enterprise edition - _BrowserStack for Enterprise._ In the 7 months since launch -xx-xx- this product as increased the Monthly Recurring Revenue by 7%.


## Customer Research

We ran extensive customers studies in the form of user interviews, surveys, and experiments on customers across software & technology, finance, retail, education, government and more. 30 companies including Twitter, Geico, BBC, Xerox and Tableau participated in the research. The following problems emerged:

![Personas and Problems](/assets/images/saas_personas.png)
{: .negative-margin-top }
{: .negative-margin-bottom }

## Features identified

1. Single sign-on
2. Usage analytics
3. Advanced user management
4. IP whitelisting
5. Advanced Local testing
6. Data-center location

### Single Sign-on
We built SSO integrations with enterprise-grade directory services like Google Apps, LDAP, SAML, Active Directory, and Azure. SSO enables large enterprises to offer a secure authentication experience to its employees, allowing them to log into BrowserStack (and other applicable systems) using a single username and password.

![Single sign-on](/assets/images/saas_sso.png)

### Usage Analytics
An interactive analytics dashboard that allows customers to assess coverage, resource utilisation and testing frequency on BrowserStack. The challenge was to be transparent with customers without triggering cancellations and downgrades.

![Usage analytics](/assets/images/usage.png)

### Advanced User Management
Advanced team management allows enterprises to organize their testing teams and allocate VMs. By creating sub-teams within their account, Enterprises can separate various teams in the organization by both access and parallel test allocation.
Ability to create sub-teams and assign an Administrator to each.
Resources (e.g. VMs for Automate) can be allocated between different teams.
Each sub-team will have its own Automate dashboard-- eliminating noise from others.

### Revocable API Keys
BrowserStack offers a REST API to obtain new key credentials for automate and local testing. This enables organization to revoke access to compromised keys or recycle keys to prevent unauthorized access to testing resources on BrowserStack.
API Keys allow a company to programmatically interact with BrowserStack which helps them automate functionality. This allows people to deeply integrate with BrowserStack and maintain/improve existing workflows.

### IP Whitelisting
In certain large companies, IT departments control access and mitigate risk by restricting access to internal networks. The most common of restriction is IP Address based, meaning that connections from an external resource must come from an expected IP range. BrowserStack IP Whitelisting enables these enterprises to have uninterrupted and seamless access to our testing resources across all products. Now, BrowserStack can offer a set of IP ranges that the customer can easily provide to their IT team for inclusion in the network security policies.
This ensures that a company’s network security policy remains intact. It also helps companies control access which mitigates risk exposure.

### Advanced Local Testing
Enterprises need to funnel all traffic through their network to enforce internal monitoring, logging, and security policies. Advanced local testing allows our customers to resolve any URL on remote VMs via their network.
BrowserStack Advanced Local Testing allows the entire account to funnel traffic through their network as opposed to doing it on an individual basis.
It allows for account-wide enforcement rather than a user by user opt-in. It is a centralized flag that allows companies to control network traffic. It reduces risk by allowing admins to force all users to comply with network security protocols.


## Feature Validation

Before investing majorly in building these features, I split each into a mini experiment to gauge demand and better understand risks. Explained below are these experiments:

### Usage analytics experiment
Before investing a sophisticated dashboard we ran two experiments to:
- Validate metrics we had chosen for the report
- Quantify risk of cancellations and downgrades

We created 30-day reports and sent them via email to 4000 paying groups. We split these groups by team size into two cohorts - Freelancers or single license accounts multi-account licenses. Saw 15% churn in freelancer cohort
and 4.79% churn in > 5

We concluded the results were statistically significant. In a follow up survey (with 1800 participants) 68% found the report very helpful, the remaining wanted more granularity in terms of usage and timeframes. Based on the feedback we finalized the following metrics matrix for the analytics dashboard:

-table-

-dashboard image-

-usage impact-

Net MRR impact was a 6.9% increase in upgrade MRR. Was closed as a success.

### SSO Beta

Validated SSO requirements. SSO was a deal-breaker. ¼ of overall lost deals were lost because of SSO. Launched SSO Beta - where we had one customer for each identity provider. After 4 successful integrations and 2 weeks of close monitoring, the 4 customers were ready to pay to continue using Single sign-on. In the first month after launch, the Sales team was able to close 3 deals, each more than $100k.

### Targeted Sales pitches
Are people actually willing to pay?

## Product plans and pricing

## Packaging
Our key takeaway was that Enterprise software is purchased only after it passes all checks laid down by various departments - Engineering, IT, Legal and Finance. To make the product, we also wanted to make sure the packaging met all requirements from each department. In fact, as will follow in the solution - the features and services were grouped by department to make it easier for each persona to self select and evaluate with ease. We also identified a set of add-ons:

- Data centre location allows an enterprise to specify from which singular data center it runs its tests.
- Unlimited data retention gives enterprises the option to retain their automate logs.
- Priority support is an add-on that comes with senior support resources and SLAs for business critical applications.
- Custom MSAs
- Bespoke Training is an add-on that offers training modules to end-users such as QAs and test engineers to help them be more successful with manual and automation testing.
- TAM is a designated BrowserStack expert who can provide technical guidance and ongoing support to maximize the returns on your BrowserStack investment.

-packaging image-

## Pricing Strategy

We designed Enterprise plans for annual or multi-year terms only and a minimum of 10 users (Live, Automate) and 5 parallel tests (Automate Pro). We followed a Mixed bundling approach as it offered much needed flexibility to Enterprises with very diverse needs. Core features bundled together while professional services sold as optional add-ons.


## Phased Launch

### Phase 1
Soft launch on the Pricing page to gauge demand. 8% of total queries received on Salesforce were for Enterprise, specifically asking for Single sign-on, usage analytics and IP whitelisting.

 -image of pricing page-

### Phase 2

Build a dedicated landing page (www.browserstack.com/enterprise) that talks about the benefits offered by each feature within the Enterprise offering. Internal tools. Sales intelligence tool for sales and renewals to proactively reach out to customers. This was for the customer success team. Metrics:

## Impact
qualified Leads increased by 200%
Win-rate up by 12%
7.8% of the MRR comes from the Enterprise Product.


## Retrospective

Note: Data analyzed is from May-5th-2017 to Sep-19th-2017
⅓  Enterprise opportunities lost

-table-

- Customers only need specific Enterprise features and don't want to pay for features they don't need
- TAM is not being pitched to customers, in the few cases that it was > customers were happy with SE + AE support and no longer felt the need for a TAM
- Data centre location (6) and Priority support (5) are the attractive add-ons. - Customers don't feel add-ons are over-priced, they feel base Enterprise pricing is too high
- For usage analytics, customers want usage by user
- Pricing is a concern for existing users, new users are mostly comfortable with the price-points


## Future Scope

1. Improve conversion, Long way to go. 7.8% of MRR to 25% by 2018. Offer enterprise free trial self-service. Reduce dependence on Sales, make this possible as self service. For that need to get the pricing right. and automate SSO and a whole bunch of stuff. Improve offering.
2. Experiment with pricing to see how customers view bundling and design bundling accordingly.
3. Encouraging outcome-oriented thinking. examples: "testing suite" or "performance suite", instead of individual products/features.
4. Sales enablement
