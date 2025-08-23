# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page


### Screenshot

![Screenshot of Mobile Version](/assets/images/Screenshot%20Mobile%20Version.png)


![Screenshot of Desktop Version](/assets/images/Screenshot%20Desktop%20Version.png)


### Links

- Solution URL: [Solution](https://github.com/RoxySash/Results-Summary-Component-Main.git)
- Live Site URL: [Live Site](https://roxysash.github.io/Results-Summary-Component-Main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow



### What I learned

I learned how to get hsla value to match the designs. It was fun a little confusing at first but reading through some mdn docs really put it in perspective.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
:root {
  --fs: 1rem; /* 18 px */
  --fxs: 0.856rem;
  --fs-large: 3.5rem;
  --fs-small: 1.4rem;
  --fs-medium: 1.1rem;
  --ff: "Hanken Grotesk", sans-serif;

  --lightred: hsl(0, 100%, 67%);
  --orangeyyellow: hsl(39, 100%, 56%);
  --greenteal: hsl(166, 100%, 37%);
  --cobaltblue: hsl(234, 85%, 45%);

  --lightred-alpha: hsla(0, 100%, 67%, 0.1);
  --orangeyyellow-alpha: hsla(39, 100%, 56%, 0.1);
  --greenteal-alpha: hsla(166, 100%, 37%, 0.1);
  --cobaltblue-alpha: hsla(234, 85%, 45%, 0.1);
  /* Gradients */

  --lightslateblue-bg: hsl(252, 100%, 67%);
  --lightroyalblue-bg: hsl(241, 81%, 54%);

  /* hsla */

  --lightslateblue-bg-tr: hsla(252, 100%, 67%, 1);
  --lightroyalblue-bg-tr: hsla(241, 81%, 54%, 1);

  --violetblue-circle: hsla(256, 72%, 46%, 1);
  --persianblue-circle: hsla(241, 72%, 46%, 0);

  /* Neutral */

  --white: hsl(0, 0%, 100%);
  --paleblue: hsl(221, 100%, 96%);
  --lightlavender: hsl(241, 100%, 89%);
  --darkgrayblue: hsl(224, 30%, 27%);

  --lightlavender-tr: hsla(241, 100%, 89%, 0.9);
  --darkgrayblue-alpha: hsla(224, 30%, 27%, 0.5);
}
```


### Continued development

This challenge has a little JS challenge however I will confront it another time. I need to work on these faster and I will do more challenges.


## Author

- Frontend Mentor - [@RoxySash](https://www.frontendmentor.io/profile/RoxySash)
- Bluesky - [@RoxaneDev](https://bsky.app/profile/roxanedev.bsky.social)


