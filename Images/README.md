# Responsive images

- `.img-fluid`. This applies `max-width: 100%;` and `height: auto;` to the image so that it scales with the parent element.\

```html
    <img src="..." class="img-fluid" alt="...">
```

- `.img-thumbnail` to our border-radius utilities, you can use .img-thumbnail to give an image a rounded 1px border appearance.\
```html
    <img src="..." class="img-thumbnail" alt="...">
```

- Aligning images: Align images with the helper float classes or text alignment classes.\
```html
    //left, right
    <img src="..." class="rounded float-start" alt="...">
    <img src="..." class="rounded float-end" alt="...">

    //center
    <img src="..." class="rounded mx-auto d-block" alt="...">
    <div class="text-center">
        <img src="..." class="rounded" alt="...">
    </div>
```

- Picture: If you are using the `<picture>` element to specify multiple `<source>` elements for a specific `<img>`, make sure to add the .img-* classes to the `<img>` and not to the `<picture>` tag.
```html
    <picture>
        <source srcset="..." type="image/svg+xml">
        <img src="..." class="img-fluid img-thumbnail" alt="...">
    </picture>
```