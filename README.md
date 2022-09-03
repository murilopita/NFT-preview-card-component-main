# Frontend Mentor - Stats preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

<br>
<br>

# Table of contents

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


<br>
<br>

# Overview
<br>

## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size.
- See hover states for interactive elements.

<br>

## Screenshot

<br>

<h3 align='center'>Desktop Version</h3>

<br>

<img src="images/reademe_img/screenshot-desktop.png">

<br>
<br>

<h3 align='center'>Mobile Version</h3>

<img src="images/reademe_img/screenshot-mobile.png">

<br>
<br>

## Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/nft-preview-card-component-70-J9G0kGb)
- Live Site URL: [Live Site at Vercel](https://nft-preview-card-component-main-seven-silk.vercel.app/)

<br>
<br>

# My process

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Design

<br>

## What I learned

In this challenge, I learned how to use the ':hover' and your properties and the pseudo-element '::after'. I used them to bring an interactive element effect over the main image.

<h2 align='center'>Code</h2>

```css
.card-img::after{
    content: url(images/icon-view.svg);
    background:hsla(178, 100%, 50%, 0.5);
    position: absolute;
    inset: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: all 0.25s ease;
    width: 90%;
    left: 5%;
    border-radius: 0.5rem;
}

.card-img:hover::after{
    opacity: 1;
}
```
<h2 align='center'>Preview</h2>

<br>

<img src="images/reademe_img/screenshot-active.png">

<br>

## Continued development

I'll keep practicing more about pseudo-element and pseudo-class 'cause I had some difficult to make the hover effect in the main image.

<br>

## Useful resources

- [MDN WEB DOCS -> ::after](https://developer.mozilla.org/pt-BR/docs/Web/CSS/::after)
- [MDN WEB DOCS -> :hover](https://developer.mozilla.org/pt-BR/docs/Web/CSS/:hover)

<br>

# Author

- GitHub - [murilopita](https://github.com/murilopita/NFT-preview-card-component-main)
- Frontend Mentor - [@murilopita](https://www.frontendmentor.io/profile/murilopita)


<br>

<h3 align='center'> It's have been a pleasure to be part of this community!</h3> 