# Bootstrap 5 Default Settings
  Bootstrap 5 uses a default `font-size` of 1rem (16px by default), and its `line-height` is 1.5.
  In addition, all `<p>` elements have `margin-top: 0` and `margin-bottom: 1rem` (16px by default).


# BS5 Text/Typographic
  1. Heading (class)
    BS5 styles HTML headings (`.h1` to `.h6`) with a bolder font-weight and a responsive font-size.
    
    > Syntax: `class = "h1"` or dùng thẻ `<h1>`.

    ```html
      <p class="h1">h1. Bootstrap heading</p>
      <p class="h2">h2. Bootstrap heading</p>
      <p class="h3">h3. Bootstrap heading</p>
      <p class="h4">h4. Bootstrap heading</p>
      <p class="h5">h5. Bootstrap heading</p>
      <p class="h6">h6. Bootstrap heading</p>
    ```


  2. Display heading (class)
    Display headings are used to stand out more than normal headings (larger font-size and lighter font-weight), and there are six classes to choose from: `.display-1` to `.display-6`.

    ```html
      <h1 class="display-1">Display 1</h1>
      <h1 class="display-2">Display 2</h1>
      <h1 class="display-3">Display 3</h1>
      <h1 class="display-4">Display 4</h1>
      <h1 class="display-5">Display 5</h1>
      <h1 class="display-6">Display 6</h1>
    ```

  3. Lead
    Make a paragraph stand out by adding `.lead`.
    ```html
      <p class="lead">This is a lead paragraph. It stands out from regular paragraphs.</p>
    ```

  4. Inline text elements
    - `<mark>` or `.mark` highlight.\
    - `<del>` deleted text.\
    - `<s>` or `.text-decoration-line-through` no longer accurate.\
    - `<ins>` an addition to the document.\
    - `<u>` or `.text-decoration-underline` underlined.\
    - `<small>` or `.small` is used to create a smaller, secondary text in any heading.\
    - `<strong>` bold text.\
    - `<em>` italicized text.\
    
      ```html
        <p>You can use the mark tag to <mark>highlight</mark> text.</p>
        <p><del>This line of text is meant to be treated as deleted text.</del></p>
        <p><s>This line of text is meant to be treated as no longer accurate.</s></p>
        <p><ins>This line of text is meant to be treated as an addition to the document.</ins></p>
        <p><u>This line of text will render as underlined.</u></p>
        <p><small>This line of text is meant to be treated as fine print.</small></p>
        <p><strong>This line rendered as bold text.</strong></p>
        <p><em>This line rendered as italicized text.</em></p>
      ```

  4. Text utilities
- Abbreviations: BS5 will style the HTML `<abbr>` element with a dotted border bottom and a cursor with question mark on hover.
```html
        <p><abbr title="attribute">attr</abbr></p>
```
      
- Blockquotes: The HTML spec requires that blockquote attribution be placed outside the `<blockquote>`. When providing attribution, wrap your `<blockquote>` in a `<figure>` and use a `<figcaption>` or a block level element (e.g., `<p>`) with the .blockquote-footer class. Be sure to wrap the name of the source work in `<cite`> as well.
    
  ```html
        <figure>
          <blockquote class="blockquote">
            <p>A well-known quote, contained in a blockquote element.</p>
          </blockquote>
          <figcaption class="blockquote-footer">
            Someone famous in <cite title="Source Title">Source Title</cite>
          </figcaption>
        </figure>
```

  5. Alignment
    - `.text-start` Indicates left-aligned text\
    - `.text-center` Indicates center-aligned text\
    - `.text-end` Indicates right-aligned text\
    - `.text-break` Prevents long text from breaking layout\
    - `.text-decoration-none` Removes the underline from a link\
    - `.text-nowrap` Indicates no wrap text\
    - `.text-lowercase`	Indicates lowercased text\
    - `.text-uppercase` Indicates uppercased text\
    - `.text-capitalize` Indicates capitalized text\
    - `.initialism` Displays the text inside an `<abbr>` element in a slightly smaller font size\
    - `.list-unstyled` Removes the default list-style and left margin on list items\
    - `.list-inline` Places all list items on a single line\
    - `.text-truncate` class to truncate the text with an ellipsis. (HAY)\
  
  6. List
    - Inline
      ```html
        <ul class="list-inline">
          <li class="list-inline-item">This is a list item.</li>
          <li class="list-inline-item">And another one.</li>
          <li class="list-inline-item">But they're displayed inline.</li>
        </ul>
      ```
    - Unstyled
      ```html
        <ul class="list-unstyled">
          <li>This is a list.</li>
          <li>It appears completely unstyled.</li>
          <li>Structurally, it's still a list.</li>
          <li>However, this style only applies to immediate child elements.</li>
          <li>Nested lists:
            <ul>
              <li>are unaffected by this style</li>
              <li>will still show a bullet</li>
              <li>and have appropriate left margin</li>
            </ul>
          </li>
          <li>This may still come in handy in some situations.</li>
        </ul>
      ```

# Responsive font sizes
  In Bootstrap 5, we’ve enabled responsive font sizes by default, allowing text to scale more naturally across device and viewport sizes. (sass)
