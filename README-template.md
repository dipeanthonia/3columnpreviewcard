# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/dipeanthonia/3columnpreviewcard.git](https://github.com/dipeanthonia/3columnpreviewcard.git)
- Live Site URL: [https://dipeanthonia.github.io/3columnpreviewcard/](https://dipeanthonia.github.io/3columnpreviewcard/)

## My process

Firstly, I put all the texts in using HTML, using CSS flexbox to place the cards horizontally,I didnt do muchh with flexbox on this project mainly just the "display:flex;" property was used.I used CSS basic properties such as the margins, padding, font size and many more that was necessary. Most times i always outline the border of the container i'm working in to know how and what to do in my work and so that i dont work outsid emy container. Making my links resposive was kind of a challenge at first but using the "inherit" value made my work easy

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

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

## Author

- Frontend Mentor - [@dipeanthonia](https://www.frontendmentor.io/profile/dipeanthonia)

