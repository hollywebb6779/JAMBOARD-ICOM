# HTML and CSS Basics for CSS Art

## Table of Contents

- [Introduction](#introduction)
- [CSS](#css)
- [Box Model](#box-model)
- [Border-radius](#border-radius)
- [height, width](#height-width)
- [background-color](#background-color)
- [border-radius](#border-radius-1)
- [transform:translateY/translateX](#transform-translateytranslatex)
- [Box-Shadow](#box-shadow)

## Introduction

All CSS art is made up of basic shapes created by setting styles to an HTML <div> element. The HTML really just provides the web browser with a structure of how the art should be drawn or built. The real magic happens in the class styling of each <div> tag. By adding border styles, background colors, and changing the border radius of a <div> web element, you can create various basic shapes like circles, triangles, rectangles, trapezoids, and ovals.

## CLIP PATH

The clip-path property allows you to determine the shape from either a circle, ellipse, or polygon. Then you can specify the shape’s size and position. For the purposes of this tutorial, we’ll focus on creating shapes primarily with border styles rather than the clip-path property.

Clip-path allows you to define a shape that will determine what parts of your HTML element are shown. You can use it to create all different kinds of shapes! Check out the MDN web docs for clip-path. Even better, there's a great tool for creating these shapes in a handy UI - Clippy.

## CSS

CSS selectors
CSS properties and values
Box model (margin, padding, border)
Positioning (static, relative, absolute, fixed)
Flexbox and grid layout
Transforms and transitions
Animations
Pseudo-classes and pseudo-elements
Media queries for responsive design

## Box Model

As we know, everything in CSS is a box. So, a rectangle(or square) is the basic shape we will manipulate to create every other shape. This is the raw material.
By default, the size (width, height) of a box is determined by the content and specified margin, padding. As we won't be having any HTML content, we need to explicitly mention the width and height of the (block) boxes - div is the normally used element.

## Border-radius

is a great way to create not only circles and ellipses, but also organic looking shapes.

## height, width

These properties are used to set the height and width of your element. Default div size is determined by the HTML content it contains. Without any content, your div won’t appear to exist. It’s important to explicitly mention these properties for this reason. Usepx or % values to define your div’s size.

## background-color

This property sets the color of your div. I like using Google’s color picker to find the perfect hue and its corresponding HEX or RGB value.

## border-radius

This property sets the radius of your div’s corners. Divs are square by default, but you can generate other shapes by manipulating borders. If you assign one value to this property, that radius applies to all four corners. For example, border-radius: 50% makes a circle. You can specify up to three additional values to adjust corners separately.

## transform:translateY/translateX

This property repositions your div vertically/ horizontally along a 2D plane. Positioning elements is an essential part of creating more complex designs. Use px values to start moving components around your canvas.

## Box-Shadow

While creating CSS art, box-shadow can be used create copies of a shape in addition to simulating a 3d effect. Multiple box-shadows can be applied to an element to create multiple copies of different sizes. Inset borders can be used to create shadows as well.
