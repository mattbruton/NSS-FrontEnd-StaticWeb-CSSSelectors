#  HTML/CSS Exercise - CSS Selectors

This is an introductory NSS Evening Cohort 3 exercise which exposed students to CSS selectors.

==============================

- Viewing/Downloading Project
    - [To View Hosted Project](#to-view-hosted-project)
    - [Installation](#installation)
    - [To Run](#torun)
- Specifications and Project Information
    - [Languages] (#languages)
    - [Tools] (#tools)
    - [Specifications] (#specifications)

==============================

## Viewing/Downloading Project

### To View Hosted Project

[HTML/CSS Exercise - CSS Selectors](https://mb-nss-exercises.firebaseapp.com/css-selectors/index.html)

### Installation

Clone the repository from GitHub:

`git clone https://github.com/mattbruton/NSS-FrontEnd-StaticWeb-CSSSelectors.git`

Navigate to the project from the directory it was cloned into:

`cd NSS-FrontEnd-StaticWeb-CSSSelectors/`

### To Run

If you need a command line http server, to install http-server globally:

`npm install http-server -g`

Then:

`http-server` or `http-server -p XXXX` (the X's represent the port of your choice)

You should now be able to open your browser and type `localhost:8080` to view the project.

## Specs and Project Information

### Languages

1. HTML
1. CSS

### Tools Used

1. [Git](https://git-scm.com/)
1. [Atom](https://atom.io/)
1. [NPM http-server](https://www.npmjs.com/package/http-server)

### Specifications

==============================

1. The header element should have a 1px border. Color, you pick.
1. Convert the ul in the navigation element into a series of horizontal links with # as the href value, without bullets, and have some space between them horizontally.
1. Ensure that the navigation is semantically marked as such (i.e. wrap it in the correct HTML tag).
1. Any text in an element with class "disabled" should be colored grey, unless it is inside an anchor tag. If inside an anchor, it should be colored purple.
1. Any text inside an element with a class of "active" should be colored yellow.
1. Section elements should be contained within an article element.
1. There are two missing closing tags in this document. Make sure you add them back in.
1. Make the `"I'm red"` text colored red
1. Make the `"I'm blue"` text colored blue
1. The sibling `h4` of the red element should have a background color of red
1. The sibling `h4` of the blue element should have background color of blue
1. Any `h4` that is a direct child of grandparent should have a 1px border with rounded corners.
1. Elements with a class of `promo` should have bold text that is also colored gold.
1. Without adding any other attributes to the `input` fields in the footer, write a CSS selector that makes any text input field have a height of `25px`.

==============================