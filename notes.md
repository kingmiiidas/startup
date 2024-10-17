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





index.html
Let's break down this code line by line:

```html
<!DOCTYPE html>
```
- This declares the document type as HTML5, telling the browser that this is an HTML5 document.

```html
<html lang="en">
```
- This begins the HTML document and sets the language to English (`lang="en"`).

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="css/style.css">
</head>
```
- `<head>`: This is the head section of the HTML where meta information about the page is defined.
- `<meta charset="UTF-8">`: Specifies the character encoding as UTF-8, ensuring the document can handle a wide range of characters.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the page is responsive by setting the viewport to match the device’s width, making it scale correctly on mobile devices.
- `<title>Login Page</title>`: Sets the title of the webpage to "Login Page," which will appear in the browser tab.
- `<link rel="stylesheet" href="css/style.css">`: Links an external CSS file (`style.css`) located in the `css` directory to style the webpage.

```html
<body class="login-body">
```
- This begins the body section and applies the class `login-body` for styling purposes, which is likely defined in the CSS file.

```html
<header>
    <nav>
        <a href="index.html">Home</a>
        <a href="discovery.html">Discovery</a>
    </nav>
</header>
```
- This defines a header with a navigation bar (`<nav>`), containing two links (`<a>`):
  - The first link navigates to the "Home" page (`index.html`).
  - The second link navigates to the "Discovery" page (`discovery.html`).

```html
<main>
    <div class="login-container">
        <h2 class="h2">Login Page</h2>
```
- `<main>`: This tag is used to encapsulate the main content of the page.
- `<div class="login-container">`: Creates a `div` container with the class `login-container` for layout or styling purposes, likely handled in CSS.
- `<h2 class="h2">Login Page</h2>`: This is a second-level heading (`<h2>`) with the text "Login Page" and a class `h2` applied for possible custom styling.

```html
<form class="forms" action="discovery.html" method="get">
```
- This begins a form with the class `forms`. It sends a GET request to `discovery.html` when submitted, though traditionally, login forms use the `POST` method for security.
  
```html
<label for="username">Username:</label><br>
<input type="text" id="username" name="username" required><br><br>
```
- `<label for="username">`: Label for the "username" field.
- `<input type="text" id="username" name="username" required>`: This creates an input field where users can enter their username. The `required` attribute ensures that this field must be filled in to submit the form.

```html
<label for="password">Password:</label><br>
<input type="password" id="password" name="password" required><br><br>
```
- `<label for="password">`: Label for the "password" field.
- `<input type="password" id="password" name="password" required>`: This creates a password input field. The characters entered will be masked (hidden). The `required` attribute ensures the password field must be filled in.

```html
<button type="button" onclick="location.href='discovery.html'">Login</button>
<button type="button" onclick="location.href='/create-account'">Create Account</button>
```
- These are two buttons, but instead of submitting the form, they use the `onclick` attribute to redirect the user:
  - The first button redirects to `discovery.html`, simulating a successful login.
  - The second button redirects to `/create-account`, likely leading to a page for account creation.

```html
</form>
</div>
</main>
```
- Closes the form, `div`, and `main` tags.

```html
<footer class="footer">
    <p>Zufas LLC</p>
    <a href="https://github.com/kingmiiidas/startup.git"><p>Github</p></a>
</footer>
```
- `<footer>`: This is the footer section of the page.
- `<p>Zufas LLC</p>`: Displays the text "Zufas LLC" inside a paragraph.
- `<a href="https://github.com/kingmiiidas/startup.git"><p>Github</p></a>`: Provides a clickable link to a GitHub repository, with the text "Github" displayed inside a paragraph.

```html
</body>
</html>
```
- Closes the body and HTML document.

### Summary:
- The page is a simple login form styled with external CSS, containing navigation links, a login form, and buttons that redirect users to other pages (instead of handling form submission in the backend). It also has a footer with a link to a GitHub repository.




style.css
Here's a line-by-line breakdown of the CSS code you provided:

```css
.login-body {
    background-image: url('loginback.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}
```
- Sets the background of the body to an image `loginback.jpg` that covers the entire screen (`background-size: cover`).
- Centers the background image both horizontally and vertically (`background-position: center`), and prevents it from repeating (`background-repeat: no-repeat`).
- Uses Flexbox to arrange the contents in a column, center them both vertically and horizontally (`justify-content: center; align-items: center`).
- Sets the height to the full viewport (`100vh`) and removes default margins (`margin: 0`).

```css
.backImage {
    background-image: url('discback.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
    width: 100vw;
    position: relative;
    top: 0;
    left: 0;
    z-index: -1;
    color: white;
    font-family: 'Franklin Gothic Medium';
}
```
- Styles a background image `discback.jpg` to cover the entire viewport (`height: 100vh`, `width: 100vw`).
- Sets the image in the center without repeating, similar to the previous style.
- Positions the element relatively (`position: relative`) and moves it to the top-left corner.
- Sets `z-index: -1` to place the background behind other elements.
- Text is styled with the color white, using the `Franklin Gothic Medium` font.

```css
header {
    width: 100%;
    text-align: center;
    text-decoration-color: white;
    background-color: rgba(252, 239, 94, 0.8);
    border-radius: 15px;
    padding: 20px; 
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
    margin: 20px 0; 
}
```
- Sets the header width to 100%, aligns text to the center, and makes the text decoration white.
- Adds a semi-transparent background color (`rgba(252, 239, 94, 0.8)`).
- Rounds the corners (`border-radius: 15px`), adds padding, and applies a shadow to the header (`box-shadow`).
- Adds margins above and below the header (`margin: 20px 0`).

```css
.forms {
    color: rgb(236, 100, 10);
    font-size: 120%;
}
```
- Styles form elements with a specific color (`rgb(236, 100, 10)`) and increases font size to 120%.

```css
.h2 {
    font-style: oblique;
    text-align: center;
    font-size: 200%;
    color: white;
    -webkit-text-stroke: 1px rgb(236, 97, 17);
}
```
- Styles an `<h2>` header with an oblique font style, centers it, and increases the font size to 200%.
- Sets the text color to white and adds a 1px orange stroke around the text (`-webkit-text-stroke`).

```css
nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}
```
- Styles navigation links (`<a>`), giving them a 15px margin on the left and right.
- Sets the text color to white, removes the underline (`text-decoration: none`), and makes the text bold.

```css
.login-container {
    text-align: center;
}
```
- Centers the content inside the `login-container`.

```css
footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    font-size: 150%;
    color: white;
    text-align: center;
    padding: 10px;
}
```
- Positions the footer at the bottom of the page (`position: absolute; bottom: 0`) and sets its width to 100%.
- Increases the font size by 150%, sets the text color to white, centers the text, and adds padding around the footer content.

```css
.profile-container {
    display: flex;
    padding: 20px;
    align-items: left;
    border-bottom: 1px solid #ccc;
    justify-content: flex-start;
}
```
- Uses Flexbox to layout the `profile-container`, adds 20px of padding, and aligns items to the left.
- Adds a light gray bottom border (`border-bottom: 1px solid #ccc`).

```css
.icon {
    width: 50px;
    height: 50px;
    margin-right: 20px;
}
```
- Styles the `.icon` class to have a fixed size of 50px by 50px, and adds a 20px margin to the right.

```css
.user-info {
    flex-grow: 1;
}
```
- Allows the `.user-info` element to grow and take up the remaining space in the Flexbox layout.

```css
.user-info h3 {
    margin: 0;
    padding: 0;
    font-size: 18px;
}
```
- Removes default margin and padding from the `<h3>` inside `.user-info` and sets the font size to 18px.

```css
.offers {
    display: flex;
    flex-direction: row;
    margin-top: 10px;
}
```
- Uses Flexbox to layout `.offers` in a row and adds a 10px top margin.

```css
.offers input[type="text"] {
    width: 300px;
    padding: 5px;
    margin-right: 10px;
}
```
- Styles text input fields within `.offers` to have a width of 300px, 5px of padding, and a 10px margin on the right.

```css
.offers button {
    padding: 5px 10px;
}
```
- Styles buttons inside `.offers`, giving them 5px padding on the top and bottom, and 10px on the left and right.

```css
.footer {
    text-align: center;
    padding: 10px;
    font-size: 20px;
    color: dodgerblue;
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #fff;
    border-top: 1px solid #ccc;
}
```
- Styles the `.footer` class with centered text, 10px padding, and a font size of 20px.
- Sets the text color to `dodgerblue` and positions the footer at the bottom of the page (`position: fixed; bottom: 0`).
- Ensures the footer spans the full width of the page and gives it a white background with a light gray top border.

```css
.logo {
    position: absolute;
    bottom: 10px;
    right: 10px;
    width: 50px;
    height: 50px;
    background-color: #fff;
    border-radius: 50%;
    border: 1px solid #000;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 24px;
    font-weight: bold;
}
```
- Positions the `.logo` at the bottom-right corner (`position: absolute; bottom: 10px; right: 10px`).
- Gives it a circular shape (`border-radius: 50%`) with a white background and a black border.
- Centers any content within the `.logo` using Flexbox (`display: flex; justify-content: center; align-items: center`) and makes the text inside it bold and 24px in size.

### Summary:
This CSS provides a clean layout and styling for a login page, with responsive design elements, background images, flexbox-based layouts for containers, and form input customization. It also includes a fixed footer and a stylized logo.
