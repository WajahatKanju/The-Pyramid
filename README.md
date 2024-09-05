# Pyramid Animation with Sun and Shadow

This project showcases an animated pyramid with a sun rising above it and casting a shadow on the ground, all done using HTML and CSS.

## Demo

You can view the pyramid animation in action [here](https://s6.ezgif.com/tmp/ezgif-6-23ce495018.gif).  
*(![Animation](https://s6.ezgif.com/tmp/ezgif-6-23ce495018.gif))*

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Customization](#customization)
- [License](#license)

## Introduction

This is a simple CSS animation project that illustrates how to create a dynamic scene featuring:
- A pyramid with two sides
- A sun that rises and sets
- A shadow cast by the pyramid as the sun moves
- A sky and ground that change color as part of the animation

The animation uses `@keyframes` to smoothly animate elements like the sun, pyramid shading, shadow, and sky.

## Technologies Used

- **HTML5** for structure
- **CSS3** for styling and animations

## Setup

To get the project up and running locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/WajahatKanju/The-Pyramid
    ```

2. Navigate into the project directory:
    ```bash
    cd the-pyramid
    ```

3. Open the `index.html` file in your browser to see the animation:
    ```bash
    open index.html
    ```

## Usage

Simply open the `index.html` file in a modern web browser. The pyramid and sun animation should automatically start playing.

## Code Overview

### HTML Structure

The basic structure of the HTML file includes a container for the animation:

```html
<div class="frame">
    <div class="center">
        <div class="circle">
            <div class="sky"></div>
            <div class="sun"></div>
            <div class="side-left"></div>
            <div class="side-right"></div>
            <div class="shadow"></div>
            <div class="ground"></div>
        </div>
    </div>
</div>
```

### CSS Structure

The animations are driven by CSS` @keyframes`. For example, the sun's movement is controlled by the `sun-goes-down` keyframe:

```css
@keyframes sun-goes-down {
  0% {
    background: #F57209;
    transform: rotate(-70deg);
  }
  30% {
    background: #FFEF00;
    transform: rotate(-28deg);
  }
  100% {
    background: #F57209;
    transform: rotate(70deg);
  }
}

```

The pyramid's shadow and color transitions are also controlled with keyframes.

### Customization

You can easily customize the animation by changing the following:

