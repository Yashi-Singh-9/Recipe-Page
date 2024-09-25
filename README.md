# Frontend Mentor - Recipe Page Solution
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Flexbox](https://img.shields.io/badge/Flexbox-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive Design](https://img.shields.io/badge/Responsive%20Design-FF6F61?style=for-the-badge&logo=responsive-design&logoColor=white)
[![Netlify Status](https://api.netlify.com/api/v1/badges/5ff28672-1dad-4f43-a2b3-257e378f7ee9/deploy-status)](https://app.netlify.com/sites/recipe-page-frontendmentor-solution/deploys)
![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-fefefe?style=for-the-badge&logo=frontend-mentor&logoColor=black)
[![Last Commit](https://img.shields.io/github/last-commit/Yashi-Singh-9/Recipe-Page?style=for-the-badge)](https://github.com/Yashi-Singh-9/Recipe-Page)

This is a solution to the [Recipe Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- View the recipe page with a clean and responsive design
- See the preparation time, ingredients, instructions, and nutritional values clearly
- View an image of the dish

### Screenshot

![Desktop Preview](images/Desktop-Preview.png)

![Mobile Preview](images/Mobile-Preview.png)

### Links

- Live Site URL: [Live Site ](https://recipe-page-frontendmentor-solution.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Working on this project helped me reinforce my understanding of:

- **CSS Custom Properties**: Using variables for consistent styling across the project.
- **Flexbox**: Aligning and distributing space among items in a container.
- **Responsive Design**: Ensuring the layout adapts well to different screen sizes using media queries.

Code snippets I’m proud of:

```html
<figure>
    <img src="images/image-omelette.jpeg" alt="A plate of served omelette with a golden-brown crust" role="img" aria-label="Served omelette">
</figure>
```

```css
body {
    margin: 0;
    padding: 0;
    font-family: 'Young Serif', serif; 
    background-color: var(--stone-100);
    line-height: 1.6;
    font-size: 16px;
    display: flex;
    flex-direction: column; 
    align-items: center;
    min-height: 100vh;
}
```

```css
.instructions-steps li::before {
    content: counter(list-counter) ". ";
    color: hsl(14, 45%, 36%);
    position: absolute;
    left: -30px;
    top: 0;
    font-weight: 700;
}
```

### Continued development

In future projects, I aim to:

- **Explore CSS Grid**: For more complex layouts and design patterns.
- **Improve Accessibility**: By testing and enhancing the accessibility features of the website.
- **Experiment with JavaScript**: To add interactive elements and dynamic content.

### Useful resources

- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide was essential in understanding Flexbox.
- [MDN Web Docs on Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries) - Helpful for implementing responsive design.

## Author

- Frontend Mentor - [@Yashi-Singh-9](https://www.frontendmentor.io/profile/Yashi-Singh-9)
- LinkedIn - [@Yashi Singh](www.linkedin.com/in/yashi-singh-b4143a246)

## Acknowledgments

A special thank you to Frontend Mentor for providing this challenge. It was an excellent opportunity to enhance my skills and practice real-world web design techniques. Also, thanks to the Frontend Mentor community for their feedback and support throughout the development of this project. Lastly, a shout-out to [MDN Web Docs](https://developer.mozilla.org) for their comprehensive documentation and tutorials.
