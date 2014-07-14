---
layout: post
title:  "#01: Crosspollinating Security"
categories: security
---

Forty years ago, [Winston W. Royce][royce] described what has later been named 
the [waterfall model][waterfall], pictured to the right. He states the he believed in the concept, but: 
'the implementation described [..] is risky and invites failure'; due to the testing occurring very late in the lifecycle, and the long way from initial requirements to operation.

<div style="float:right;margin:0 10px 10px 0" markdown="1">
  ![Waterfall](/images/waterfall.png "The classic waterfall model from Managing the Development of Large Software Systems by Winston W. Royce (1970)")
</div>

Twenty years ago, when I was studying software engineering, the waterfall philosophy was still the foundation for how large-scale systems were developed. The results were predictable &mdash; a string of failures in development of large-scale software systems in the late eighties and throughout the nineties.

In the software development world, the backlash to the [Big Design Up Front][bduf] (BDUF) of the waterfall model was to do what Royce really proposed: iterative, incremental and evolutionary development. One of the best known models based on these principles is [Barry Boehm][boehm]'s [spiral model][spiral] in 1986.

In the same year Hirotaka Takeuchi and Ikujiro Nonaka published the [The New New Product Development Game][newnew] in [Harvard Business Review][hbr]. Instead of rigid sequential development (the 'relay race' approach), they propose a (the 'rugby' approach) where development emerge from multidisciplinary teams working together from start to finish. A few years later, this philosophy was adapted to the software development world by [Ken Schwaber][schwaber] and [Jeff Sutherland][sutherland] in the [Scrum framework][scrum], officially presented at 
[OOPSLA][oopsla] in 1995. This again led to the [agile software development][agile] movement, culminating with the publication of the [Agile Manifesto][manifesto] in 2001.

While the software development world has clearly progressed beyond the top-down approach of years past, enterprise security still seem to cling to this approach -- based on perceived stakeholder interests, we create entire [information security management systems][isms] (ISMS) in the style of [ISO/IEC 27001][iso27001] in order to solve the enterprise security conundrum.

The problem is that entities like this are more or less designed to operate as a crudely bolted-on accessory to the enterprise instead of as a organically integrated part of the daily activities.  As a result, properly ensuring a reasonable level of security in a modern enterprise is a 
[sisyphusian task][sisyphus], where 'security' are running behind in an effort to catch up with the dynamic complexity of a modern enterprise.

<strong>In short -- we need to learn from developments in other disciplines in order to achieve our goal of both effective and efficient security.</strong>

The next posts on this blog will attempt to explore the implicit and explicit connections between security and related disciplines.

[oopsla]: http://www.oopsla.org/oopsla-history/
[scrum]: http://www.scrum.org/
[sutherland]: http://jeffsutherland.com/
[schwaber]: http://www.controlchaos.com/
[hbr]: http://hbr.org/
[iso27001]: http://www.iso.org/iso/catalogue_detail?csnumber=42103
[agile]: http://en.wikipedia.org/wiki/Agile_software_development
[royce]:      http://en.wikipedia.org/wiki/Winston_W._Royce
[waterfall]:  http://en.wikipedia.org/wiki/Waterfall_model
[bduf]:       http://en.wikipedia.org/wiki/Big_Design_Up_Front
[newnew]:     http://apln-richmond.pbwiki.com/f/New%20New%20Prod%20Devel%20Game.pdf
[isms]:       http://en.wikipedia.org/wiki/Information_security_management_system
[sisyphus]:   http://en.wikipedia.org/wiki/Sisyphus
[boehm]:      http://sunset.usc.edu/Research_Group/barry.html
[spiral]:     http://portal.acm.org/citation.cfm?doid=12944.12948 "A spiral model of software development and enhancement"
[manifesto]:  http://agilemanifesto.org/
