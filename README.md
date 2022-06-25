# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

https://github.com/bahati7/fylo-dark-theme-landing-page-master/blob/main/design/desktop-design.jpg

https://github.com/bahati7/fylo-dark-theme-landing-page-master/blob/main/design/mobile-design.jpg

### Links

- Solution URL: https://www.frontendmentor.io/solutions/fylodarkthemelandingpagemaster-n1HYOTrHAJ
- Live Site URL: https://fylo-dark-theme-landing-page-master-alpha.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

combination of css grid and flexbox for the layout


```css

.grid{
    padding-top: 2rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background: var(--DarkBlueMainBg);
}
.grid .row{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(30rem,1fr));
    gap: 1.5rem;
}
}
```



## Author

- Website - https://bahatiphilemon.netlify.app/
- Frontend Mentor - https://www.frontendmentor.io/profile/bahati7
- Twitter - https://twitter.com/PhilemonBahati



## Acknowledgments

Thank you to Frontend Mentor team - https://www.frontendmentor.io/