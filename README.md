# Frontend Mentor — Order Summary Card

A solution to the [Order Summary Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [Features](#features)
  - [Improvements](#improvements)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View hover states for all interactive elements
- See the optimal layout depending on their device screen size

### Screenshot

![My Solution](/my-solution.png)

### Links

- Solution URL: https://github.com/kevinbdx35/frontendmentor-challenges-1
- Live Site URL: https://kevinbdx35.github.io/frontendmentor-challenges-1-newbie/

## My Process

### Built With

- Semantic HTML5
- CSS custom properties
- Flexbox
- Mobile-first responsive design

### Features

- Hover and focus states on all interactive elements
- Fully responsive (375px mobile → 1440px desktop)
- Smooth CSS transitions

### Improvements

- `<header>&nbsp;</header>` → `<div class="bg-pattern" aria-hidden="true">` (correct semantics)
- `<h3>` → `<h1>` (page heading hierarchy)
- `<small id="price">` → `<span class="plan-price">` (correct semantic element)
- `.btn:focus { outline: 0 }` → `focus-visible` with a visible outline
- `body { height: 100vh; overflow: hidden }` → `min-height: 100vh`
- Removed fixed `.card-title { height: 20px }`
- Added CSS custom properties (7 variables)
- Renamed `.author` → `.plan-box` for clarity
- Removed `X-UA-Compatible` meta tag

## Author

- Website — [Kévin B.](https://kevinbdx35.github.io/kevinb/)
- Frontend Mentor — [@kevinbdx35](https://www.frontendmentor.io/profile/kevinbdx35)

## License

MIT
