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


