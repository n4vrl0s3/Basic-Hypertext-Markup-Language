# HTML Form Tutorial

This tutorial demonstrates how to create a basic HTML form. The tutorial is divided into two parts:

1. **Form.html**: This file contains a simple form with basic input elements such as text, email, password, radio buttons, checkboxes, dropdown menus, and text areas.
2. **Form Extended.html**: This file extends the basic form by adding fieldsets for better organization, additional input types like date and number, and a multiple select dropdown for hobbies.

Both files include step-by-step comments to guide you through the process of creating and enhancing HTML forms.

## Example: Basic Form (Form.html)

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" /><br /><br />

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" /><br /><br />

  <input type="submit" value="Submit" />
</form>
```

## Example: Extended Form (Form Extended.html)

```html
<form>
  <fieldset>
    <legend>Personal Information</legend>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" /><br /><br />

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" /><br /><br />
  </fieldset>

  <input type="submit" value="Submit" />
</form>
```
