# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot



Desktop Design:

![desktop-design](/Users/janell/Desktop/Frontend Mentor/3-column-preview-card-component-main/desktop-design.png)

Mobile Design:

![mobile-design](/Users/janell/Desktop/Frontend Mentor/3-column-preview-card-component-main/mobile-design.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Plain HTML / CSS
- Flexbox
- Responsive Design (Mobile Friendly!)

### What I learned

While working on this challenge, all was going well until I went to check the mobile view.. Unlike the desktop version, which was displaying correctly, the mobile view was not centered on the screen. After first assuming the issue may lie with my CSS width, padding, or margin properties I had no luck and decided to search the internet for the answer.

After a minute of searching I discovered [this thread on StackOverflow](https://stackoverflow.com/questions/17756649/disable-the-horizontal-scroll). After briefly reading the original poster's issue, I saw I had the same problem. Luckily, I applied the first response to my code and it instantly solved my issue! (Thanks, Omar!)

```css
html, body {
    max-width: 100%;
    overflow-x: hidden;
}
```
### Continued development

Im happy with the way my code turned out and seems to be an exact replica of the challenge provided from FrontEnd Mentor. However when resizing my display window on desktop, I notice the *'Learn More'* buttons are not always in line with each other. I'd like to better understand why that is.

### Useful resources

- [StackOverflow](https://stackoverflow.com/) - This website was incredibly effective at helping me solve my overflow issue (ironic, I know.). I will definitely revisit this site in the future.



## Author

- Website - [AJ DeMarco](https://www.e-flexsocial.com)

  

## Acknowledgments

Thanks to Omar, a user at StackOverflow.com for providing the answer to my overflow issue! 
