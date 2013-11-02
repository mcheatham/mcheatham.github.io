---
title: Research
layout: main
nav: 2
---
<a id="wsn"></a>
Confidentiality in Wireless Sensor Networks
-------------------------------------------

Wireless sensor networks (and by extension, ubiquitous sensing) have the
potential to be a transformative technology &mdash; something like the internet
the fundamentally changes the way we live and work.  These networks can someday
be used to extend our awareness by monitoring our homes while we are out, or a
parking lot while we are walking to our cars late at night, or even what is
going on inside our bodies.  The can also enable autonomous responses to
changing environmental conditions, such as turning on our favorite music when
we enter a room or watering crops precisely when they need it.  In the rush to
develop technologies such as this to the point where their potential can be
realized, securitiy is often given little attention.  As we have seen in the
case of the internet, trying to retroactively harden a technology that is
already in widespread use is extremely difficult and often comes up short.  Now
is the time to make wireless sensor networks trustworthy, not after they have
become commonplace.

For my PhD dissertation I am attempting to come up with a way to model the
degree of confidentiality in a wireless sensor network.  I then plan to apply
the model I develop to security schemes (particularly key distribution and
encryption methods) that have been proposed for use in WSNs.  I also plan to
quantify the overhead of these methods in terms of memory, communications,
computation, and energy.  I will also clearly state the assumptions of these
methods and consider their practicality.  Assuming current encryption-based
approaches to ensuring confidentiality of data aggregation are not sufficient
in all cases, I then plan to develop non-cryptographic approaches for use
instead of or in addition to the current methods.  I will then use the same
framework to compare this new security scheme to the current encryption-based
solutions.

<a id="sna"></a>
Social Network Analysis
-----------------------

A social network is a graph in which the nodes represent people and the edges
represent some type of communication or collaboration between them. In this
work, I consider such a graph where the people are employees of the Air Force
Research Laboratory and the relationship is joint authorship on a publication.
With this type of graph, it is possible to answer questions such as "Which
employees are working with the greatest number of others?" and "Are John Doe
and Jane Smith connected by collaboration with a shared intermediary?" I also
explore adding keywords from the papers as nodes. With this enhanced graph, it
is possible to answer queries such as "Who is our leading expert on sensors?"
or "Do we have anyone with expertise in both microelectronics and C
programming?" I would like to examine the utility of this type of tool in
comparison with traditional methods of searching and browsing.

In the future I would also like to look at using the information within this
social network for the formation of ad-hoc teams. Because each team member
interacts with all the others, the size of the search space is very large. A
genetic algorithm could be used to efficiently explore this space. The fitness
function for the GA would be supplied by the manager forming the team and
tailored to the problem at hand. It might include such criteria as relevant
subject knowledge, importance of team members having worked together
previously, importance of having recognized experts on the team, and optimal
number of team members, among others.

<ul>
{% include references_by_subject.html subject="social network" %}
</ul>

<a id="aiwf"></a>
AI Planning in Workflow Management Systems
------------------------------------------

Collaborative environments allow geographically distributed groups to work
together to generate new knowledge. This work focuses on workflow management
systems (WfMS), which are a component of many contemporary collaborative
environments. A workflow is a series of operators chained together to
accomplish a goal. An example is the process a company goes through when
ordering new inventory. Steps in the process might include collecting cost
estimates, choosing a vendor, ordering the product, and testing it on arrival,
and adding the item to the company's internal inventory tracking system. As the
number and diversity of operators available for use in workflows increases, it
becomes more difficult to know what services are available and how they can be
combined to solve a given problem. Researchers involved in next-generation
grid-based collaborative systems have suggested using AI planning techniques to
help automate workflow creation. This work considers whether this approach can
also be applied to the workflow management systems available in current
collaborative environments.

<ul>
{% include references_by_subject.html subject="ai planning" %}
</ul>

<a id="thesis"></a>
Genetic Algorithms for Text Classification
------------------------------------------

A Nearest Neighbor Classifier (NNC) approaches the problem of text
classification by computing a similarity metric between feature vector
representations of an unknown document and a set of known prototype documents.
The accuracy and speed of the NNC are dependent upon the choices of features
and prototypes. In this work we consider the use of a genetic algorithm to
optimize the feature and prototype sets for an NNC. We also examine whether
simultaneously evolving the feature and prototype sets produces better results
than sequential optimization.

<ul>
{% include references_by_subject.html subject="text classification" %}
</ul>

<a id="programming"></a>
Type-safe Programming Languages
-------------------------------

I am also doing joint research with Kevin Cleereman at the Air Force Research
Laboratory and Krishnaprasad Thirunarayan at Wright State University on
improving the efficiency and expressiveness of type-safe programming languages.

<ul>
{% include references_by_subject.html subject="type safe" %}
</ul>
