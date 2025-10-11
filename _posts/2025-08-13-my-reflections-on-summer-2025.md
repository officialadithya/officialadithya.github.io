---
layout: post
title: my reflections on summer 2025
date: 2025-08-13 00:00:00
description: what i've been up to this summer!
tags: math, theory, computer-science
categories: non-technical
disqus_comments: true
related_posts: false
mathjax: true
---

This summer, I was fortunate to attend STOC'25, EC'25, and CMMRS'25. I wanted to take some time to write a bit about my experiences and make these opportunities known to more junior undergraduates! Hopefully this isn't too long!

###### **General Takeaways & Funding Opportunities**

Conferences and summer schools are an amazing way to meet both fellow undergraduates, Ph. D. students, and faculty at other institutions. The research that's presented is an additional bonus! I am extremely grateful for the generous funding that made it possible for me to attend the following events. I recognize that some of these funding sources are not open to all students, but I encourage junior undergraduates to apply for similar sources of funding, such as those below.

At CU Boulder specifically, undergraduates may apply to [PACE](https://www.colorado.edu/pace/) for funding to present work at conferences. More generally, [UROP](https://www.colorado.edu/urop/) allows undergraduates to apply for "assistantship" and "individual" grants to fund their research. In conjunction with lab funding, UROP's grants may be able to be used for conference travel as well. I have not personally used either UROP or PACE, but I have heard glowing reviews from other students that have.

In addition, several conferences, including both STOC and EC, have a limited amount of funds available to assist those who may not be able to attend otherwise. Everyone is welcome to apply for these funds, and conferences encourage prospective attendees to not self-select out of applying. I have not personally used these sources of funding, but they are certainly helpful.

Finally, while it may be obvious, getting involved with a research group is a great way to attend conferences in that group's area of expertise!

###### **[The 57th Annual ACM Symposium on Theory of Computing (STOC'25)](https://acm-stoc.org/stoc2025/)**

STOC (along with FOCS) is one of the premier annual computer science theory conferences, featuring papers on topics like computational complexity, data structures and algorithms, coding theory and cryptography, algorithmic game theory, and more. The Boettcher Foundation's Educational Enrichment Grant, made available to all [Boettcher Scholars](https://boettcherfoundation.org/scholarships/), fully funded my travel to STOC.

I wanted to attend STOC since it'd give me a chance to learn more about topics in "core" theoretical computer science, beyond what I had already had exposure to at CU Boulder. I was also excited to meet several graduate students and faculty to learn more about their research! On another note, who could say no to a trip to Prague?

Attending STOC was extremely fun. Each day started with a workshop, followed by several paper presentations with coffee breaks throughout, and finally some time to wander the streets of Prague in the evening. 

I chose to attend the [Total Search Problems in Theoretical Computer Science](https://sites.google.com/view/totalsearch2025/) workshop every day. There, I encountered my first introduction to the complexity classes **TFNP**, **PPA**, **PPAD**, **PLS**, **PPP**, and more! The workshop talks presented the next few days were also interesting. I particularly liked [Daniel Mitropolsky](https://dmitropolsky.github.io)'s talk "TFNP and Cryptography: An Interplanetary Tour of Impagliazzo's Worlds" and [Noah Stephens-Davidowitz](https://www.noahsd.com)' talk "The more the merrier! On total coding and lattice problems and the complexity of finding multicollisions."

STOC had cool paper presentations as well! All the papers in the "Best Papers" track were interesting, but I especially enjoyed [Ryan Williams](https://people.csail.mit.edu/rrw/)' talk on "Simulating Time in (Nearly) Square-Root Space," a breakthrough showing that

$$\textbf{TIME}[t(n)]\subseteq\textbf{SPACE}\left[\sqrt{t(n)\log t(n)}\right]$$

for every function $$t(n)\geq n.$$ The best simulation bedfore Williams' result was discovered in 1975 by John E. Hopcroft, Wolfgang J. Paul, and Leslie G. Valiant. The talk was inspiring, and beyond the technical details presented, it had a good message. Williams urged other theorists not to be dissuaded by so-called barriers, and that often, we could break them if we just stare at the correct papers for a while, and believe in ourselves.

Beyond the "Best Papers" track, other talks I liked included
1. [Kamesh Munagala](https://www.kameshmunagala.org)'s talk "Metric Distortion of Small-group Deliberation,"
1. [Venkat Guruswami](https://people.eecs.berkeley.edu/~venkatg/)'s talk "Redundancy Is All You Need,"
1. [Prasanna Ramakrishnan](https://web.stanford.edu/~pras1712/)'s talk "Six Candidates Suffice to Win a Voter Majority," and 
1. Joey Rivkin's talk "A Generalized Trace Reconstruction Problem: Recovering a String of Probabilities." 

Apart from the technical parts of the conference, the lunches and coffee breaks were a nice way to meet new people, and I really enjoyed meeting several graduate students! The automatic espresso machines were a very nice addition, and they made good espresso and amazing hot chocolate.

Most evenings, after the conference, I strolled around Prague and had fun being a tourist! My favorite spots were the astronomical clock, Old Town Square, St. Vitus' cathedral, Vyšehrad, and Charles Bridge. Finally, as a classical music enthusiast, I made sure to catch a concert at the Klementinum Mirror Chapel.

I can't wait to attend my next STOC!

###### **[The 26th ACM Conference on Economics and Computation (EC'25)](https://ec25.sigecom.org)**

EC is the premier annual conference focusing on the broad field of [algorithmic economics](https://www.bowaggoner.com/whatiseconcs.html). By nature, EC is very interdisciplinary and features theoretical, empirical, and applications-based results at the intersection of economics and computer science. My advisor, [Rafael Frongillo](https://raf.prof), fully funded my travel to EC via an NSF REU grant.

EC will always hold a special place in my heart&mdash;EC'24 was the first conference I attended, and I gave a talk at its "Blockchains and Decentralized Finance" workshop. So, when Raf told me he had funds to send me to EC'25, I was beyond elated!

The structure of EC was similar to most conferences, consisting of paper presentations and coffee breaks throughout the day. On the last day, though, there was a workshop session. I chose to attend the [New Directions in Computational Social Choice](https://ec25.comsocseminar.org) workshop and really enjoyed it! Another highlight was the [Wikipedia Edit-a-Thon](https://sites.google.com/view/econcs-edit-a-thon), where several of us hoped to create or edit Wikipedia articles in algorithmic economics. I didn't edit much since I was new, but it was fun to crowdsource ideas for future improvements to the pages!

I decided to primarily attend social choice and fair division sessions throughout EC, since my senior thesis, and post-undergraduate plans, are currently geared towards working on democracy problems in general. My favorite presentations were
1. [Dominik Peters](https://dominik-peters.de)' talk "Reallocating Wasted Votes in Proportional Parliamentary Elections with Thresholds,"
1. [Carmel Baharav](https://www.carmelbaharav.com)'s talk "Alternates, Assemble! Selecting Optimal Alternates for Citizens' Assemblies,"
1. [Prasanna Ramakrishnan](https://web.stanford.edu/~pras1712/)'s talk "Metric Distortion for Tournament Voting and Beyond," and 
1. [Ratip Emin Berker](https://www.eminberker.com)'s talk "From Independence of Clones to Composition Consistency: A Hierarchy of Barriers to Strategic Nomination." 

The Best Paper/Best Student Paper talk this year was wonderful! Thanks to [Bo Waggoner's course on Algorithmic Economics](https://www.bowaggoner.com/courses/2025/csci6314/), I was able to understand the context in which "Swap Regret and Correlated Equilibria Beyond Normal-Form Game," by Eshwar Ram Arunachaleswaran, Natalie Collina, Yishay Mansour, Mehryar Mohri, Jon Schneider, and Balasubramanian Sivan, fit into the literature. They had extended the traditional notion of swap regret to a broader class of games, and showed that in several respects, their definition was the "correct" one. I had also met Natalie a few weeks earlier at STOC, so it was really nice seeing her win this award!

As always, meeting several new people at lunches and dinners was a highlight, but it was also cool to see people that I had just met at STOC again! We were lucky with the weather that week, so strolling through Palo Alto in the evening and exploring the downtown area to find dinner was fun. One night, a group of us from CU Boulder, plus Nishant Mehta of the University of Victoria, decided to do karaoke for a bit, which was a great time!

Overall, EC was an amazing experience, and I loved attending! Here's to many more.

###### **[The Cornell, Maryland, Max Planck Pre-doctoral Research School in Computer Science (CMMRS'25)](https://cmmrs.mpi-sws.org)**

CMMRS is a weeklong pre-doctoral summer school designed for students interested in computer science research. Students are given the opportunity to learn about what it is like to pursue a Ph. D. while networking with students and faculty from around the world. This year, roughly 90 students, representing 30 countries, attended. All students that attend CMMRS are fully funded by the program's sponsors, which include the Max Planck Society, Nokia Bell Labs, Huawei, and Google.

This program was incredibly well-organized and had two main components. There were several lectures focusing on different areas of active computer science research. In addition, there were three panels aimed towards answering questions on whether students should apply to Ph. D. programs, how to do so, and what research looks like in industry versus in academia. There was also a great tutorial by [Derek Dreyer](https://people.mpi-sws.org/~dreyer/) on how to write good papers and give good talks. The topics of the lectures vary each year, but my favorite lectures this year were
1. [Alexandra Silva](https://alexandrasilva.org)'s lecture "Algebraic Network Verification,"
1. [Justin Hsu](https://www.justinhsu.net)'s lecture "Type Systems: Between Theory and Practice," and
1. [Rediet Abebe](https://www.redietabebe.com)'s lecture "When does Resource Allocation Require Prediction?"

The environment at CMMRS was welcoming. Lecturers always encouraged us to ask questions at any point in the presentation. And in the panels, the organizers made it clear that no questions were off limits or taboo. This made both the lectures and panels very effective. We often interacted with lectures and panelists in a casual setting; for example, we'd usually have lunch or dinner with them, frequently see them during the day, or even run into them while exploring the city. I was astonished by the degree that lecturers and panelists made themselves available to us throughout the week!

Each day, we started with breakfast at the Saarbrücken Youth Hostel. Then, we'd take a short bus over to the Max Planck Institute for Software Systems. From there, most days started with a lecture. After that, we'd have a break with delicious snacks and a wide selection of drinks, go back in for a second lecture, have lunch, and then either have another lecture, panel, or another activity in the afternoon. In the evenings, dinner was provided at the hostel, and then we'd have a lot of free time to play board games, explore the city, or rest in preparation for the next day.

One of the highlights of CMMRS was meeting so many people from so many different countries. Often, we had upwards of ten countries represented at our lunch or dinner table! For many of us, it was the first time we had met people from certain countries, and these experiences were invaluable. 

CMMRS is a great program, and I recommend it to everyone! The application usually closes in mid-February.

###### **Acknowledgments**

I want to acknowledge the support of [Rafael Frongillo](https://raf.prof) for coordinating my funding for EC'25 and being a reference for my CMMRS application; [Huck Bennett](https://home.cs.colorado.edu/~hbennett/) for providing feedback on my CMMRS application; [Sriram Sankaranarayanan](https://home.cs.colorado.edu/~srirams/) for being a reference for my CMMRS application; Joan Gabriele for providing feedback on my application for the Boettcher Foundation's Educational Enrichment Grant; [The Boettcher Foundation](https://boettcherfoundation.org/scholarships/) for funding my STOC'25 travel; and [Lorenzo Alvisi](https://www.cs.cornell.edu/lorenzo/) and [Peter Druschel](https://people.mpi-sws.org/~druschel/) for coordinating CMMRS'25.

In addition, I want to acknowledge all the amazing people I met at STOC, EC, and CMMRS! You were all so fun to talk to, and I hope to stay in touch!