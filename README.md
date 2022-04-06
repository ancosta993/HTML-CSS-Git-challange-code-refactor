# HTML and CSS Code Refactor Challange 1
Click [hear](https://ancosta993.github.io/HTML-CSS-Git-challange-code-refactor/) for the deployed website.

## The purpose of this project is: 
* Replace various HTML elements with semantic HTML elements
* Add alt attribute for the images
* Logically structure the HTML codes
* Consolidate CSS code and remove redundant codes

### Replace various HTML Elements with Semantic HTML elements
* Header section <div></div> replaced <header></header>
* Navigation section <div></div> replaced with <nav></nav>
* All the <div><div> tags in the middle sections are replaced with <seciton></section>
* For the <section></section> elments with class="content", <article><article> element replaced <div><div>.
* Footer section <div></div> replaced with <footer></footer>

### Add alt attribute for the images
* For the section with the class content, alt attributes are added appropriately for the displayed images.
* For the section with the class benefits, alt attributes are left empty due the images being merely icons and not holding any significant meaning.

### Logically structured the HTML code
* Followed the general flow of content with the feader first and footer last with the rest of the sections in the middle. All the contents from header to the footer is added inside the <body></body> tag. All the lines were indented appropriately.

### Consolidate CSS code and remove redundant code
* CSS code follows the structure of the HTML elements. In other words, the order of elements in CSS follows that of the HTML (header first, other contents in the middle, and footer at the end).
* Comments were added to the codes
* Redundant codes were deleted and use the CSS chain selector for more concise code.

## Finished Website Screenshot
  ![Final Product](./assets/images/final-site-screenshot.png)
