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
9. [Buttons](#Buttons)
10. [Pictures](#Pictures)
12. [Sections](#sections)
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
