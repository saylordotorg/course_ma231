---
layout: default
title: "MA231: Abstract Algebra I"
course_description: "A survey of how attributes of sets of mathematical objects behave when one or more properties we associate with real numbers are restricted, through a review of basic set theory, integers, and functions, followed by an exploration of the fundamentals of groups, rings, and fields."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Fundamentals of Rings** <span id="3"></span> 
*Rings are “larger” structures than groups, because they are sets with
two binary operators instead of one and because they have more
properties than groups.  Technically, a ring is a commutative group,
under addition, with the added property of being associative under
multiplication.  The distributive property connects the two operations. 
The study of rings began as a study of generalizations on addition and
multiplication of integers.  Interestingly, the desire to generalize
structures of number sets and operations came from the interest in
solving Fermat’s Last Theorem.*  
 *             
 We begin the unit with a more formal definition of rings and look at
ring properties.  We will then look at commutative and non-commutative
rings (note that if a ring is commutative under multiplication, it is
defined as a “commutative ring”).  The study of these two classes of
rings arose independently and mathematicians tended not to work on both
at the same time.  Though most research has focused on commutative
rings, non-commutative rings have become an important area of study over
the last sixty years.  We do wish to familiarize ourselves with
non-commutative rings, but we will not spend too much time studying
them, for such a study could realistically command an entire course of
its own. *  
  
 *Next, we will move into the concept of ideals, which is based on the
work of J.  W.  R.  Dedekind.  It was Dedekind and his ideals that first
moved abstract algebra from number theory to structure theory.  Dedekind
was looking for the properties of “ideal complex numbers,” but he
generalized his findings to abstract structures rather than working
strictly with number sets.  He defined an ideal as a subring whose
elements, when multiplied by **any** element of the larger ring, result
in an element of the subring.  That is, for a ring **R** and a subring
**S**, if the product rs is in **S** for every r in **R** and s in
**S**, then **S** is an ideal.  A **maximal ideal** is the “largest
proper ideal” of a ring.  That is, if **R** is a ring and **I** is an
ideal of **R**, then **I** is maximal, if there are no* larger*proper
ideals in **R**.  Another way of approaching maximal ideals is if **J**
is any ideal in **R** containing **I**, then either **J** = **R** or
**J** = **I**.  **Prime ideals** extend the idea of prime numbers to
rings.  That is, rather than looking at properties of prime numbers, we
can look at subsets of a ring that share many of the properties of prime
numbers.  This enables us to look at mathematical structures other than
the familiar ones that may share similar qualities.*  
 *             
 Modules over rings, for instance, are generalizations of vector
spaces.  Vector spaces have scalars that form fields.  Modules only
require scalars to form rings, which are simpler and may not have an
identity element over module multiplication.  The primary difference
between modules and vector spaces are that a module does not necessarily
have a basis and certain modules may not have unique rank.*  
 *             
 As with groups, homomorphisms are mappings from one ring to another
that preserve structures and isomorphisms are homomorphisms that are
also onto and 1-1.  As with the study of mappings on groups, the
interest is in seeing what kinds of ring structures arise when we have
mappings across rings that may not be entirely similar.*  
 *             
 We will end the unit looking at a particular kind of ring, called the
polynomial ring.  These are formed by polynomials in one or more
variables with coefficients in some ring **R**.  Again, the interest is
in finding generalizations of what we know about familiar polynomials
with number coefficients.  What we will learn is that polynomial rings
are either prime or factor uniquely.*

**Unit 3 Time Advisory**  
This unit will take you 42 hours to complete.

☐    Subunit 3.1: 10 hours

☐    Reading material: 5 hours  
  
 ☐    Video: 3 hours  
  
 ☐    Assignment: 2 hours

☐    Subunit 3.2: 5 hours

☐    Subunit 3.3: 5 hours

☐    Subunit 3.4: 4 hours

☐    Subunit 3.5: 5 hours

☐    Subunit 3.6: 3 hours

☐    Subunit 3.7: 3 hours

☐    Subunit 3.8: 1 hour

☐    Subunit 3.9: 5 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Define and generate rings.
-   Determine whether or not a subring is an ideal.
-   Determine whether or not a ring mapping is a homomorphism or
    isomorphism.

**3.1 Definitions and Properties of Rings** <span id="3.1"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Rings”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “16.1
    Rings,”pages 239-244.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.   <span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); ">The
    material linked above is licensed under the </span><span
    class="Apple-style-span"
    style="border-collapse: collapse; font-family: arial, sans-serif; font-size: 13px; color: rgb(0, 0, 0); "><span
    class="Apple-style-span" style="border-collapse: collapse; ">[GNU
    Free Documentation
    License](http://www.gnu.org/licenses/fdl.html)<span
    class="Apple-style-span"
    style="border-collapse: collapse; "> (HTML)</span><span
    class="Apple-style-span" style="border-collapse: collapse; ">.  It
    is attributed to Thomas W. Judson and the original version can be
    found
    [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).</span></span></span>

-   **Lecture: Harvard University Extension: Dr. Benedict Gross’s “Math
    E-222 Abstract Algebra”: “Rings”**
    Link: Harvard University Extension: Dr. Benedict Gross’s “Math E-222
    Abstract Algebra”: “[Rings Part
    1](http://www.youtube.com/watch?v=0ennNPHLz1c),” "[Rings Part
    2](http://www.youtube.com/watch?v=5dXuDMvxpjk)," and "[Rings Part
    3](http://www.youtube.com/watch?v=_K_IRztjZRw)" (YouTube)  
      
     Also Available in: [Adobe Flash, Quicktime, or
    Mp3](http://www.extension.harvard.edu/openlearning/math222/)  
      
     Instructions: Please click on the links and watch each video in its
    entirety.  To choose another format, scroll down to Week 9 and
    choose the format most appropriate for your internet connection. 
    Then download Parts 1-3 of the “Rings: Examples of Rings and Basic
    Properties and Constructions” lectures listed in Week 9.  Please
    watch all of the videos in their entirety (about 53 minutes for Part
    1, about 48 minutes for Part 2, and about 50 minutes for Part 3). 
    These video clips discuss properties and constructions of rings.  
        
     Terms of Use: This video has been posted with permission for
    non-profit educational use by Harvard University.  The original
    version can be found
    [here](http://www.extension.harvard.edu/openlearning/math222/).  

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”: “Exercise
    Problems 1 and 3”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:“Rings”: “Exercise
    Problems 1 and
    3”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problems 1 and 3 on page 257.  Then, check
    the solutions on page 405.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**3.2 Example of Rings** <span id="3.2"></span> 
-   **Reading: Wikipedia: “Ring (Mathematics)”**
    Link: Wikipedia: “[Ring
    (Mathematics)](https://resources.saylor.org/archived/wp-content/uploads/2011/04/Ring-mathematics.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage.  This webpage
    contains a concise rendering of information on rings, including
    useful examples.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Ring_(mathematics)) (HTML).

-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “Ring”**
    Link: Wolfram MathWorld: Eric. W. Weisstein’s
    “[Ring](http://mathworld.wolfram.com/Ring.html)” (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage for a concise rendering of information on rings.  It is
    short but has a number of links to related topics of interest. 
    Halfway down the page there is an interesting explanation of
    optional properties of rings and examples of rings that rise from
    changes in properties.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

**3.3 Commutative and Non-Commutative Rings** <span id="3.3"></span> 
**3.3.1 Commutative Rings** <span id="3.3.1"></span> 
-   **Reading: Wikipedia: Commutative Ring**
    Link: Wikipedia: “[Commutative
    Ring](https://resources.saylor.org/archived/wp-content/uploads/2011/04/Commutative-Ring.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on commutative rings, including various
    examples.  This topic is useful toward Abstract Algebra II.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Commutative_ring) (HTML).

**3.3.2 Non-Commutative Rings** <span id="3.3.2"></span> 
-   **Reading: Wikipedia: “Noncommutative Ring”**
    Link: Wikipedia: “[Noncommutative
    Ring](https://resources.saylor.org/archived/wp-content/uploads/2011/04/Noncummutative-ring.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on non-commutative rings, including various
    examples.  This topic is useful toward Abstract Algebra II.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Non-commutative_ring) (HTML).

**3.4 Ideals** <span id="3.4"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Rings”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “16.3 Ring
    Homomorphisms and Ideals,” pages 246-250.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”: “Exercise Problem
    5”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Rings:” “Exercise
    Problem
    5”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Practice what you have learned by completing problem
    5 on page 258.  Then, check the solution on page 404.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**3.5 Maximal and Prime Ideals** <span id="3.5"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Rings”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “16.4
    Maximal and Prime Ideals,” pages 250-252.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”: “Exercise Problem
    4”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Rings”: “Exercise
    Problem
    4”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problem 4 on page 258.  Then, check the
    solution on page 404.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**3.6 Modules** <span id="3.6"></span> 
-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “Module”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s
    “[Module](http://mathworld.wolfram.com/Module.html)” (HTML)  
        
     Instructions: Please click on the link to read the information on
    the page.  This webpage contains a concise rendering of information
    on modules, which are abstractions of vector spaces, with the
    primary exception being the coefficients are over rings instead of
    fields.  An example is the set of integers, which is a module over
    itself.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “Module (Mathematics)”**
    Link: Wikipedia: “[Module
    (Mathematics)](https://resources.saylor.org/archived/wp-content/uploads/2011/04/Module-mathematics.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on modules, including various examples.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Module_(mathematics)) (HTML).

**3.7 Ring Homomorphisms** <span id="3.7"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Rings”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “16.3 Ring
    Homomorphisms and Ideals,” pages 246-249.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”: “Exercise Problem
    19”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Rings”: “Exercise
    Problem
    19”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problem 19 on page 259.  Then, check the
    solution on page 404.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**3.8 Ring Isomorphisms** <span id="3.8"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Rings”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “16.3 Ring
    Homomorphisms and Ideals,” pages 249-250.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**3.9 Polynomial Rings** <span id="3.9"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Polynomials”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Polynomials”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: For the section on examples of sets, read “Chapter
    17: Polynomials,” pages 263-277.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Polynomials”: “Exercise
    Problem 2”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Polynomials”: “Exercise
    Problem
    2”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/MA231-1.1.1book.pdf) (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Try to do problem 2 on page 278, and then check the
    solution on page 405.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).


