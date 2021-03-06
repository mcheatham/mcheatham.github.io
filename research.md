---
title: Research
layout: main
nav: 3
---
<a id="alignment"></a>
<h2>Ontology Alignment</h2>

The vision of the Semantic Web is that computers as well as humans will be able
to leverage the information on the web. One important capability that would
facilitate this goal is ontology alignment. An ontology is a representation of
the concepts in a domain and how they relate to one another. Creating an
ontology involves a lot of design decisions, which tend to be influenced by the
designers' backgrounds and the application they are targeting. The result is
that two ontologies that represent the same domain will not necessarily be the
same. The goal of ontology alignment is to determine when an entity in one
ontology is semantically related to an entity in another ontology. 

My dissertation research focused on this topic. I began by examining
the performance of different string metrics when applied to ontology alignment.
It is important to systematically analyze this because all current alignment systems
use a string similarity metric in some capacity. Therefore, improvement in
metric selection will improve the state of the art in the field generally. This 
work was published at ISWC. The work showed that choosing string similarity metrics 
carefully, based on characteristics of the particular ontologies to be aligned, can 
achieve very good performance on class alignment. Aligning properties is more 
challenging though, both for string metrics and full-featured alignment systems. I 
developed a string-based approach to property alignment as part of my dissertation 
that achieves much better performance.

Going forward, I plan to focus on co-reference resolution and finding more complex 
relationships between ontologies than 1-to-1 equivalences. My hope is to use a 
combination of natural language processing, statistical, and design pattern-based 
approaches to achieve this goal. 

<ul>
{% include references_by_subject.html subject="alignment" %}
</ul>

<a id="odp"></a>
<h2>Ontology Design Patterns</h2>

There are some concepts that come up repeatedly across many different datasets 
on the Semantic Web. Examples include groups of entities describing the trajectory 
of a moving object, such as a person, migrating bird, or ship, or information 
about an organization, such as its location, the people involved, the things it 
produces, etc. These recurring concepts are often encoded as Ontology Design 
Patterns. An ODP is a self-contained partial ontology. It represents the core 
components of the concept it seeks to model, as identified by domain experts. 
ODPs avoid making any unnecessary ontological commitments in order to remain 
applicable in a diverse range of situations. I have been to several GeoVoCamps, 
in which domain experts come together with modelling experts to create ontology 
design patterns important for datasets in their field of interest. In addition 
to continued involvement in these kinds of modelling exercises, I would like to 
investigate the potential for using these ODPs for ontology alignment and for making 
sense of unstructured text available on the web. 

<ul>
{% include references_by_subject.html subject="odp" %}
</ul>

<a id="privacy"></a>
<h2>Privacy Concerns of Big Data</h2>

I am also interested in applying ontology alignment techniques to issues related 
to the privacy concerns of Big Data. Currently, many linked datasets are 
anonymized before being made available on the Semantic Web. This anonymization 
process often involves ensuring k-anonymity, which requires that at least k 
individuals have all possible combinations of pseudo- identifier characteristics. 
For instance, if the dataset contains information about people’s voting district, 
gender, and birth month and year, at least k people would be required to have all 
combinations of these attributes (if not, either fake data is added or the 
information is made more coarse, e.g. by providing only birth year rather than 
month and year). As the dimensionality of data increases (i.e. more features are 
available for each person), k-anonymity breaks down. Often this happens when new 
datasets are released that can be joined with existing datasets through some 
public fields. I would like to research semantically-informed attacks and defenses 
of privacy on the Semantic Web. 

<ul>
{% include references_by_subject.html subject="privacy" %}
</ul>

<a id="reversing"></a>
<h2>Software Reverse Engineering</h2>

Software reverse engineering is the process of analyzing a program in order to
learn how it works. This has many uses, but my research has focused on gaining
an understanding of the behavior of malware. This type of reversing generally
involves examining an executable for which no source code is available,
identifying the original entry point, and slogging line-by-line through
assembly code. Working at the assembly code level is extremely tedious &mdash;
insight often comes more quickly and easily if the level of abstraction can be
raised. While employed at Riverside Research (see <a
href="work.html#riverside">here</a>) I worked to make this possible by creating
Function Insight, an easy-to-use tool that leverages rule-based, machine
learning, and data mining techniques to aid non-experts in analyzing anomalous
sections of executables. I am interested in continuing this work at Wright State.

<ul>
{% include references_by_subject.html subject="reversing" %}
</ul>

<a id="wsn"></a>
<h2>Confidentiality in Wireless Sensor Networks</h2>

Wireless sensor networks (and by extension, ubiquitous sensing) have the
potential to be a transformative technology &mdash; something like the internet
the fundamentally changes the way we live and work.  These networks can someday
be used to extend our awareness by monitoring our homes while we are out, or a
parking lot while we are walking to our cars late at night, or even what is
going on inside our bodies.  They can also enable autonomous responses to
changing environmental conditions, such as turning on our favorite music when
we enter a room or watering crops precisely when they need it.  In the rush to
develop technologies such as this to the point where their potential can be
realized, security is often given little attention.  As we have seen in the
case of the internet, trying to retroactively harden a technology that is
already in widespread use is extremely difficult and often comes up short.  Now
is the time to make wireless sensor networks trustworthy, not after they have
become commonplace.

While with the Trusted Layered Sensing group in AFRL, I worked to model the
degree of confidentiality in a wireless sensor network. The intent was to use
this model to compare security schemes (particularly key distribution and
encryption methods) that have been proposed for use in WSNs.  My feeling was
that existing comparisons of different approaches lacked a holistic
perspective, in that implicit assumptions made by some methods required
lower-level protocols that obviated efficiency gains claimed by the method
itself. I still think this is the case &mdash; it was, and still is,
important that models consider the impact of all such assumptions in terms of
memory, communications, computation, and energy requirements. This work led to
the establishment of two SBIR topics (see <a href="work.html#afrl">here</a>).

<a id="sna"></a>
<h2>Social Network Analysis</h2>

A social network is a graph in which the nodes represent people and the edges
represent some type of communication or collaboration between them. In this
work, I considered such a graph where the people are employees of the Air Force
Research Laboratory and the relationship is joint authorship on a publication.
With this type of graph, it is possible to answer questions such as "Which
employees are working with the greatest number of others?" and "Are John Doe
and Jane Smith connected by collaboration with a shared intermediary?" I also
explored adding keywords from the papers as nodes. With this enhanced graph, it
is possible to answer queries such as "Who is our leading expert on sensors?"
or "Do we have anyone with expertise in both microelectronics and C
programming?"

I also investigated using the information within this type of social 
network for the formation of ad-hoc teams (e.g. a new project has come up for 
which Company X would like to bid; who should be involved in writing the 
proposal?). The size of the search space is very large, so a genetic algorithm 
was used. The fitness function for the GA is supplied by the manager forming 
the team and tailored to the problem at hand. It might include such criteria 
as relevant subject knolwedge, importance of team members having worked 
together previously, importance of having recognized experts on the team, and 
optimal number of team members, among others. This work was done at The Design 
Knowledge Company as part of the BUCKI SBIR Project, see 
<a href="work.html#tdkc">here</a> and <a href="funding.html">here</a>.  

<ul>
{% include references_by_subject.html subject="social network" %}
</ul>

<a id="aiwf"></a>
<h2>AI Planning in Workflow Management Systems</h2>

Collaborative environments allow geographically distributed groups to work
together to generate new knowledge. This work focused on workflow management
systems (WfMS), which are a component of many contemporary collaborative
environments. A workflow is a series of operators chained together to
accomplish a goal. An example is the process a company goes through when
ordering new inventory. Steps in the process might include collecting cost
estimates, choosing a vendor, ordering the product, testing it on arrival,
and adding the item to the company's internal inventory tracking system. As the
number and diversity of operators available for use in workflows increases, it
becomes more difficult to know what services are available and how they can be
combined to solve a given problem. Researchers involved in next-generation
grid-based collaborative systems have suggested using AI planning techniques to
help automate workflow creation. This work considered whether this approach can
also be applied to the workflow management systems available in current
collaborative environments.

<ul>
{% include references_by_subject.html subject="ai planning" %}
</ul>

<a id="thesis"></a>
<h2>Genetic Algorithms for Text Classification</h2>

A Nearest Neighbor Classifier (NNC) approaches the problem of text
classification by computing a similarity metric between feature vector
representations of an unknown document and a set of known prototype documents.
The accuracy and speed of the NNC are dependent upon the choices of features
and prototypes. In this work we considered the use of a genetic algorithm to
optimize the feature and prototype sets for an NNC. We also examined whether
simultaneously evolving the feature and prototype sets produces better results
than sequential optimization.

<ul>
{% include references_by_subject.html subject="text classification" %}
</ul>

<a id="programming"></a>
<h2>Type-safe Programming Languages</h2>

I also did some joint research with Kevin Cleereman at the Air Force Research
Laboratory and Krishnaprasad Thirunarayan at Wright State University on
improving the efficiency and expressiveness of type-safe programming languages.

<ul>
{% include references_by_subject.html subject="type safe" %}
</ul>
