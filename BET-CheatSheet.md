
## HTML
HTML is used for structuring the content of a web page.

### Basic HTML Structure
```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

### Common HTML Tags
- `<h1>` to `<h6>`: Headings
- `<p>`: Paragraph
- `<a href="URL">Link Text</a>`: Create hyperlinks
- `<img src="image.jpg" alt="Description">`: Insert images
- `<ul>` and `<ol>`: Unordered and ordered lists
- `<li>`: List items

---

## CSS
CSS is used for styling web pages.

### Adding CSS
You can add CSS to your HTML document within a `<style>` element in the `<head>` section or link an external CSS file.

```html
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```

### Basic CSS Rules
```css
/* Select an element by its tag */
h1 {
    color: red;
}

/* Select elements by class */
.button {
    background-color: blue;
}

/* Select elements by ID */
#header {
    font-size: 24px;
}
```

---

## JavaScript
JavaScript adds interactivity to web pages.

### Adding JavaScript
You can add JavaScript to your HTML document within a `<script>` element in the `<head>` or at the end of the `<body>`.

```html
<script src="script.js"></script>
```

### Basic JavaScript
```javascript
// Variables
let name = "John";
const age = 25;

// Functions
function greet(person) {
    return "Hello, " + person;
}

// Events
document.getElementById("myButton").addEventListener("click", function() {
    alert("Button clicked!");
});
```

---

## Useful Websites
- [W3Schools JavaScript Tutorial](https://www.w3schools.com/js/)
- [Mozilla Developer Network (MDN) JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)