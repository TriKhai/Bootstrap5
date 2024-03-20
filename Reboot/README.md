# Page default

- `<html>` and `<body>` are updated\
    - `box-sizing: border-box`
    - `font-size: 16px` (assume)
    - `background-color: #fff`
    - Native font stack:
    ```html
        $font-family-sans-serif:
        // Cross-platform generic font family (default user interface font)
        system-ui,
        // Safari for macOS and iOS (San Francisco)
        -apple-system,
        // Windows
        "Segoe UI",
        // Android
        Roboto,
        // Basic web fallback
        "Helvetica Neue", Arial,
        // Linux
        "Noto Sans",
        "Liberation Sans",
        // Sans serif fallback
        sans-serif,
        // Emoji fonts
        "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji" !default;
    ```

- Headings , paragraphs
    - `margin-top` removed
    - Headings `margin-bottom: .5rem`
    - Paragraphs `margin-bottom: 1rem`

- Lists 
    - All lists `<ul>, <ol>, <dl> ` have their `margin-top` removed
    - Nested lists have no `margin-bottom`
    - reset the `padding-left` on `<ul>` and `<ol>` elements
