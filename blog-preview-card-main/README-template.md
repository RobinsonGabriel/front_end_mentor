# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS animations
- Mobile-first workflow


### What I learned

I don't think I've ever really had to use a pseudoclass for anything, but I can appreciate their use a bit better after
playing with them for the :hover and :focus components for this project. I didn't realize how much the browser can do for you
in terms of making the design more responsive without having to break out some JS script, which cuts down the effort I need
to expend and makes it feel a bit easier to target specific components.


```css
.entry-author:hover, .entry-author:focus{
    border-radius: 5px;
    background-color: rgb(255, 217, 0);
   
}

h2:hover, h2:focus{
    color: rgb(255, 251, 0);
}

.entry-category:hover, .entry-category:focus{
    
    animation: mymove .15s 1 forwards;
}
@keyframes mymove {
    from {color: black;}
    to {color: azure;}
  }
```

The above is what I added with those particular pseudo classes. The keyframe animation was mostly me working around a bit of a personal
dislike of how the element looked shifting from black to not black. My main reason for adjusting it was partly stylistic, but also
for comfort: since I wanted to stick to some type of white/off white to stay as close to the color pallet as possible I wanted to also
make it as not jarring as possible. Alternatively I could have changed the opacity of the text only/added a border if that was deemed
too excessive. It was also a reason to just play with something a bit more interesting.


**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I do want to try using SASS or similar soon if I keep playing with CSS, partly because the CSS file feels way too big,
 I may take a second pass at it in the future and see if I can take out any redundant/unused rules, but otherwise it 
 just seems excessive for a single element. 
 I do appreciate that if this were in a layout that had, say, 10 of these cards, 
 it would scale fine as all of the elements have descriptive classes. That said I just want to make sure I'm keeping it tight for both
 performance concerns and readability.

### Useful resources

(https://developer.mozilla.org/en-US/docs/Web/CSS) -- Mozilla's documentation around any web-based coding is still some of the
most intuitive I can think of, wish it was shown to me as an undergraduate as it definitely helped quite a bit.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@RobinsonGabriel](https://www.frontendmentor.io/profile/RobinsonGabriel)


**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
