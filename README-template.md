# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
    - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://ryyhardy.github.io/frontend-mentor-blog-preview-card/](https://ryyhardy.github.io/frontend-mentor-blog-preview-card/)

## My process

### Built with

- Semantic HTML5
- CSS
- Flexbox (a little bit)

### What I learned

I learned how to use the cascade of CSS to my advantage. When I was going through this challenge,
I wasn't happy with how the text elements were organized. Using what I knew about specificity
helped me clean up the CSS a bit and move on to other parts of the challenge.

For example, I used the "p" selector as a default for the paragraphs, and I used classes to overwrite
it when needed.

```css
.blog-card p {
  font-size: 0.9rem;
  line-height: 1.6em;
  color: var(--gray);
}

.blog-card .date {
  color: var(--black);
  font-weight: 500;
  font-size: 0.8rem;
  padding-bottom: 1em;
}

```

### Continued development

I want to take advantage of the way CSS works rather than working against it. The cleanest CSS
I've seen follows those principles, and I would like to learn more about how to do that.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
