## Frontend Mentor - QR code component solution

This is a solution to the QR code component challenge on Frontend Mentor [https://www.frontendmentor.io/solutions/qr-code-solution-DHVUIFg7J](https://www.frontendmentor.io/solutions/qr-code-solution-DHVUIFg7J). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

* [Overview](#overview)
    * [Screenshot](#screenshot)
    * [Links](#links)
* [My process](#my-process)
    * [Built with](#built-with)
    * [What I learned](#what-i-learned)
* [Author](#author)

## Overview

### Screenshot

[Add a screenshot of your solution here](../qr-code-component-main/design/final_desing_by_erceppi.png)

### Links

- Solution URL: [Add solution URL here](https://erceppi.github.io/QR-code-component)

## My process

### Built with

- HTML5
- CSS
- Flexbox

### What I learned

In this project, I practiced using flexbox to achieve a layout for the QR code and text content. While the current code uses justify-content: space-around, other flexbox properties can be used to achieve different layouts. I also explored responsive design techniques to ensure the component looks good on different screen sizes.

Here's an example of the flexbox properties used in this code:
```css
.container {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    background-color: hsl(0, 0%, 100%);
    margin: 10rem 5rem;
    padding: 2rem;
    border-radius: 2rem;
    max-width: 48rem;
}

.container__qr {
    max-width: 100%;
    border-radius: 1.5rem;
}
```

In this example, the justify-content: space-around property distributes the QR code image and text content with even space between them along the main axis (which is the vertical axis in this case due to flex-direction: column).

## Author

* Website - [Claudio Ceppi](https://github.com/erceppi/)
* Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/erceppi)

I hope this README provides a clear overview of my QR code component solution!