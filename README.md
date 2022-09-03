# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

- I am still learning the very basic of CSS. I frequently struggle with centering the card in the center of the page. This time I learnt that in order to center the card. I need to do this: 
```css
body {
  display: flex;
    align-items: center;
}

.card{
  margin: 0 auto;
}
```

- At some point I could not figure out why the color of .number could change.
Instead of doing this:
  ```css
    .number{
      font-size: 18px;
      font-weight: 700;
      color: var(--Very-dark-desaturated-blue);
      margin-bottom: 5px;
}
```

I need to do this:
```css
footer p.number{
    font-size: 18px;
    font-weight: 700;
    color: var(--Very-dark-desaturated-blue);
    margin-bottom: 5px;
}
```

### Continued development

- Cleaner HTML
  I need to plan more before start to code my html file. It would be easier to style it with css later on.

### Useful resources

- [Profile Card Component | Frontend Mentor Challenge | Day 4](https://www.youtube.com/watch?v=NZpG9EBKYWc) - Mr. Coder provides a concrete demonstraion of completing this challenge. As a beginner, I find it really useful to follow his process step by step.


## Acknowledgments
I followed the instruction of Mr. Coder's video (see [Useful resources](#useful-resources)) to complete this challenge. Hopefully once I get more comfortable with what I have learnt, I can take the challenge all by myself!🙌
