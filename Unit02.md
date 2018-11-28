---
layout: default
title: "MA231: Abstract Algebra I"
course_description: "A survey of how attributes of sets of mathematical objects behave when one or more properties we associate with real numbers are restricted, through a review of basic set theory, integers, and functions, followed by an exploration of the fundamentals of groups, rings, and fields."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Fundamentals of Groups** <span id="2"></span> 
*Groups are the most fundamental of all algebraic structures. 
Consisting of a set with an operator (often called a binary operator),
groups are simple, yet powerful, entities with applications in fields
such as physics and economics.  With fewer properties than, say, the set
of real numbers with addition and multiplication, general groups give
rise to structures that are as elegant as they are sometimes strange. 
As such, the study of groups is often where students of mathematics
“trip up.”  To avoid problems, do not make assumptions that are not
available.  For instance, we are aware that the field of real numbers is
commutative under the property of multiplication.  That is, for any real
numbers a and b, a\*b = b\*a.  However, while n?n matrices are groups
under matrix multiplication, we can show examples where AB ? BA.*  
 *             
 We will then study some examples of groups, beginning with the **finite
group**, which you will likely find easy to study.  We will also look at
some special types of groups, such as cyclic and permutation groups. 
Cyclic groups are generated from a single element.  In fact, if the set
G contained nothing but powers of some element g, then G = \<g\> =
{g<sup>n</sup> |n is an integer} and g would be called the “generator of
G.”  Interestingly, a certain set of permutations of some set M is also
a group (a **permutation group**).  The set of **all** possible
permutations on M is called the **symmetric group** of M. This is an
important group that has relevance in Abstract Algebra II, when we will
study Galois Theory.  Another important example, especially in Linear
Algebra, is the **general linear group of invertible matrices**.  You
will see more of this group in Abstract Algebra II.*  
  
 *After defining and examining a few examples of groups, we will see
that any subset of a set with group properties for an operator is itself
a group if it has the same properties.  These groups are called
“subgroups.”  We will also consider functions from one group to
another.  Any function (also called a “mapping”) that retains consistent
properties from one group to the next is called a homomorphism.  That
is, as we consider an operation \* on group G and ? on group H, if some
mapping f on G paired elements of G with those of H (that is, f(g) = h
for some g in G and h in H) such that f(a\*b) = f(a)?f(b), then f would
be a **homomorphism** of G into H, and G and H would be considered
**homomorphic**.  If the mapping f were also 1-1 and onto (that is, the
domain or image of the mapping covers all of H), f would be an
**isomorphism**.  The study of such mappings is important, for if H were
a simpler group than G and we discovered that H and G were isomorphic,
then anything we discover about H is also true of G.*  
  
 *We will end this unit with cosets.  Cosets are formed of true
subgroups of one group and single elements of the larger group.  If all
cosets are of the form gH = Hg, where H is a subgroup of G and g is in
G, then H is called **normal**.  This is important to remember because,
in general, gH may **not** be equal to Hg.  This is why we cannot assume
commutativity.  Cosets are analogous to equivalence classes on the
integers, because they partition groups into distinct sets.  Factor
groups are normal subgroups.*

**Unit 2 Time Advisory**  
This unit will take you 39 hours to complete.

☐    Subunit 2.1: 4 hours

☐    Subunit 2.2: 12 hours

☐    Subunit 2.2.1: 3 hours  
  
 ☐    Subunit 2.2.2: 3 hours  
  
 ☐    Subunit 2.2.3: 3 hours  
  
 ☐    Subunit 2.2.4: 1.5 hours  
  
 ☐    Subunit 2.2.5: 1.5 hours

☐    Subunit 2.3: 4 hours

☐    Subunit 2.4: 5 hours

☐    Subunit 2.5: 4 hours

☐    Subunit 2.6: 10 hours

☐    Subunit 2.6.1: 5 hours  
  
 ☐    Subunit 2.6.2: 5 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Define and generate groups.
-   Determine whether or not a group is cyclic.
-   Determine whether or not a mapping is a homomorphism or isomorphism.
-   Find all the cosets of a particular set.

**2.1 Definition of a Group** <span id="2.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Groups”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “3.2
    Definitions and Examples,” pages 40-47.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF). 

-   **Lecture: YouTube: Nathan Carter's “Visual Group Theory”: “Part I”
    and “Visual Group Theory”: “Part II”**
    Link: YouTube: Nathan Carter's “[Visual Group Theory”: “Part
    I”](http://www.youtube.com/watch?v=E3hg3nk7gTQ&feature=related) (YouTube)
    and “[Visual Group Theory”: “Part
    II”](http://www.youtube.com/watch?v=F2YXeEXV4WY&feature=related)
    (YouTube)  
        
     Instructions: Please click on the links above, and view each video
    in its entirety (1:28 minutes for “Part I” and 9:58 minutes for
    “Part II”).  These video lecture is an interesting way of discussing
    groups in terms of visual symmetries.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Groups”: “Exercise
    Problems 2, 8, 15, and 17”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Groups”: “Exercise
    Problems 2, 8, 15, and
    17”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Work through problems 2, 8, 15, and 17 on page 51. 
    After you complete each exercise, please see the solutions on page
    397.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF). 

**2.2 Examples of Groups** <span id="2.2"></span> 
**2.2.1 Finite Groups** <span id="2.2.1"></span> 
-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “Finite Group”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s “[Finite
    Group](http://mathworld.wolfram.com/FiniteGroup.html)” (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage.  This webpage contains a concise rendering of
    information on finite groups.  It also contains a visual
    representation of several common finite groups.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html). MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: Finite Groups**
    Link: Wikipedia: “[Finite
    Group](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/04/Finite-group.pdf)”
    (PDF)  
        
     Instructions: Please read the entire web page.  This webpage
    contains a concise rendering of information on finite groups.  It
    also contains a visual representation of several common finite
    groups.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Finite_group) (HTML).

-   **Web Media: YouTube: Klein Four's “Finite Simple Group (of Order
    2)” Humor Video**
    Link: YouTube: Klein Four’s “[Finite Simple Group (of Order
    2)](http://www.youtube.com/watch?v=BipvGD-LCjU)” (YouTube) Humor
    Video  
        
     Instructions: Please note that viewing this video is optional and
    this humorous video is meant to entertain.  Who says mathematicians
    can't laugh?  This is a now-famous piece of group theory humor set
    to a four-part *a capella* arrangement.  Klein Four, a group of
    Northwestern University mathematicians, recorded this in front of an
    audience in their math department in November, 2006.  Though
    intended strictly for humor, the use of terminology is correct and
    useful information can still be gleaned from the video.  Please
    click on the link, and view the video in its entirety (about 3
    minutes).   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.2 Cyclic Groups** <span id="2.2.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Cyclic Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and
    Applications](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf):
    “Cyclic Groups” (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read Chapter 4,
    “Cyclic Groups”, pages 57-73.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410 417 of the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF). 

-   **Reading: Knowledgerush: “Cyclic Group”**
    Link: Knowlegerush: “[Cyclic
    Group](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA231-2.2.2.pdf)” 
    (PDF)  
        
     Instructions: Click on the link above, and read the webpage in its
    entirety for a discussion on cyclic groups and good examples of
    cyclic groups.  The page contains information on properties of
    cyclic groups and ties cyclic groups to other group types that will
    be covered later.  
        
     Terms of Use: <span class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">The
    material linked above is licensed under the </span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span
    class="Apple-style-span" style="border-collapse: collapse; ">[GNU
    Free Documentation
    License](http://www.gnu.org/licenses/fdl.html)<span
    class="Apple-style-span"
    style="border-collapse: collapse; "> (HTML)</span><span
    class="Apple-style-span" style="border-collapse: collapse; ">.  The
    original version can be found
    [here](http://www.knowledgerush.com/kr/encyclopedia/Cyclic_group/) (HTML). </span></span></span>

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Cyclic Groups”: “Exercise
    Problems 3 and 4”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and
    Applications](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf):
    “Cyclic Groups”: “Exercise Problems 3 and 4” (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Complete problems 3 and 4 on page 69.  After you have
    finished each problem, check the solutions on page 397.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributid to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF). 

**2.2.3 Permutation Groups** <span id="2.2.3"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Permutation Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Permutation
    Groups”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read Chapter 5
    “Permutation Groups”, pages 74-91.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Lecture: YouTube: “Symmetries of a star and Its Permutation
    Group”**
    Link: YouTube: “[Symmetries of Star and Its Permutation
    Group](http://www.youtube.com/watch?v=Jdbw8kMVmdQ)” (YouTube)  
        
     Instructions: Please click on the link, and view the video in its
    entirety.  The video discusses a permutation group of a regular
    geometric figure (a Star of David).  This is an interesting visual
    presentation.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Youtube User: S22105 and can be viewed in its
    original form [here](http://www.youtube.com/watch?v=IraAiJzO9Yw). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Permutation Groups”:
    “Exercise Problems 1, 2, and 3”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Permutation Groups”:
    “Exercise Problems 1, 2, and
    3”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Work through problems 1, 2, and 3 on page 88.  After
    you complete these, check your answers on page 398.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**2.2.4 Symmetric Group** <span id="2.2.4"></span> 
-   **Reading: Wolfram MathWorld: Eric. W. Weisstein’s “Symmetric
    Group”**
    Link: Wolfram MathWorld: Eric. W. Weisstein’s “[Symmetric
    Group](http://mathworld.wolfram.com/SymmetricGroup.html)”  (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage.  This webpage contains a concise rendering of
    information on symmetric groups.  It also contains a visual
    representation of symmetric group multiplication table.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).   MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “Symmetric Group”**
    Link: Wikipedia: “[Symmetric
    Group](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/04/Symmetric-group.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage.  This webpage
    contains a concise rendering of information on finite groups.  It
    also contains a visual representation of several common finite
    groups.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Symmetric_group) (HTML).

**2.2.5 General Linear Group of Invertible Matrices** <span
id="2.2.5"></span> 
-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “General Linear
    Group”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s “[General Linear
    Group](http://mathworld.wolfram.com/GeneralLinearGroup.html)”
    (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage for a concise rendering of information on the general
    linear group.  It is short but has a number of links to related
    topics of interest.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “General Linear Group”**
    Link: Wikipedia: “[General Linear
    Group](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/04/General-linear-group.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on general linear groups, including various
    examples.  This topic is useful toward Abstract Algebra II.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/General_linear_group) (HTML).

**2.3 Subgroups** <span id="2.3"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Groups”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “3.3
    Subgroups,” pages 47-50.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free <span
    style="display: none; "> </span>Documentation<span
    style="display: none; "> </span>
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

-   **Lecture: YouTube: VeritySeeker’s “Basic Abstract Algebra, Part 8”
    Discussion**
    Link: YouTube: VeritySeeker’s “[Basic Abstract Algebra, Part
    8](http://www.youtube.com/watch?v=7YwOrlVy4Fw) ”Discussion
    (YouTube)  
        
     Instructions: Please click on the link, and view the video in its
    entirety (5:42 minutes) to learn about subgroups.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Groups”: “Exercise
    Problems 34 and 40”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and
    Applications](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)*: *“Groups”:
    “Exercise Problems 34 and 40” (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Complete problems 34 and 40 on page 52.  Then, check
    your answers against the solutions on page 397.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

**2.4 Homomorphisms** <span id="2.4"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Homomorphisms”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Homomorphisms”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “Chapter
    11: Homomorphisms,” pages 165-171.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

-   **Lecture: YouTube: VeritySeeker’s “Basic Abstract Algebra, Part 5”
    Discussion**
    Link: YouTube: VeritySeeker’s “[Basic Abstract Algebra, Part
    5](http://www.youtube.com/watch?v=_pgX8JZVGXc)” Discussion
    (YouTube)  
        
     Instructions: Please click on the link, and view the video in its
    entirety (7:39 minutes) for a discussion on group homomorphisms and
    isomorphisms in a fairly straight-forward manner.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Homomorphisms”: “Exercise
    Problems 2, 4, and 9”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Homomorphisms”:
    “Exercise Problems 2, 4, and
    9”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problems 2, 4, and 9 on page 173.  After
    you complete the assigned problems, check the solutions on page
    402.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

**2.5 Isomorphisms** <span id="2.5"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Isomorphisms”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Isomorphisms”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “Chapter 9:
    Isomorphisms,” pages 141-151.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Isomorphisms”: “Exercise
    Problems 1, 2, 6, and 8”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Isomorphisms”: “Exercise
    Problems 1, 2, 6, and
    8”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Work on problems 1, 2, 6, and 8 on page 151.  Then,
    check your answers against the solutions on page 401.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).  

**2.6 Cosets, Normal Subgroups, and Factor Groups** <span
id="2.6"></span> 
**2.6.1 Cosets** <span id="2.6.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Cosets and LaGrange’s
    Theorem”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and
    Applications](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf):
    “Cosets and LaGrange’s Theorem” (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “6.1
    Cosets,” pages 92-94.  
      
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file. The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML). The original
    version can be found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Lecture: Harvard University Extension: Dr. Benedict Gross’s “Math
    E-222 Abstract Algebra”: “Equivalence Relations; Cosets; Examples”**
    Link: Harvard University Extension: Dr. Benedict Gross’s “Math E-222
    Abstract Algebra”: “[Equivalence Relations; Cosets;
    Examples](http://www.youtube.com/watch?v=25EgOQOXodE)” (YouTube)  
      
     Also Available in: [Adobe Flash, Quicktime, or
    Mp3](http://www.extension.harvard.edu/openlearning/math222/)  
        
     Instructions: Please click on the link, and watch the video in its
    entirety.  To choose another format, scroll down to Week 2 and
    choose the format most appropriate for your internet connection to
    download the second lecture listed in Week 2 titled “Equivalence
    Relations; Cosets; Examples.”  Please watch the entire video (about
    47 minutes) to learn about equivalence relations and how they are
    related to cosets.  
        
     Terms of Use: This video has been reposted with permission for
    non-profit educational use by Harvard University.  The original
    version can be found
    [here](http://www.extension.harvard.edu/openlearning/math222/).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Cosets and Lagrange's
    Theorem”: “Exercise Problems 1 and 5”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Cosets and Lagrange's
    Theorem”: “Exercise Problems 1 and
    5”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problems 1 and 5 on page 98.  Then, check
    the solutions on page 399.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 of the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**2.6.2 Normal Subgroups and Factor Groups** <span id="2.6.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Normal Subgroups and
    Factor Groups”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Normal Subgroups and
    Factor
    Groups”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf) 
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “Chapter
    10: Normal Subgroups and Factor Groups,” pages 155-161.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 of the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Lecture: YouTube: “Normal Subgroup Example 1”**
    Link: YouTube: “[Normal Subgroup Example
    1](http://www.youtube.com/watch?v=srX9yA-on6g)” (YouTube)  
        
     Instructions: Please click on the link, and view the short video,
    which is approximately 2 minutes, for an example of a normal
    subgroup.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of Youtube User: S22105, and can be viewed in its
    original form [here](http://www.youtube.com/watch?v=2bweveCGrL4). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Normal Subgroups and
    Factor Groups”: “Exercise Problems 1, 8, and 13”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Normal Subgroups and
    Factor Groups”: “Exercise Problems 1, 8, and
    13”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Work through problems 1, 8, and 13 on page 163. 
    Then, check the solutions on page 402.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).


