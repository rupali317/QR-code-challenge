
# Frontend Mentor - QR code component solution

  

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

  

## Table of contents

  

- [Overview](#overview)

- [Screenshot](#screenshot)

- [Links](#links)

- [My process](#my-process)

- [Built with](#built-with)

- [What I learned](#what-i-learned)

- [Continued development](#continued-development)

- [Useful resources](#useful-resources)

- [Author](#author)

- [Acknowledgments](#acknowledgments)

  

## Overview

  

### Screenshot

![QR code component screenshot](https://github.com/rupali317/QR-code-challenge/blob/main/images/Screenshot%20for%20QR%20code%20component.png)


  



  

### Links

  

- Solution URL: [QR code github](https://github.com/rupali317/QR-code-challenge)

- Live Site URL: [QR code challenge live](https://rupali317.github.io/QR-code-challenge/)

  

## My process

  

### Built with

  

- Semantic HTML5 markup

- CSS custom properties

- Flexbox

- CSS Grid

  

### What I learned

  
1. meta tags are one of the factors that increase SEO and good for accessibility

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
<meta name="description" content="Front-end mentor's QR code component challenge is perfect for individuals new to CSS and HTML">
<meta name="keywords" content="HTML, CSS, Desktop design, Mobile design">
<meta name="author" content="Rupali Roy Choudhury">
```

2. Preconnection concept while obtaining fonts. Preconnect is a resource hint that tells the browser to initiate an early connection to the specified domain. It can improve the loading speed of resources, such as web fonts, by starting the connection process early in the page's lifecycle.

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
```

3. Difference between margin and margin-block/margin-inline. The latter takes into account of writing mode (handy when page is translated in different languages which adopt different writing modes)

4. Importance of mentioning height and width attributes for image tag in order to prevent CLS

  

### Continued development

  

1) I would like to implement this project using ReactJS, Sass.
2) Instead of getting fonts from another link, I would like to host it locally to improve web performance metrics like LCP, FCP
3) In another iteration, I would like to explore how to vertically position the qr code to the center especially when the bottom tab exists
4) Segregate the CSS reset in a separate css file (esp handy for larger projects)

![Mobile screenshot Brave browser](https://github.com/rupali317/QR-code-challenge/blob/main/images/Screenshot%20in%20my%20mobile%20-%20Brave%20browser.jpg)
  

### Useful resources

  

- [New Viewport Units](https://ishadeed.com/article/new-viewport-units/#:~:text=Be%20careful%20with%20the%20dvh,is%20scrolling%20up%20or%20down.) - This can potentially help me in centering the screen in mobile that have tabs (as mentioned above).
  

## Author

  

- Website - [Rupali Roy Choudhury](https://www.linkedin.com/in/rupali-rc/)

- Frontend Mentor - [@rupali317](https://www.frontendmentor.io/profile/rupali317)


  

## Acknowledgments

I express my gratitude towards my mentor - Deborah for the insightful code review session
  
I want to thank Grace Snow for helping me solve an issue where the css file was not loading in Safari but worked in other browsers like Chrome, Brave, Firefox, Edge. It was because I had left the value empty for link tag's type attribute. 

I referred to the following articles:
1. https://www.joshwcomeau.com/css/custom-css-reset/
2. https://andy-bell.co.uk/a-more-modern-css-reset/
3. https://fedmentor.dev/posts/
