# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/desktop%20version.png)
![](./images/mobile%20version.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

With this challenge, I explored using min and clamp for adjusting width and height depending on different screen sizes, instead of setting fixed sized and using media query.


```css
body {
    height: min(100vh, 900px);
    width: clamp(100%, 100%, 1440px);
}
.card {
    width: min(90%, 350px, 350px);
}
```

### Continued development

I had a trouble with the image having a new image on top of it with a background color when I hover. I fixed it, but I don't feel confident with my solution. I'm still not quite knowledgeable with seudo, so I am planning to tackle it with future projects.

### Useful resources

- [Resource 1](https://www.youtube.com/watch?v=U9VF-4euyRo) - When it comes to CSS, I would highly recommend Kevin powel, he is direct to the point and likes exploring new css tricks. This video helped me grasp the idea of min,max, and clamp.

## Author

- Website - [@jiehlaraee](https://github.com/jiehlarae)
- Frontend Mentor - [@jiehlarae](https://www.frontendmentor.io/profile/jiehlarae)
- Twitter - [@JiehlaDacara](https://twitter.com/JiehlaDacara)