# SIZING
- Width and height utilities are generated from the utility API in _utilities.scss. Includes support for `25%, 50%, 75%, 100%`, and `auto by default`. Modify those values as you need to generate different utilities here.

- Width: 
```html
    <div class="w-25 p-3" style="background-color: #eee;">Width 25%</div>
    <div class="w-50 p-3" style="background-color: #eee;">Width 50%</div>
    <div class="w-75 p-3" style="background-color: #eee;">Width 75%</div>
    <div class="w-100 p-3" style="background-color: #eee;">Width 100%</div>
    <div class="w-auto p-3" style="background-color: #eee;">Width auto</div>
```

- Heigth
```html
    <div style="height: 100px; background-color: rgba(255,0,0,0.1);">
    <div class="h-25 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 25%</div>
    <div class="h-50 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 50%</div>
    <div class="h-75 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 75%</div>
    <div class="h-100 d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height 100%</div>
    <div class="h-auto d-inline-block" style="width: 120px; background-color: rgba(0,0,255,.1)">Height auto</div>
    </div>
```

- You can also use max-width: 100%; and max-height: 100%; utilities as needed.  
```html
    <img src="..." class="mw-100" alt="...">
    <div style="height: 100px; background-color: rgba(255,0,0,.1);">
        <div class="mh-100" style="width: 100px; height: 200px; background-color: rgba(0,0,255,.1);">Max-height 100%</div>
    </div>
```

- You can also use utilities to set the width and height relative to the viewport.
```html
    <div class="min-vw-100">Min-width 100vw</div>
    <div class="min-vh-100">Min-height 100vh</div>
    <div class="vw-100">Width 100vw</div>
    <div class="vh-100">Height 100vh</div>
```
