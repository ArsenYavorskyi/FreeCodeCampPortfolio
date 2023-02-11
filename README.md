# FreeCodeCamp - Portfolio Final Project

This is a final project for the FreeCode Camp ["Responsive Web Design"](https://www.freecodecamp.org/learn/2022/responsive-web-design/) course.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

<p align="center">
  <img src="img/Снимок экрана 2023-02-11 в 13.22.40.png" alt="Project Photo"/>
</p>

### Links

-   Live Site URL: [https://yazdrahobycha.github.io/Not-a-real-portfolio/](https://yazdrahobycha.github.io/Not-a-real-portfolio/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   FontAwesome icons library

### What I learned

Despite the perception of this project being relatively straightforward, there were some challenges that arose during its development. One instance was creating a hover animation utilizing the before and after pseudo-elements, which required a bit of extra effort to get right:

<details>
<summary>Implementation of `hover` elements</summary>

```css
.btn:hover i {
    transform: translateX(5px);
}

.btn:hover {
    background-color: var(--color-red);
}
```

</details>

Additionally, this project marked my first experience integrating the "FontAwesome" icon library onto the website, which proved to be a learning experience in itself as I navigated through the process of implementation.

<details>
<summary>FontAwesome library implementation</summary>

```html
<section id="contact" class="contact">
    <h2 class="contact__title">Let's work together...</h2>
    <p><i>How do you take your coffee?</i></p>
    <div class="contact__links">
        <a href="#" target="_blank" class="contact__link">
            <i class="fab fa-facebook-square"></i>
            Facebook
        </a>
        <a href="#" target="_blank" class="contact__link">
            <i class="fab fa-github"></i>
            GitHub
        </a>
        <a href="" target="_blank" class="contact__link">
            <i class="fab fa-twitter"></i>
            Twitter
        </a>
        <a href="mailto:ars.yar24@gmail.com" class="contact__link">
            <i class="fa-solid fa-envelope"></i>
            Email
        </a>
        <a href="mailto:ars.yar24@gmail.com" class="contact__link">
            <i class="fa-solid fa-bell"></i>
            Ring Me
        </a>
    </div>
</section>
```

</details>

### Continued development

- Enhance proficiency in utilizing icons from external libraries
- Streamline the coding process to achieve maximum efficiency
- Enhance expertise in managing responsive images.

## Author

- Instagram - [@yazdrahobycha](https://instagram.com/yazdrahobycha?igshid=YmMyMTA2M2Y=)
- Telegram - [Орсен](https://t.me/yazdrahobb)