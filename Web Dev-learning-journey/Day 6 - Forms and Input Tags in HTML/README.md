# Day 6 - HTML Forms and Input Tags

## 📝 Overview
Day 6 focused on understanding **HTML Forms** and the different types of **input tags** used to gather user data on a web page. Forms are one of the most important components in web development, enabling interaction between users and the application.

## 📚 Key Concepts
- **Forms**: A structure for collecting user data, utilizing various input fields.
- **Input Tags**: Different types of input elements used for capturing different kinds of data.
- **Attributes**: How attributes like `action`, `name`, `placeholder`, and `autofocus` enhance the functionality of forms.

## 🔑 Main Topics Covered

1. ### **Form Element**
   - The `<form>` tag is used to define a form and encapsulates all the input elements.
   - The `action` attribute specifies where the form data will be sent upon submission.

   ```html
   <form action="post">
   ```

2. ### **Text Input**
   - The `<input type="text">` tag is used to capture single-line text inputs like usernames.

   ```html
   <label for="Username"> Enter your Username </label>
   <input type="text" id="Username" name="Username" placeholder="Enter your Username" autofocus>
   ```

3. ### **Radio Buttons**
   - `<input type="radio">` is used when users need to select one option from a group (e.g., gender selection).

   ```html
   <input type="radio" id="male" name="gender" value="male">
   <label for="male">Male</label>
   <input type="radio" id="female" name="gender" value="female">
   <label for="female">Female</label>
   ```

4. ### **Textarea**
   - The `<textarea>` tag allows users to input multiple lines of text.

   ```html
   <label for="comment">Enter your comment</label>
   <textarea name="comment" rows="4" cols="50"></textarea>
   ```

5. ### **Dropdown Menu**
   - The `<select>` tag defines a dropdown list of options, where users can pick one value from a list.

   ```html
   <label for="fruits">Choose a fruit:</label>
   <select name="fruits">
       <option value="apple">Apple</option>
       <option value="banana">Banana</option>
       <option value="cherry">Cherry</option>
   </select>
   ```

## 🚀 What's Next?
In the next session, I will dive deeper into **form validation** and explore how to ensure that form data is valid before submission.

## 🔗 Resources
- **GitHub Repository**: [Day 6 - HTML Forms and Inputs](https://github.com/Itssanthoshhere/Sigma-Web-Dev/tree/main/Web%20Dev-learning-journey/Day%206%20-%20Forms)
- **CodeWithHarry HTML Playlist**

## 🏷️ Tags
HTML Forms, Input Tags, Web Development, Web Design, Learning Journey, CodeWithHarry

