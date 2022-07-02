Integrating Video and Programming Practice
==========================================

This is a brief summary of *Integrating Video and Programming Practice*,
presented at the [27th annual ACM conference on Innovation and
Technology in Computer Science Education (ITiCSE
2022)](https://iticse.acm.org/2022/) in Dublin, Ireland and published in
the proceedings.

This presentation page is available at
[learnbyfailure.com/integrating-video](https://learnbyfailure.com/integrating-video/)
and its source is available on
[GitHub](https://github.com/kbuffardi/integrating-video/).

Preface
=======

-   Increasing demand for eLearning resources to support asynchronous
    and remote learning
    -   Needs and challenges underscored by educational responses to
        COVID-19 pandemic
-   There are ongoing efforts to broaden participation in computing
    -   Need to teach computing in ways that are [relevant and
        meaningful to broader
        audiences](https://doi.org/10.1145/3502870.3506568)

Previous Work
-------------

-   Began with a [needs assessment to identify students’
    interests](../interests/)
    -   Study revealed significant discrepancies in some areas of
        students’ interests, especially by gender
        -   Students who identified as women or non-binary were only
            about half as likely to express interest in **games** and
            electronic hobbies like **robotics and microcontrollers**
        -   Minoritized students (by race and/or gender) expressed a
            variety of interests from multimedia to athletics and
            wellness, but seldomly considered those interests relevant
            to coding

We want to provide students with **new perspectives and applications of
coding** so they can **discover how it is relevant and meaningful to
their lives**.

-   [Chico State](https://csuchico.edu) and [UC Santa
    Barbara](https://ucsb.edu) are **Hispanic-Serving Institutions**
    -   Embraced unique opportunity to share perspectives of
        historically marginalized students
    -   Hired students to record brief demonstrations of how they would
        **relate CS1 topics to their lives and interests**
-   In a CS1 course, weekly (online) readings were supplemented with:
    -   Video that demonstrated the same concept
        -   Example: **Jessica uses primitive data types to represent
            soccer player data** <!--html_preserve-->
            <iframe width="560" height="315" src="https://www.youtube.com/embed/BVK6rCz_7SQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            <!--/html_preserve-->
    -   Link to a [CodeWorkout](https://codeworkout.cs.vt.edu)
        collection of coding exercises to practice the corresponding
        concept
-   [Preliminary study compared affective
    outcomes](../sigcse2022-platform/) to other offerings of CS1
    (without the video and practice exercises) and found significantly
    greater gains
    -   Students tended to watch videos weekly, but **fewer than a third
        practiced weekly**

We want to complement unique perspectives with **hands-on, interactive
practice to reinforce coding applications**

Integration of Video with Coding Practice
=========================================

We developed a Minimum Viable Product (MVP) integrating the video and
interactive practice features, as demonstrated here: [C++ variables for
soccer players](https://codewit.us/tutorial/variables_soccer/).

In a term of CS1 at UCSB, we adopted Codewit.us

-   Codewit.us was supplementary material to each reading, with
    corresponding concepts
-   Gathered post-term surveys with additional questions to solicit
    formative feedback
-   Investigated three research questions:
    1.  When video and practice are separate, how often do students
        engage in practice as frequently as watching videos? *(post-hoc
        analysis of previous term)*
    2.  When video and practice are integrated, are students more likely
        to also engage in practice if they watch videos?
    3.  What do students like and dislike about their experiences?

Findings
--------

**RQ1** - in post-hoc analysis of the term where videos and practice
problems were provided separately (n=55), we discarded students who
never used either and found:

-   **58%** of students practiced **less often**
-   **11%** practiced as often
-   **31%** practiced **more often** than watching videos.

**RQ2** - with the same procedure, we summarized how often students
(n=156) practiced (in comparison to how often they watched videos):

-   **38% less often**
-   **27% as often**
-   **36% more often**

and used a Chi-square goodness of fit test to compare the expected
vs. observed trends:

<table>
<thead>
<tr class="header">
<th style="text-align: right;"></th>
<th style="text-align: left;">Less</th>
<th style="text-align: left;">Same</th>
<th style="text-align: left;">More</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: right;">Expected</td>
<td style="text-align: left;">58%</td>
<td style="text-align: left;">11%</td>
<td style="text-align: left;">31%</td>
</tr>
<tr class="even">
<td style="text-align: right;">Observed</td>
<td style="text-align: left;">38%</td>
<td style="text-align: left;">27%</td>
<td style="text-align: left;">36%</td>
</tr>
</tbody>
</table>

*$<sup>2</sup> =17.037, df=2, p&lt;.001*

When the video and practice features were integrated, **students
practiced more frequently relative to how often they watched videos.**

**RQ3** - performed thematic analysis of open-ended survey responses
about what students liked and disliked

Future Work
===========

**Scaffolding concepts** from worked examples to bug fixing and fill-in
the blank gradually to coding from scratch

**Multimedia recording** featuring improved view of live coding,
presenter gestures, and drawings/markup

Plan to adopt Codewit.us as *primary homework*, following a **Mastery
Learning model**

Open Materials
==============

[Codewit.us](https://codewit.us) is free. GitHub hosts the free and open
source software including [the MVP used in this
study](https://github.com/kbuffardi/codewit-mvp) as well as our active
repository for [CodeWitUs](https://github.com/kbuffardi/codewitus)’s
future releases.

Videos are made available via [our YouTube
Channel](https://www.youtube.com/channel/UCP8J1udzFAdZqdaSUPlAsZg/videos)

C++ coding problems are available via
[CodeWorkout](https://codeworkout.cs.vt.edu/gym/exercises/search?utf8=%E2%9C%93&search=c%2B%2B)

Acknowledgements
================

The authors of this paper are grateful for the instructors who
incorporated the surveys and/or Codewit.us into their courses, which was
essential for this work. This material is based upon work supported by
the Learning Lab, an initiative of California Governor’s Office of
Planning and Research. Any opinions, findings, and conclusions or
recommendations expressed in this material are those of the author(s)
and do not necessarily reflect the views of the Learning Lab.

Particular thanks to our students who have shared their valuable
insights in producing videos to date:

-   Johanna Alvarado
-   Juan Aguirre-Ayala
-   Andrea Anez
-   Phinease Francis
-   Jason Gonzalez
-   Jessica Martinez
-   Destiny Rogers

As well as research assistants who contributed to the platform design
and development:

-   Subhed Chavan
-   Daniel Dempsey
-   Isabel Hernandez
-   Aryan Mittal

Full Paper
==========

The full paper will be available via ACM Digital library *coming soon*

To cite this paper, use the following reference in your bibliography:

> Kevin Buffardi and Richert Wang. 2022. Integrating Videos with
> Programming Practice. In Proceedings of the 27th ACM Conference on
> Innovation and Technology in Computer Science Education Vol 1 (ITiCSE
> 2022), July 8–13, 2022, Dublin, Ireland. ACM, New York, NY, USA, 7
> pages.
> <a href="https://doi.org/10.1145/3502718.3524778" class="uri">https://doi.org/10.1145/3502718.3524778</a>

Or import the following *BibTeX* reference:

*Coming soon*