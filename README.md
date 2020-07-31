# CodePen exercise 03 - Landing page

## What I'm building
Bogus landing page with no defined product to practice the HTML and CSS lessons from the corresponding course on FreeCodeCamp. This is exercise 3 out of 5 and the original code can be found at [CodePen](https://codepen.io/minicarbonara/pen/dyGqjgz).

## Requirements (per assignment)
To make a **landing page** featuring:
- A header element with id="header"
- A header image with id="header-img"
- A nav element inside #header with id="nav-bar" fixed to the top of the viewport
- Three clickable elements inside nav-bar with class="nav-link" linking to three sections of the page
- An embedded video with id="video"
- A form with id="form"
- An email input field with id="email" with placeholder and validation
- An input submit with id="submit" and action to the link provided
- At least one media query
- At least one flex element

## How I'm planning it to look, and why
My main reference is the example from [FreeCodeCamp's CodePen](https://codepen.io/freeCodeCamp/pen/RKRbwL) passing all tests from this exercise. Following that, and since I saw *The Matrix* again last week, I'm making a green-on-black, monospaced minimal website selling matrix-inspired clothing and accessories (and I'm writing it in Spanish because fuck it). It will have a **fixed, responsive header** like that of the example and a **centered wrapper** to keep content on a tidy column in the middle. Like the example it will showcase **three products** with pictures and descriptions to be shown as a row on wide viewports or column on thinner ones.

## Steps
### Setting the basic content
1. Start HTML file: add the header element, the nav element inside it, and the three links
2. Add the header image
3. Create content wrapper and three sections with distinct IDs for form, video and content
4. Update the navbar links to target these sections
5. Create form
6. Embed video
7. Add placeholder content to the content section

### Styling the shit out of it
8. Start CSS file: add basic colors, text sizes and font-family
9. Style header + nav-bar and affix to top of viewport
10. Apply flexbox to nav links
11. Style content wrapper for bg and alignment
12. Style sections for vertical spacing and width
13. Apply flexbox to content elements

### Adding media queries for responsive layout
14. Add media query to restyle header for vp width < 600px
15. Add media query to products section for vp width < 500px

I hope any of this works.