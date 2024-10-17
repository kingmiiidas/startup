You can reference other notes in any md file. 
### 1. **In the following code, what does the link element do?**

The `<link>` element is used to include external resources into the HTML document, commonly stylesheets. Example:

```html
<link rel="stylesheet" href="styles.css">
```

This code links the `styles.css` file to the HTML page, which contains CSS rules to style the page.

### 2. **In the following code, what does a div tag do?**

The `<div>` tag is a block-level container used to group elements for styling and layout purposes. It doesn’t have any default styling but is commonly used with CSS to structure a web page.

```html
<div class="container">Content goes here</div>
```

This creates a division that can be styled and controlled separately.

### 3. **What is the difference between the #title and .grid selector?**

- `#title` refers to an element with the specific `id="title"`. IDs are unique and should only be used once per page.
- `.grid` refers to any element with the class `grid`. Classes can be reused across multiple elements.

Example:
```css
#title {
  color: blue;
}

.grid {
  display: grid;
}
```

### 4. **What is the difference between padding and margin?**

- **Padding** is the space between the content of an element and its border.
- **Margin** is the space outside the border, between the element and adjacent elements.

Example:
```css
.box {
  padding: 10px;
  margin: 15px;
}
```

This gives the box 10px of space inside the border and 15px outside.

### 5. **Given this HTML and CSS, how will the images be displayed using flex?**

If images are placed inside a container with `display: flex;`, the images will be laid out in a row (default for flex) unless otherwise specified.

```css
.container {
  display: flex;
}
```

This would arrange the images horizontally.

### 6. **What does the following padding CSS do?**

```css
.element {
  padding: 20px 10px 15px 5px;
}
```

This applies padding in the order: top (20px), right (10px), bottom (15px), and left (5px).

### 7. **What does the following code using arrow syntax function declaration do?**

```js
const add = (a, b) => a + b;
```

This declares an arrow function `add` that takes two arguments (`a`, `b`) and returns their sum.

### 8. **What does the following code using map with an array output?**

```js
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2);
console.log(doubled);
```

Output: 
```js
[2, 4, 6]
```

The `map` function creates a new array by multiplying each element of `numbers` by 2.

### 9. **What does the following code output using getElementByID and addEventListener?**

```js
document.getElementById("myBtn").addEventListener("click", function() {
  alert("Button clicked");
});
```

When the button with `id="myBtn"` is clicked, an alert saying "Button clicked" will appear.

### 10. **What does the following line of JavaScript do using a # selector?**

```js
document.querySelector("#myElement").style.color = "blue";
```

This selects the element with `id="myElement"` and changes its text color to blue.

### 11. **Which of the following are true about the DOM?**
- The DOM (Document Object Model) is an API that represents the structure of HTML documents as a tree.
- It allows JavaScript to manipulate HTML elements.

### 12. **By default, the HTML span element has a default CSS display property value of:**

`inline`. The `<span>` tag is an inline element.

### 13. **How would you use CSS to change all the div elements to have a background color of red?**

```css
div {
  background-color: red;
}
```

### 14. **How would you display an image with a hyperlink in HTML?**

```html
<a href="https://example.com">
  <img src="image.jpg" alt="Example Image">
</a>
```

### 15. **In the CSS box model, what is the ordering of the box layers starting at the inside and working out?**

- Content
- Padding
- Border
- Margin

### 16. **Given the following HTML, what CSS would you use to set the text "trouble" to green and leave the "double" text unaffected?**

HTML:
```html
<span class="trouble">trouble</span>double
```

CSS:
```css
.trouble {
  color: green;
}
```

### 17. **What will the following code output when executed using a for loop and console.log?**

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
```

Output:
```
0
1
2
3
4
```

### 18. **How would you use JavaScript to select an element with the id of “byu” and change the text color of that element to green?**

```js
document.getElementById("byu").style.color = "green";
```

### 19. **What is the opening HTML tag for a paragraph, ordered list, unordered list, second level heading, first level heading, third level heading?**

- Paragraph: `<p>`
- Ordered list: `<ol>`
- Unordered list: `<ul>`
- Second level heading: `<h2>`
- First level heading: `<h1>`
- Third level heading: `<h3>`

### 20. **How do you declare the document type to be HTML?**

```html
<!DOCTYPE html>
```

### 21. **What is valid JavaScript syntax for if, else, for, while, switch statements?**

Examples:
```js
if (condition) { ... } else { ... }

for (let i = 0; i < 10; i++) { ... }

while (condition) { ... }

switch(expression) {
  case 'x':
    // code
    break;
  default:
    // code
}
```

### 22. **What is the correct syntax for creating a JavaScript object?**

```js
const person = {
  name: "John",
  age: 30
};
```

### 23. **Is it possible to add new properties to JavaScript objects?**

Yes, you can dynamically add properties:

```js
person.job = "Developer";
```

### 24. **If you want to include JavaScript on an HTML page, which tag do you use?**

```html
<script src="script.js"></script>
```

### 25. **Given the following HTML, what JavaScript could you use to set the text "animal" to "crow" and leave the "fish" text unaffected?**

HTML:
```html
<span id="animal">animal</span> <span id="fish">fish</span>
```

JavaScript:
```js
document.getElementById("animal").innerText = "crow";
```

### 26. **Which of the following correctly describes JSON?**

JSON (JavaScript Object Notation) is a lightweight data interchange format. It is easy for humans to read and write, and easy for machines to parse and generate.

### 27. **What does the console command `chmod`, `pwd`, `cd`, `ls`, `vim`, `nano`, `mkdir`, `mv`, `rm`, `man`, `ssh`, `ps`, `wget`, `sudo` do?**

- `chmod`: Change file permissions.
- `pwd`: Print working directory.
- `cd`: Change directory.
- `ls`: List files in a directory.
- `vim` / `nano`: Text editors.
- `mkdir`: Create a directory.
- `mv`: Move or rename a file.
- `rm`: Remove a file.
- `man`: Display manual for a command.
- `ssh`: Connect to a remote server.
- `ps`: Display running processes.
- `wget`: Download files from the web.
- `sudo`: Execute commands as the superuser.

### 28. **Which of the following console command creates a remote shell session?**

`ssh` creates a secure shell session to a remote server.

### 29. **Which of the following is true when the -la parameter is specified for the `ls` console command?**

`ls -la` lists all files (including hidden files) in long format.

### 30. **Which of the following is true for the domain name `banana.fruit.bozo.click`, which is the top-level domain, which is a subdomain, which is a root domain?**

- Top-level domain: `click`
- Root domain: `bozo.click`
- Subdomain: `banana.fruit.bozo.click`

### 31. **Is a web certificate necessary to use HTTPS?**

Yes, a web certificate is necessary for a site to use HTTPS.

### 32. **Can a DNS A record point to an IP address or another A record?**

Yes, a DNS A record can point to an IP address but not another A record.

### 33. **Port 443, 80, 22 is reserved for which protocol?**

- Port 443: HTTPS
- Port 80: HTTP
- Port 22:

 SSH

### 34. **What will the following code using Promises output when executed?**

```js
const promise = new Promise((resolve, reject) => {
  resolve('Success!');
});
promise.then((message) => {
  console.log(message);
});
```

Output:
```
Success!
```



