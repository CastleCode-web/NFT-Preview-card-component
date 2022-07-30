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
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [](https://github.com/CastleCode-web/NFT-Preview-card-component)
- Live Site URL: []( https://castlecode-web.github.io/NFT-Preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow



### What I learned

I learned how to control image overlay by setting opacity to 0(not showing anything) and 1(showing all.). I also learned how to add shadow to a container. 



```css
.image{
    position: relative;
    width: 100%;
}
.image_img{
    display: block;
    width: 100%;
    border-radius: 10px;
}
.image_overlay{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 255, 247, 0.4);
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    border-radius: 10px;
}
```


### Continued development

I want to learn more on image overlay and media query

### Useful resources

- [Helful Resourses](https://www.youtube.com/watch?v=exb2ab72Xhs) - This helped me to understand how to control image overlay more


## Author

- Linkedln - [CastleCode](https://www.linkedin.com/in/castlecode/)
- Frontend Mentor - [@Feyisara2306](https://www.frontendmentor.io/profile/Feyisara2306)
- Twitter - [@CastleCode_web](https://twitter.com/CastleCode_web)


## Acknowledgments

Thanks to Frontend Mentor for giving me this opportunity to participate in these challenges.
