---
templateKey: blog-post
title: Outside-In API Design Approach
date: 2019-03-19T17:59:04.439Z
description: API Design using an outside-in approach. Related to API domain modelling.
tags:
  - API Design
  - API
---
Outside-in is a consumer oriented approach—versus a systems oriented, inside-out approach. 

Approach outside-in from the perspective of the consumer (or stakeholder):

- Customers: ultimate consumers of the service a company provides. A service or API ultimately has to satisfy the customer.

- Developers: work with the APIs, the systems that make a company run. Developers provide or implement the capabilities to the customer. An API that is clear, concise and complete (or flexible enough to change) will enable developers to provide better value to the customer.

- Partners:  people and organisations that collaborate with your organisation to improve or enhance value to the customer (and perhaps the developer). The improvement could be as simple as not having to reinvent the wheel, thus allowing your organisation to concentrate on their core business. 

Design the API to be clear, concise and approachable for the consumers. To ensure the API is understood and meets expectations you'll have to have a conversation—ongoing conversations—with all the stakeholders. Or, at least with someone that is representing those stakeholders. There may be situations where complexity cannot be entirely avoided. Some things are just complex. But, you can still provide clarity, and approachability.

Think of your API as a product. If you have a product that no one knows how to use, or doesn't meet expectations, then your product won't get used. At a minimum you'll spend a lot of extra time and money on supporting the product.

An “outside-in” approach fundamentally flips the API design perspective from a systems-centric, “inside-out” view that starts with what systems do now, to a holistic, “outside-in” view that focuses on fulfilling customer, partner and developer needs through the products and services of your organization.

Flexible design, not over-designed APIs and services. The APIs are built with extensibility in mind. This allows for unforeseen direction.

Bounded context. Provide a service that is bound by the domain, or the specific business offering. The API does not try to take into account all meanings, all aspects of the business, it sticks to its own subject matter.  Any meaning, any service or offering is tied to the specific area of the business. This allows the domain owner to stick to what it knows best. It also means that the domain owner is responsible for everything in is domain. This ties into the notion of product ownership. There will be messages, services, data that are outside of the domain that are relied upon. In that case the domain will be a customer/developer/partner of the outside service. And, should be treated as such.

API first design. The contract is built with an understanding of what the system will do—for the stakeholders—rather than how the API will be implemented.

There should be an ubiquitous language for each domain. This means that the definition of anything is specific to that domain. It may be that (will be) a specific term will have different meanings in different parts of the business. This helps everyone keep on track. Ambiguity is removed. Superfluous data and capabilities are kept at a minimum.
