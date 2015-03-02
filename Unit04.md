---
layout: default
title: "MA231: Abstract Algebra I"
course_description: "A survey of how attributes of sets of mathematical objects behave when one or more properties we associate with real numbers are restricted, through a review of basic set theory, integers, and functions, followed by an exploration of the fundamentals of groups, rings, and fields."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Fundamentals of Fields** <span id="4"></span> 
*We conclude this course with a unit on fields.  Fields are general sets
with some defined operations of addition and multiplication that have
all the familiar properties of rational, real, and complex numbers. 
They form commutative groups over both addition and multiplication and
have the distributive property that connects the two operations.*  
 *             
 We will begin the unit with a formal definition of fields and consider
field properties.  We will then look at some examples of fields and
learn about field extensions.  An extension of some field **K** is
nothing more than a field **M** that contains **K** as a subfield. 
Consider the real numbers **R** as an extension of the rational numbers
**Q**.  **R** contains irrational numbers and, more importantly,
transcendental numbers.  Transcendental numbers can never be solutions
to algebraic equations.  Further, if there are algebraic and
transcendental extensions of fields in specific, what other kinds of
properties might be missing from one field **F** but included in some
minimal field containing **F**, in general?*  
 *             
 For instance, there are splitting fields.  If P(X) is a polynomial over
some field **K**, then any field **L** containing **K** which P(X) can
“split” into linear factors X - a<sub>i</sub> is called a splitting
field of P(X).  If the field is the rational numbers **Q** and we
consider a polynomial P(X) = X<sup>3</sup> – 7 with coefficients in the
rationals, one solution is irrational and two are complex, meaning that
we would need an extension with those solutions, at minimum.  Any
extension that contains all three roots would be a splitting field.*  
 *             
 There is also the issue of P-closures.  Suppose a field **K** does not
have a certain property P.  Then any extension **L** containing **K**
that had property P would be called a P-closure for **K**.  One example
is complex numbers being the **algebraic closure** for real numbers,
since some polynomials with real coefficients have complex roots.  In
addition, an extension field of **K** is a **separable closure** for
**K** if it contains the smallest set of all possible finite separable
extensions of **K** within the algebraic closure.*

**Unit 4 Time Advisory**  
This unit will take you 24 hours to complete.

☐    Subunit 4.1: 5 hours

☐    Subunit 4.2: 5 hours

☐    Subunit 4.3: 5 hours

☐    Subunit 4.4: 5 hours

☐    Subunit 4.5: 4 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Define and generate fields.
-   Find an extension field given a field and polynomial solutions.
-   Determine algebraic closure.

**4.1 Definition and Properties of a Field** <span id="4.1"></span> 
-   **Reading: Wolfram MathWorld: Eric. W. Weisstein’s “Field” and
    “Field Axioms”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s
    “[Field](http://mathworld.wolfram.com/Field.html)” (HTML) and
    “[Field Axioms](http://mathworld.wolfram.com/FieldAxioms.html)”
    (HTML)  
        
     Instructions: Please click on each link to read the information on
    each webpage.  The first webpage titled “Field” contains a concise
    rendering of information on fields.  It is very short, but provides
    a good explanation in a few sentences of what a field is and is
    not.  The second webpage titled “Field Axioms” contains a concise
    rendering of information on field axioms (properties).  It is very
    short, but provides a good explanation in a few sentences of what
    makes a field a field.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “Field (Mathematics)”**
    Link: Wikipedia: “[Field
    (Mathematics)](http://www.saylor.org/site/wp-content/uploads/2011/04/Field-mathematics.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on fields, including various interesting
    examples.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Field_(mathematics)) (HTML).

**4.2 Extension Fields** <span id="4.2"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Fields” and “Rings”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Fields” and
    “Rings”](http://www.saylor.org/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Please read “21.1 Extension Fields,” pages 329-340,
    and then read “16.3 Ring Homomorphisms and Ideals,” pages 246-250.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Fields”: “Exercise
    Problem 2”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Fields”: “Exercise
    Problem
    2”](http://www.saylor.org/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Work through problem 2 on page 350.  Then, check the
    solution on page 407.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**4.3 Splitting Fields** <span id="4.3"></span> 
-   **Reading: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Fields”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications:
    “Fields”](http://www.saylor.org/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Please read “21.2 Splitting Fields,” pages 340-343.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

-   **Assessment: Stephen F. Austin State University: Thomas W. Judson’s
    Abstract Algebra Theory and Applications: “Fields”: “Exercise
    Problem 3”**
    Link: Stephen F. Austin State University: Thomas W. Judson’s
    [Abstract Algebra Theory and Applications: “Fields”: “Exercise
    Problem
    3”](http://www.saylor.org/site/wp-content/uploads/2011/07/MA231-1.1.1book.pdf) (PDF)  
      
     Also available in:  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA231-1.1.1book-Thomas-W.-Judson.epub)  
      
     Instructions: Complete problem 3 on page 350, and then check your
    answer on page 407.  
        
     Terms of Use: Please respect the copyright, license, and terms of
    use displayed on pages 410-417 on the PDF file.  The material linked
    above is licensed under the [GNU Free Documentation
    License](http://www.gnu.org/licenses/fdl.html) (HTML).  It is
    attributed to Thomas W. Judson and the original version can be
    found [here](http://abstract.ups.edu/download/aata-20100827.pdf) (PDF).

**4.4 Algebraic Closures** <span id="4.4"></span> 
-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “Algebraic
    Closure”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s “[Algebraic
    Closure](http://mathworld.wolfram.com/AlgebraicClosure.html)”
    (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage for a summary of algebraic closure.  It is very short
    but provides a good explanation in a few sentences.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “Algebraic Closure”**
    Link: Wikipedia: “[Algebraic
    Closure](http://www.saylor.org/site/wp-content/uploads/2011/04/Algebraic-closure.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage.  This webpage
    contains a concise rendering of information on algebraic closure,
    including various examples.  This topic is useful toward Abstract
    Algebra II.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Algebraic_closure) (HTML).

**4.5 Separability** <span id="4.5"></span> 
-   **Reading: Wolfram MathWorld: Eric W. Weisstein’s “Separable
    Extension”**
    Link: Wolfram MathWorld: Eric W. Weisstein’s “[Separable
    Extension](http://mathworld.wolfram.com/SeparableExtension.html)”
    (HTML)  
        
     Instructions: Please click on the link to read the information on
    the webpage for information on separable field extensions.  It is
    very short but provides a good explanation in a few sentences.  
        
     Terms of Use: Please respect Wolfram MathWorld's [terms of
    use](http://mathworld.wolfram.com/about/terms.html).  MathWorld
    webpages are free for academic use and may be hyperlinked, according
    to their [FAQ
    site](http://mathworld.wolfram.com/about/faq.html#linking).

-   **Reading: Wikipedia: “Separable Extensions”**
    Link: Wikipedia: “[Separable
    Extension](http://www.saylor.org/site/wp-content/uploads/2011/04/Seperable-extension.pdf)”
    (PDF)  
        
     Instructions: Please read the entire webpage for a concise
    rendering of information on separable field extensions, including
    various examples.  This topic is useful toward Abstract Algebra
    II.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Separable_extension) (HTML).


