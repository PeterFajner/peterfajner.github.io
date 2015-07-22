---
layout: post
title: Mandelbrot Generator
---

A few days ago I created a Mandelbrot set generator in JavaScript, available at [https://peterfajner.github.io/Fractals-JS/](https://peterfajner.github.io/Fractals-JS/). You can set the width of the canvas as well as the horizontal and vertical minimums and maximums. Here's what it looks like with the default settings of {x:[-2,2], y:[-2,2], width:1000px}:

![](/mandelbrot_default_settings "default settings")

Here's what a zoomed-in image looks like, at {x:[-0.25,0.1], y:[-1,-0.6], width:1000px}:

![](/mandelbrot_alternate_settings "alternate settings")


I plan on adding the ability to save the canvas as an image, to import and export canvas settings via the URL, to change the colour palette, and to create different fractals.