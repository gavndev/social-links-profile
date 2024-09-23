# Profile Card (Mini Project)

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of Contents

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

- See hover and focus states for all interactive elements on the page

### GIF

![](./assets/images/profilecard_solution.gif)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned some basic CSS animations and created the heart beating effect as well as a subtle "hovering" effect!

```css
@keyframes floatOrg {
    0%, 100% {
        transform: translateY(0) rotate3d(0, 0, 1, 0deg);
    }
    25%{
        transform: translateY() rotate3d(0, 0, 1, 1deg);

    }
    50% {
        transform: translateY(-5px) rotate3d(0, 0, 1, -1deg);
    }
    75%{
        transform: translateY() rotate3d(0, 0, 1, 1deg);

    }
}

@keyframes floatAlt {
    0%, 100% {
        transform: translateY(0) rotate3d(0, 0, 1, 0deg);
    }
    25%{
        transform: translateY() rotate3d(0, 0, 1, 0deg);

    }

    50% {
        transform: translateY(-3px) rotate3d(0, 0, 1, 1deg);
    }

    75%{
        transform: translateY() rotate3d(0, 0, 1, 0deg);

    }
}

@keyframes pulseHeart {
    0%, 100% {
        transform: scale(1);
    }
    
    50% {
        transform: scale(1.2);
    }
}

@keyframes fadeIn {
    0% {
        transform: scale(0);  opacity: 0;
    }
    100% {
        transform: scale(1); opacity: 1;
    }
}
```


### Continued development

I explore many new elements, styles and features of both HTML and CSS through making this project and I plan to
expand it as I make progress on my journey! Some things I have planned are to add a separate section for an
'About Me' description and more!

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helped me for learning CSS animations, understanding the box model, and pretty much every obscure element or keyword I have problems using (like @keyframes, :hover, and .root, to name a few).
- [Stack Overflow](https://stackoverflow.com/) - Some would say it's dated, but any question you might've had, was definitely asked here, same for mine! Incredible resources lie here!

## Author

- LinkedIn - [Gavin Griggs](https://www.linkedin.com/in/gavin-griggs-frmthe44/)
- Frontend Mentor - [@gavndev](https://www.frontendmentor.io/profile/gavndev)
- Discord - [@g2vn](https://discordapp.com/users/291408962320990210)
- Instagram - [@gaaavnnn](https://www.instagram.com/gaaavnnn)

## Acknowledgments

Jovan Banks, my best friend, really supported me and pushed me through making this. My very first project and I'm incredibly proud of it

Frontend Mentor, for the great idea and constant practice, I wil definitely be doing more!