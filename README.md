# Odoo_test_SLG

For the second phase of the selection process for the Odoo’s Web designer vacancy, I was required to do the following test:

Converting the image “Odoo_mock-up.jpg” into a static HTML page using Bootstrap v4.6, with these specifications:

Use as much as possible Bootstrap variables and SCSS maps.
The final result should look correct on a viewport size ≥ 992.
In the “Awards” section, the 5 boxes should be clickable with a hover effect.
The “Helpful answers” section should be fully functional.


<h2>Methodology</h2>

Like in my usual design projects, I followed the Double Diamond methodology and adapted it to this test, that consist in four key steps: Discover, Definition, Development and Deliver. 

<h3>Discover</h3>
In this phase I read the instructions for the test and the attached files, such as the mock-up image, the text file and the images folder. 

<h3>Definition</h3>
With the information from the discover phase, I was able to define an action plan to accomplish the test. 

First, I decomposed the mock-up using photoshop, to define the column system, the color palette, the font, the text hierarchy, some basic components (such as buttons) and some margin and padding measures.

Then, I analyzed the interactive elements and behaviors expected in this test to start reading some documentation to define what I was going to do.

Finally, I identified some inconsistencies in the design (detailed in the “Improvements” section of this “Read me” text), to define the changes I was going to make to improve the design and interactions. 

<h3>Development</h3>
I used Visual Studio to develop this project. I started writing a .html file with a basic Bootstrap structure to start coding. Then, I created a .scss file and define my variables and collections according to the findings in the definition phase. And finally, it was all about coding.
In this phase, I divided the mock-up in sections, and I tested every finished element to adapt it to a responsive behavior and to identify potential problems to improve them in an iterative process.

<h3>Deliver</h3>
Once finished, I uploaded to a GitHub repository the following files, for you to evaluate them:

- index.html
- styles.sass
- styles.css 
- styles.css.map 
- images folder



<h2>Findings</h2>

Generally speaking, I find this design appropriate, simple and clean, which helps the information to be easy to read and comprehend. 

The color palette is well-defined, it prevents readability problems by having such an eye-friendly and well-contrasted colors, and creating a comprehensible identity by defining wisely the color hierarchy.

The font was appropriate too, along with the text hierarchy that helps to guide the user reading through all sections, showing the most important information.

The components were also fine, it is always clear which are the interactive elements, where a section starts and ends.

But, in the other hand, there were also some problems in this mock-up.

First, there were some inconsistencies, like the use of some icons (e.g. the two types of arrows used in the “learn more” and “view all” buttons), some buttons/clickable elements styles (e.g. the “view all” link, the “see case studies” button, and the final “learn more” button which should be the same), and some text hierarchy inconsistencies mostly in titles.

Then, it was not so clear the expected behavior of the awards section, which gives me a messy impression with the “up and down” disposition.

Finally, and related to the text hierarchy problem, the “I want to start a new project” title is not visible. This section should be more important since it’s the call-to-action to sell the product.


<h2>Improvements</h2>

I allowed myself to do the following improvements in the realization of this static website that, even if they are small changes, I think they contribute enormously to improve the comprehension and experience of navigating through it.

1. I made the whole website responsive.
2. Even if it was not part of the mock-up, I implemented a responsive menu for >992 viewports.
3. I established a unique style for the “view all”, “see case studies” and “learn more” buttons, with an unique arrow icon and a border-bottom that indicates that it is a clickable link to more information.
4. In the “Features” section, I use the same structure than in the other sections (Tag, Title, text and elements), because the logic of each section is to highlight an idea, give the user a little description and then add a complement. So, I added a title and a paragraph with the same text hierarchy as the other sections.
5. In the “Awards” section, I applied the same title hierarchy (h2) to the section title, so it would be evident that it was an independent section.
6. I made the “Awards” section an automatically animated carousel, in which each card moves one at a time to the left, and that responds to the “swipe” gest in mobile. Also, I kept the idea of “up and down” design in the hover effect, that makes each card elevate, adding a border color and a shadow. Finally, each card is clickable and leads to the home page of each brand.
7. I applied the same title hierarchy (h2) to the “I want to start a new project” section, to highlight this idea and increase the purchase rate.
8. In the footer, each social media icon has a hover effect and is clickable, leading to each odoo’s social media pages. 


