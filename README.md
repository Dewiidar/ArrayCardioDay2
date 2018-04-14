# 04 - Array Cardio Day 1 - JavaScript30 Challenge

### Practising: 
Array.prototype.some(),
Array.prototype.every(),
Array.prototype.find(),
Array.prototype.findIndex()

### Notes : 
```javascript
console.log({everyoneAdult}); // print the variable name and its value
```
```javascript
console.table(comments); //logs a table
```

we can create a new array from the current one (except some values) using the spread operator "..."; it convert the values to array items.

```javascript
    var newArray2 = [
      ...comments.slice(0, commentIndex),
      ...comments.slice(commentIndex) //return the value from this index till the end of the original array
    ];
```

## Getting Started

Clone or download the repository to your local drive.

### Prerequisites

What you need to install:

This project was created using Gulp automation tool, you can run the following command to the local repo directory to install all the dev dependencies 

```
npm install
```

### Write gulp in the terminal / command line to run the live server.

## Authors

* **Mohamed Dewidar** - *practising the mentioned methods* - [Linkedin](https://www.linkedin.com/in/mohamed-dewidar-331252153/)

## License

This project is licensed under the MIT License. (open-source)

## Acknowledgments

* Wesbos - *creator of the challenge* - (https://github.com/wesbos/JavaScript30)