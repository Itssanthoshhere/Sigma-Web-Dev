# Day 4: Images, Lists, and Tables in HTML

On **Day 4**, I learned how to use **HTML elements** to work with **Images**, **Lists**, and **Tables**. These elements are essential for displaying structured content in a clean and organized manner.

---

## 🌐 Overview

This project explores the following concepts:
- **Images** (`<img>`): Display images with height, source, and alternate text.
- **Lists**:
  - **Unordered Lists (`<ul>`)**: Present bullet-pointed items.
  - **Ordered Lists (`<ol>`)**: Present numbered or lettered items.
- **Tables** (`<table>`): Organize data in rows and columns, with header and footer sections.

---

## 📂 File Structure

```
Day 4 - Images, Lists, and Tables
│
├── index.html         # HTML file with images, lists, and tables
└── README.md          # Project documentation
```

---

## 📝 Commented HTML Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">  <!-- Character encoding set to UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  <!-- Responsive design settings -->
    <title>Images</title>  <!-- Title of the webpage -->
</head>

<body>
    <!-- Image element to display an image with height and alternate text -->
    <img height='230' src="image.png" alt="Train image">  <!-- Displays an image of a train -->

    <br>  <!-- Line break for spacing -->

    <!-- Table structure -->
    <table>
        <!-- Caption providing context about the table -->
        <caption>Employee Details</caption>
        
        <!-- Table header containing column names -->
        <thead>
            <tr>
                <th>Name</th>
                <th>Designation</th>
                <th>Fav Language</th>
            </tr>
        </thead>

        <!-- Table body with employee details -->
        <tbody>
            <tr>
                <td>Sandy</td>
                <td>Programmer</td>
                <td>C++</td>
            </tr>
            <tr>
                <td colspan="2">Sam</td>
                <td rowspan="2">Java</td>
            </tr>
            <tr>
                <td colspan="2">Ram</td>
            </tr>
        </tbody>

        <!-- Table footer -->
        <tfoot>
            <tr>
                <td colspan="2">Ajay</td>
                <td rowspan="2">Python</td>
            </tr>
        </tfoot>
    </table>

    <!-- Unordered list with square bullets -->
    <ul type="square">
        <li>Sandy</li>
        <li>Vishal</li>
        <li>Ravi</li>
    </ul>

    <!-- Ordered list with alphabetic order (A, B, C) -->
    <ol type="A">
        <li>Sandy</li>
        <li>Hashu</li>
        <li>Dheekshu</li>
    </ol>

</body>

</html>
```

---

## 🚀 What's Next?

Next, I’ll explore **HTML Forms** and how to handle user inputs for building interactive web pages.

---

## 🔗 Connect with Me
- **LinkedIn:** [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)
- **GitHub:** [Itssanthoshhere](https://github.com/Itssanthoshhere)
