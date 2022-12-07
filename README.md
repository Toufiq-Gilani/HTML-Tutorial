# HTML TUTORIAL

<br>

## Total 20 Topic

- T1. Introduction to HTML
- T2. Environment Setup
- T3. Check The Markup (HTML, XHTML, …) of Web Documents
- T4. There Are 2 Types of HTML Tag
- T5. Basic Structure of HTML
- T6. Inside Head Tag
- T7. Headings, Paragraphs, Horizontal Rules, Line Breaks
- T8. HTML Text Formatting
- T9. HTML Comments
- T10. HTML Entities
- T11. HTML Links & Images
- T12. HTML Lists
- T13. HTML Block and Inline Elements
- T14. HTML class & id
- T15. HTML Iframes
- T16. HTML Audio & Video
- T17. HTML Canvas & SVG Graphics & Progress Bar
- T18. HTML Forms
- T19. HTML Accessible Form
- T20. HTML Tables

<br>

## Topic 1. Introduction to HTML

- HTML stands for Hyper Text Markup Language.
- HTML is the standard markup language for creating Web pages.
- HTML describes the structure of a Web page.
- HTML elements tell the browser how to display the content.
- With the help of markup tag we can display text, image, video etc. on the webpage.

<br>

## Topic 2. Environment Setup

### Browser
- Google Chrome
- Firefox

### Version Control
- Github

### Editor

- [Visual Studio Code](https://code.visualstudio.com/)
- [Sublime Text](https://www.sublimetext.com/)
- [Codespaces](https://github.com/features/codespaces)
- [Atom](https://atom.io/)
- [Notepad++](https://notepad-plus-plus.org/)
- [Brackets](https://brackets.io/)
- [Vim](https://www.vim.org/)
- [CoffeeCup](https://www.coffeecup.com/)
- [Codepen](https://codepen.io/)
- [Replit](https://replit.com/)

<br>

## Topic 3. Check The Markup (HTML, XHTML, …) of Web Documents

- [After Writing Your HTML Code You Can Check The Validity On This Website](https://validator.w3.org/)

<br>

## Topic 4. There Are 2 Types of HTML Tag

### (1) Pair/container tag and (2) Empty tag.
- Pair tag has starting and ending, Empty tag has no closing tag.
- Some of the example of pair tag and empty tag are given below:

```html
<!-- Some examples of Pair/container tag -->
<html>
 ...
</html>
<head>
 ...
</head>
<body>
 ...
</body>
<p> ... </p>
<h1> ... </h1>

<!-- Some examples of Empty tag -->
<br>
<hr>
<img>
<input>
```

<br>

## Topic 5. Basic Structure of HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Title Here</title>
</head>
<body>
    
</body>
</html>
```

<br>

## Topic 6. Inside Head Tag

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Free Complete HTML Tutorial For Web Development">
    <meta name="keywords" content="HTML, html, html tutorial, web development">
    <meta name="author" content="Toufiq Gilani R">
    <meta name="robots" content="INDEX, FOLLOW">
    <link rel="stylesheet" href="GILANI.css">
    <script src="GILANI.js"></script>
    <title>Title</title>
</head>
<body>
    
</body>
</html>
```

<br>

## Topic 7. Headings, Paragraphs, Horizontal Rules, Line Breaks

```html
<body>
    <!--HTML headings are defined with the <h1> to <h6> tags-->
    <h1>This is Headings 1</h1>
    <h2>This is Headings 2</h2>
    <h3>This is Headings 3</h3>
    <h4>This is Headings 4</h4>
    <h5>This is Headings 5</h5>
    <h6>This is Headings 6</h6>

    <!--The HTML <p> element defines a paragraph-->
    <p>This is a Paragraph.</p>
    <p>This is Another Paragraph.</p>

    <!--This is Horizontal Rules Tag-->
    <hr>

    <!--The HTML <br> element defines a line break-->
    <p>This is<br>a paragraph<br>with line breaks.</p>
</body>
```

<br>

## Topic 8. HTML Text Formatting

```html
<body>
    <b>This Text is Bold</b> <br>
    <strong>This Text is Important!</strong> <br>

    <i>This Text is Italic</i> <br>
    <em>This Text is Emphasized.</em> <br>

    <small>This is Some Smaller Text.</small> <br>

    <mark>Do not forget to buy milk today.</mark> <br>

    <del>My favorite color is blue red.</del> <br>
    <ins>My favorite color is blue red.</ins> <br>

    H<sub>2</sub>O <br>
    (a+b)<sup>2</sup> <br>

    <pre>
        "Amongst the trees, there is a tree,
            the leaves of which do not fall and is like a Muslim.
        Tell me the name of that tree."
            Everybody started thinking about the trees of the desert areas.
        And I thought of the date-palm tree
            but felt shy to answer the others then asked,
        "What is that tree, O Allah's Messenger?"
            He replied, "It is the date-palm tree."
    </pre>
</body>
```

<br>

## Topic 9. HTML Comments

```html
<!-- Write your Comments Here -->
```

<br>

## Topic 10. HTML Entities

```html
&lt; &gt; &nbsp; &pound; &yen; &euro; &copy; &reg;
```

- `&lt;` Create Less Than Symbol.
- `&gt;` Create Greater Than Symbol.
- `&nbsp;` Create Non-Breaking Space Symbol.
- `&pound;` Create Pound Symbol.
- `&yen;` Create Yen Symbol.
- `&euro;` Create Euro Symbol.
- `&copy;` Create Copyright Symbol.
- `&reg;` Create Registered Trademark Symbol.

<br>

## Topic 11. HTML Links & Images

```html
<body>
    <a href="https://www.youtube.com/" target="_blank">Youtube</a>
    <a href="https://www.facebook.com/" target="_blank">Facebook</a>

    <!--Link to an Email Address-->
    <a href="mailto:toufiqjilanirabbu7@gmail.com">Send Mail</a>

    <!--Use an Image as a Link-->
    <a href="" target="_blank">
    <img src="" alt="">
    </a>

    <!--Button as a Link-->
    <button onclick="document.location='default.asp'">HTML Tutorial</button>

    <!--HTML Images-->
    <img src="img_chania.jpg" alt="Images">
    <img src="pineapple.jpg" alt="Images" width="200px" height="200px">
    <img src="pineapple.jpg" alt="Images" style="width: 150px; height: 150px;">
</body>
```

<br>

## Topic 12. HTML Lists

```html
<body>
    <h2>Unordered HTML List</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVA</li>
        <li>PYTHON</li>
        <li>PHP</li>
    </ul>
    <!--The CSS "list-style-type" property is used to define the style of the list item marker-->
    <!--Example - list-style-type: disc; circle; square; none;-->

    <h2>Ordered HTML List</h2>
    <ol>
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVA</li>
        <li>PYTHON</li>
        <li>PHP</li>
    </ol>
    <!--The "type" attribute of the <ol> tag, defines the type of the list item marker-->
    <!--Example - type="1" type="A" type="a" type="I" type="i"-->

    <h2>HTML Description Lists</h2>
    <dl>
        <dt>HTML</dt>
        <dd>Hyper Text Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheets</dd>
        <dt>JS</dt>
        <dd>JavaScript</dd>
        <dt>SQL</dt>
        <dd>Structured Query Language</dd>
        <dt>PHP</dt>
        <dd>PHP: Hypertext Preprocessor</dd>
    </dl>
</body>
```

<br>

## Topic 13. HTML Block and Inline Elements

```html
<body>
    <!--Block-level Elements-->
    <!--Two commonly used block elements are: <p> and <div>-->
    <p style="border: 1px solid teal;">This is Paragraph</p>
    <div style="border: 1px solid tomato;">This is DIV</div>

    <div style="background-color: LightGray; color: DodgerBlue; padding: 20px;">
        <h2>Algeria</h2>
        <p>Algeria is a North African country with a Mediterranean coastline and a Saharan desert interior.</p>
        <p>Many empires have left legacies here, such as the ancient Roman ruins in seaside Tipaza.</p>
    </div>

    <!--Inline Elements-->
    <!--The <span> element is an inline container used to mark up a part of a text, or a part of a document-->
    <p>This is an inline span <span style="border: 1px solid SlateBlue;">Hello World</span> element inside a paragraph.</p>
    <p>My mother has <span style="color: MediumSeaGreen; font-weight: bold;">green</span> eyes.</p>
</body>
```

<br>

## Topic 14. HTML class & id

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML class & id</title>
    <style>
        .para{
            color: red;
            font-size: 120%;
        }
        .align{
            text-align: center;
        }
        .city{
            background-color: tomato;
            color: black;
            border: 2px solid black;
            margin: 20px;
            padding: 20px;
        }

        #header{
            background-color: lightskyblue;
            color: black;
            padding: 40px;
            text-align: center;
        }
    </style>
</head>
<body>
    <!--Using The class Attribute-->
    <h1>My <span class="para">Important</span> Heading</h1>

    <!--Multiple Classes-->
    <div class="city align">
        <h2>Ankara</h2>
        <p>Ankara is the capital of Turkey</p>
    </div>

    <!--Using The class Attribute-->
    <div class="city">
        <h2>Algiers</h2>
        <p>Algiers is the capital of Algeria</p>
    </div>

    <!--Using The id Attribute-->
    <h1 id="header">My Header</h1>
</body>
</html>
```

<br>

## Topic 15. HTML Iframes

```html
<body>
    <iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/X2YnP50cwNU" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen></iframe>
</body>
```

<br>

## Topic 16. HTML Audio & Video

```html
<body>
    <!--HTML Audio-->
    <audio controls autoplay muted>
        <source src="Next One Roa.mp3" type="audio/mpeg">
    </audio>

    <!--HTML Video-->
    <video controls autoplay muted width="500px" height="350px">
        <source src="Aerial Video Of Coastline.mp4" type="video/mp4">
    </video>
</body>
```

<br>

## Topic 17. HTML Canvas & SVG Graphics & Progress Bar

```html
<body>
    <h1>Progress Bar</h1>
    <ol>
        <li>HTML: <progress min="0" max="100" value="70"></progress></li>
        <li>CSS: <progress min="0" max="100" value="30"></progress></li>
        <li>JAVA: <progress min="0" max="100" value="60"></progress></li>
        <li>PYTHON: <progress min="0" max="100" value="80"></progress></li>
    </ol>

    <!--HTML Canvas Graphics-->
    <canvas id="mycanvas" width="500px" height="500px" style="border: 2px solid teal;"></canvas>
    <!--After creating the rectangular canvas area, you must add a JavaScript to do the drawing-->

    <!--HTML SVG Graphics-->
    <img src="Dark_Orange_Burst_Flower.svg" alt="SVG">
</body>
```

<br>

## Topic 18. HTML Forms

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Forms</title>
</head>
<body>
    <h1>Registration Form</h1>
    <form action="#" method="post" autocomplete="on">
        <div>
            <label for="firstname">First Name:</label> <input type="text" name="firstname" id="firstname" value="Gilani" readonly>
        </div>
        <br>
        <div>
            <label for="lastname">Last Name:</label> <input type="text" name="lastname" id="lastname" value="Toufiq" disabled>
        </div>
        <br>
        <div>
            <label for="myemail">Email:</label> <input type="email" name="myemail" id="myemail" size="50" autofocus>
        </div>
        <br>
        <div>
            <label for="mypassword">Password:</label> <input type="password" name="mypassword" id="mypassword">
        </div>
        <br>
        <div>
            <label for="phone">Phone:</label> <input type="tel" name="phone" id="phone" maxlength="15" placeholder="123-456-789">
        </div>
        <br>
        <div>
            <label for="website">Your Website url:</label> <input type="url" name="website" id="website" required>
        </div>
        <br>
        <div>
            <label for="age">Enter your Age:</label> <input type="number" name="age" id="age" min="18" max="35" value="25">
        </div>
        <br>
        <div>
            <label for="mydate">Date of Birth:</label> <input type="date" name="mydate" id="mydate">
        </div>
        <br>
        <div>
            <label for="month">Fav Month:</label> <input type="month" name="month" id="month">
        </div>
        <br>
        <div>
            <label for="color">Select Fav Color:</label> <input type="color" name="color" id="color">
        </div>
        <br>
        <div>
            <label for="anger">Anger Control:</label> <input type="range" name="anger" id="anger" min="0" max="50">
        </div>
        <br>
        <div>
            <label for="file">Choose your File:</label> <input type="file" name="file" id="file">
        </div>
        <br>
        <div>
            <h4>Choose your favorite Web language:</h4>
            <div>
                <input type="radio" name="language" id="html" value="html"> <label for="html">HTML</label> <br>
                <input type="radio" name="language" id="css" value="css"> <label for="css">CSS</label> <br>
                <input type="radio" name="language" id="java" value="java"> <label for="java">JavaScript</label>
            </div>
        </div>
        <br>
        <div>
            <h4>Choose your Religion:</h4>
            <div>
                <input type="checkbox" name="select" id="islam" value="islam"> <label for="islam">Islam</label> <br>
                <input type="checkbox" name="select" id="islam" value="islam"> <label for="islam">Islam</label> <br>
                <input type="checkbox" name="select" id="islam" value="islam"> <label for="islam">Islam</label>
            </div>
        </div>
        <br>
        <div>
            <label for="department">Department:</label>
            <select name="department" id="department">
                <option value="CSE">CSE</option>
                <option value="EEE">EEE</option>
                <option value="LLB">LLB</option>
            </select>
        </div>
        <br>
        <div>
            <label for="mycar">Car:</label>
            <select name="mycar" id="mycar">
                <option value="tes">Tesla</option>
                <option value="ben">Bentley</option>
            </select>
        </div>
        <br>
        <div>
            <label for="message">Message:</label> <br>
            <textarea name="message" id="message" cols="50" rows="10"></textarea>
        </div>
        <br>
        <div>
            <input type="submit" value="Submit">
            <input type="reset" value="Clear">
        </div>
    </form>
</body>
</html>
```

<br>

## Topic 19. HTML Accessible Form

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Form</title>
</head>
<body>
    <form action="https://formspree.io/f/xdojepok" method="post">
        <div>
            <label for="name">Your Name:</label>
            <input name="name" id="name" type="text">
        </div>
        <br>
        <div>
            <label for="email">Your Email:</label>
            <input name="email" id="email" type="email">
        </div>
        <br>
        <div>
            <label for="message">Your Message:</label> <br>
            <textarea name="message" id="message" cols="30" rows="10"></textarea>
        </div>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

<br>

## Topic 20. HTML Tables

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tables</title>
    <style>
        table, th, td{
            border: 1px solid #008080;
            border-collapse: collapse;
        }
        th, td{
            border-color: #14274E;
            text-align: center;
            padding: 50px;
        }
        tr:nth-child(even) {
            background-color: #99F3BD;
        }
        tr:nth-child(odd) {
            background-color: #ED6663;
        }
        th:nth-child(even), td:nth-child(even) {
            background-color: #3DB2FF;
        }
        tr:hover{
            background-color: #B42B51;
        }
        tr{
            border-bottom: 2px solid #005691;
        }
    </style>
    <!-- border-radius: 10px; border-style: dotted; border-spacing: 30px; rowspan="2" <colgroup> Vertical Table Headers -->
</head>
<body>
    <table style="width: 100%;">
        <caption>World War I</caption>
        <thead>
            <tr>
                <th colspan="2">Allied Powers</th>
                <th colspan="2" style="width: 60%;">Central Powers</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>France</td>
                <td>British Empire</td>
                <td>Germany</td>
                <td>Austria-Hungary</td>
            </tr>
            <tr style="height: 300px;">
                <td>Russia</td>
                <td>Serbia</td>
                <td>Ottoman Empire</td>
                <td>Bulgaria</td>
            </tr>
            <tr>
                <td>Belgium</td>
                <td>Portugal</td>
                <td>Wilhelm II</td>
                <td>Franz Joseph I</td>
            </tr>
            <tr>
                <td>Romania</td>
                <td>Montenegro</td>
                <td>Mehmed V</td>
                <td>Ferdinand I</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

<br>

# HTML-TUTORIAL
