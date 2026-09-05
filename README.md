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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](images/screenshot.png)



### Links

- Solution URL: [Code URL](https://github.com/aknb-ii/Blog-Preview-Card)
- Live Site URL: [Live Demo](https://aknb-ii.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In HTML I learnt about the purpose of the article tag and how its useful for SEO and in CSS i learnt a concept of setting margin and padding to 0 to alter default inputs and to use of box sizing to prevent unwanted expansion of an already stated dimension

```html
<article class="blog-preview">
    <img class="blog-thumbnail" src="images/illustration-article.svg" alt="">
    <p class="label">Learning</p>
    <p>Published 21 Dec 2023</p>
    <h2>HTML & CSS foundations</h2>
    <p class="description">These languages are the backbone of every website, defining structure, content, and presentation.</p>
    <div class="authour-preview" >
      <img class="authour-avatar" src="images/image-avatar.webp" alt="Authour's Image">
      <p>Greg Hooper</p>
    </div>

  </article>
```
```css
*{
  box-sizing: border-box;
  margin: 0; padding: 0;
}
```


### Continued development

- More ways to optimize coding to prevent unnecessarily long and complex code just like the ":root" in CSS.

### Useful resources

- [SuperSimpleDev](https://www.youtube.com/results?search_query=supersimpledev+html%2B+css+course) - This video really helped with learning HTML+ CSS.
- [Programming with Mosh](https://www.youtube.com/results?search_query=programming+with+mosh+html+course) - This is one of the videos i watched to learn HTML.


### AI Collaboration
- Gemini: I used Gemini to remember some forgotten elements and styling, I asked questions whenever I felt stuck. I also used it to understand basic useful git commands to upload my code to GitHub. It worked very well for me.


## Author

- Frontend Mentor - [@TundeTheGreat](https://www.frontendmentor.io/profile/TundeTheGreat)
- Twitter - [@aknb_ii](https://www.twitter.com/aknb_ii)


## Acknowledgments

I thank God for his Grace.
Special thanks to SuperSimpleDev & Programming with Mosh on YouTube for their free videos on HTML & CSS.
