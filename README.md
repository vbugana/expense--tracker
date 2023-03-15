# Expense Tracker Application

Keep track of income and expenses. Add and remove items and save to local storage

## Description

This is a JavaScript code for a simple expense tracker application. The application allows the user to add and remove transactions, and displays the total balance, income, and expense.

The code starts by defining constants for HTML elements (balance, money_plus, money_minus, list, form, text, and amount) and getting the transactions from the local storage. If the local storage does not have any transactions, an empty array is created.

The addTransaction function is triggered when the user submits the form. It checks if the text and amount fields are not empty, and if not, it creates a new transaction object with a random ID and the values from the text and amount fields. The new transaction is added to the transactions array, added to the DOM using the addTransactionDOM function, and the values are updated using the updateValues function. The new transaction is also saved to the local storage, and the text and amount fields are cleared.

The generateID function generates a random ID for a transaction.

The addTransactionDOM function creates a new list item element and sets its class to "minus" or "plus" depending on the sign of the transaction amount. It then sets the innerHTML of the item element to the text and amount of the transaction, and adds a delete button that calls the removeTransaction function with the ID of the transaction.

The updateValues function calculates the total balance, income, and expense by mapping the transaction amounts to an array, reducing the array to a total amount, and filtering and reducing the array for income and expense separately. The amounts are formatted to two decimal places and displayed on the HTML elements.

The removeTransaction function removes a transaction from the transactions array by filtering out the transaction with the specified ID, updates the local storage, and updates the DOM and values by calling the init function.

The updateLocalStorage function updates the local storage with the current transactions array.

The init function clears the list element, adds all transactions to the DOM using the addTransactionDOM function, and updates the values using the updateValues function.

Finally, the init function is called to initialize the application, and the addTransaction function is bound to the submit event of the form element to handle adding new transactions.

## Project Specifications

- Create UI for project
- Display transaction items in DOM
- Show balance, expense and income totals
- Add new transation and reflect in total
- Delete items from DOM
- Persist to local storage

## Technologies Used

![HTML 5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS 3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## 😂 Here is a random joke that'll make you laugh!

![Jokes Card](https://readme-jokes.vercel.app/api)

https://mdb.pushkaryadav.in/generate

