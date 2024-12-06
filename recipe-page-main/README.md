# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

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

## Overview
Static recipe website, flexible and mobile friendly.

### Screenshot

![Screenshot of webpage. Picture of Omelett, description, preparation time and ingredients of the recipe](https://github.com/ricardoacz/frontend-repo/blob/main/recipe-page-main/project-screenshot.png?raw=true)

### Links

- Solution URL: [https://github.com/ricardoacz/frontend-repo/tree/main/recipe-page-main](https://github.com/ricardoacz/frontend-repo/tree/main/recipe-page-main)
- Live Site URL: [https://rcfrontendmentor-recipe-page.netlify.app/](https://rcfrontendmentor-recipe-page.netlify.app/)

## My process

- I started building the html first for the main site and use sections to organize blocks of contents.
- I create my style from top to bottom, using and resuing classes to keep it simple.
- For mobile, I created new html lines that I would show and hide depending on the resolution of the client device.
- I used the reference photos to check proportions and I tested the mobile verion of the site on my own phone.

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

I reviewed how to float elements to create the list at the end for the nutrition values. I played around with html classes and containers to organize the content on the page when applying css to it.

Html elemenst to create the a line of nutrition property and value.

```html
<div class="nutrition-item">
          <div class="property">
            <span>Calories</span>
          </div>
          <div class="value">
            <span>277kcal</span>
          </div>
        </div>
```
CSS rules to keep the nutrition property and value in one line. I used the border property to better visualize each element when necessary.

```css
.nutrition {
    font-family: 'outfit', Arial, Helvetica, sans-serif;;
    clear: both;
}

.nutrition-item {
    /* border: 2px solid red; */
    width: 100%;
    height: 10px
    /* margin-bottom: 30px; */
}

.property {
    /* border: 2px solid blue; */
    height: 100%;
    width: 50%;
    color: rgb(119, 118, 116);
    float: left;
}

.value {
    /* border: 2px solid purple; */
    height: 100%;
    width: 50%;
    color: rgb(123, 78, 62);
    font-weight: 600;
    float: right;
}
```

### Continued development

I want to practice more with media queries to adjust the elements to fit better when viewing the site on a tablet in vertical mode.

### Useful resources

- [CSS Media Squeries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) - This helped me to write the media queries for the mobile view.

## Author

- Frontend Mentor - [@ricardoacz](https://www.frontendmentor.io/profile/ricardoacz)

