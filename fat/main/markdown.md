# Rules and Guidelines
Hello! This is our first article on design.
Here, you will find the core rules.
Our design system is called "Fat Design," created by vexikoff.

## Core Rules
- Using corner radii that exceed 30% of the element's height is unattractive.
- Applying shadows and gradients everywhere is unattractive.
### Do this instead:
- Use corner radii between `2` and `6` pixels.
- Keep the width-to-height ratio greater than `2:1` but less than `16:2`. Ideal ratios are `16:1`, `8:1`, or `4:1`.
- Use borders sparingly. They should be at most 1 pixel wide and at least `7.5%` darker than the background.
- This design system is intended exclusively for designers. If you are not a designer, please do not use it; opt for Fluent or Material Design instead.

## Examples
### What to avoid
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Test</title>
</head>
<body>
    <div>text</div>
    <div class="mini">minitext</div>
</body>
</html>
```
and
```css
div {
    font-size: 16px;
}
.mini {
    font-size: 12px;
}
```
### What to do
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Test</title>
</head>
<body>
    <h1>text</h1>
    <p>minitext</p>
</body>
</html>
```
and
```css
body {
    margin: 0; 
    padding: 0; 
    font-family: sans-serif;
}

h1 {
    font-size: 24px;
}

p {
    font-size: 16px;
}
```
