# X-men players

This is a sixth practice of mine Frontend studies, a personal challenge to improve mine coding skills building own projects. 

## Table of contents

- [X-men players](#x-men-players)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Feed Back](#feed-back)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![](/src/assets/screenshot.png)

### Links

- Code URL: [GitHub](https://github.com/Akherox/x-men-players)
- Live Site URL: [GitHub Pages](https://akherox.github.io/x-men-players/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Responsive CSS

### What I learned

How to use var() function and @keyframes.

```css
.lista-de-personagens .personagem.selecionado {
    height: 205px;
    border: 8px solid;
    margin: -8px;
	border-image: conic-gradient(from var(--angle), var(--c2), var(--c1) 0.1turn, var(--c1) 0.51turn, var(--c2) 0.51turn) 1;
	animation: borderRotate var(--d) linear infinite forwards;
}

@keyframes borderRotate {
	100% {
		--angle: 420deg;
	}
}
```

### Feed Back

I`m going to improve using var() function on css.

### Useful resources

- [Example resource 1](https://github.com/Akherox/marvel-pvp) - This helped me for it was an old project that i made.
- [Example resource 2](https://github.com/Akherox/pokedex-complex) - This is another project that helped me.

## Author

- Website - [Bryan Bravo](https://www.linkedin.com/in/alex-bravo-008-mk)
- GitHub Profile - [@Akherox](https://github.com/Akherox)
