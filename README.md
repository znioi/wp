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

Here’s the polished version of the README for GitHub:

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
