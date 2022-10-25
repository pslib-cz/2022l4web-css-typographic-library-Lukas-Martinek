# portfolio.css - CSS typhographic library
**Author:** *Lukas Martinek*
## Demo site
Link to **[demo](https://pslib-cz.github.io/2022l4web-css-typographic-library-Lukas-Martinek/)** site for preview.
## Description
portfolio.css is CSS typhographic library which you can download for free. It was created for school project. If you have finished code and dont want to waste time, you can use my project. portfolio.css is styling headings, text markups, lists, tables, buttons and images.
## Content of the documentation
1. [Implementation](#Implementation)
2. [Headings](#Headings)
3. [Types of text](#Text)
4. [Lists](#Lists)
5. [Table](#Table)
6. [Buttons](#Buttons)
7. [Images](#Images)
## Implementation
1. Download file **[portfolio.css](https://github.com/pslib-cz/2022l4web-css-typographic-library-Lukas-Martinek/blob/master/portfolio.css)**
2. Put file in your project file
3. Link file into your code
    <link href="portfolio.css" rel="stylesheet">
## Headings
There are 5 headings tags which you can use:
* 50px for `<h1>` (non-mobile)
* 35px for `<h2>`
* 30px for `<h3>`
* 25px for `<h4>`
* 20px for `<h5>`
## Text
Modified tags: `<b>`, `<i>`, `<s>`, `<mark>`
If you want to underline text, use span with class "underlined"
## Lists
For lists we use this syntax
```html
<ul>
    <li>Example</li>
    <li>Example
        <ul>
            <li>Example</li>
            <li>Example</li>
        </ul>
    </li>
</ul>
```
## Table
Basic table is created from 3 tags - th, td and tr. Th is used for headings, td is table cell and tr is table row
```html
<tr><th>Heading</th><th>Head</th><th>Head</th></tr>
<tr><td>Cell</td><td>Cell</td><td>Cell</td></tr>
<tr><td>Cell</td><td>Cell</td><td>Cell</td></tr>
```
## Buttons
There are 4 types of buttons. Always use tag a and add class button - this is basic one. Then you can add other classes for different types of buttons.
* Basic - .button
* Reversed - .button .btn-reversed
* Red - .button .btn-red
* Blue - .button .btn-blue
```html
<a href="" class="button btn-red">Text</a>
```
## Images
If you want to put just one picture, use this syntax:
```html
<figure class="gallery__item">
    <a href="./img/example_1.jpg">
        <img alt="" src="./img/example_1.jpg">
            <figcaption>
                Imagine caption
            </figcaption>
    </a>
</figure>
```
If you want to create gallery of pictuer, you need to put div with class gallery first
```html
<div class="gallery">
                <figure class="gallery__item">
                    <a href="./img/example_1.jpg">
                        <img alt="" src="./img/example_1.jpg">
                        <figcaption>
                            Imagine caption
                        </figcaption>
                    </a>
                </figure>
                <figure class="gallery__item">
                    <a href="./img/example_2.jpg">
                        <img alt="" src="./img/example_2.jpg">
                        <figcaption>
                            Imagine caption
                        </figcaption>
                    </a>
                </figure>
                <figure class="gallery__item">
                    <a href="./img/banner.jpg">
                        <img alt="" src="./img/banner.jpg">
                        <figcaption>
                            Imagine caption
                        </figcaption>
                    </a>
                </figure>
            </div>
```