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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

-[Desktop Version](screenshots/NFT-Desktop.png)
-[Mobile Version](screenshots/NFT-Mobile.png)
-[Hover](screenshots/NFT-Hover1.png)
-[Hover 2](screenshots/NFT-Hover2.png)
-[Hover 3](screenshots/NFT-Hover3.png)


### Links

- [Solution URL](https://your-solution-url.com)
- [Live Site URL](https://devcloty.github.io/NFT-Preview-Card/nft.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- Mobile-first workflow


### What I learned

This project is great for practicing Flexbox and positions. Sometimes, placing an image where we want is quite a challenge!

Something I always forget is the ability to position an object with translate. And in this case I think it was the best way to position the view icon.

```css
.image-hover img {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate) - Translate behavior explanation


## Author

- GitHub - [DevCloty](https://github.com/DevCloty)
- Frontend Mentor - [DevCloty](https://www.frontendmentor.io/profile/DevCloty)

