# Project 1

This project demonstrates the creation of a basic HTML page with a contact form, a table structure, a navigation bar, and image placeholders.

## Table of Contents

- [Form Creation](#form-creation)
- [Table Structure](#table-structure)
- [Navigation Bar](#navigation-bar)
- [Adding Images](#adding-images)

## Form Creation

The contact form includes the following fields:

- Name (text input)
- Email (email input)
- Message (textarea)
- Submit button

Additionally, a radio button group asks how the user found the site (e.g., Google, Social Media).

## Table Structure

A table is created to display sample product data with the following columns:

- Product Name
- Price
- Quantity

The table includes at least 3 products with their respective details and a header row to label the columns.

## Navigation Bar

A simple navigation bar is created with the following links:

- Home
- About
- Contact

The links are organized using an unordered list (`<ul>`).

## Adding Images

A placeholder image is added using [placehold.co](https://placehold.co/300x200). Additionally, a second image with a rounded border is included using the style attribute.

## HTML Code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Project1</title>
    <link rel="stylesheet" href="" />
  </head>
  <body>
    <h1>Navigation Bar</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <h1>Contact Form</h1>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required /><br /><br />
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required /><br /><br />
    <label for="message">Message:</label>
    <textarea id="message" name="message" required></textarea><br /><br />
    <div>
      <label>How did you find us?</label>
      <label>
        <input type="radio" name="referral" value="google" />Google
      </label>
      <label>
        <input type="radio" name="referral" value="friend" />Friend
      </label>
      <label> <input type="radio" name="referral" value="other" />Other </label>
    </div>
    <button type="submit">Submit</button>
    <h1>Tables for products</h1>
    <table>
      <thead>
        <tr>
          <th>Product Name</th>
          <th>Price</th>
          <th>Qty</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>T-shirt</td>
          <td>$1.25</td>
          <td><input type="number" value="1" /></td>
        </tr>
        <tr>
          <td>Key Chain</td>
          <td>$2.25</td>
          <td><input type="number" value="1" /></td>
        </tr>
        <tr>
          <td>Hats</td>
          <td>$6.25</td>
          <td><input type="number" value="1" /></td>
        </tr>
      </tbody>
    </table>
    <h1>Image Placeholder</h1>
    <img
      src="https://via.placeholder.com/300x200/FF0000/FFFFFF"
      alt="Red Placeholder"
    />
  </body>
</html>
```
