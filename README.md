# React-Mini-Practice

## Project 1: Menu App

Build a simple restaurant-style menu that displays a list of items.  
Each item should have a **name**, **price**, an **availble** boolean and a button to “Add to Order.”

### Requirements
- In your App.jsx create an array of food items (name + price + id + available (boolean)).
- Create a `Menu` component to display each Food Item.
- Pass the individual item as props to a `MenuItem` component.
- Each `MenuItem` should display:
  - The food name
  - The price
  - A button (like “Add to Order”)
  - A way to indicate to the user whether the item is available or not
- When the button is clicked, call a function passed down from the parent (e.g. `handleAdd(itemName)`).
- The parent function should `console.log` or `alert` something like:  
  `"Added [itemName] to order!"
