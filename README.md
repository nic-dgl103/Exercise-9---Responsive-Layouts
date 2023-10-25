# Exercise 8: Responsive Layouts

## Objectives
You will code a webpage made up of a series of different content blocks that you can choose from some provided layouts. First you will code the layout for mobile screens, then you will add media queries and use flexbox to modify the layout for tablet and desktop screen sizes.

## Instructions
Remember to:
* Regularly save your files and check out what your web page looks like in a web browser.
* Make regular commits and pushes. **Your instructor will be looking at how you wrote your commit messages!**
### 1. Get set up
* Clone your remote exercise repository onto your local machine.
* Add a comment in the head element of the homepage including: the course code and your section number - your name - Responsive Layouts. Example:
```
<!-- DGL 103 CVS1 - your name - Responsive Layouts -->
```
### 2. Choose your content block layouts
You can choose your content blocks by visiting this site: https://xd.adobe.com/view/a971d502-33a5-46ea-81be-1fd2c5b2076b-fc22/flow
There are two layouts for each of the seven provided content blocks. You must choose one layout from each content block and use the provided high fidelity wireframes as a guide to code the HTML and CSS for a webpage that has the following content structure:
1. Header
2. Hero
3. Benefits
4. Features
5. Testimonials
6. Call-to-action
7. Footer

### 3. Code the content blocks for mobile
1. In VS Code, create two new files called index.html and style.css. Link your external stylesheet to your HTML file. 
2. Code each one of your chosen content blocks for mobile. 
    * Your HTML should be clean and semantic. 
    * Mobile layouts usually follow the normal flow of content so you may not need flexbox for anything but the header. Use padding and margin to control the vertical space in the layout. 
    * The hamburger menu must work, you can use thw Responsive Nav codepen as inspiration: https://codepen.io/AskClaireGuiot/pen/BaMydwd?editors=1100
    * Make sure that your mobiel HTML and CSS are perfectly finished and your CSS is well organised before you move on to step 4 or your code will become a mess.
    * To simulate what your web page might look like on a mobile device: 
      1. With the webpage open in Chrome, right-click > Inspect. 
      2. In the DevTools window, click on the Toggle Device button (in top left-hand corner).
      3. In the browser window, select iPhone SE (375px wide) from the Dimensions drop down menu.

By designing for the small screen first we're using what is known as a mobile-first approach. By doing this, we create a basic design that will fit small screens and low bandwidth, and then we add advanced features or layouts as the screen grows and users switch from cell data to wi-fi. This ensures that we're designing an experience that will work for everyone. 

### 4. Adapt the layout for vertical tablets
1. In the browser window, select iPad Mini (768px wide) from the Dimensions drop down menu.
2. In VS Code, add the following media query at the bottom of your CSS:
```
  /* Medium devices (vertical ipads, 768px and up) */
@media only screen and (min-width: 768px) {

}
```
3. Add, in the media query, all the CSS needed to adapt the layout so that it looks like the tablet version of your chosen content blocks. You may need to add some container elements to the HTML to control the relationships between your flex containers and flex items.

### 5. Adapt the layout for desktop screens
1. In the browser window, select Responsive from the Dimensions drop down menu. Enter 1200px in the viewport width field and press enter. Note: If the computer that you are working on has a small screen and you can't see the whole viewport window then you may need to work on a lab computer.
2. In VS Code, add the following media query at the bottom of your CSS:
```
  /* Large devices (desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {

}
```
3. Add, in the media query, all the CSS necessary to adapt the layout so that it looks like the desktop version of your chosen content blocks. In the wireframes, the desktop layouts are 1440px wide so that you can see the negative space on either side of the content.

Note: For a professional website I would also check what the layout looks like in between the breakpoints. You do not need to do this for the exercise.
  1. In the browser window, select Responsive from the Dimensions drop down menu.
  2. Drag to expand your viewport width and watch how your layout behaves at all sizes.
  3. If anything in the layout looks awkward, I would record the viewport width and add a new media query using the width of the viewport as the min-width.

### 4. Format, organize and add comments 
* Use the Prettier VSCode extension to format HTMl and CSS code.
* Add organizational CSS comments and order your style rules so that your CSS is easy to read.
* Add a few comments to explain your HTML and CSS code and highlight anything of interest.

### 5. Check for errors
* Use the VSCode HTMLHint extension and validate your HTML code to make sure that it is correct: https://validator.w3.org/#validate_by_upload. Take a screenshot of the results.
* Validate your CSS code to make sure that it is correct: https://jigsaw.w3.org/css-validator/ for CSS. Take a screenshot of the results.

**You have now completed your exercise but you still need to push your edits to GitHub and submit it in Brightspace. Make sure to follow the instructions in the How to Complete Your Exercises Guide.** 