# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)
- [Questions](#questions)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size - 375px - 1440px
- See hover and focus states for interactive elements - I only added a hover state based on the colors provided in the style guide.

### Screenshot

(images/preview-card%201440.png)
(images/product%20preview%20Chrome%20375px.JPG)
(images/product%20preview%20Firefox%20375px.JPG)

### Links

- Solution URL Vercel: https://product-preview-card-nu-one.vercel.app/
- Solution URL Netlify: https://product-preview-hill.netlify.app/
- Github Repo: https://github.com/webdevhill/product-preview-card

### Built with

- CSS custom properties
- Flexbox - I tried to keep it DRY as possible
- Mobile-first workflow - built at 375px break at 768px

### What I learned

This is my second frontendmentor challenge. I did this one mobile first with flexbox. The code is fairly clean at 375px. I do mix px and rem. After the media query for 768 and above I started "eyeballing" some of the individual elements with padding and margins. I would like to see how my solution holds up to the design when submitted.

### Continued development

Their has to be a better way than "eyeballing" padding and margins. Possibly a combination of grid and flexbox? I am not certain.

## Author

- Frontend Mentor - [@webdevhill](https://www.frontendmentor.io/profile/webdevhill)

## Acknowledgments

- Hey @vcarames. It's been 3, 4 months already? These are really fun to me. But they are deceptively simple. Position, margins, and padding is somewhat trick to get px perfect. I want tosubmit to see how it holds up to the original. I really should try to do one a week along with my other projects. How are you?

### Questions

I had to an extra 180px when I deployed the app on Vercel and Netlify. Now it looks completely "wrong" with the extra padding when I open it with live server in Visual Studio Code.

Why is that? The positioning of the primary container is completely different on the local host compared to Vercel or Netlify deployment. And just for fun I include a mozilla Firefox browser screenshot @375px to show the diference crossbrowser.
