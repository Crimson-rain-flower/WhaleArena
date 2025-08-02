# Dive into Whale Arena
This repository contains an advanced CSS theme system built with custom properties, utility
layers, and enhanced typography. It is designed for projects that require seamless light/dark
mode support, high-quality text rendering, and a modern, maintainable design
system—especially when using Tailwind CSS or similar utility frameworks.
---
## Features
### 1. **Light & Dark Theme Support**
- Uses CSS custom properties for all key colors.
- Easily switch between themes using the `.dark` class.
### 2. **Semantic Color Tokens**
- `@theme inline` maps base variables to semantically meaningful tokens for easier use
across your codebase.
### 3. **Typography & Font Smoothing**
- Enhanced base styles for headings, paragraphs, labels, buttons, and inputs.
- Utilities like `.text-quality-enhanced`, `.text-crisp`, and `.text-smooth` for fine-tuning text
rendering.
### 4. **Gradients & Utilities**
- Includes utility classes, like `.bg-gradient-radial`, for easily applying radial gradients.
### 5. **Accessibility & Usability**
- Improved selection styles for better UX.
- Smooth scrolling and font size adjustments for accessibility.
---
## Getting Started
### 1. **Include the CSS in your project**
Add the CSS file to your project and make sure it's loaded globally.
### 2. **Switch Themes**
To activate dark mode, add the `.dark` class to the root HTML element or body:
```html
<body class="dark">
<!-- Your content -->
</body>
```
### 3. **Using Semantic Tokens**
Reference variables in your CSS or Tailwind configuration:
```css
background: var(--color-background);
color: var(--color-foreground);
```
### 4. **Typography Utilities**
Apply enhanced text rendering where needed:
```html
<h1 class="text-quality-enhanced">Welcome</h1>
```
### 5. **Custom Gradients**
Use radial gradient utilities:
```html
<div class="bg-gradient-radial"></div>
```
---
## Example Tailwind Extension
You can extend Tailwind to use these variables:
```js
// tailwind.config.js
module.exports = {
theme: {
extend: {
colors: {
background: 'var(--color-background)',
foreground: 'var(--color-foreground)',
accent: 'var(--color-accent)',
// ...other variables
},
borderRadius: {
md: 'var(--radius-md)',
lg: 'var(--radius-lg)',
},
},
},
darkMode: 'class', // enable dark mode via class
}
```
---
## Customization
- Change values in `:root` for your default (light) theme.
- Override in `.dark` for dark mode.
- Add or modify custom properties for your design needs.
---
## License
Feel free to use, modify, and distribute this CSS system in your projects.
---
**Author:** Crimson-rain-flower
*
*
L
a
s
t
U
p
d
a
t
e
d:*
*
2
0
2
5
-
0
8
-
0
2
