# skrebets-course1.github.io

*version 0.0.3*

## Link

https://skrebets.github.io/skrebets-course1.github.io/

## Description

This project represents a one-page website with several features:

**1. flex-box**

One-dimensional layout method for laying out items in rows or columns. Items flex to fill additional space and shrink to fit into smaller spaces.
```css
.two-columns {
    width: 80%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
```
**2. grid**

Using the grid value of the display property; you can define columns and rows on your grid using the grid-template-rows and grid-template-columns properties.
```css
.cards {
    width: 80%;
    padding-top: 60px;
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
    grid-row-gap: 60px;
    grid-column-gap: 100px;
}
```
**3. iframe**

Represents a nested browsing context, embedding another HTML page into the current one.
```html
<div class="video__iframe video__iframe_left">
    <iframe width="515" height="316" src="https://www.youtube.com/embed/5MgBikgcWnY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
```
**4. keyframes (animations)**

Controls the intermediate steps in a CSS animation sequence by defining styles for keyframes (or waypoints) along the animation sequence.
```css
@keyframes rotation {
    from {
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}

.kaufman__triangle {
    height: 877px;
    width: 877px;
    position: absolute;
    top: 0px;
    right: -210px;
    background-image: url(../images/triangle.svg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    animation: rotation 20s linear infinite;
}
```
## Technologies

A list of technologies which are used in project:

1. HTML5,
2. CSS3.
