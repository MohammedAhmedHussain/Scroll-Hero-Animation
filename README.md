# Scroll-Driven Hero Animation

## Overview

This project is a scroll-based hero section animation built using **HTML, CSS, and JavaScript with GSAP**.
It demonstrates smooth UI interactions where elements respond dynamically to user scroll input.

The core idea is to create a visually engaging landing section where motion is controlled by scroll progress instead of time-based animations.

---

## Live Demo

https://mohammedahmedhussain.github.io/Scroll-Hero-Animation/

---

## GitHub Repository

https://github.com/MohammedAhmedHussain/Scroll-Hero-Animation

---

## Features

* Car moves horizontally from **left to right based on scroll**
* Smooth animations using **GSAP**
* Text **“WELCOME ITZFIZZ”** appears gradually with scroll
* Responsive layout with a clean gradient background
* Supports **mouse, keyboard, and touch interactions**
* Lightweight and performance-focused implementation

---

## Tech Stack

* HTML5
* CSS3
* JavaScript (Vanilla)
* GSAP (GreenSock Animation Platform)

---

## How It Works

* Scroll input is captured using:

  * Mouse wheel
  * Keyboard arrows
  * Touch gestures

* Scroll progress is converted into a value between **0 → 1**

* This progress value controls:

  * Car position using `translateX`
  * Text visibility using `opacity`
  * Subtle movement using `transform`

* GSAP is used to ensure:

  * Smooth transitions
  * Better performance
  * Clean animation handling

---

## Project Structure

```
Scroll-Hero-Animation/
│── index.html
│── F1-car.png
│── README.md
```

---

## Setup Instructions

1. Clone the repository:

   ```
   git clone https://github.com/MohammedAhmedHussain/Scroll-Hero-Animation.git
   ```

2. Open the project folder.

3. Run the project:

   * Open `index.html` in a browser
     OR
   * Use VS Code Live Server

---

## Performance Considerations

* Uses `transform` instead of layout-changing properties
* Minimal DOM manipulation
* Smooth easing with GSAP
* Optimized for responsiveness and fluid motion

---


## Author

Mohammed Ahmed Hussain
Email: [mohdahmedhussain.59@gmail.com](mailto:mohdahmedhussain.59@gmail.com)


