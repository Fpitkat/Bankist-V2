# Project Learning Summary

This project was a deep dive into JavaScript, focusing on various aspects of the language. Here's a summary of what was learned:

## Working with Arrays

The project involved extensive use of JavaScript arrays. The `splice` method was used to delete elements from an array. This method changes the contents of an array by removing or replacing existing elements.

```javascript
accounts.splice(index, 1);
```

## Event Handling

Event handling in JavaScript was a key part of this project. Event listeners were added to HTML elements to respond to user interactions. The `addEventListener` method was used to set up these listeners.

```javascript
btnSort.addEventListener('click', function (e) {
  e.preventDefault();
  displayMovements(currentAccount, !sorted);
  sorted = !sorted;
});
```

## Working with Numbers

The project also covered how to work with numbers in JavaScript. The `Number` function was used to convert a string to a number. The unary plus (`+`) operator was also used for this purpose.

```javascript
console.log(Number('23'));
console.log(+'23');
```

## DOM Manipulation

Manipulating the Document Object Model (DOM) was another important aspect of this project. The `style` property was used to change the appearance of HTML elements.

```javascript
containerApp.style.opacity = 0;
```

## Form Handling

The project involved handling form inputs. The `value` property was used to get and set the value of form inputs.

```javascript
inputCloseUsername.value = inputClosePin.value = '';
```

This project was a great opportunity to learn and practice these JavaScript concepts. It provided a solid foundation for further exploration of the language.
