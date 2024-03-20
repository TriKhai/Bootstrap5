# Tables

1. Overview
- Due to the widespread use of `<table>` elements across third-party widgets like calendars and date pickers, Bootstrap’s tables are opt-in. Add the base class `.table` to any `<table>`, then extend with our optional modifier classes or custom styles. All table styles are not inherited in Bootstrap, meaning any nested tables can be styled independent from the parent.
```html
    <table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```

2. Variants
-  Use contextual classes to color tables, table rows or individual cells.\
```html
    <!-- On tables -->
    <table class="table-primary">...</table>
    <table class="table-secondary">...</table>
    <table class="table-success">...</table>
    <table class="table-danger">...</table>
    <table class="table-warning">...</table>
    <table class="table-info">...</table>
    <table class="table-light">...</table>
    <table class="table-dark">...</table>

    <!-- On rows -->
    <tr class="table-primary">...</tr>
    <tr class="table-secondary">...</tr>
    <tr class="table-success">...</tr>
    <tr class="table-danger">...</tr>
    <tr class="table-warning">...</tr>
    <tr class="table-info">...</tr>
    <tr class="table-light">...</tr>
    <tr class="table-dark">...</tr>

    <!-- On cells (`td` or `th`) -->
    <tr>
        <td class="table-primary">...</td>
        <td class="table-secondary">...</td>
        <td class="table-success">...</td>
        <td class="table-danger">...</td>
        <td class="table-warning">...</td>
        <td class="table-info">...</td>
        <td class="table-light">...</td>
        <td class="table-dark">...</td>
    </tr>
```

3. Accented tables
- Striped rows: Use `.table-striped` to add zebra-striping to any table row within the <tbody>.
```html 
    <table class="table table-striped">
    ...
    </table>
```

- Hoverable rows: Add `.table-hover` to enable a hover state on table rows within a `<tbody>`.
```html
    <table class="table table-hover">
    ...
    </table>
```

- Active tables: Highlight a table row or cell by adding a `.table-active` class.
```html
    <table class="table">
        <thead>
            ...
        </thead>
        <tbody>
            <tr class="table-active">
            ...
            </tr>
            <tr>
            ...
            </tr>
            <tr>
            <th scope="row">3</th>
            <td colspan="2" class="table-active">Larry the Bird</td>
            <td>@twitter</td>
            </tr>
        </tbody>
    </table>
```

4. Table borders
- Bordered tables: Add `.table-bordered` for borders on all sides of the table and cells. ( can be added to change colors ).\
    ```html
        <table class="table table-bordered">
        ...
        </table>    
    ```

- Tables without borders: add `.table-borderless` for a table without borders.
```html
    <table class="table table-borderless">
    ...
    </table>
```

5. Small tables
- Add .table-sm to make any .table more compact by cutting all cell padding in half.
```html
    <table class="table table-sm">
    ...
    </table>
```

6. More
- You can also put the `<caption>` on the top of the table with `.caption-top`.
```html
    <table class="table caption-top">
        <caption>List of users</caption>
        <thead>
            <tr>
            <th scope="col">#</th>
            <th scope="col">First</th>
            <th scope="col">Last</th>
            <th scope="col">Handle</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <th scope="row">1</th>
            <td>Mark</td>
            <td>Otto</td>
            <td>@mdo</td>
            </tr>
            <tr>
            <th scope="row">2</th>
            <td>Jacob</td>
            <td>Thornton</td>
            <td>@fat</td>
            </tr>
            <tr>
            <th scope="row">3</th>
            <td>Larry</td>
            <td>the Bird</td>
            <td>@twitter</td>
            </tr>
        </tbody>
    </table>
```


