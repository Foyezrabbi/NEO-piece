# Planets fact site

![Design preview for the Planets fact site coding challenge](./src/assets/preview.jpg)

## Table of contents

-   [Overview](#overview)
    -   [Intro](#intro)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [Features](#features)
-   [Setup](#setup)
-   [Useful resources](#useful-resources)

## Overview

### Intro

NEO-Piece is an interactive web app designed to bring the wonders of the cosmos to your fingertips. This modern orrery goes beyond the traditional models by offering a dynamic, embedded experience that allows users to explore not only planets but also Near-Earth Objects (NEOs) such as asteroids, comets, and even Potentially Hazardous Asteroids (PHAs). With NEO-Piece, you can immerse yourself in the intricacies of celestial mechanics, gaining insights into the movement and characteristics of these fascinating objects that inhabit our solar neighborhood.

### The challenge

Since a mechanical model of the solar system was presented to Charles Boyle, 4th Earl of Orrery, in 1713, such models have been referred to as orreries. The first orreries were physical models, but today we can use numerous tools to create virtual orreries that have many more features than their ancient mechanical counterparts. Your challenge is to create an interactive orrery web app that is embedded in a webpage and displays celestial bodies such as planets, Near-Earth Asteroids, Near-Earth Comets, and Potentially Hazardous Asteroids.

### Links

-   [LIVE PREVIEW](https://planets-tediko.netlify.app/) to check my solution.

## My process

### Built with

-   ReactJS
-   Webpack
-   Styled-components
-   Mobile first
-   Semantic HTML5 markup
-   JavaScript
-   Flexbox
-   Grid
-   Framer Motion API

### Features

-   I used **_ReactJS_** library to create an app. React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.
-   I tried to write a project using **_styled-components_** library. Styled Components are one of the new ways to use CSS in modern JavaScript. It is the meant to be a successor of CSS Modules, a way to write CSS that's scoped to a single component, and not leak to any other element in the page. Also allows you to write plain CSS in your components without worrying about class name collisions.
-   The first time I used **_Prettier_**. Prettier is an opinionated code formatter. It removes all original styling and ensures that all outputted code conforms to a consistent style.
-   To animate the pages transitions and mobile-menu animations I used **_Framer Motion API_**. Framer Motion is an open source, production-ready library that's designed for creating creative animations.
-   Added `counter()` function for my _pseudo-elements_ content in _Tab button_. **CSS counters** let you adjust the appearance of content based on its location in a document. For example, you can use counters to automatically number the headings in a webpage.
-   The **_solar system_** was recreated from this great [Codepen](https://codepen.io/kowlor/pen/ZYYQoy) created by _Malik Dellidj_. It's all based on div rotation with _pseudo-elements_ inside that contains the images of the planets.
-   Implemented **_defer_** to my script tag. The defer attribute tells the browser not to wait for the script. Instead, the browser will continue to process the HTML, build DOM. The script is fetched asynchronously, and it’s executed only after the HTML parsing is done.
-   Implemented `prefers-reduced-motion` CSS media feature which is used to detect if the user has requested that the system minimize the amount of non-essential motion it uses. Prevent animations in brief.
-   `:focus-visible` pseudo class. This selector only indicate focus when it is helpful to the user - such as in cases where the user interacts with the page via a keyboard or some other non-pointing device. It isn't supported by Safari yet, but there is simple [workaround](https://stackoverflow.com/questions/31402576/enable-focus-only-on-keyboard-use-or-tab-press).
-   Tried to create more accessible mobile navigation. Used the `aria-expanded` and `aria-controls` attributes.
-   To create this project I used webpack. More specifically i used `laravel mix` which is a wrapper for webpack and targets the 80% usecase.

## Setup

To run this project, clone it and install it locally using npm:

```
$ git clone git@github.com:Foyezrabbi/NEO-piece.git
$ cd NEO-piece
$ npm install
```

Use npm to build and compile assets in a local environment:

```
$ npm run build
```

Watch assets for changes and rebuild your bundle each time you update a file with:

```
$ npm run mix-watch
or
$ npx mix watch
```

## Useful resources

-   [DOCS - ReactJS](https://reactjs.org/)
-   [VIDEO - ReactJS tutorial by The Net Ninja](https://www.youtube.com/watch?v=j942wKiXFu8&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d)
-   [LINK - Styled-components](https://styled-components.com/)
-   [LINK - Prettier](https://prettier.io/)
-   [LINK - Framer Motion API](https://www.framer.com/api/motion/)
-   [VIDEO - CSS Counters](https://youtu.be/0gayskscLY4?t=355)
-   [DOCS - CSS Counters](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Lists_and_Counters/Using_CSS_counters)
-   [LINK - Solar system](https://codepen.io/kowlor/pen/ZYYQoy)
-   [LINK - async/defer](https://flaviocopes.com/javascript-async-defer/#the-position-matters)
-   [LINK - webpack](https://laravel-mix.com/docs/6.0/what-is-mix)
