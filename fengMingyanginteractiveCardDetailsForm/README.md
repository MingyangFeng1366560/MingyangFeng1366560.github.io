# Welcome to this week's project! 👋

## Folder Structure

firstnameLastnameInteractiveCardDetailsForm
├── index.html
├── design/
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   └── mobile-design.jpg
├── images
│   ├── bg-card-back.png
│   ├── bg-card-front.png
│   ├── bg-main-desktop.png
│   ├── bg-main-mobile.png
│   ├── card-logo.svg
│   └── favicon-32x32.png
└── css/
└── core.css
└── theme.css
└── styles.css

## Colors

```CSS
    --white: hsl(0, 0%, 100%);
    --light-grayish-violet: hsl(270, 3%, 87%);
    --dark-grayish-violet: hsl(279, 6%, 55%);
    --very-dark-violet: hsl(278, 68%, 11%);
    --purple-1: hsl(249, 99%, 64%);
    --purple-2: hsl(278, 94%, 30%);
    --button-shadow-hover: hsl(278, 94%, 30%, 0.4);
    --button-shadow-active: hsl(278, 94%, 30%, 0.6);
    --red: hsl(0, 100%, 66%);
```

## Font

-   Family: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk)
-   Weights: 500 and 700

## To do this challenge, you need a good understanding of:

1.  Responsive Design (typography and media)
2.  :before and/or :after pseudo selectors
3.  Position absolute and position relative
4.  CSS Transition
5.  CSS Animation

## Challenge:

-   For the purple background gradient image, you can only use the **picture** and **img** elements

-   (Check the design folder for more information) - in the desktop version, the purple image should take
    only 40% of the width. It should **NEVER** stop growing regarless of the screen size

-   You can **ONLY** use background-image for the "card-logo.svg" in the images/ folder
    Do not forget about the different CSS properties you can use for the background-image:

        -   background-repeat
        -   background-position

-   The height of main elements in the page should be the same height as the **VIEWPORT**. Meaning, you cannot scroll down and the content is always
    presented in the same space as the **VIEWPORT** only

-   For better browser performance, it is better to use **transform** and **opacity** to change your elements'
    states either for animation or transition behaviours

-   Form max-width is 750px

-   Credit cards - at 64em breakpoint (Make sure to use rem units):

    -   Max-width: 500px
    -   Min-width: 400px
    -   Max-height: 294px

## The only @media query allowed for the page

-   Start coding at 320px

-   @media 64em - which is equivalent to 1024px

## Media queries for Typography

-   You can make your own decision. The only requirement is that there must not be more than **TWO** media queries for typography

## Research Skills are being tested

### Form element

-   appearance: textfield;
-   border-block-start-color
-   border-block-end-color
-   border-left-color
-   border-right-color

### Animations

-   CSS Animations
-   animation-name
-   animation-duration
-   animation-timing-function
-   animation-delay
-   animation-fill-mode: forwards

### Tips:

-   **REMEMBER** the browser is responsive by default, start working at 320px

-   **START** with 320px and layout **ALL** the elements for HTML with no styles. Everything should be
    a block under the other as that is the way for mobile. Then apply styles and start changing the screen size to check when the design breaks

**Have fun building!** 🚀
