```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Custom CSS Framework</title>
    <link rel="stylesheet" href="/CSS/main.css">
</head>
<body>
    <h1>Custom CSS Framework</h1>
    <button class="btn-primary">Primary Button</button>
</body>
</html>
```
```css
/* base.css */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

h1, h2, h3, h4, h5, h6 {
    margin: 0;
    padding: 0.5em 0;
}

p {
    margin: 0 0 1em;
    padding: 0;
}
```

```css
/* components.css */
.btn-primary {
    display: inline-block;
    padding: 0.5em 1em;
    color: #fff;
    background-color: #007bff;
    border: none;
    border-radius: 0.25em;
    text-align: center;
    text-decoration: none;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.btn-primary:hover {
    background-color: #0056b3;
}

.card {
    padding: 1em;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 0.25em;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 1em 0;
}
```
```css
/* utilities.css */
.m-0 {
    margin: 0;
}

.mt-1 {
    margin-top: 0.5em;
}

.mt-2 {
    margin-top: 1em;
}

.p-1 {
    padding: 0.5em;
}

.p-2 {
    padding: 1em;
}

.text-center {
    text-align: center;
}

.text-right {
    text-align: right;
}
```

```css
/* main.css */
/* Import base styles */
@import url('base.css');

/* Import components */
@import url('components.css');

/* Import utilities */
@import url('utilities.css');
```
