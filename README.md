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
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

Added goals added by Trevor Merrick

- Use :focus to highlight buttons for better visibility/accessability

### Screenshot

![](/design/screenshot-mobile.png)
![](/design/screenshot-desktop.png)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/mobile-first-card-component-using-css-gridareas-and-sass-with-mixins-6-wKX4elJ)
- Live Site URL: [Live Site URL](https://tmerrick17.github.io/profile-card-component/)

## My process

With the HTML basic content provided, worked on:
  - assigning CSS class names using the BEM method
  - used SASS (7-1 file structure, I only needed to use 4 modular folders in this project)
  - creating variables in SASS for color schemes, fonts, font-sizes, etc
  - adding Google Fonts provided
  - reset CSS to give all browsers a common starting point

Next worked on:
  - built mobile first
  - Figuring out where to use Flex vs Grid (used both)
  - Used grid-areas for the "card" class content
  - Worked on media query for tablet/desktop
  - Worked on adding the circles in the background with the svg's provided

Finally worked on:
  - Worked on accessibility features for footer links
  - Finishing touches like smaller mobile view and making the card still looked good

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid areas (grid-template-areas: "grid-areas here...")
- Mobile-first workflow
- @mixins

### What I learned

This time using Sass and the 7-1 modular structure for Sass came easier.  I also created a file system with some of the basic Sass code in there so that I could get started on this project faster.  

Using CSS grid-areas was great to work on. It took me a while to figure out part of it because it had an overlapping picture over a background image.  I also checked out some other solutions from Frontend Mentor and none of them used CSS grid-areas; they used position: relative and absolute.

I also used an @mixin for the first time.  I had some Sass code that was in 3 different classes but they were related and so I created an @mixin to simply shorten the amount of code I would need to create for all three classes.

### Continued development

In the future I want to keep using @mixins and eventually @functions.  Also I want to continue using grid-areas.  Javascript though is the real big thing I need to keep working on.

### Useful resources

- [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - I watch his videos over and over again for great CSS/Sass tips and tricks.

## Author

- Website - [Trevor Merrick](https://trevormerrick.com)
- LinkedIn - [@trevormerrick](https://www.linkedin.com/in/trevormerrick/)
- GitHub - [@tmerrick17](https://github.com/tmerrick17/)
- Frontend Mentor - [@tmerrick17](https://www.frontendmentor.io/profile/tmerrick17)
- Twitter - [@tcmerrick](https://www.twitter.com/tcmerrick)

