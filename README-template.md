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

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Firstly, I put all the texts in using HTML, using CSS flexbox to place the cards horizontally,I didnt do muchh with flexbox on this project mainly just the "display:flex;" property was used.I used CSS basic properties such as the margins, padding, font size and many more that was necessary. Most times i always outline the border of the container i'm working in to know how and what to do in my work and so that i dont work outsid emy container. Making my links resposive was kind of a challenge at first but using the "inherit" value made my work easy

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this project, it was the first time i had to use the "inherit" value, it was possible with a lot of brainstorming because at first i had no idea of how to make my link resposive with the attributes i was given to work with,so basically i learnt the use of my "inherit" value and how to make page resposnive with CSS.

To see how you can add code snippets, see below:
this is the first time i actually worked on linnk like and i'm extremely proud of this because all my video watching and reading online about is not in vain just took a little brainstorming.

```css
.proud-of-this-css {
  a {
    background-color: hsl(0, 0%, 95%);
    padding: 15px 25px;
    border-radius: 30px;
    text-transform: capitalize;
    font-size: 1.5em;
    text-decoration: none;
  }
  .sedanscard a {
    color: hsl(31, 77%, 52%);
  }
  .suvscard a {
    color: hsl(184, 100%, 22%);
  }
  .luxurycard a {
    color: hsl(179, 100%, 13%);
  }
  a:hover {
    border: 2px solid hsl(0, 0%, 95%);
    background-color: inherit;
    color: hsl(0, 0%, 95%);
  }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
