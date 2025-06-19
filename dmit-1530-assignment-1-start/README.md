# DMIT1530: Assignment 1

This lab is an idividual exercise worth 20% of your overall mark. 

For the complete rubric and Figma wireframe, please refer to your course section's Brightspace instance. 

The following instructions will help you work through the HTML and CSS required to create this website.

## Introduction

For this lab, you will build a two-page website with a responsive layout. The topic is a fictitious architectural firm. It will will assess the following concepts:

1. How to structure markup for flexbox layouts. 

2. CSS properties for the flex container (the parent element).

3. CSS properties for flex items (the direct child elemnts).

4. Relative Units

5. Advanced CSS Selectors

6. Fluid Web Design and Maximum-Width Containers

7. Media Queries and Responsive Web Design

---

## HTML

Before adding any styles, you must mark-up all of your content. Begin by filling in the meta information in the &lt;head&gt; of each HTML document; remember to give a unique &lt;title&gt; and description for each page. Then, start building your &lt;body&gt; by pasting all of the content from the **website-content markdown file** into your HTML files, semantically marking them up, and adding appropriate sectioning elements.


### Navigation & Footer

The top-level navigation and footer will be identical on every page of your website. 

All of the links referencing other pages on the website should be fully functional; however, links to external resources (mail clients, maps, telephone numbers, etc.) may use placeholder characters (#).


### Validation

Your HTML must **validate without any errors**; however, a warning that your website uses filler text rather than English is acceptable.


### Media Queries

As you work through the media queries for each page, be mindful of the specificity and scope of your selectors.

You should have a minimum of two media queries, for a total of three 'views' or layouts. You will *need to choose* which breakpoints (i.e. which minimum widths) achieve the look, feel, and functionality of the website in your provided screenshots. 

When defining padding and margins, do not fixate on a pixel-perfect measurement. Instead, focus on making sure that the layout is fluid and looks good at any viewport width. Do this by utilising relative units and flexbox properties such as ``justify-content`` and ``align-items``.


#### A Note on Your Maximum-Width Layouts

At your largest breakpoint or view, your layout should switch to a maximum-width centred layout.

Even when you switch to a maximum-width layout, your background colours and background images should span the entire width of the viewport. 


#### A Hint About Differentiating Page Layouts

If you find that you are having difficulty differentiating between each page with a single stylesheet, try adding a unique class to a high-level element and using this class in your selector statements. 

# PDF Instruction:
DMIT 1530: Assignment 1
Introduction
This Assignment is an individual exercise worth 20% of your overall mark.
For this Assignment, you will build a two-page website with a responsive layout. The topic
is a fictitious architectural firm. It will will assess the following concepts:
1. How to structure markup for flexbox layouts.
2. CSS properties for the flex container (the parent element).
3. CSS properties for flex items (the direct child elements).
4. Relative Units
5. Advanced CSS Selectors
6. Fluid Web Design and Maximum-Width Containers
7. Media Queries and Responsive Web Design
Instructions
HTML
Before adding any styles, you must mark-up all of your content. Begin by filling in the meta
information in the <head> of each HTML document; remember to give a unique <title>
and description for each page.
Then, start building your <body> by pasting all of the content from the **website-content
markdown file** into your HTML files, semantically marking them up, and adding
appropriate sectioning elements.
Navigation & Footer
DMIT 1530 – Web Design Fundamentals II | Assignment 1 1
The top-level navigation and footer will be identical on every page of your website.
All of the links referencing other pages on the website should be fully functional; however,
links to external resources (mail clients, maps, telephone numbers, etc.) may use
placeholder characters (#).
Validation
Your HTML must validate without any errors or warning; any submissions that do not
validate will receive the maximum deduction possible.
Media Queries
As you work through the media queries for each page, be mindful of the specificity and
scope of your selectors.
You should have a minimum of two media queries, for a total of three 'views' or layouts per
page. You will need to choose which breakpoints (i.e. which minimum widths) achieve the
look, feel, and functionality of the website in your provided screenshots.
When defining padding and margins, do not fixate on a pixel-perfect measurement. Instead,
focus on making sure that the layout is fluid and looks good at any viewport width. Do this
by utilising relative units and flexbox properties such as justify-content and
align-items.
A Note on Your Maximum-Width Layouts
At your largest breakpoint or view, your layout should switch to a maximum-width centred
layout.
Even when you switch to a maximum-width layout, your background colours and
background images should span the entire width of the viewport.
A Hint About Differentiating Page Layouts: If you find that you are having difficulty
differentiating between each page with a single stylesheet, try adding a unique class to a
high-level element and using this class in your selector statements.
DMIT 1530 – Web Design Fundamentals II | Assignment 1 2
Submission
Push the assignment files to the GitHub Classroom assignment before the due date.
Late assignments will not be accepted.

# Developer Notes:
## Common Colours, Typographic Styles, and Lengths
This Figma has Local Variable and Local Styles. Study these colours and typographic settings, as they are applied throughout the composition.

### Hint
These would make for ezxellent CSS Custom Porpoerties, or variables.
All distances between elements are measured in intervals of 0.5 real ephemeral units (rem). In order to use this website's design system as effectiively as possible, you could also convert these measurements into variables.

## Common Mistakes
Before using a non-semantic tag (i.e. a <span> or a <div>), check to see whether or not a semantic element could be used instead, such as a <section>.

Remember that all <section> elements must have at least one heading inside.

It does not make sense to mark up a single asterisk as its own heading because it is a decorative flourish or ornamentation meant to separate points (ex. a dinkus), not real content.

Do not mark up headings based upon their size. Instead make sure that they are in a logical, descending order in each semantic section.

Do not use any break tag (<br/>) to break the line or add space, as this is non-semantic.
Instead, try using a <span> element and vairous CSS properties.

If you need to hook part of an element inside of another element (ex. part of a text element), try using <span>.

Do not use any bold tags (<b>), as these are deprecated. Instead, try <strong>.

# Brightspace Instructions
Instructions
Assignment 1 is a two-page responsive flexbox layout. 

Download the assets folder for the required images, the Figma file for the layout, and the accompanying instructions and marking guide.

Next, follow the provided GitHub Classroom Link to accept the assignment and clone down a local copy of the generated repository. Work on this repository locally and push your commits back up to the remote repository as you work. Your instructor will see your work as you submit commits and can provide help or feedback from these files if requested.

Submission Requirements
The assignment will be submitted via the GitHub Classroom repository. Push all completed files to the repository before the due date and time. Any commits submitted after the due date will be rolled back and ignored.

LATE SUBMISSIONS WILL NOT BE GRADED.