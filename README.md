# wp
## for you ,for all of us 💫



---

# Experiment 1: Create a Web Page for Your CV Using HTML

## Problem Statement  
Create a web page that presents your CV using various HTML tags, including `<ul>`, `<ol>`, `<table>`, etc.

---

## Theory  
Creating a CV in HTML involves utilizing different tags to structure and present information effectively:

1. **Semantic Structure Tags**:  
   - `<header>`: For the CV title or personal details.  
   - `<section>`: To group content such as contact info, education, and work experience.  
   - `<h1>`, `<h2>`: Headings for hierarchical organization.

2. **Lists**:  
   - `<ul>`: For unordered lists (e.g., skills, contact details).  
   - `<ol>`: For ordered lists (e.g., chronological work experiences).

3. **Tables**:  
   - `<table>`, `<tr>`, `<th>`, `<td>`: For tabular data such as qualifications or skill levels.

4. **Text Formatting**:  
   - `<p>`, `<strong>`, `<em>`: For text descriptions and emphasis.

5. **Links**:  
   - `<a>`: Hyperlinks to external pages or internal sections.  
   - `mailto:`: Linking email addresses for direct emailing.

6. **Styling**:  
   - Use CSS for enhanced visual presentation, including fonts, colors, and layout adjustments.

---

## Source Code  

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV</title>
</head>

<body>
    <center>
        <table border="2" cellpadding="2" cellspacing="5" width="50%">
            <tr>
                <td>
                    <strong>Name</strong><br>
                    <b>Address</b><br>
                    +91 xxxxxxxxxx
                </td>
            </tr>
            <tr>
                <td>
                    <strong>Career Objective</strong><br>
                    I want to become an AI/ML and Robotics Engineer.
                </td>
            </tr>
            <tr>
                <td>
                    <strong>Academic Qualifications</strong>
                    <table width="100%" border="2">
                        <tr>
                            <td width="50%">Intermediate</td>
                            <td width="50%">12th</td>
                        </tr>
                        <tr>
                            <td width="50%">High School</td>
                            <td width="50%">10th</td>
                        </tr>
                    </table>
                </td>
            </tr>
            <tr>
                <td>
                    <strong>Coding Languages</strong>
                    <ul>
                        <li>Python</li>
                        <li>Web Development (HTML, CSS, JavaScript)</li>
                        <li>C++</li>
                        <li>C</li>
                        <li>MATLAB</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <strong>Software Skills</strong>
                    <ul>
                        <li>Canva</li>
                        <li>Figma</li>
                        <li>Adobe Photoshop, Premiere Pro & Illustrator</li>
                        <li>Git & GitHub</li>
                        <li>Google Colab</li>
                        <li>Windows, Linux, Unix</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <strong>Personal Details</strong>
                    <table border="2" width="100%">
                        <tr>
                            <td>Name</td>
                            <td>Your Name</td>
                        </tr>
                        <tr>
                            <td>Mother's Name</td>
                            <td>Your Mother's Name</td>
                        </tr>
                        <tr>
                            <td>Date of Birth</td>
                            <td>16-7-2024</td>
                        </tr>
                        <tr>
                            <td>Email</td>
                            <td>name@gmail.com</td>
                        </tr>
                        <tr>
                            <td>Gender</td>
                            <td>Male</td>
                        </tr>
                        <tr>
                            <td>Nationality</td>
                            <td>Indian</td>
                        </tr>
                        <tr>
                            <td>Languages Known</td>
                            <td>
                                <ul>
                                    <li>English</li>
                                    <li>Hindi</li>
                                    <li>Punjabi</li>
                                    <li>French</li>
                                    <li>Spanish</li>
                                </ul>
                            </td>
                        </tr>
                        <tr>
                            <td>Hobbies</td>
                            <td>
                                <ul>
                                    <li>Coding</li>
                                    <li>Listening to Music</li>
                                    <li>Reading</li>
                                    <li>Football</li>
                                    <li>Cricket</li>
                                </ul>
                            </td>
                        </tr>
                    </table>
                </td>
            </tr>
        </table>
    </center>
</body>

</html>
```

---

## Learning Outcome  
Developed proficiency in using various HTML tags to organize and present a CV in a structured, visually appealing format. Gained experience in:  
- Semantic HTML elements.  
- Lists, tables, and text formatting.  
- Embedding and linking external resources.  
- Basic styling techniques using CSS.  

--- 



---

# Experiment 2: Create a Web Page Displaying Programming Languages' Details Using CSS

## Problem Statement  
Create a webpage that displays brief details of various programming languages, utilizing different types of CSS styles.

---

## Theory  
Cascading Style Sheets (CSS) enhance the visual presentation and structure of HTML documents. CSS allows for better customization, styling, and reusability. The three types of CSS are:

1. **Inline CSS**  
   - Styling applied directly to an HTML element using the `style` attribute.  
   - Example: `<p style="color: blue;">This is blue text.</p>`

2. **Internal or Embedded CSS**  
   - Defined within the `<style>` tag in the `<head>` section of an HTML document.  
   - Applies styles to elements within that specific HTML page.

3. **External CSS**  
   - CSS code is written in a separate file (e.g., `style.css`) and linked to the HTML document using the `<link>` tag.  
   - Promotes consistent styling across multiple pages.  

---

## Source Code  

### HTML Code  

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Programming Languages Overview</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="mainContainer">
      <div class="headingContainer">
        <h1>Programming Languages Overview</h1>
      </div>
      <div class="cardContainer">
        <!-- Python Card -->
        <div class="card">
          <div class="inner">
            <div class="front">
              <p>Python</p>
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Python_logo_01.svg/2048px-Python_logo_01.svg.png" alt="Python Logo"/>
            </div>
            <div class="back">
              <h3>Overview</h3>
              <p>
                Python is a powerful, high-level programming language known for its readability and simplicity. It is object-oriented, intuitive, and efficient, emphasizing problem-solving over technical details.
              </p>
            </div>
          </div>
        </div>

        <!-- JavaScript Card -->
        <div class="card">
          <div class="inner">
            <div class="front">
              <p>JavaScript</p>
              <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript Logo"/>
            </div>
            <div class="back">
              <h3>Overview</h3>
              <p>
                JavaScript is a dynamic, lightweight programming language used for creating interactive web pages. It supports both client-side and server-side development with powerful object-oriented capabilities.
              </p>
            </div>
          </div>
        </div>

        <!-- C++ Card -->
        <div class="card">
          <div class="inner">
            <div class="front">
              <p>C++</p>
              <img src="https://raw.githubusercontent.com/isocpp/logos/master/cpp_logo.png" alt="C++ Logo"/>
            </div>
            <div class="back">
              <h3>Overview</h3>
              <p>
                C++ is a middle-level, general-purpose language supporting procedural and object-oriented programming. Developed by Bjarne Stroustrup, it combines high- and low-level features for versatile programming.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```

### External CSS Code (`style.css`)  

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
}

.mainContainer {
  text-align: center;
  padding: 20px;
}

.headingContainer h1 {
  color: #333;
  margin-bottom: 20px;
}

.cardContainer {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.card {
  width: 250px;
  height: 300px;
  perspective: 1000px;
}

.inner {
  position: relative;
  width: 100%;
  height: 100%;
  transform-style: preserve-3d;
  transition: transform 0.8s;
}

.card:hover .inner {
  transform: rotateY(180deg);
}

.front, .back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

.front {
  background-color: #fff;
}

.front img {
  max-width: 80px;
  margin: 10px 0;
}

.back {
  background-color: #007bff;
  color: #fff;
  transform: rotateY(180deg);
}
```

---

## Learning Outcome  
This experiment demonstrates proficiency in:  
- Using **inline, internal, and external CSS**.  
- Structuring content effectively using HTML and styling with CSS.  
- Implementing interactive and visually appealing components like flip cards.  

---



---

# Experiment 3: Simple Calculator Application Using JavaScript and HTML  

---

## Problem Statement  
Create a webpage that demonstrates a **simple calculator application** using **JavaScript** and **HTML**. The calculator should support basic arithmetic operations such as addition, subtraction, multiplication, and division.

---

## Theory  

Creating a simple calculator combines HTML and JavaScript to design and implement the structure and functionality of the application.  

### **HTML Structure**  
- **Input Field**: Displays numbers and mathematical expressions.  
- **Buttons**: Represent numbers, operators, and functionalities such as clear, backspace, and evaluation.  
- **Layout**: Organize buttons and the display for a user-friendly interface using `<div>` and `<table>` tags.  

### **JavaScript Functionality**  
1. **Event Handling**: Use event listeners to handle button clicks.  
2. **Insert Operations**: Add user inputs (numbers or operators) to the display.  
3. **Evaluation**: Compute expressions using the `eval()` function (with proper handling of the multiplication symbol).  
4. **Clear Display**: Reset the display.  
5. **Backspace Functionality**: Remove the last character from the input field.  

### **Interaction Between HTML and JavaScript**  
- **DOM Manipulation**: Retrieve and update HTML elements using JavaScript.  
- **Display Update**: Ensure inputs and results are displayed dynamically based on user interactions.  

---

## Source Code  

### HTML and JavaScript  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator Program in JavaScript</title>
    <style>
        /* Outer layout of the Calculator */
        .formstyle {
            width: 300px;
            height: 400px;
            margin: 20px auto;
            border: 3px solid skyblue;
            border-radius: 5px;
            padding: 20px;
            text-align: center;
            background-color: grey;
        }

        /* Top horizontal bar */
        h1 {
            text-align: center;
            padding: 10px;
            background-color: skyblue;
            color: white;
        }

        .btn {
            width: 50px;
            height: 50px;
            font-size: 25px;
            margin: 2px;
            cursor: pointer;
            background-color: red;
            color: white;
        }

        .textview {
            width: 223px;
            margin: 5px;
            font-size: 25px;
            padding: 5px;
            background-color: lightgreen;
        }
    </style>
    <script>
        // Insert number or operator into the textview
        function insert(num) {
            document.form1.textview.value += num;
        }

        // Evaluate the expression
        function equal() {
            var exp = document.form1.textview.value;
            if (exp) {
                document.form1.textview.value = eval(exp.replace('x', '*'));
            }
        }

        // Backspace function to remove the last character
        function backspace() {
            var exp = document.form1.textview.value;
            document.form1.textview.value = exp.substring(0, exp.length - 1);
        }

        // Clear the textview
        function clearText() {
            document.form1.textview.value = '';
        }
    </script>
</head>
<body>
    <h1>Calculator Program in JavaScript</h1>
    <div class="formstyle">
        <form name="form1">
            <input class="textview" name="textview" readonly>
        </form>
        <center>
            <table>
                <tbody>
                    <tr>
                        <td><input class="btn" type="button" value="C" onclick="clearText()"></td>
                        <td><input class="btn" type="button" value="B" onclick="backspace()"></td>
                        <td><input class="btn" type="button" value="/" onclick="insert('/')"></td>
                        <td><input class="btn" type="button" value="x" onclick="insert('x')"></td>
                    </tr>
                    <tr>
                        <td><input class="btn" type="button" value="7" onclick="insert(7)"></td>
                        <td><input class="btn" type="button" value="8" onclick="insert(8)"></td>
                        <td><input class="btn" type="button" value="9" onclick="insert(9)"></td>
                        <td><input class="btn" type="button" value="-" onclick="insert('-')"></td>
                    </tr>
                    <tr>
                        <td><input class="btn" type="button" value="4" onclick="insert(4)"></td>
                        <td><input class="btn" type="button" value="5" onclick="insert(5)"></td>
                        <td><input class="btn" type="button" value="6" onclick="insert(6)"></td>
                        <td><input class="btn" type="button" value="+" onclick="insert('+')"></td>
                    </tr>
                    <tr>
                        <td><input class="btn" type="button" value="1" onclick="insert(1)"></td>
                        <td><input class="btn" type="button" value="2" onclick="insert(2)"></td>
                        <td><input class="btn" type="button" value="3" onclick="insert(3)"></td>
                        <td><input class="btn" type="button" value="=" onclick="equal()"></td>
                    </tr>
                    <tr>
                        <td colspan="4"><input class="btn" type="button" value="0" onclick="insert(0)"></td>
                    </tr>
                </tbody>
            </table>
        </center>
    </div>
</body>
</html>
```

---

## Learning Outcomes  

1. Understand how to structure a **calculator interface** using **HTML elements**.  
2. Gain proficiency in implementing calculator functionality using **JavaScript**, including handling user inputs and performing mathematical operations.  
3. Learn how **HTML and JavaScript** interact through **DOM manipulation** to create dynamic and interactive applications.  

---



---

# **Experiment No. 4**: CRUD Operations (To-Do/Grocery List)

---

## **Problem Statement**  
Create a web page implementing **basic CRUD operations** (Create, Read, Update, Delete) using **JavaScript** and **HTML** to manage a **to-do/grocery list**.

---

## **Theory**

CRUD operations form the backbone of most interactive web applications. Implementing them for a **to-do list** involves the following key aspects:  

### **HTML Structure**  
1. **Input Field**: Enables users to enter new items.  
2. **List Display**: Dynamically shows the to-do items using `<ul>` and `<li>` elements.  
3. **Action Buttons**: Provides buttons for editing and deleting each list item.  

### **JavaScript Functionality**  
1. **Create**: Add new items to the list.  
2. **Read**: Display all existing items dynamically.  
3. **Update**: Modify an existing item based on user input.  
4. **Delete**: Remove an item from the list.  

### **Interaction Between HTML and JavaScript**  
- **DOM Manipulation**: Dynamically add, modify, or remove HTML elements based on user actions.  
- **Event Handling**: Capture user actions like button clicks or keypress events to trigger JavaScript functions.  

---

## **Source Code**

### **HTML**  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" />
    <style>
        /* CSS Styling */
        @import url('https://fonts.googleapis.com/css2?family=Borel&display=swap');

        body {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            background: #2f363e;
            font-family: 'Borel', cursive;
        }

        .box {
            width: 450px;
            height: 550px;
            padding: 30px 50px;
            border-radius: 30px;
            background: #2f363e;
            box-shadow: 25px 25px 75px rgba(0, 0, 0, 0.25), 
                        inset 5px 5px 20px rgba(255, 255, 255, 0.2);
        }

        h2 {
            color: #fff;
            text-align: center;
            font-size: 1.5rem;
        }

        #inputBx {
            width: 100%;
            padding: 10px;
            font-size: 1rem;
            border-radius: 20px;
            border: none;
            outline: none;
        }

        .list li {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #4b535d;
            border-radius: 20px;
            margin-bottom: 10px;
            padding: 10px 20px;
        }

        .delete-btn, .edit-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 25px;
            height: 25px;
            border-radius: 50%;
            cursor: pointer;
            color: white;
        }

        .delete-btn {
            background: #e74c3c;
        }

        .edit-btn {
            background: #3498db;
        }
    </style>
</head>
<body>
    <div class="box">
        <h2>To-Do List</h2>
        <input type="text" placeholder="Write here..." id="inputBx">
        <ul class="list"></ul>
    </div>
    <script>
        // JavaScript Logic
        let list = document.querySelector(".list");
        let inputBx = document.getElementById("inputBx");

        // Add item to the list
        inputBx.addEventListener("keydown", function (event) {
            if (event.key === "Enter" && inputBx.value.trim() !== "") {
                addToList(inputBx.value.trim());
                inputBx.value = "";
            }
        });

        function addToList(text) {
            let listItem = document.createElement("li");
            let listText = document.createElement("span");
            listText.textContent = text;

            let deleteBtn = document.createElement("button");
            deleteBtn.classList.add("delete-btn");
            deleteBtn.innerHTML = '<i class="fas fa-times"></i>';

            let editBtn = document.createElement("button");
            editBtn.classList.add("edit-btn");
            editBtn.innerHTML = '<i class="fas fa-pencil-alt"></i>';

            deleteBtn.addEventListener("click", () => list.removeChild(listItem));
            editBtn.addEventListener("click", () => {
                let newText = prompt("Edit item:", listText.textContent);
                if (newText !== null && newText.trim() !== "") {
                    listText.textContent = newText.trim();
                }
            });

            listItem.appendChild(listText);
            listItem.appendChild(editBtn);
            listItem.appendChild(deleteBtn);
            list.appendChild(listItem);
        }
    </script>
</body>
</html>
```

---

## **Learning Outcomes**  

1. **Understanding CRUD Operations**: Gained hands-on experience with implementing **create**, **read**, **update**, and **delete** functionalities in JavaScript.  
2. **HTML and JavaScript Integration**: Learned to dynamically update the webpage using **DOM manipulation** and handle user interactions through **event listeners**.  
3. **Improved Coding Skills**: Developed skills in JavaScript-based list management, user interface updates, and responsive interactions.

---



---

# **Experiment No. 5**: JavaScript Basics – Data Types, Statements, Keywords, and Operators

---

## **Problem Statement**  
Create a JavaScript application to explore and demonstrate the use of various **data types**, **statements**, **keywords**, and **operators**.

---

## **Theory**

### **JavaScript Essentials**  

1. **Data Types**  
   - **Primitive Types**: Numbers, Strings, Booleans, `null`, `undefined`.  
   - **Complex Types**: Objects (including Arrays, Functions).  

2. **Statements**  
   - **Conditional Statements**: `if`, `else if`, `else`, `switch`.  
   - **Looping Statements**: `for`, `while`, `do...while`.  
   - **Control Statements**: `break`, `continue`.  

3. **Keywords**  
   - **Variable Declaration**: `var`, `let`, `const`.  
   - **Function Declaration**: `function`.  
   - **Scope Keywords**: `this`, `global`.  
   - **Error Handling**: `try`, `catch`, `throw`.  

4. **Operators**  
   - **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`.  
   - **Assignment Operators**: `=`, `+=`, `-=`, etc.  
   - **Comparison Operators**: `==`, `===`, `!=`, etc.  
   - **Logical Operators**: `&&`, `||`, `!`.  
   - **Bitwise Operators**: `&`, `|`, `^`, etc.  

---

## **Source Code**

### **HTML**  

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Basics App</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>JavaScript Basics Demonstration</h1>
    <script src="script.js"></script>
</body>
</html>
```

### **CSS**  

```css
body {
    font-family: Arial, sans-serif;
    margin: 20px;
    text-align: center;
    background-color: #f9f9f9;
}

h1 {
    color: #333;
}

code {
    font-family: "Courier New", Courier, monospace;
    background-color: #f4f4f4;
    padding: 4px;
    border-radius: 3px;
    display: inline-block;
}
```

### **JavaScript**  

```javascript
// Variables and Data Types
let numberVar = 42;
let stringVar = "Hello, JavaScript!";
let booleanVar = true;
let arrayVar = [10, 20, 30];
let objectVar = { key: "value" };

// Arithmetic Operators
let addition = 5 + 10;
let subtraction = 20 - 5;
let multiplication = 4 * 5;
let division = 20 / 4;
let modulus = 25 % 4;

// Conditional Statement
let age = 18;
if (age >= 18) {
    document.write("<p><strong>Condition:</strong> You are eligible to vote.</p>");
} else {
    document.write("<p><strong>Condition:</strong> You are not eligible to vote.</p>");
}

// Looping Statement
document.write("<h2>Looping Example</h2>");
document.write("<p>Using <code>for</code> loop to iterate through an array:</p>");
for (let i = 0; i < arrayVar.length; i++) {
    document.write("<p>Element " + (i + 1) + ": " + arrayVar[i] + "</p>");
}

// Keywords and Error Handling
try {
    let result = "test" / 2;
    if (isNaN(result)) throw "Invalid Division";
} catch (error) {
    document.write("<p><strong>Error Caught:</strong> " + error + "</p>");
}

// Displaying Results
document.write("<h2>Variables and Data Types</h2>");
document.write("<p><strong>Number:</strong> " + numberVar + "</p>");
document.write("<p><strong>String:</strong> " + stringVar + "</p>");
document.write("<p><strong>Boolean:</strong> " + booleanVar + "</p>");
document.write("<p><strong>Array:</strong> " + arrayVar.join(", ") + "</p>");
document.write("<p><strong>Object:</strong> " + JSON.stringify(objectVar) + "</p>");

document.write("<h2>Operators in Action</h2>");
document.write("<p><strong>Addition:</strong> " + addition + "</p>");
document.write("<p><strong>Subtraction:</strong> " + subtraction + "</p>");
document.write("<p><strong>Multiplication:</strong> " + multiplication + "</p>");
document.write("<p><strong>Division:</strong> " + division + "</p>");
document.write("<p><strong>Modulus:</strong> " + modulus + "</p>");
```

---

## **Output**  

### **1. Variables and Data Types**  
- Number: `42`  
- String: `"Hello, JavaScript!"`  
- Boolean: `true`  
- Array: `[10, 20, 30]`  
- Object: `{"key": "value"}`  

### **2. Operators in Action**  
- Addition: `15`  
- Subtraction: `15`  
- Multiplication: `20`  
- Division: `5`  
- Modulus: `1`  

### **3. Conditional and Looping Statements**  
- Conditional Example: Displays eligibility to vote based on `age`.  
- Loop Example: Iterates through an array and displays each element.  

### **4. Error Handling**  
Demonstrates the `try-catch` mechanism for managing runtime errors.  

---

## **Learning Outcomes**

1. **Recognized and Utilized JavaScript Features**: Demonstrated proficiency in using various **data types**, **statements**, **keywords**, and **operators**.  
2. **Applied Conditional and Looping Constructs**: Showcased the practical implementation of conditional checks and iterative logic.  
3. **Error Handling Expertise**: Gained insights into handling runtime errors using `try-catch`.  
4. **Improved Debugging Skills**: Learned to test and validate application logic dynamically.  

---



---

# **Experiment No. 6**: Working with Window and Document Objects in JavaScript

---

## **Problem Statement**  
Create a JavaScript application to explore and demonstrate the use of **Window Objects** and **Document Objects**, including their properties, methods, and events.

---

## **Theory**

### **1. Window Object**  
The `window` object represents the browser's window and provides methods, properties, and events to interact with the browser.

- **Properties**:  
  - `window.innerWidth`: Width of the viewport.  
  - `window.innerHeight`: Height of the viewport.  

- **Methods**:  
  - `window.alert()`: Displays an alert box.  
  - `window.open()`: Opens a new browser window.  
  - `window.close()`: Closes the current browser window.  

- **Events**:  
  - `window.onload`: Executes when the page is fully loaded.  
  - `window.onresize`: Executes when the window is resized.  

### **2. Document Object**  
The `document` object represents the HTML document loaded in the browser and allows manipulation of its structure and content.

- **Accessing Elements**:  
  - `document.getElementById()`: Access elements by their ID.  
  - `document.querySelector()`: Access elements using CSS selectors.  

- **Modifying Content**:  
  - `innerHTML`: Updates or retrieves the HTML content inside an element.  
  - `textContent`: Updates or retrieves text content inside an element.  

- **Events**:  
  - `document.addEventListener()`: Adds event listeners for user interactions.  

---

## **Source Code**

### **HTML**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Window and Document Objects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Window and Document Objects Demo</h1>

    <button onclick="showAlert()">Show Alert</button>
    <button onclick="changeBackgroundColor()">Change Background Color</button>
    <button onclick="displayViewportSize()">Show Viewport Size</button>

    <div id="output"></div>

    <script src="script.js"></script>
</body>
</html>
```

---

### **CSS**

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 50px;
}

h1 {
    color: #333;
}

button {
    padding: 10px;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
}

#output {
    margin-top: 20px;
    font-size: 18px;
    color: #555;
}
```

---

### **JavaScript**

```javascript
// Function to show an alert using the Window Object
function showAlert() {
    window.alert('Hello, this is a window alert!');
}

// Function to change the background color using the Document Object
function changeBackgroundColor() {
    document.body.style.backgroundColor = getRandomColor();
}

// Helper function to generate a random color
function getRandomColor() {
    const letters = '0123456789ABCDEF';
    let color = '#';
    for (let i = 0; i < 6; i++) {
        color += letters[Math.floor(Math.random() * 16)];
    }
    return color;
}

// Function to display viewport size using Window Object
function displayViewportSize() {
    const width = window.innerWidth;
    const height = window.innerHeight;
    const outputDiv = document.getElementById('output');
    outputDiv.textContent = `Viewport Size: ${width}px x ${height}px`;
}

// Event Listener to handle window resizing
window.onresize = function () {
    console.log('Window resized!');
    displayViewportSize(); // Update viewport size dynamically
};
```

---

## **Output**

### **1. Buttons for User Interaction**  
- **Show Alert**: Displays an alert box with a message.  
- **Change Background Color**: Changes the background color of the page to a random color.  
- **Show Viewport Size**: Displays the current browser viewport dimensions in pixels.

### **2. Dynamic Resizing Feedback**  
Logs the "Window resized!" message in the console and updates the displayed viewport size when the window is resized.

---

## **Learning Outcomes**

1. **Window Object Interactions**: Gained knowledge of properties (`innerWidth`, `innerHeight`) and methods (`alert`, `onresize`) to interact with the browser.  
2. **Document Object Manipulation**: Practiced accessing and modifying HTML elements using methods (`getElementById`, `innerHTML`) and responding to user actions.  
3. **Event Handling**: Successfully used `window.onresize` and other event listeners to perform dynamic updates based on user interactions.  
4. **Practical Implementation**: Developed a simple but effective JavaScript application that combines Window and Document Object functionalities.  

---



---

# **Experiment No. 7**: Object Creation and Methods in JavaScript  

---

## **Problem Statement**  
Create a JavaScript application to demonstrate object creation using **object literals**, **constructor functions**, and **ES6 classes**, and showcase methods added through **function assignments** and **prototypes**.

---

## **Theory**

### **1. Object Creation**  
Objects in JavaScript can be created using multiple techniques:  

- **Object Literals**: Directly define objects with `{}` notation.  
  ```javascript
  let obj = { key: 'value' };
  ```  

- **Constructor Functions**: Define reusable object templates with `function` syntax.  
  ```javascript
  function ObjName(prop) {
      this.prop = prop;
  }
  ```  

- **ES6 Classes**: Modern syntax for creating classes and objects.  
  ```javascript
  class ObjName {
      constructor(prop) {
          this.prop = prop;
      }
  }
  ```

### **2. Adding Methods**  
Methods can be added to objects using:  

- **Function Assignment**: Directly assign functions as properties to objects.  
  ```javascript
  obj.methodName = function() { ... };
  ```  

- **Prototypes**: Share methods across all instances of an object.  
  ```javascript
  ObjName.prototype.methodName = function() { ... };
  ```  

---

## **Source Code**

### **HTML**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Object Creation and Methods</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Object Creation and Methods</h1>

    <button onclick="createBook()">Create Book</button>
    <button onclick="createCar()">Create Car</button>

    <script src="script.js"></script>
</body>
</html>
```

---

### **CSS**

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 50px;
}

h1 {
    color: #333;
}

button {
    padding: 10px;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
}
```

---

### **JavaScript**

```javascript
// Object Creation with Constructor Function
function Book(title, author, pages) {
    this.title = title;
    this.author = author;
    this.pages = pages;

    // Method to display book information
    this.displayInfo = function () {
        alert(`Title: ${this.title}\nAuthor: ${this.author}\nPages: ${this.pages}`);
    };
}

// Adding a prototype method to Book
Book.prototype.getSummary = function () {
    return `${this.title} by ${this.author} (${this.pages} pages)`;
};

// Creating a Book instance
function createBook() {
    let myBook = new Book('The Great Gatsby', 'F. Scott Fitzgerald', 180);

    // Calling methods
    myBook.displayInfo();
    console.log(myBook.getSummary());
}

// Object Creation with ES6 Class
class Car {
    constructor(make, model, year) {
        this.make = make;
        this.model = model;
        this.year = year;
    }

    // Method inside the class
    displayInfo() {
        alert(`Make: ${this.make}\nModel: ${this.model}\nYear: ${this.year}`);
    }

    // Prototype method
    startEngine() {
        return `The engine of ${this.make} ${this.model} is starting...`;
    }
}

// Creating a Car instance
function createCar() {
    let myCar = new Car('Toyota', 'Corolla', 2020);

    // Calling methods
    myCar.displayInfo();
    console.log(myCar.startEngine());
}

// Object Creation with Literal
let person = {
    name: 'Alice',
    age: 25,
    greet: function () {
        return `Hello, my name is ${this.name} and I am ${this.age} years old.`;
    }
};

console.log(person.greet());
```

---

## **Output**  

### **1. Book Creation and Methods**  
- **Create Book Button**: Creates a `Book` object and displays its details using an alert and a console log.  

### **2. Car Creation and Methods**  
- **Create Car Button**: Creates a `Car` object and displays its details using an alert and a console log.  

### **3. Literal Object**  
- `person` object is logged to the console with a greeting message.  

---

## **Learning Outcomes**

1. Gained expertise in creating objects using **object literals**, **constructor functions**, and **ES6 classes**.  
2. Demonstrated the ability to add methods to objects using **function assignment** and **prototype methods**.  
3. Learned to construct reusable object templates and define methods within those templates, highlighting key concepts of **object-oriented programming**.  
4. Practiced practical JavaScript application development for object creation and method assignment.  

---



---

# **Experiment No. 8**: Iteration with Loops  

---

## **Problem Statement**  
Create a JavaScript application demonstrating the concept of iteration using loops (`for`, `while`, `do...while`). Include examples of array iteration and conditional iteration.

---

## **Theory**

### **1. Loop Structures in JavaScript**  

- **`for` Loop**: Executes a block of code a specified number of times.
  ```javascript
  for (let i = 0; i < 5; i++) {
      console.log(i);
  }
  ```

- **`while` Loop**: Executes a block of code as long as the condition evaluates to true.
  ```javascript
  let i = 0;
  while (i < 5) {
      console.log(i);
      i++;
  }
  ```

- **`do...while` Loop**: Executes a block of code at least once, then continues if the condition evaluates to true.
  ```javascript
  let i = 0;
  do {
      console.log(i);
      i++;
  } while (i < 5);
  ```

### **2. Applications of Iteration**  

- **Repetitive Tasks**: Use loops to repeat code for calculations or logic.  
- **Array Iteration**: Process or manipulate each element in an array.  
- **Conditional Iteration**: Combine conditional statements with loops to filter data or control logic.

---

## **Source Code**

### **HTML**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iteration with Loops</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Iteration with Loops</h1>

    <button onclick="displayBooks()">Display Books</button>

    <div id="bookContainer"></div>

    <script src="script.js"></script>
</body>
</html>
```

---

### **CSS**

```css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 50px;
}

h1 {
    color: #333;
}

button {
    padding: 10px;
    font-size: 16px;
    margin: 10px;
    cursor: pointer;
}

#bookContainer {
    text-align: left;
    margin-top: 20px;
}

.bookInfo {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 10px;
    margin-bottom: 10px;
}
```

---

### **JavaScript**

```javascript
// Object Constructor for Book
function Book(title, author, pages) {
    this.title = title;
    this.author = author;
    this.pages = pages;

    // Method to return formatted book information
    this.displayInfo = function () {
        return `<div class="bookInfo">
                    <p><strong>Title:</strong> ${this.title}</p>
                    <p><strong>Author:</strong> ${this.author}</p>
                    <p><strong>Pages:</strong> ${this.pages}</p>
                </div>`;
    };
}

// Function to display books using different loop structures
function displayBooks() {
    // Creating an array of Book objects
    let books = [
        new Book('The Great Gatsby', 'F. Scott Fitzgerald', 180),
        new Book('To Kill a Mockingbird', 'Harper Lee', 281),
        new Book('1984', 'George Orwell', 328)
    ];

    // Accessing the bookContainer element in the HTML
    let bookContainer = document.getElementById('bookContainer');
    bookContainer.innerHTML = ''; // Clearing previous content

    // 1. Using a for loop
    bookContainer.innerHTML += "<h2>For Loop</h2>";
    for (let i = 0; i < books.length; i++) {
        bookContainer.innerHTML += books[i].displayInfo();
    }

    // 2. Using a for...of loop
    bookContainer.innerHTML += "<h2>For...Of Loop</h2>";
    for (const book of books) {
        bookContainer.innerHTML += book.displayInfo();
    }

    // 3. Using a while loop
    bookContainer.innerHTML += "<h2>While Loop</h2>";
    let j = 0;
    while (j < books.length) {
        bookContainer.innerHTML += books[j].displayInfo();
        j++;
    }

    // 4. Using a do...while loop
    bookContainer.innerHTML += "<h2>Do...While Loop</h2>";
    let k = 0;
    do {
        bookContainer.innerHTML += books[k].displayInfo();
        k++;
    } while (k < books.length);
}
```

---

## **Output**  

### **Description of Output**  
1. Clicking **"Display Books"** displays book information using four different loops (`for`, `for...of`, `while`, `do...while`).  
2. Each book's details (title, author, and pages) are displayed in the browser dynamically.  

### **Sample Display in Browser**  
- **For Loop**: Displays books using a `for` loop.  
- **For...Of Loop**: Displays books using a `for...of` loop.  
- **While Loop**: Displays books using a `while` loop.  
- **Do...While Loop**: Displays books using a `do...while` loop.  

---

## **Learning Outcomes**  

1. Mastered **loop structures** (`for`, `while`, `do...while`) to automate repetitive tasks.  
2. Understood **array iteration** and its practical applications in processing data.  
3. Combined loops with **conditional logic** for enhanced control over iterations.  
4. Gained insights into practical implementation of loops in **dynamic web applications**.

---












-
-
-

# VIVA QUESTIONS

---

## **Viva Questions and Answers**

### **Data Types**
1. **Q: What are the primitive data types in JavaScript?**  
   **A:** Primitive data types include `Number`, `String`, `Boolean`, `Null`, `Undefined`, `Symbol`, and `BigInt`.

2. **Q: What is the difference between `null` and `undefined`?**  
   **A:** `null` represents an intentional absence of a value, while `undefined` means a variable has been declared but not assigned a value.

3. **Q: What is a complex data type?**  
   **A:** Complex data types include objects such as arrays, functions, and objects themselves.

4. **Q: How is an array different from an object in JavaScript?**  
   **A:** An array is a special type of object designed to store indexed elements, whereas an object stores data in key-value pairs.

5. **Q: What is the `typeof` operator?**  
   **A:** The `typeof` operator returns the type of a given variable, such as `string`, `number`, or `object`.

---

### **Statements**
6. **Q: What is a conditional statement in JavaScript?**  
   **A:** Conditional statements like `if`, `else if`, `else`, and `switch` are used to perform different actions based on conditions.

7. **Q: What is the syntax of an `if` statement?**  
   **A:**  
   ```javascript
   if (condition) {
       // code block to execute if condition is true
   }
   ```

8. **Q: What is the difference between `switch` and `if-else`?**  
   **A:** `switch` is used for equality comparisons between a variable and several values, while `if-else` can handle a broader range of conditions, including relational comparisons.

9. **Q: What are looping statements in JavaScript?**  
   **A:** Looping statements like `for`, `while`, and `do...while` are used to execute a block of code repeatedly as long as a specified condition is true.

10. **Q: What is the difference between `while` and `do...while` loops?**  
    **A:** A `while` loop checks the condition before executing the loop block, while a `do...while` loop executes the block at least once before checking the condition.

---

### **Keywords**
11. **Q: What is the difference between `var`, `let`, and `const`?**  
    **A:**  
    - `var` has function or global scope.  
    - `let` has block scope.  
    - `const` is block-scoped and used for variables that cannot be reassigned.

12. **Q: What is the use of the `this` keyword?**  
    **A:** The `this` keyword refers to the object from which the current function was called.

13. **Q: What is `try...catch` used for in JavaScript?**  
    **A:** It is used for handling exceptions and errors gracefully during code execution.

14. **Q: Can you redeclare a variable using `let`?**  
    **A:** No, `let` does not allow redeclaration within the same scope.

15. **Q: What happens if you declare a variable without any keyword?**  
    **A:** The variable is implicitly assigned to the global scope, which is generally discouraged.

---

### **Operators**
16. **Q: What are JavaScript arithmetic operators?**  
    **A:** Arithmetic operators include `+`, `-`, `*`, `/`, `%`.

17. **Q: What is the difference between `==` and `===`?**  
    **A:** `==` checks for value equality after type coercion, while `===` checks for strict equality, including type.

18. **Q: What does the `&&` operator do?**  
    **A:** It returns true if both operands are true; otherwise, it returns false.

19. **Q: What are assignment operators in JavaScript?**  
    **A:** Assignment operators include `=`, `+=`, `-=`, `*=`, `/=`.

20. **Q: What is the `%` operator?**  
    **A:** The `%` operator returns the remainder of a division operation.

---

### **Practical Usage**
21. **Q: How do you declare a variable in JavaScript?**  
    **A:** Use `var`, `let`, or `const`. Example: `let x = 10;`

22. **Q: How do you access object properties in JavaScript?**  
    **A:** Use dot notation or bracket notation. Example: `objectName.propertyName` or `objectName['propertyName']`.

23. **Q: Write a basic `if` statement to check if a number is positive.**  
    **A:**  
    ```javascript
    if (number > 0) {
        console.log("The number is positive");
    }
    ```

24. **Q: How do you loop through an array using `for`?**  
    **A:**  
    ```javascript
    let arr = [1, 2, 3];
    for (let i = 0; i < arr.length; i++) {
        console.log(arr[i]);
    }
    ```

25. **Q: What is a function in JavaScript?**  
    **A:** A reusable block of code designed to perform a specific task.

---

### **Debugging and Best Practices**
26. **Q: How do you debug JavaScript code?**  
    **A:** By using browser developer tools, `console.log()`, breakpoints, and debugging tools.

27. **Q: What happens if you try to use a variable before declaring it?**  
    **A:** You will get a `ReferenceError` if `let` or `const` is used, or `undefined` if `var` is used due to hoisting.

28. **Q: Why is it better to use `let` and `const` over `var`?**  
    **A:** Because `let` and `const` provide block scope and avoid unintended behavior due to hoisting.

29. **Q: Can a `const` variable be changed?**  
    **A:** No, you cannot reassign a `const` variable, but you can modify the contents if it’s an object or array.

30. **Q: What does `NaN` mean?**  
    **A:** `NaN` stands for "Not-a-Number" and indicates an invalid number result.

---

### **Advanced Questions**
31. **Q: What is type coercion in JavaScript?**  
    **A:** Automatic or implicit conversion of values from one data type to another, such as converting a string to a number.

32. **Q: Can JavaScript handle asynchronous operations?**  
    **A:** Yes, using promises, async/await, or callback functions.

33. **Q: What are template literals?**  
    **A:** Strings enclosed by backticks (`) that allow embedded expressions using `${}`.

34. **Q: What are logical operators in JavaScript?**  
    **A:** `&&`, `||`, `!`.

35. **Q: How do you compare objects in JavaScript?**  
    **A:** Use deep comparison techniques since objects are reference types.

---

### **Practical Scenarios**
36. **Q: Write a `switch` statement to print the day of the week.**  
    **A:**  
    ```javascript
    let day = 3;
    switch (day) {
        case 1: console.log("Monday"); break;
        case 2: console.log("Tuesday"); break;
        case 3: console.log("Wednesday"); break;
        default: console.log("Invalid day");
    }
    ```

37. **Q: How do you concatenate strings in JavaScript?**  
    **A:** Using `+` or template literals. Example:  
    ```javascript
    let result = "Hello" + " World!";
    ```

38. **Q: How do you convert a string to a number?**  
    **A:** Use `Number()`, `parseInt()`, or `parseFloat()`.

39. **Q: Write a program to find the factorial of a number using a loop.**  
    **A:**  
    ```javascript
    let num = 5, factorial = 1;
    for (let i = 1; i <= num; i++) {
        factorial *= i;
    }
    console.log(factorial);
    ```

40. **Q: How can you handle errors in JavaScript?**  
    **A:** By using `try...catch`.

---

### **Miscellaneous**
41. **Q: What is JavaScript?**  
    **A:** JavaScript is a high-level, interpreted programming language used to create dynamic and interactive web content.

42. **Q: Is JavaScript case-sensitive?**  
    **A:** Yes, JavaScript is case-sensitive.

43. **Q: What is the purpose of `break` in a loop?**  
    **A:** To exit the loop immediately.

44. **Q: Can you nest loops in JavaScript?**  
    **A:** Yes, you can nest loops.



-

-

-

## EXP 02 


---

## **Viva Questions and Answers**

### **Defining Functions**
1. **Q: What is a function in JavaScript?**  
   **A:** A function is a block of code designed to perform a specific task, which can be invoked or called multiple times.

2. **Q: How do you define a function in JavaScript?**  
   **A:** You can define a function using the `function` keyword followed by the function name, parameters, and the function body.  
   Example:  
   ```javascript
   function greet(name) {
       console.log("Hello, " + name);
   }
   ```

3. **Q: What is a function expression?**  
   **A:** A function expression defines a function inside an expression. It can be assigned to a variable.  
   Example:  
   ```javascript
   const add = function(a, b) {
       return a + b;
   };
   ```

4. **Q: What are arrow functions in JavaScript?**  
   **A:** Arrow functions provide a shorter syntax for writing functions and are defined using the `=>` syntax.  
   Example:  
   ```javascript
   const multiply = (a, b) => a * b;
   ```

5. **Q: What is a named function?**  
   **A:** A named function is a function that has a specific name assigned to it.  
   Example:  
   ```javascript
   function subtract(a, b) {
       return a - b;
   }
   ```

---

### **Calling Functions**
6. **Q: How do you call a function in JavaScript?**  
   **A:** A function is called by using its name followed by parentheses, with any required arguments inside the parentheses.  
   Example:  
   ```javascript
   greet("Alice");
   ```

7. **Q: What are default parameters in JavaScript?**  
   **A:** Default parameters allow you to set default values for function parameters if no value is passed.  
   Example:  
   ```javascript
   function greet(name = "Guest") {
       console.log("Hello, " + name);
   }
   ```

8. **Q: What is a callback function?**  
   **A:** A callback function is a function passed as an argument to another function to be executed later.  
   Example:  
   ```javascript
   function fetchData(callback) {
       console.log("Fetching data...");
       callback();
   }
   fetchData(() => console.log("Data fetched!"));
   ```

9. **Q: What is recursion in JavaScript?**  
   **A:** Recursion is a technique where a function calls itself to solve a problem.  
   Example:  
   ```javascript
   function factorial(n) {
       if (n === 0) return 1;
       return n * factorial(n - 1);
   }
   ```

10. **Q: What is the `arguments` object in JavaScript?**  
    **A:** The `arguments` object is an array-like object that contains all the arguments passed to a function, even if they are not named parameters.

---

### **Arguments**
11. **Q: Can you pass more arguments than defined parameters in a function?**  
    **A:** Yes, you can pass more arguments than defined parameters, and they will be accessible through the `arguments` object.

12. **Q: What is the spread operator used for in functions?**  
    **A:** The spread operator (`...`) is used to pass an indefinite number of arguments to a function as an array.  
    Example:  
    ```javascript
    function sum(...numbers) {
        return numbers.reduce((a, b) => a + b);
    }
    ```

13. **Q: What is the rest parameter in JavaScript?**  
    **A:** The rest parameter (`...`) allows you to represent an indefinite number of arguments as an array.  
    Example:  
    ```javascript
    function sum(...args) {
        return args.reduce((acc, curr) => acc + curr, 0);
    }
    ```

14. **Q: What is the purpose of the `return` statement in JavaScript?**  
    **A:** The `return` statement is used to exit a function and optionally send a value back to the caller.

15. **Q: What happens if a function does not have a return statement?**  
    **A:** If a function does not explicitly return a value, it returns `undefined` by default.

---

### **Scope**
16. **Q: What is the scope of a variable?**  
    **A:** The scope of a variable defines where it is accessible in your code. It can either be global or local to a function or block.

17. **Q: What is the difference between global and local scope?**  
    **A:** A global variable is accessible anywhere in the code, while a local variable is only accessible within the function or block where it is declared.

18. **Q: What is block-level scope?**  
    **A:** Block-level scope refers to variables declared using `let` or `const`, which are confined to the block, statement, or expression in which they are defined.

19. **Q: What is function scope?**  
    **A:** Function scope refers to variables that are declared inside a function and can only be accessed within that function.

20. **Q: What is lexical scoping?**  
    **A:** Lexical scoping refers to the way functions are nested in JavaScript. Inner functions have access to the variables in their outer functions.

---

### **Function Expressions and Statements**
21. **Q: What is a function expression?**  
    **A:** A function expression defines a function inside an expression, typically assigned to a variable.

22. **Q: How does a function expression differ from a function declaration?**  
    **A:** A function expression is not hoisted, while a function declaration is hoisted and can be used before its definition in code.

23. **Q: Can functions be passed as arguments to other functions?**  
    **A:** Yes, functions can be passed as arguments, which is commonly known as a higher-order function.

24. **Q: How do you return multiple values from a function in JavaScript?**  
    **A:** You can return multiple values using an array, object, or destructuring assignment.

25. **Q: Can you declare a function inside another function?**  
    **A:** Yes, you can declare a function inside another function, and the inner function will have access to the variables of the outer function.

---

### **Advanced Function Concepts**
26. **Q: What is a higher-order function?**  
    **A:** A higher-order function is a function that takes one or more functions as arguments, returns a function as a result, or both.

27. **Q: What is closure in JavaScript?**  
    **A:** A closure is a function that retains access to its lexical environment, even after the function has finished executing.

28. **Q: What are immediately invoked function expressions (IIFE)?**  
    **A:** IIFE is a function that runs as soon as it is defined. It is often used to create a new scope.  
    Example:  
    ```javascript
    (function() {
        console.log("I am an IIFE!");
    })();
    ```

29. **Q: What is a callback hell?**  
    **A:** Callback hell refers to the situation when multiple nested callbacks make the code difficult to read and maintain. This is typically resolved using promises or `async/await`.

30. **Q: What is memoization in JavaScript?**  
    **A:** Memoization is an optimization technique where the results of expensive function calls are stored, and the cached result is returned when the same inputs occur again.

---

### **Practical Usage**
31. **Q: Write a function that takes a number and returns whether it’s even or odd.**  
    **A:**  
    ```javascript
    function checkEvenOdd(number) {
        return number % 2 === 0 ? "Even" : "Odd";
    }
    ```

32. **Q: How do you handle function overloading in JavaScript?**  
    **A:** JavaScript does not support function overloading directly. Instead, you can check the number and type of arguments passed to the function using `arguments` or rest parameters.

33. **Q: How would you write a function that accepts two numbers and returns their sum?**  
    **A:**  
    ```javascript
    function add(a, b) {
        return a + b;
    }
    ```

34. **Q: How do you pass an object to a function in JavaScript?**  
    **A:** You can pass an object by simply passing it as an argument.  
    Example:  
    ```javascript
    const person = { name: "John", age: 30 };
    function greetPerson(person) {
        console.log("Hello, " + person.name);
    }
    greetPerson(person);
    ```

35. **Q: What is the difference between `call()`, `apply()`, and `bind()` in JavaScript?**  
    **A:**  
    - `call()` invokes the function immediately with the specified `this` value and arguments.  
    - `apply()` is similar to `call()`, but the arguments are passed as an array.  
    - `bind()` returns a new function with the specified `this`

## exp 3


---

## **Viva Questions and Answers**

### **Understanding JavaScript Events**
1. **Q: What is an event in JavaScript?**  
   **A:** An event is an action or occurrence detected by JavaScript, such as a mouse click, keypress, or page load.

2. **Q: What are some common events in JavaScript?**  
   **A:** Common events include `click`, `mouseover`, `mouseout`, `keydown`, `keyup`, `submit`, `load`, `resize`, and `focus`.

3. **Q: What is event handling in JavaScript?**  
   **A:** Event handling is the process of responding to user interactions with elements on a web page by executing a specified function.

4. **Q: What is the difference between `onload` and `onclick` events?**  
   **A:** `onload` occurs when the web page or an image is fully loaded, while `onclick` triggers when an element is clicked.

5. **Q: What is the DOM in the context of event handling?**  
   **A:** The DOM (Document Object Model) is a programming interface that allows JavaScript to interact with and manipulate HTML elements and handle their events.

---

### **Attaching Event Listeners**
6. **Q: How do you attach an event listener to an element in JavaScript?**  
   **A:** Use the `addEventListener()` method.  
   Example:  
   ```javascript
   document.getElementById("button").addEventListener("click", handleClick);
   ```

7. **Q: What is the syntax of the `addEventListener` method?**  
   **A:** `element.addEventListener(event, function, useCapture);`

8. **Q: What is the difference between inline event handling and `addEventListener`?**  
   **A:** Inline event handling adds the event directly in HTML (`onclick="functionName()"`), while `addEventListener` separates JavaScript from HTML and allows multiple listeners.

9. **Q: How do you remove an event listener?**  
   **A:** Use the `removeEventListener()` method.  
   Example:  
   ```javascript
   element.removeEventListener("click", handleClick);
   ```

10. **Q: Can you attach multiple event listeners to the same element?**  
    **A:** Yes, you can attach multiple event listeners to the same element, and they will execute in the order they were added.

---

### **Types of Events**
11. **Q: What are mouse events in JavaScript?**  
    **A:** Mouse events include `click`, `dblclick`, `mousedown`, `mouseup`, `mouseover`, `mousemove`, and `mouseout`.

12. **Q: What are keyboard events?**  
    **A:** Keyboard events include `keydown`, `keyup`, and `keypress`.

13. **Q: What is the difference between `keydown` and `keypress`?**  
    **A:** `keydown` triggers when a key is pressed, while `keypress` triggers when a printable character key is pressed.

14. **Q: What is the `submit` event used for?**  
    **A:** The `submit` event is triggered when a form is submitted.

15. **Q: What is the difference between `focus` and `blur` events?**  
    **A:** `focus` occurs when an element gains focus (e.g., a text field), and `blur` occurs when the focus is lost.

---

### **Event Object**
16. **Q: What is the event object in JavaScript?**  
    **A:** The event object contains information about the event, such as its type, target element, and additional details like mouse position or key pressed.

17. **Q: How do you access the event object in an event handler?**  
    **A:** The event object is passed as a parameter to the event handler function.  
    Example:  
    ```javascript
    element.addEventListener("click", function(event) {
        console.log(event.target);
    });
    ```

18. **Q: What is the `event.target` property?**  
    **A:** It refers to the element that triggered the event.

19. **Q: What is the `event.type` property?**  
    **A:** It returns the type of the event (e.g., `click`, `mouseover`).

20. **Q: What is the purpose of `preventDefault()`?**  
    **A:** It prevents the default behavior of an event, such as stopping a form submission or a link redirection.  
    Example:  
    ```javascript
    event.preventDefault();
    ```

---

### **Event Propagation**
21. **Q: What is event propagation?**  
    **A:** Event propagation is the process of event execution through the DOM, starting from the target element and moving outward or inward.

22. **Q: What are the phases of event propagation?**  
    **A:** The phases are capturing phase, target phase, and bubbling phase.

23. **Q: What is the difference between event capturing and event bubbling?**  
    **A:** In capturing, the event starts from the root and moves to the target. In bubbling, it starts from the target and propagates to the root.

24. **Q: How do you stop event propagation?**  
    **A:** Use the `stopPropagation()` method to prevent the event from propagating further.  
    Example:  
    ```javascript
    event.stopPropagation();
    ```

25. **Q: Can you prevent both default behavior and propagation in an event?**  
    **A:** Yes, by calling `event.preventDefault()` and `event.stopPropagation()` in the same event handler.

---

### **Event Delegation**
26. **Q: What is event delegation?**  
    **A:** Event delegation is a technique where a single event listener is added to a parent element to handle events for its child elements.

27. **Q: Why is event delegation useful?**  
    **A:** It improves performance by reducing the number of event listeners and ensures dynamic elements are also handled.

28. **Q: How do you implement event delegation?**  
    **A:** Attach a listener to the parent and use `event.target` to determine the clicked child.  
    Example:  
    ```javascript
    document.getElementById("parent").addEventListener("click", function(event) {
        if (event.target.tagName === "BUTTON") {
            console.log("Button clicked!");
        }
    });
    ```

29. **Q: What is the disadvantage of event delegation?**  
    **A:** It can lead to unwanted behavior if not properly filtered for specific child elements.

30. **Q: Can event delegation handle dynamically created elements?**  
    **A:** Yes, it is one of the primary advantages of event delegation.

---

### **Advanced Concepts**
31. **Q: What is `once` in `addEventListener`?**  
    **A:** The `once` option ensures the event listener is executed only once.  
    Example:  
    ```javascript
    element.addEventListener("click", handleClick, { once: true });
    ```

32. **Q: What is throttling in JavaScript events?**  
    **A:** Throttling limits the number of times a function executes over time, often used with scroll or resize events.

33. **Q: What is debouncing in JavaScript events?**  
    **A:** Debouncing delays the execution of a function until after a specified delay has passed since the last event.

34. **Q: What are synthetic events in JavaScript?**  
    **A:** Synthetic events are abstractions used in frameworks like React to normalize native DOM events across browsers.

35. **Q: Can an element trigger multiple events simultaneously?**  
    **A:** Yes, for example, a `click` event might trigger both a `mousedown` and `mouseup` event.

---

### **Practical Usage**
36. **Q: Write an example of handling a `mouseover` event.**  
    **A:**  
    ```javascript
    element.addEventListener("mouseover", () => {
        console.log("Mouse is over the element!");
    });
    ```

37. **Q: How do you handle multiple events with a single handler?**  
    **A:** Use `switch` or conditional statements inside the handler to differentiate events.  
    Example:  
    ```javascript
    element.addEventListener("click", handleEvent);
    element.addEventListener("mouseover", handleEvent);

    function handleEvent(event) {
        switch (event.type) {
            case "click":
                console.log("Clicked!");
                break;
            case "mouseover":
                console.log("Mouse Over!");
                break;
        }
    }
    ```

38. **Q: How can you trigger an event programmatically?**  
    **A:** Use the `dispatchEvent` method.  
    Example:  
    ```javascript
    element.dispatchEvent(new Event("click"));
    ```

39. **Q: How do you log the key pressed during a `keydown` event?**  
    **A:**  
    ```javascript
    document.addEventListener("keydown", (event) => {
        console.log("Key pressed: " + event.key);
    });
    ```

40. **Q: How do you bind an event handler dynamically?**  
    **A:** By attaching it to an element programmatically using `addEventListener`.

---

## exp 4


---

## **Viva Questions and Answers**

### **Basics of DOM**
1. **Q: What is the DOM in JavaScript?**  
   **A:** The DOM (Document Object Model) is a programming interface for HTML and XML documents that represents the structure of a webpage as a tree of objects.

2. **Q: What are the main components of the DOM?**  
   **A:** The DOM consists of three main components:  
   - **Elements** (HTML elements as objects)  
   - **Attributes** (properties of elements)  
   - **Text** (content inside elements)

3. **Q: What is the difference between the DOM and the BOM?**  
   **A:** The DOM is used to access and manipulate HTML content, while the BOM (Browser Object Model) provides access to browser features like `window`, `navigator`, and `location`.

4. **Q: How can you access the DOM in JavaScript?**  
   **A:** You can access the DOM using methods like `document.getElementById()`, `document.querySelector()`, or properties like `document.body`.

5. **Q: What is the root element of the DOM?**  
   **A:** The `<html>` element is the root of the DOM tree.

---

### **Accessing DOM Elements**
6. **Q: What is `document.getElementById()`?**  
   **A:** It is a method that retrieves an element by its unique `id` attribute.  
   Example:  
   ```javascript
   const element = document.getElementById("myId");
   ```

7. **Q: What is `document.getElementsByClassName()`?**  
   **A:** It returns a live HTMLCollection of elements with a specific class name.

8. **Q: How does `document.querySelector()` differ from `document.getElementById()`?**  
   **A:** `querySelector()` returns the first element matching a CSS selector, while `getElementById()` retrieves an element by its `id`.

9. **Q: What does `document.querySelectorAll()` do?**  
   **A:** It returns a static NodeList of all elements matching a CSS selector.

10. **Q: What is the difference between `childNodes` and `children`?**  
    **A:**  
    - `childNodes` includes all child nodes (elements, text, and comment nodes).  
    - `children` only includes child elements (no text or comment nodes).

---

### **Modifying HTML Elements**
11. **Q: How do you change the text content of an element?**  
    **A:** Use the `textContent` or `innerHTML` property.  
    Example:  
    ```javascript
    element.textContent = "Hello!";
    ```

12. **Q: What is the difference between `innerHTML` and `textContent`?**  
    **A:**  
    - `innerHTML` can insert HTML tags along with text.  
    - `textContent` inserts plain text and ignores HTML tags.

13. **Q: How do you add a new attribute to an element?**  
    **A:** Use the `setAttribute()` method.  
    Example:  
    ```javascript
    element.setAttribute("class", "newClass");
    ```

14. **Q: How do you remove an attribute from an element?**  
    **A:** Use the `removeAttribute()` method.  
    Example:  
    ```javascript
    element.removeAttribute("class");
    ```

15. **Q: How do you change the style of an element?**  
    **A:** Use the `style` property.  
    Example:  
    ```javascript
    element.style.color = "red";
    ```

---

### **Adding and Removing Elements**
16. **Q: How do you create a new DOM element?**  
    **A:** Use the `document.createElement()` method.  
    Example:  
    ```javascript
    const newDiv = document.createElement("div");
    ```

17. **Q: How do you add an element to the DOM?**  
    **A:** Use methods like `appendChild()` or `append()`.  
    Example:  
    ```javascript
    parentElement.appendChild(newDiv);
    ```

18. **Q: How do you remove an element from the DOM?**  
    **A:** Use the `remove()` method or `removeChild()` on its parent.  
    Example:  
    ```javascript
    element.remove();
    ```

19. **Q: What is the difference between `append()` and `appendChild()`?**  
    **A:**  
    - `append()` allows adding multiple nodes or strings and does not return a value.  
    - `appendChild()` adds a single node and returns it.

20. **Q: How do you replace an existing DOM element?**  
    **A:** Use the `replaceChild()` method.  
    Example:  
    ```javascript
    parentElement.replaceChild(newElement, oldElement);
    ```

---

### **Event Handling in DOM**
21. **Q: How do you attach an event handler to a DOM element?**  
    **A:** Use the `addEventListener()` method.  
    Example:  
    ```javascript
    element.addEventListener("click", handleClick);
    ```

22. **Q: How do you dynamically add a click event to a button?**  
    **A:**  
    ```javascript
    const button = document.createElement("button");
    button.textContent = "Click Me";
    button.addEventListener("click", () => alert("Button clicked!"));
    document.body.appendChild(button);
    ```

23. **Q: How do you handle a `mouseover` event?**  
    **A:**  
    ```javascript
    element.addEventListener("mouseover", () => {
        console.log("Mouse hovered over the element");
    });
    ```

24. **Q: What is the difference between `addEventListener` and inline event handling?**  
    **A:** `addEventListener` separates HTML and JavaScript, allows multiple listeners, and offers more control compared to inline event handling.

25. **Q: How do you stop an event from propagating?**  
    **A:** Use `event.stopPropagation()`.  

---

### **Traversing the DOM**
26. **Q: What is the `parentNode` property in DOM?**  
    **A:** It refers to the parent of the current node.

27. **Q: How do you find all child elements of a node?**  
    **A:** Use the `children` property.  
    Example:  
    ```javascript
    const children = parentElement.children;
    ```

28. **Q: What is the `nextSibling` property?**  
    **A:** It refers to the next sibling node in the DOM.

29. **Q: How do you access the first child of an element?**  
    **A:** Use the `firstChild` or `firstElementChild` property.

30. **Q: What is the difference between `firstChild` and `firstElementChild`?**  
    **A:**  
    - `firstChild` includes any child node (e.g., text or comment).  
    - `firstElementChild` only includes element nodes.

---

### **Modifying Classes**
31. **Q: How do you add a class to an element?**  
    **A:** Use the `classList.add()` method.  
    Example:  
    ```javascript
    element.classList.add("newClass");
    ```

32. **Q: How do you remove a class from an element?**  
    **A:** Use the `classList.remove()` method.  
    Example:  
    ```javascript
    element.classList.remove("oldClass");
    ```

33. **Q: What is the `classList.toggle()` method?**  
    **A:** It adds a class if it is not present and removes it if it is.  
    Example:  
    ```javascript
    element.classList.toggle("active");
    ```

34. **Q: How do you check if an element has a specific class?**  
    **A:** Use the `classList.contains()` method.  
    Example:  
    ```javascript
    if (element.classList.contains("highlight")) {
        console.log("Class is present");
    }
    ```

35. **Q: Can you set multiple classes at once?**  
    **A:** Yes, using `className` or multiple `classList.add()` calls.

---

### **Styling with CSS**
36. **Q: How do you change the background color of an element?**  
    **A:**  
    ```javascript
    element.style.backgroundColor = "blue";
    ```

37. **Q: How do you get the computed style of an element?**  
    **A:** Use `getComputedStyle()`.  
    Example:  
    ```javascript
    const style = window.getComputedStyle(element);
    console.log(style.color);
    ```

38. **Q: How do you add CSS classes dynamically?**  
    **A:** Use `classList.add()` to dynamically apply styles.

39. **Q: What is the difference between inline styles and classes?**  
    **A:** Inline styles are added directly to an element via the `style` attribute, while classes are defined in CSS and applied using `class` attributes.

## exp 5
### **Experiment 5: JavaScript DOM Manipulation**  



---

## **Viva Questions and Answers**

### **Basics of DOM**
1. **Q: What does DOM stand for?**  
   **A:** DOM stands for Document Object Model. It represents the structure of an HTML or XML document as a tree of objects.

2. **Q: Why is the DOM important in JavaScript?**  
   **A:** The DOM allows JavaScript to interact with and manipulate the content, structure, and styles of a web document dynamically.

3. **Q: What are DOM nodes?**  
   **A:** DOM nodes are the elements, attributes, or text in the DOM tree, representing each part of the document.

4. **Q: What are the different types of DOM nodes?**  
   **A:** The main types include:  
   - Element nodes  
   - Attribute nodes  
   - Text nodes  
   - Comment nodes

5. **Q: How do you access the DOM in JavaScript?**  
   **A:** You can access the DOM using methods like `document.getElementById()`, `document.querySelector()`, or `document.getElementsByTagName()`.

---

### **DOM Manipulation Methods**
6. **Q: How do you select an element by its ID?**  
   **A:** Use the `document.getElementById()` method.  
   Example:  
   ```javascript
   let element = document.getElementById('myId');
   ```

7. **Q: What is the purpose of `querySelector()`?**  
   **A:** `querySelector()` selects the first element that matches a CSS selector.  
   Example:  
   ```javascript
   let element = document.querySelector('.className');
   ```

8. **Q: How do you add a new element to the DOM?**  
   **A:** Use `document.createElement()` to create an element and `appendChild()` or `append()` to add it to the DOM.  
   Example:  
   ```javascript
   let newDiv = document.createElement('div');
   document.body.appendChild(newDiv);
   ```

9. **Q: How do you remove an element from the DOM?**  
   **A:** Use the `remove()` method or `removeChild()` on the parent node.  
   Example:  
   ```javascript
   let element = document.getElementById('myId');
   element.remove();
   ```

10. **Q: What is the difference between `innerHTML` and `textContent`?**  
    **A:**  
    - `innerHTML` can set or get the HTML content of an element.  
    - `textContent` sets or gets only the text within an element, ignoring HTML tags.

---

### **DOM Properties**
11. **Q: How do you change the style of an element using JavaScript?**  
    **A:** Use the `style` property of the element.  
    Example:  
    ```javascript
    let element = document.getElementById('myId');
    element.style.color = 'red';
    ```

12. **Q: How do you get the value of an input field?**  
    **A:** Use the `value` property of the input element.  
    Example:  
    ```javascript
    let inputValue = document.getElementById('myInput').value;
    ```

13. **Q: What is the purpose of `classList` in DOM?**  
    **A:** The `classList` property allows adding, removing, or toggling CSS classes on an element.  
    Example:  
    ```javascript
    element.classList.add('newClass');
    ```

14. **Q: How do you set an attribute for an element?**  
    **A:** Use the `setAttribute()` method.  
    Example:  
    ```javascript
    element.setAttribute('src', 'image.jpg');
    ```

15. **Q: What is the `dataset` property?**  
    **A:** The `dataset` property is used to access custom data attributes (`data-*`) on an element.  
    Example:  
    ```javascript
    let dataValue = element.dataset.value;
    ```

---

### **Events in DOM**
16. **Q: What are DOM events?**  
    **A:** DOM events are interactions or changes in the browser, like clicks, key presses, or mouse movements.

17. **Q: How do you add an event listener to an element?**  
    **A:** Use the `addEventListener()` method.  
    Example:  
    ```javascript
    element.addEventListener('click', function() {
        console.log('Element clicked!');
    });
    ```

18. **Q: What is the difference between `onclick` and `addEventListener()`?**  
    **A:**  
    - `onclick` can only bind one event listener to an element.  
    - `addEventListener()` allows multiple listeners for the same event.

19. **Q: What is event bubbling?**  
    **A:** Event bubbling is when an event propagates from the target element up to its ancestors.

20. **Q: How do you stop event bubbling?**  
    **A:** Use the `stopPropagation()` method.  
    Example:  
    ```javascript
    event.stopPropagation();
    ```

---

### **Traversing the DOM**
21. **Q: How do you access the parent of an element?**  
    **A:** Use the `parentNode` or `parentElement` property.

22. **Q: What is the `children` property in DOM?**  
    **A:** The `children` property returns a live HTMLCollection of all child elements of an element.

23. **Q: How do you find the first child of an element?**  
    **A:** Use the `firstChild` or `firstElementChild` property.  
    Example:  
    ```javascript
    let firstChild = element.firstElementChild;
    ```

24. **Q: How do you find the next sibling of an element?**  
    **A:** Use the `nextSibling` or `nextElementSibling` property.

25. **Q: How do you loop through all child elements of an element?**  
    **A:** Use a `for` loop with the `children` property or `forEach()` with `childNodes`.  
    Example:  
    ```javascript
    Array.from(element.children).forEach(child => console.log(child));
    ```

---

### **Advanced DOM**
26. **Q: What is the difference between `NodeList` and `HTMLCollection`?**  
    **A:**  
    - `NodeList` is a static or live collection of nodes.  
    - `HTMLCollection` is always live and only contains element nodes.

27. **Q: How do you clone an element in the DOM?**  
    **A:** Use the `cloneNode()` method.  
    Example:  
    ```javascript
    let clone = element.cloneNode(true);
    ```

28. **Q: What is a shadow DOM?**  
    **A:** Shadow DOM is a part of the web component specification, allowing encapsulation of styles and DOM structure.

29. **Q: How do you defer the execution of a script?**  
    **A:** Use the `defer` attribute in the `<script>` tag.

30. **Q: What is a virtual DOM?**  
    **A:** A virtual DOM is an in-memory representation of the real DOM used in libraries like React for efficient updates.

---

### **Debugging and Errors**
31. **Q: How do you check if an element exists in the DOM?**  
    **A:** Use a conditional check with `document.querySelector()` or `document.getElementById()`.  
    Example:  
    ```javascript
    if (document.getElementById('myId')) {
        console.log('Element exists');
    }
    ```

32. **Q: What happens if you try to access an element that does not exist?**  
    **A:** It returns `null`.

33. **Q: What is a DOMException?**  
    **A:** A DOMException is an error that occurs during DOM-related operations, like `NotFoundError` or `SyntaxError`.

34. **Q: How can you debug DOM issues?**  
    **A:** Use browser developer tools, console logs, or breakpoints in the DOM inspector.

35. **Q: What is the `DOMContentLoaded` event?**  
    **A:** It fires when the HTML document is completely loaded and parsed, without waiting for stylesheets, images, and subframes.

---

### **Practical Examples**
36. **Q: Write JavaScript to change the background color of a `<div>` with ID `box`.**  
    **A:**  
    ```javascript
    document.getElementById('box').style.backgroundColor = 'blue';
    ```

37. **Q: How do you find all elements with a specific class name?**  
    **A:** Use `document.getElementsByClassName()` or `document.querySelectorAll()`.  
    Example:  
    ```javascript
    let elements = document.getElementsByClassName('myClass');
    ```

38. **Q: How do you toggle a class on an element?**  
    **A:** Use the `classList.toggle()` method.  
    Example:  
    ```javascript
    element.classList.toggle('hidden');
    ```

## exp 6



---

## **Viva Questions and Answers**

### **Basics of Form Validation**
1. **Q: What is form validation in JavaScript?**  
   **A:** Form validation ensures the data entered into a form meets specified criteria before being submitted to the server.

2. **Q: What are the types of form validation?**  
   **A:**  
   - **Client-side validation:** Done using JavaScript or HTML5.  
   - **Server-side validation:** Performed on the server.

3. **Q: Why is client-side validation important?**  
   **A:** It improves user experience by providing immediate feedback and reduces server load.

4. **Q: Why do we still need server-side validation?**  
   **A:** Client-side validation can be bypassed, so server-side validation ensures security and data integrity.

5. **Q: Can HTML5 handle validation without JavaScript?**  
   **A:** Yes, HTML5 provides built-in validation using attributes like `required`, `pattern`, `min`, `max`, and `type`.

---

### **Common Validation Techniques**
6. **Q: How do you check if a field is empty in JavaScript?**  
   **A:** Use the `.value` property to check the input field's value.  
   Example:  
   ```javascript
   if (input.value === "") {
       alert("Field cannot be empty");
   }
   ```

7. **Q: How do you validate an email address?**  
   **A:** Use a regular expression.  
   Example:  
   ```javascript
   const emailPattern = /^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6}$/;
   if (!emailPattern.test(email.value)) {
       alert("Invalid email address");
   }
   ```

8. **Q: What is the `required` attribute in HTML5?**  
   **A:** It ensures the field must be filled before form submission.

9. **Q: How do you validate if a password meets specific criteria?**  
   **A:** Use a combination of conditions or regular expressions.  
   Example:  
   ```javascript
   if (password.length < 8 || !/\d/.test(password)) {
       alert("Password must be at least 8 characters and contain a number");
   }
   ```

10. **Q: How do you validate if two fields (e.g., passwords) match?**  
    **A:** Compare their values.  
    Example:  
    ```javascript
    if (password.value !== confirmPassword.value) {
        alert("Passwords do not match");
    }
    ```

---

### **Event Handling in Forms**
11. **Q: What is the `onsubmit` event?**  
    **A:** It triggers when a form is submitted.

12. **Q: How do you prevent a form from submitting when validation fails?**  
    **A:** Use `event.preventDefault()`.  
    Example:  
    ```javascript
    form.addEventListener("submit", (event) => {
        if (!isValid) {
            event.preventDefault();
            alert("Form is invalid");
        }
    });
    ```

13. **Q: What is the `oninput` event?**  
    **A:** It triggers every time the value of an input field changes.

14. **Q: How do you handle form validation when the user leaves a field?**  
    **A:** Use the `onblur` event.  
    Example:  
    ```javascript
    input.addEventListener("blur", () => {
        if (input.value === "") {
            alert("Field is required");
        }
    });
    ```

15. **Q: What is the `change` event in form elements?**  
    **A:** It triggers when the value of a form element changes and loses focus.

---

### **Regular Expressions in Validation**
16. **Q: What is a regular expression?**  
    **A:** A pattern used to match strings or validate input.

17. **Q: How do you validate a phone number?**  
    **A:** Use a regular expression.  
    Example:  
    ```javascript
    const phonePattern = /^\d{10}$/;
    if (!phonePattern.test(phone.value)) {
        alert("Invalid phone number");
    }
    ```

18. **Q: How do you validate input length using JavaScript?**  
    **A:** Use the `.length` property.  
    Example:  
    ```javascript
    if (input.value.length < 5) {
        alert("Input must be at least 5 characters long");
    }
    ```

19. **Q: What is the purpose of the `pattern` attribute in HTML5?**  
    **A:** It defines a regular expression for validating the value of an input field.

20. **Q: How do you use the `pattern` attribute for validation?**  
    **A:**  
    ```html
    <input type="text" pattern="[A-Za-z]{3,}" title="At least 3 letters" required>
    ```

---

### **Handling Errors and Feedback**
21. **Q: How do you display error messages in form validation?**  
    **A:** Use `alert()`, insert messages in the DOM, or display them near the field with CSS.  
    Example:  
    ```javascript
    errorElement.textContent = "Invalid input";
    ```

22. **Q: How can you highlight invalid fields?**  
    **A:** Use CSS to style the field dynamically.  
    Example:  
    ```javascript
    if (!isValid) {
        input.style.borderColor = "red";
    }
    ```

23. **Q: What is the `setCustomValidity()` method?**  
    **A:** It sets a custom error message for validation.  
    Example:  
    ```javascript
    input.setCustomValidity("This field is required");
    ```

24. **Q: How do you reset a form?**  
    **A:** Use the `reset()` method.  
    Example:  
    ```javascript
    form.reset();
    ```

25. **Q: How do you check if a form is valid in JavaScript?**  
    **A:** Use the `checkValidity()` method.  
    Example:  
    ```javascript
    if (!form.checkValidity()) {
        alert("Form is invalid");
    }
    ```

---

### **Advanced Validation**
26. **Q: How do you validate a dropdown selection?**  
    **A:** Check the selected value.  
    Example:  
    ```javascript
    if (dropdown.value === "") {
        alert("Please select an option");
    }
    ```

27. **Q: How do you validate a checkbox group?**  
    **A:** Ensure at least one checkbox is checked.  
    Example:  
    ```javascript
    const checkboxes = document.querySelectorAll("input[type='checkbox']");
    const isChecked = Array.from(checkboxes).some(checkbox => checkbox.checked);
    if (!isChecked) {
        alert("Please select at least one option");
    }
    ```

28. **Q: How do you validate a radio button group?**  
    **A:** Check if one radio button is selected.  
    Example:  
    ```javascript
    const radios = document.querySelectorAll("input[type='radio']");
    const isSelected = Array.from(radios).some(radio => radio.checked);
    ```

29. **Q: How do you handle validation for dynamically added fields?**  
    **A:** Add event listeners to new fields or use delegation.  
    Example:  
    ```javascript
    form.addEventListener("input", (event) => {
        validateField(event.target);
    });
    ```

30. **Q: What is live validation?**  
    **A:** Validation that occurs as the user types or interacts with the form.

---

### **HTML5 Form Validation Features**
31. **Q: What does the `novalidate` attribute do in a form?**  
    **A:** It disables built-in HTML5 validation.

32. **Q: What is the `min` attribute used for in number inputs?**  
    **A:** It sets the minimum acceptable value.

33. **Q: What is the `maxlength` attribute?**  
    **A:** It specifies the maximum number of characters allowed in an input.

34. **Q: How do you use the `step` attribute?**  
    **A:** It defines the increment for numeric input.  
    Example:  
    ```html
    <input type="number" min="0" step="5">
    ```

35. **Q: What is the `title` attribute in form inputs?**  
    **A:** It provides a tooltip with additional instructions.

---

### **Practical Examples**
36. **Q: Write a script to validate a form with name, email, and password fields.**  
    **A:**  
    ```javascript
    form.addEventListener("submit", (event) => {
        if (name.value === "" || !emailPattern.test(email.value) || password.length < 8) {
            event.preventDefault();
            alert("Form is invalid");
        }
    });
    ```

37. **Q: How do you validate a date field?**  
    **A:** Compare the input value with `new Date()`.  

## exp 7

### **Experiment 7: JavaScript Events - Event Handling, Types of Events, and Event Propagation**  



---

## **Viva Questions and Answers**

### **Basics of Events**
1. **Q: What is an event in JavaScript?**  
   **A:** An event is an interaction or occurrence, such as a mouse click, keypress, or form submission, that can be handled using JavaScript.

2. **Q: How do you handle events in JavaScript?**  
   **A:** Events can be handled using inline HTML attributes, DOM properties (`onclick`), or `addEventListener()`.

3. **Q: What is the `addEventListener()` method?**  
   **A:** `addEventListener()` attaches an event handler to an element without overwriting existing event handlers.

4. **Q: What is the syntax for `addEventListener()`?**  
   **A:**  
   ```javascript
   element.addEventListener(event, handler, useCapture);
   ```

5. **Q: What are the advantages of `addEventListener()` over `onclick`?**  
   **A:**  
   - It allows multiple event handlers for the same event.  
   - It supports capturing and bubbling phases.  
   - It provides better separation of HTML and JavaScript.

---

### **Types of Events**
6. **Q: What are the different types of events in JavaScript?**  
   **A:**  
   - Mouse Events (`click`, `dblclick`, `mousemove`, `mousedown`, `mouseup`)  
   - Keyboard Events (`keydown`, `keypress`, `keyup`)  
   - Form Events (`submit`, `focus`, `blur`, `change`)  
   - Window Events (`load`, `resize`, `scroll`, `unload`)  
   - Touch Events (`touchstart`, `touchend`, `touchmove`)

7. **Q: What is a mouse event?**  
   **A:** Mouse events are triggered by interactions with the mouse, such as clicks or movements.

8. **Q: How do you detect a key press in JavaScript?**  
   **A:** Use `keydown`, `keyup`, or `keypress` events on an element.  
   Example:  
   ```javascript
   document.addEventListener('keydown', (e) => {
       console.log(e.key);
   });
   ```

9. **Q: What is a form event?**  
   **A:** A form event occurs when users interact with a form element, such as submitting or focusing.

10. **Q: What is the `load` event?**  
    **A:** The `load` event occurs when the entire page, including resources like images and scripts, is fully loaded.

---

### **Event Properties**
11. **Q: What is the `event` object in JavaScript?**  
    **A:** The `event` object contains information about the event, such as its type, target element, and more.

12. **Q: How do you get the target element of an event?**  
    **A:** Use the `target` property of the `event` object.  
    Example:  
    ```javascript
    element.addEventListener('click', (e) => {
        console.log(e.target);
    });
    ```

13. **Q: What is the difference between `target` and `currentTarget`?**  
    **A:**  
    - `target`: Refers to the actual element that triggered the event.  
    - `currentTarget`: Refers to the element to which the event listener is attached.

14. **Q: What is the `type` property of an event?**  
    **A:** The `type` property returns the type of the triggered event (e.g., `click`, `keydown`).

15. **Q: How do you prevent the default behavior of an event?**  
    **A:** Use the `preventDefault()` method.  
    Example:  
    ```javascript
    element.addEventListener('submit', (e) => {
        e.preventDefault();
    });
    ```

---

### **Event Propagation**
16. **Q: What is event propagation?**  
    **A:** Event propagation is the flow of events through the DOM hierarchy, consisting of three phases: capturing, target, and bubbling.

17. **Q: What is event bubbling?**  
    **A:** Event bubbling occurs when an event starts at the target element and propagates up to its ancestors.

18. **Q: What is event capturing?**  
    **A:** Event capturing occurs when an event propagates from the root element down to the target element.

19. **Q: How do you stop event propagation?**  
    **A:** Use the `stopPropagation()` method.  
    Example:  
    ```javascript
    element.addEventListener('click', (e) => {
        e.stopPropagation();
    });
    ```

20. **Q: What is the difference between `stopPropagation()` and `stopImmediatePropagation()`?**  
    **A:**  
    - `stopPropagation()`: Prevents the event from reaching parent elements.  
    - `stopImmediatePropagation()`: Prevents the event from reaching other handlers on the same element and its parent elements.

---

### **Event Delegation**
21. **Q: What is event delegation?**  
    **A:** Event delegation is a technique where a single event listener is attached to a parent element to handle events on its child elements.

22. **Q: Why use event delegation?**  
    **A:**  
    - Reduces the number of event listeners in the DOM.  
    - Handles dynamically added elements.

23. **Q: How do you implement event delegation?**  
    **A:** Use the `target` property of the event object to identify the clicked element.  
    Example:  
    ```javascript
    document.getElementById('parent').addEventListener('click', (e) => {
        if (e.target.className === 'child') {
            console.log('Child clicked!');
        }
    });
    ```

24. **Q: What are the limitations of event delegation?**  
    **A:**  
    - May become complex for deeply nested elements.  
    - Does not work for certain events like `blur` and `focus`.

25. **Q: What is the difference between inline event handlers and delegated event handlers?**  
    **A:** Inline handlers are directly assigned in HTML, while delegated handlers use a parent element to listen for events.

---

### **Advanced Concepts**
26. **Q: What is the difference between `mouseenter` and `mouseover`?**  
    **A:**  
    - `mouseenter`: Does not bubble; triggered when the mouse enters the target element.  
    - `mouseover`: Bubbles; triggered when the mouse enters the target or its child elements.

27. **Q: What is the `once` option in `addEventListener()`?**  
    **A:** The `once` option ensures that the event listener is executed only once.  
    Example:  
    ```javascript
    element.addEventListener('click', handler, { once: true });
    ```

28. **Q: How do you remove an event listener?**  
    **A:** Use the `removeEventListener()` method.  
    Example:  
    ```javascript
    element.removeEventListener('click', handler);
    ```

29. **Q: What is the `passive` option in event listeners?**  
    **A:** The `passive` option improves performance by letting the browser know that the event listener will not call `preventDefault()`.

30. **Q: What is throttling in event handling?**  
    **A:** Throttling ensures that an event handler is executed at most once in a specified time interval.

---

### **Practical Examples**
31. **Q: How do you change the text of a button when clicked?**  
    **A:**  
    ```javascript
    document.getElementById('button').addEventListener('click', (e) => {
        e.target.textContent = 'Clicked!';
    });
    ```

32. **Q: How do you detect a double-click event?**  
    **A:** Use the `dblclick` event.  
    Example:  
    ```javascript
    element.addEventListener('dblclick', () => console.log('Double clicked!'));
    ```

33. **Q: How do you handle a keyboard event for the Enter key?**  
    **A:**  
    ```javascript
    document.addEventListener('keydown', (e) => {
        if (e.key === 'Enter') {
            console.log('Enter key pressed');
        }
    });
    ```

34. **Q: How do you prevent a right-click context menu?**  
    **A:**  
    ```javascript
    document.addEventListener('contextmenu', (e) => e.preventDefault());
    ```

35. **Q: How do you handle a form submission event?**  
    **A:**  
    ```javascript
    form.addEventListener('submit', (e) => {
        e.preventDefault();
        console.log('Form submitted');
    });
    ```

---



---
## exp 8
## **Viva Questions and Answers**

---

### **Introduction to AJAX**
1. **Q: What is AJAX?**  
   **A:** AJAX (Asynchronous JavaScript and XML) is a technique for creating dynamic, fast, and interactive web applications by sending and receiving data asynchronously without reloading the webpage.

2. **Q: What does AJAX stand for?**  
   **A:** Asynchronous JavaScript and XML.

3. **Q: Why is AJAX used?**  
   **A:** To improve user experience by allowing data to be updated dynamically without a full page reload.

4. **Q: Can AJAX only work with XML?**  
   **A:** No, AJAX can handle various data formats, including JSON, XML, HTML, and plain text.

5. **Q: What are the core technologies used in AJAX?**  
   **A:**  
   - HTML and CSS for presentation.  
   - JavaScript for interactivity.  
   - XML/JSON for data exchange.  
   - XMLHttpRequest or Fetch API for server communication.

---

### **XMLHttpRequest Basics**
6. **Q: What is the `XMLHttpRequest` object?**  
   **A:** It is a JavaScript object used to send and receive HTTP requests and responses asynchronously.

7. **Q: How do you create an `XMLHttpRequest` object?**  
   **A:**  
   ```javascript
   const xhr = new XMLHttpRequest();
   ```

8. **Q: What are the main methods of `XMLHttpRequest`?**  
   **A:**  
   - `open(method, URL, async)`  
   - `send(data)`  
   - `setRequestHeader(header, value)`

9. **Q: What is the difference between `GET` and `POST` in AJAX?**  
   **A:**  
   - `GET` requests data from the server (used for fetching).  
   - `POST` sends data to the server (used for updates or uploads).

10. **Q: How do you send a GET request using `XMLHttpRequest`?**  
    **A:**  
    ```javascript
    xhr.open("GET", "url", true);
    xhr.send();
    ```

---

### **Working with Fetch API**
11. **Q: What is the Fetch API?**  
    **A:** The Fetch API provides a modern, promise-based way to make HTTP requests in JavaScript.

12. **Q: How do you fetch data using the Fetch API?**  
    **A:**  
    ```javascript
    fetch("url")
      .then(response => response.json())
      .then(data => console.log(data))
      .catch(error => console.error(error));
    ```

13. **Q: What is the difference between `XMLHttpRequest` and Fetch API?**  
    **A:**  
    - Fetch API uses Promises, while `XMLHttpRequest` relies on event-based callbacks.  
    - Fetch API is simpler and more readable.

14. **Q: How do you handle errors in the Fetch API?**  
    **A:** Use `.catch()` to handle network errors or check `response.ok` for HTTP errors.

15. **Q: How can you send a POST request using Fetch?**  
    **A:**  
    ```javascript
    fetch("url", {
        method: "POST",
        headers: {
            "Content-Type": "application/json"
        },
        body: JSON.stringify(data)
    });
    ```

---

### **AJAX Events**
16. **Q: What are the ready states in `XMLHttpRequest`?**  
    **A:**  
    - `0` (UNSENT): Request not initialized.  
    - `1` (OPENED): Connection established.  
    - `2` (HEADERS_RECEIVED): Request received.  
    - `3` (LOADING): Processing request.  
    - `4` (DONE): Request finished, and response is ready.

17. **Q: What is the `onreadystatechange` event?**  
    **A:** An event triggered whenever the ready state changes.

18. **Q: How do you handle asynchronous responses?**  
    **A:** Use the `onreadystatechange` or a callback function to process the server's response.

19. **Q: What is the `onload` event in AJAX?**  
    **A:** It triggers when the request is completed successfully.

20. **Q: How do you monitor AJAX progress?**  
    **A:** Use the `onprogress` event to track the progress of a request.

---

### **JSON and AJAX**
21. **Q: What is JSON?**  
    **A:** JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy to read and write for humans and machines.

22. **Q: How do you parse JSON data in JavaScript?**  
    **A:** Use `JSON.parse()`.  
    Example:  
    ```javascript
    const data = JSON.parse(jsonString);
    ```

23. **Q: How do you convert an object to JSON format?**  
    **A:** Use `JSON.stringify()`.  
    Example:  
    ```javascript
    const jsonString = JSON.stringify(object);
    ```

24. **Q: How do you handle JSON data with Fetch?**  
    **A:** Use `.json()` on the response object.  
    Example:  
    ```javascript
    fetch("url")
      .then(response => response.json())
      .then(data => console.log(data));
    ```

25. **Q: How is JSON different from XML?**  
    **A:**  
    - JSON is more lightweight and easier to parse.  
    - XML supports attributes and hierarchical data better.

---

### **Cross-Origin and Security**
26. **Q: What is CORS?**  
    **A:** CORS (Cross-Origin Resource Sharing) is a mechanism that allows or restricts resources on a web server depending on the origin of the request.

27. **Q: What causes a CORS error?**  
    **A:** A CORS error occurs when the server does not allow requests from a different origin.

28. **Q: How do you solve CORS issues?**  
    **A:** Ensure the server includes the appropriate headers (e.g., `Access-Control-Allow-Origin`) in the response.

29. **Q: What are common security risks with AJAX?**  
    **A:**  
    - Cross-Site Scripting (XSS).  
    - Cross-Site Request Forgery (CSRF).  
    - Insecure data transmission.

30. **Q: How do you secure AJAX requests?**  
    **A:** Use HTTPS, validate inputs, and implement proper server-side validation.

---

### **Asynchronous Programming**
31. **Q: What is a callback function?**  
    **A:** A function passed as an argument to another function, executed after the operation is complete.

32. **Q: What are Promises?**  
    **A:** Promises are objects representing the eventual completion or failure of an asynchronous operation.

33. **Q: What are the states of a Promise?**  
    **A:**  
    - **Pending**  
    - **Fulfilled**  
    - **Rejected**

34. **Q: How do you handle Promises?**  
    **A:** Use `.then()` for success and `.catch()` for errors.

35. **Q: What is `async`/`await`?**  
    **A:** Syntactic sugar for Promises, allowing asynchronous code to look synchronous.

---

### **Practical Scenarios**
36. **Q: Write a script to fetch user data from an API and display it.**  
    **A:**  
    ```javascript
    fetch("https://api.example.com/users")
      .then(response => response.json())
      .then(data => {
          data.forEach(user => console.log(user.name));
      });
    ```

37. **Q: How do you handle timeouts in AJAX?**  
    **A:** Use `timeout` in `XMLHttpRequest` or a manual timeout with Fetch.

38. **Q: What is long polling in AJAX?**  
    **A:** A technique where the client repeatedly requests updates from the server.

39. **Q: What is the difference between polling and WebSockets?**  
    **A:** Polling involves repeated requests, while WebSockets provide real-time, two-way communication.

40. **Q: How do you upload a file using AJAX?**  
    **A:** Use `FormData` with `XMLHttpRequest` or Fetch.

---

### **Error Handling**
41. **Q: What is the `status` property in `XMLHttpRequest`?**  
    **A:** It represents the HTTP status code of the response.

42. **Q: How do you check for a successful response in Fetch?**  
    **A:** Check `response.ok`.  
    Example:  
    ```javascript
    if (!response.ok) {
        throw new Error("HTTP error");
    }
    ```

43. **Q: How do you log AJAX errors to the console?**  
    **A:** Use the `console.error()` method.

44. **Q: How do you retry a failed AJAX request?**  
    **A:** Use a loop or recursion to retry after a failure.

45. **Q: What is the `try...catch` block used for in Fetch?**  
    **A:** To handle synchronous errors in asynchronous code.

---

