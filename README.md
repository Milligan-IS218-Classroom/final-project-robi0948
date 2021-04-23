# Introduction

Using GitHub Pages [https://pages.github.com/](https://pages.github.com/) create a personal website about yourself. You must include an About page, a Resume page, and at least one other page of your choice. This will be a publicly available site, so take care to be professional.

# Instructions

1. Accept the assignment and clone the starting repository from GitHub Classroom
2. In the `/docs` folder, create an `index.html`, `resume.html`, and one other html file.
   1. CSS and JS files should also be placed in the `/docs` folder
3. Create a basic HTML document in the `index.html` file.
4. Create a commit and push it to GitHub
5. Go to the repository on GitHub
   1. Go to Settings > Pages
   2. Under Source, select the `main` branch and the `/docs` folder, then click `Save`
   3. Go to the URL, typically _your-username_.github.io/_repository-name_ and verify that your `index.html` has been published
6. Complete the rest of the requirements
   1. **Note:** It may take a while for GitHub to update your website after you commit and push it.
7. Use the Feedback Pull request to ask for help
   1. Create a commit and push it
   2. Go to the repository on GitHub
   3. Go to Pull requests > Feedback
   4. Leave a comment at the bottom
   5. Or - Select the commit to leave a comment on a specific line of code
   6. Send me an email so I know to look at it


# Restrictions

For the purpose of this assignment, you may not use the following tools:

* External CSS Frameworks or pre-built Themes (e.g. Bootstrap, Jekyll)
* CSS Preprocessors (e.g. SASS)
* Static Site Generators (e.g. Jekyll) 
* JavaScript Frameworks (e.g. jQuery)

# Permissions

You are allowed to use any and all HTML5, CSS3, or JavaScript features that are supported by the Google Chrome browser (which I will be using for grading), even features not covered by the textbook. (See [caniuse.com](https://caniuse.com/))

* CSS Custom Properties [https://developer.mozilla.org/en-US/docs/Web/CSS/--*](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
  * Really useful for creating themes
* Web Components [https://developer.mozilla.org/en-US/docs/Web/Web_Components](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
  * Probably too advanced, but you can try

# Level 1 Requirements

## Your project must complete all of the following Level 1 requirements.

* All pages must be properly formatted HTML5 documents. (T1)
* You must have a minimum of three pages. (T1)
  * About
  * Resume
  * Something Else
* You must have a navigation list with links for each of your pages. (T1)
* You must have at least two CSS3 style sheets. (T2)
* You must have a reset style sheet. (T3)
* You must have a consistent color scheme for your pages. (T2)
* You must have appropriate and consistent padding and margins for all of the elements on your pages. (T2)
  
# Level 2 Requirements

* You must create an appropriate layout for each of your pages. (T3, T5)
* Your pages must all have a responsive (mobile) design. (T5)
* Your Resume page, at least, must have an additional stylesheet for printing. (T5)

# Level 3 Requirements

## You must complete at least one of the following Level 3 requirements.

* Include graphic design elements in your design. You must include at least four different types of advanced design elements to make your pages more visually appealing (e.g. images, borders, backgrounds, gradients, transitions, and animations). (T4, T8)
* Include a well formatted and styled table. You must include both row and column groups and a caption. (T6)
* Include a well formatted and designed form. You must include at least three different control types and validation on at least one of them. (Note: Only the validation needs to work.) (T7)
* Create a simple game in JavaScript. Your script must include at least one function and must interact with the HTML DOM. (T9, T10)
  * (e.g. Rock, Paper, Scissors; Tic-Tac-Toe; Blackjack)
  * See Tips below 

# Tips

## Useful HTML Character Codes

* &copy; - \&copy;
* &#x1F600; - \&#x1F600; or \&#128512;
* &spades; - \&spades; 
* &clubs; - \&clubs;
* &hearts; - \&hearts;
* &diams; - \&diams;

Here's a more complete list: [https://www.w3schools.com/charsets/ref_utf_basic_latin.asp](https://www.w3schools.com/charsets/ref_utf_basic_latin.asp)

## JavaScript

```JS
// Respond to the user clicking an element
var btn = document.getElementById("theButton");
btn.addEventListener('click', function() {
  // Do some stuff
});

// Select random element from an array
function getRandom(array) {
  var selection = Math.floor(Math.random() * array.length);
  return array[selection];
}

// Use document.querySelectorAll() to select multiple elements
// using a CSS selector
var allGreenElem = document.querySelectorAll('.green');

// This gives you an array-like object you can loop through
for (var i = 0; i < allGreenElem.length; i++) {
  // do something with allGreenElem[i]
}
```