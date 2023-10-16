[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** *Tomáš Pacák*
## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-tomaspacak/)** site for preview.
## Dependecies
Proper implementation is required for the BasicLibrary to work (instructions below).
## Implementation
1. Download file  **[style.css](https://github.com/pslib-cz/2023-l4-web-typographic-library-tomaspacak/blob/master/docs/style.css)**
2. Add style.css inside your project folder
3. Link style.css file to every HTML page
## Usage
After you have successfully implemented style.css, you can use BasicLibrary. Which automatically sets the text style for which no classes are required. You just need to use tags (p, b, mark, i, h1 - h6,...) for components you need to use predefined classes, more about components below. You can also take a look at **[demo site](https://pslib-cz.github.io/2023-l4-web-typographic-library-tomaspacak/)** that uses BasicLibrary.
## Components
### Buttons
For buttons is used class .button. If you are not satisfied with the default design you can use the button class with the .button--2 class, for the second button design to work properly you need to use the button class as well. You can see examples below.
```html
<a class="button" href="#">Default</a>
```
```html
<button class="button">Default</button>
```
```html
<a class="button button--2" href="#">Second</a>
```
```html
<button class="button button--2">Second</button>
```
### Gallery
For the gallery to work, you need to use the classes and structure correctly. Example below is gallerry and images in the gallery.
```html
<div class="gallery">
    <a class="gallery__item" href="./img/img1_big.png">
        <figure>
            <img class="gallery__img" src="./img/img1.webp" alt="photo of moutins in spring">
            <figcaption class="gallery__description">description</figcaption>
        </figure>
    </a>
    <a class="gallery__item" href="./img/img2_big.png">
        <figure>
            <img class="gallery__img" src="./img/img2.webp" alt="photo in forest">
            <figcaption class="gallery__description">description</figcaption>
        </figure>
    </a>
</div>
```

