# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size


- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to use a flexbox, but I still have trouble understanding it.
Otherwise, I'm really proud of how I used CSS. It's a little messy.

```html
<div class="big-box">
  <div class="left-container">
    <h1>Get <span>insights</span> that help your business grow.</h1>

    <p id="main-p">Discover the benefits of data analytics and make better decisions regarding revenue, customer
    experience, and overall efficiency.</p>

    <div class="stats-heading">
      <h2>10k+</h2>
      <h2>314</h2>
      <h2>12m+</h2>
      <p>companies</p>
      <p>templates</p>
      <p>queries</p>
    </div>

  </div>

  <div class="right-container">
    <img src="images/image-header-desktop.jpg" alt="">
  </div>
</div>
```
```css
.big-box {
  background-color: hsl(244, 38%, 16%);
  display: flex;
  margin: 5em;
  border-radius: 10px;
}

.left-container {
  max-width: 100%;
  height: auto;
  margin-left: 60px;
  margin-top: 40px;
}
.right-container {
  max-width: 100%;
  height: auto;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

I'll go back and refactor the codes and add in JavaScript. Right now, I'm happy with what I built. I need to figure out how to make the image fill the div because it's bothering me. I still have trouble with css grid and applying responsive web design and accessibility concepts. Learning is fun so I'm hoping to get these concepts down by next week.

### Useful resources

- https://css-tricks.com/snippets/css/a-guide-to-flexbox/ - This helped me for understanding some flexbox tricks
- https://blog.logrocket.com/flexbox-vs-css-grid/ - This is an awesome article which helped me learn when to use flexbox vs grid. I recommend this article to anyone learning modern CSS layouts.
