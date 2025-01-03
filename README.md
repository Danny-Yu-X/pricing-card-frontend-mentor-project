# Single Price Grid Component Project

This is my solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./desktopVersion.png)

## My process

### Built with

- HTML, CSS, JavaScript
- CSS Flexbox
- Mobile-first workflow

### What I learned

While working through this project, some of my major learnings were understanding how to utilize CSS Flexbox to properly align the bottom section of the card. I also learned how to implement a button that interacts with the user when clicked upon. Styling the button was very interesting as I was able to make it sort of pop up when hovering over it.

```html
<h1>Some HTML code I'm proud of</h1>
<button onclick="alertUser()">Sign Up</button>
```
```css
button:hover {
  cursor: pointer;
  background-color: #A9C42D;
  transform: scale(1.02);
}
```
```js
function alertUser() {
  alert('Hey, you clicked the button!');
}
```

### Continued development

In future projects like this one, I plan to make clickable elements more interactive. Instead of just a simple alert to the user, I can maybe add a redirect link embedded in a button that redirects users to another page that they want. This means that I would need to incorporate more JavaScript into my project. I will also explore web application frameworks and utilize their tools to further improve my next projects.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me reference important code syntax.

## Author

### Danny Yu
