# js-dom-lc

Just a starting demo on How to use js with DOM

## Display a box on a text click

- specify an id on the clickable text
- add a script tag before closing body tag
- get the clickable Text Element
- add a click event listener
- write and test a showBox function
- call the function on click event

## Starts only when dom is ready

## Display a shopping list

- declare data

```javascript
const items = [
  {
    name: "Tomatoes",
    quantity: 5
  },
  {
    name: "Potatoes",
    quantity: 3
  },
  {
    name: "Eggs",
    quantity: 12
  },
  {
    name: "Milk",
    quantity: 2
  },
  {
    name: "Mangoes",
    quantity: 3
  }
];
```

- parse the array with a for loop
- for each item add a li html code to a string
- assign the string to the shoppingList element innerHTML property
