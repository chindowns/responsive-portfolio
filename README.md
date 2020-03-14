# Code Refactor

## Site Picture
![Site](assets/images/horiseon-screenshot.png)

## Technologies Used
- HTML - used to make the DOM more semantic and support WEB SEO as well as accessibility
- CSS - styles html elements on the page semantically and support WEB SEO and accesibility
- Git - version control system to track changes to source code
- GITHub - hosts reository taht can be deployed to GitHub Pages
- Photoshop - resize the images to make the images a usable byte size for the browser to load.

## Summary
This project is practice refactoring code and leaving the web pages in better condition than when I started working on it.  

## Code Snippet
Added this code snippet to demonstrate the addition of comments and changing classes to elements.
'''html  
/* Set minimum width in the body to ensure the css maintains formatting */  
body {  
    background-color: #d9dcd6;  
    min-width: 1337px;  
}
/* Improve semantics - change header class to header element */  
header {  
    padding: 20px;  
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;  
    background-color: #2a607c;  
    color: #ffffff;  
}
...

## Significant Changes
- Repaired the internal SEO menu link
- Set a Minimum width in the body to maintain layout integrity.  This is not a responsive website.
- Semantic improvement - converted classes in \<div> to semantic elements Header, Nav, Section, Article, Aside & Footer.
- Rezised all the images using Photoshop to improve page loading on mobile sites and slower networks
- Semantic change - updated all the images to self closing with ALT attributes.
- Converted single use classe hero to #id hero
- Merged common styling from class multiple benefits... to benefits
- Removed repetitive CSS Rule Sets

## Author Links
### Michael Downs
[LinkedIn](http://www.linkedin.com/in/michaeldownssj)  
[GitHub](https://chindowns.github.io/) 
