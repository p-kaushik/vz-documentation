---
description: >-
  Following steps demonstrate adding Visual library into any Javascript project
  using Viewzen's CDN.
---

# Method 2 - Web Components

## Import Styles and Js bundles

* **Create a new `index.html` file in your project root.** Include the `<meta name="viewport">` tag as well for [proper responsive behavior](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag) in mobile devices.

````html
// Base HTML Template
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    // Styles and Javascript preload bundles
    ...    
</head>
<body>
    // Visual components should be added here.
    ...
    // Javascript bundles
    ...
</body>
</html>
```
````

* **Include Visual's CSS and JS cdn's.** Place the `<link>` tag in the `<head>` for our CSS, javascript preload bundles, and the `<script>` tag for our JavaScript bundle before the closing `</body>`

````html
// Adding stylings and javascript bundles
```
<!DOCTYPE html>
...
<head>
    ...
    // Styles and Javascript preload bundles
    <link rel="stylesheet" href="https://embed.viewzenlabs.in/styles.css" media="print" onload="this.media='all'" />
    <link rel="modulepreload" href="https://embed.viewzenlabs.in/visual-preloader.js" />
</head>
<body>
    ...
    // Javascript bundles
    <script src="https://embed.viewzenlabs.in/visual-bundle.js" type="module"></script>
</body>
</html>
```
````

