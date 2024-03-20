# Figures
Anytime you need to display a piece of content—like an image with an optional caption, consider using a <figure>.\

Use the included .figure, .figure-img and .figure-caption classes to provide some baseline styles for the HTML5 <figure> and <figcaption> elements. Images in figures have no explicit size, so be sure to add the .img-fluid class to your <img> to make it responsive.\

```html
    <figure class="figure">
        <img src="..." class="figure-img img-fluid rounded" alt="...">
        <figcaption class="figure-caption">A caption for the above image.</figcaption>
    </figure>

```


```html
    <figure class="figure">
        <img src="..." class="figure-img img-fluid rounded" alt="...">
        <figcaption class="figure-caption text-end">A caption for the above image.</figcaption>
    </figure>
```