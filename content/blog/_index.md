---
title: "Blog"
date: 2018-07-15T12:32:37+06:00
description : "Statement: What we think about PEPP-PT (WIP)"
---
In order to understand our situation, we would first like to briefly describe how things evolved from our perspective.

We were not very surprised when the project PEPP-PT [Pan-European Privacy-Preserving Proximity Tracing] publicly launched, since it had been announced that some relevant institutions were working on a solution during the #WeVsVirus results ceremony. While we understand that it was unforeseeable how much progress the hackathon teams would make towards a tracing solution in one weekend, we did assume that once it became clear how many highly qualified developers, data protection officers and other experts were involved, a common discourse would emerge. Our goal has always been to establish cooperation and to prevent silos that would lead to different solutions. Overcoming these challenges can only work if there is a high level of acceptance in society - and by extension a consensus on a standard. Unfortunately, our efforts to establish contact with the Robert Koch Institute and other agencies involved in the PEPP-PT project remained unanswered. We concluded and share the opinion that only a common standard that works across countries and can be implemented by different apps can succeed.

Since we only have access to the documents published so far, we can only write a statement about these.

The description of the protocol PEPP-PT published contains some gaps and it is therefore not possible to evaluate it without speculation, we would rather proceed by explaining why we will continue to work on our solution.

Our primary goal is to protect the privacy of every user. Because this is especially difficult when a lot of data might be generated, privacy engineering is needed. The more data is available, the easier it is to combine it into one big picture and identify individual persons. Therefore we have to avoid publishing the data of a person’s contacts, and instead publish only the random IDs of the person concerned. In our protocol, data matching occurs on the users’ local devices, thereby decentralising the data. As far as we have been able to deduce from media reports and the published project documentation of the PEPP-PT team, the data reconciliation is done on the server. From our point of view this should be avoided.

The reason for this is the following: there is no correlation between the PIDs of a single person or several people, but there is a correlation between the people you have met. The more people are ill, the more contact data is available to the server - this allows personal and individual contact flows to be recorded.

The high level of privacy protection we are seeking to achieve means we have to make various compromises, which is why our protocol in its current form is certainly not perfect. Due to the high privacy, the data size required for checking whether a user has been in contact with someone who is infected or not is higher than with the PEPP-PT approach. We have already worked out different ways to minimize this data load, but they always bring their own trade-offs. Currently, however, the aim is to have a solution at hand as soon as possible to get life back on track. We have many ideas for optimizing the protocol. However, maintaining user anonymity is not an easy task and takes time and careful implementation.

We want a simple, comprehensible and anonymous solution and therefore continue to work on the implementation of STRICT [simply track infections] - in the hope that STRICT leads to a better standard for everyone.
