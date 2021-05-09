---
title: Data Science Education with coursera
author: Peter Baumgartner
date: '2019-06-18'
categories:
  - data-science-education
tags:
  - coursera
  - educational-design
  - self-determined-learning
slug: data-science-education-with-coursera
summary: 'Beginning in December 2016, I initiated a new personal enterprise: Learning
  the statistical programming language R to acquire competencies of a data scientist.
  The post reports on my experience with a shortcoming on a coursera course and argues
  that even advanced MOOCs are often not designed to meet the particular requirements
  of self-determined learners. With the example of learning all the different ways
  to get data into the R environment, I show that designing different learning paths
  for different learner needs could be a solution.'
bibliography: ["../../../static/media/references.bib"]
link-citations: true
disable_comments: no
draft: no
---

Beginning in December 2016, I initiated a new personal enterprise: Learning the statistical programming language R to acquire competencies of a data scientist. With “learning enterprise,” I do not mean to get just interested in a new subject, to read from time to time a relevant book and to look into some web-based tutorials. No, with “enterprise” I mean a much more significant undertaking, namely to focus and concentrate several months on a systematic study for a new set of qualifications.

![Coursera Certificate for Peter Baumgartner for the course on Data Science Toolboxes.](images/Coursera-Certificate-Toolbox-min.png)

I started with a nine-part (June 2019: now ten-part) [course specialization to data science](https://www.coursera.org/specializations/jhu-data-science), taught by three professors of [John Hopkins University](https://www.jhu.edu/) ([Jeff Leek](https://www.coursera.org/instructor/~694443), [Roger D. Peng](https://www.coursera.org/instructor/rdpeng), and [Brian Caffo](https://www.coursera.org/instructor/~688901)) and offered via the MOOC[^1]-platform [Coursera.](https://www.coursera.org/)

## One-Sided Course Philosophy

But after I have finished successfully two courses with certificates, I turned impatient with the teaching style and course philosophy. My dissatisfaction did not so much arise by these three professors but had more abstract reasons: The course has as target audience people who need certified knowledge to get into (a better) job position. People like me (experienced adult learner, who are already permanently employed and have no intention to change the job) who want to learn specific skills for their working needs, are not well supported. I do not need to provide evidence of some acquired general qualifications as most of the course participants do. I was instead looking for some Personal Knowledge ([Polanyi 1974](#ref-polanyi_personal_1974-2)), which I could combine with my life and working experiences. After a long time again in the learner role, I found it very strange that I had to spend much *learning time on material arranged by other people* which I didn’t need and had, on the other hand, to learn some stuff superficially or to skip altogether, which is essential for my use cases.

![Coursera Certificate for Peter Baumgartner for the course on R Programming.](images/Coursera-Certificate-R-Programming-min.png)

To exemplify the problem in more detail: In the third course on Getting and Cleaning Data we had to learn different ways to get data into the R environment: To download it with URLs, to scrap it from web pages, to load it from Excel sheets, to collect it via an API. But – for instance – we didn’t learn how to get data from an SQL database. I appreciate that all these different methods are conceivably relevant, and as a becoming data scientist, one should know how to apply them all. I also understand that it is impossible to learn all the different use cases in every detail. But I disagree that the best teaching method is an exemplary journey through some of these potentially essential methods!

A teaching strategy which would have better suited me and other [self-determinded learners](https://www.schoology.com/blog/heutagogy-explained-self-determined-learning-education) would have been a systematic and complete list of all approaches with their pointers to the relevant R packages and supplemented with some prototypical program snippets to get started. After a *systematic overview and instructional material of all techniques*, one should have the opportunity to choose those two or three methods which cover those skills which are essential for the particular learner. In practical assignments, self-determined learners learner should have the chance to be trained and to practice precisely only those procedures they are interested in.

<img src="images/cover-make-it-stick-min.jpg" alt="Book cover of &apos;Make It Stick&apos;" class="floatleft"/>

Another example that coursera is not interested in the self-determined learner is their change in the billing strategy: Coursera made a switch to a subscription model for the Data Science Specialization. Instead, to bill per course, you have now to pay a monthly fee, which is counteracting self-learning and autodidacticism. To economize and save money for the course, one has to study fast and without looking for additional material, exercises, or implementations for his/her use cases. Consequences are a rigid study behavior where students follow the course design uncritically and without generating and posing questions. From an educational point of view, such a course of studies contradicts the psychological research on learning thoroughly ([Ambrose et al. 2010](#ref-ambrose_how_2010); [Brown, Roediger, and McDaniel 2014](#ref-brown_make_2014)).

## How to support the self-determined learner?

<img src="images/cover-how-learning-works-min.jpg" alt="Book Cover of &apos;How Learning Works&apos;" class="floatright"/>

Consequently, I stopped my course attendance and started to look for tutorials, courses, and other learning material that are more to the point for my needs. I have to confess that I didn’t know how exciting but also how difficult this self-paced and self-determined learning approach was, respectively is. Between us educators, we are talking routinely about self-determined learning ([Deci and Ryan 2008a](#ref-deci_handbook_2008), [2012](#ref-deci_overview_2012-1), [2008b](#ref-deci_self-determination_2008-2)), but often it is just a plea without detailed tips on how to achieve it.

When we are preparing material for learners, we are restricted by the learning time of our students (measured in credit points) and have therefore to select from the available resources. This strategy poses a problem for the self-determined learner as we as teacher decide which material is essential to learn and which not. Even if we are experienced teacher on the subject material in question and know therefore which skills are generally more in demand in real-life applications, we will always be wrong whenever some of our students have different needs or requirements.

For the design of online courses, there is an easy solution. Even if every curriculum has a reference point for the average amount of learning hours a student should need to cover a specific subject, there is no restriction on quantity for uploaded material. When we quantify the necessary learning hours of each different subject branch we are going to provide, then we can leave the choices to the students. The only requirement they would have to satisfy is a certain amount of learning hours. Students have to choose from a list of options in such a way that they fulfill this requirement by the curriculum.

To provide a course design where all students have to learn the same material generates an anachronistic situation: We are living in times of opulence where for almost all products, many variants for individual choices are available. But not so in the educational sector where with cohort learning still the industrial mass production model is prevalent. It is time to change this now — and with online courses, we have already the appropriate learning environment for individualization ready at hand.

## Résumé

Online courses should not only address learner looking for (non-)formal education and validated certificates but should also support the self-determined learner with its particular learning goals. Yes, my recommended educational strategy in the case mentioned above is a laboriously and hard-working solution in two aspects:

-   You need to work out all different learning paths with their answers, examples, exercises, and tests.
-   You need to provide an introductory section with a basic explanation of each branch so that students can make an informed decision.

I agree that these two requirements for the self-determined learner are additional work. But for MOOCs with their vast numbers of learners from different backgrounds, an individualized educational design would be valuable and economically feasible. Another advantage of the suggested instructional method to teach all approaches for a specific subject (e.g., ‘How to get data into the R environment?’) is that every one of these different procedures to choose from can be explained in exhaustive detail. As the various branches of the learning material separated in different self-contained modules, it is easy to add new methods or correct out-dated ones. With the proper design approach, each of these modules is an autonomous learning object that can be used in other (learning) contexts as well.

## References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-ambrose_how_2010" class="csl-entry">

Ambrose, Susan A., Michael W. Bridges, Michele DiPietro, Marsha C. Lovett, Marie K. Norman, and Richard E. Mayer. 2010. *<span class="nocase">How Learning Works: Seven Research-Based Principles for Smart Teaching</span>*. First. Jossey-Bass.

</div>

<div id="ref-brown_make_2014" class="csl-entry">

Brown, Peter C., Henry L. Roediger, and Mark A. McDaniel. 2014. *Make It Stick: The Science of Successful Learning*. Cambridge, Massachusetts: Harvard University Press.

</div>

<div id="ref-deci_handbook_2008" class="csl-entry">

Deci, Edward L., and Richard M. Ryan. 2008a. *Handbook of Self-Determination Research*.

</div>

<div id="ref-deci_self-determination_2008-2" class="csl-entry">

———. 2008b. “Self-Determination Theory: A Macrotheory of Human Motivation, Development, and Health.” *Canadian Psychology/Psychologie Canadienne* 49 (3): 182–85. <https://doi.org/10.1037/a0012801>.

</div>

<div id="ref-deci_overview_2012-1" class="csl-entry">

———. 2012. “Overview of Self-Determination Theory.” *The Oxford Handbook of Human Motivation*, 85. <http://www.elaborer.org/cours/A16/lectures/Ryan2004.pdf>.

</div>

<div id="ref-polanyi_personal_1974-2" class="csl-entry">

Polanyi, Michael. 1974. *Personal Knowledge: Towards a Post-Critical Philosophy*. Corr. Ed. University of Chicago Pr.

</div>

</div>

[^1]: Massive Open Online Course
