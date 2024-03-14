# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/solutions/httpsgithubcomdanielfernandezdjsociallinksprofilemainfonten-Aky9iFXxby). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [ https://github.com/danielFernandezDj/social-links-profile-main--fontendmentor--3.gitsemantic-html5-marhttps://github.com/danielFernandezDj/social-links-profile-main--fontendmentor--3.git ]
- Live Site URL: [ https://danielfernandezdj.github.io/social-links-profile-main--fontendmentor--3/ ]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learn how to separate an image from there original control and attach that to the screen without move the image
out of the section control.

This is the code I use to archive that:

```html
<body>
  <section id="main-container">
    <div><a href="https://www.linkedin.com/feed/" target="_blank">
        <img src="./assets/images/image-omelette.jpeg" alt="Banner Image">
      </a>
    </div>
  </section>
```
```css
@media screen and (max-width: 375px) {
    #main-container {
        margin-bottom: 0;
        padding: 30px;
        max-width: none;
        border-radius: 0;
        padding: 25px;
    }

    img {
        width: 100%;
        border-radius: 0;
        position: absolute;
        left: 0;
        top: 0;
    }
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

## Author

- Website - [Daniel Fernandez](https://www.linkedin.com/in/daniel-fernandez-953432122/)
- Frontend Mentor - [@danielFernandezDj](https://www.frontendmentor.io/profile/danielFernandezDj)
- Twitter - [@Danielf9728](https://twitter.com/Danielf9728)

