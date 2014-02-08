---
layout: main
title: Home
nav: 1
---
<div itemscope itemtype="http://schema.org/Person">
{% capture m %}

<img itemprop="image" src="{{ site.baseurl }}/images/me.JPG"
	class="img-responsive" style="width:175px;margin:2em;float:right">

Hi, I'm <span itemprop="name"><span itemprop="givenName">Michelle</span> <span itemprop="familyName">Cheatham</span></span>. I'm currently a <span itemprop="jobTitle">Computer Science PhD student</span> at <span itemprop="worksFor" itemscope itemtype="http://schema.org/Organization"><a itemprop="url" href="http://www.wright.edu"><span itemprop="name">Wright State University</span></a></span> in <span itemprop="workLocation" itemscope itemtype="http://schema.org/Place"><a itemprop="url" href="http://en.wikipedia.org/wiki/Dayton,_Ohio"><span itemprop="name">Dayton, Ohio</span></a></span>. I work as a
<span itemprop="jobTitle">graduate research assistant</span> in the <span itemprop="memberOf" itemscope itemtype="http://schema.org/Organization"><a itemprop="url" href="http://knoesis.wright.edu/faculty/pascal/daselab.html"><span itemprop="name">Data Semantics (DaSe) Lab</span></a></span>, under the direction of <span itemprop="colleague" itemscope itemtype="http://schema.org/Person"><a itemprop="url" href="http://www.pascal-hitzler.de"><span itemprop="name"><span itemprop="givenName">Pascal</span> <span itemprop="familyName">Hitzler</span></span></a></span>.

I'm a somewhat non-traditional student, in that I worked as a civil servant 
at the Air Force Research Lab for quite awhile before going back to school. After seven 
years of government employment, TPS 
reports got the better of me. I quit my cushy government job and tried out 
various other places of employment. In the end, I landed at Wright State 
University as a PhD student in Computer Science. Being a student is great &mdash; 
I get the opportunity to meet tons of fascinating people and talk about 
interesting ideas with them. 

At this point I've finished all the course work and passed the qualifying exam, 
and I'm working on research related to ontology alignment. I should be 
defending my dissertation in August of this year. You can check out the 
research section to find out how my dissertation is proceeding.

When I'm procrastinating on my dissertation, I enjoy trying out new craft
beers with my husband <span itemprop="spouse" itemscope itemtype="http://schema.org/Person"><span itemprop="name"><span itemprop="givenName">Jason</span></span></span> or teaching my dog Shiloh new tricks (like "don't
eat the cat").

I can be reached at <span itemprop="email">firstname.lastname@gmail.com</span>
{% endcapture %}{{m | markdownify }}
</div>

<!-- add photos of me, Jason and beer, and Shiloh -->
