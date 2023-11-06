![syntax](https://github.com/nayaba/pw-lesson-03/assets/9198401/2241ee17-9c3d-43c3-a372-0e8cfac26b79)

Hey there, future JavaScripter! Ready to dive into the nuts and bolts of JavaScript? Let's chat about syntax and comments—the grammar and sticky notes of coding.

### What's Syntax?

In human language, syntax is the order of words in a sentence that makes the sentence make sense. "The cat sat on the mat" makes sense because it follows English syntax. But "Mat the on cat sat the" sounds like Yoda tried a bit too hard.

In JavaScript, syntax is pretty much the same deal. It's a set of rules for how to write statements that the computer can understand. Get it right, and the computer does what you want. Get it wrong, and it's like, "I have no idea what you're talking about."


### The Basics of JavaScript Syntax

1. **Statements**: These are like sentences. Each one tells the computer to do something, and they usually end with a semicolon (;).

```javascript
let iceCream = 'chocolate'; // This is a statement.
eat(iceCream); // And so is this.
```

2. **Variables**: Think of variables like containers on your computer that hold information. You can name them almost anything, but it's best to make it meaningful.

```javascript
let myFavoriteFood = 'pizza'; // 'let' is used to declare a variable.
```

3. **Functions**: These are blocks of code that perform a task or calculate a value. You can call a function by its name followed by parentheses ().

```javascript
function sayHello() {
  console.log('Hello there!');
}
sayHello(); // Calls the function to run.
```

4. **Operators**: They're the symbols that tell JavaScript what to do with the variables. Like `+` for addition, `-` for subtraction, etc.

```javascript
let sum = 10 + 5; // Uses the + operator to add numbers.
```

5. **Data Structures**: Arrays and objects help you organize data.

```javascript
let fruits = ['apple', 'banana', 'cherry']; // This is an array.
let car = { make: 'Toyota', model: 'Corolla' }; // This is an object.
```

6. **Case Sensitivity**: JavaScript is case sensitive—`myVariable` and `myvariable` are two different things.

```javascript
let myVariable = 10;
let myvariable = 20; // Not the same as myVariable.
```

### Comments: Your Code's Sidekick

Comments are notes to yourself or others that explain what your code is doing. Think of them as the commentary track on a DVD. They don't affect the code's operation; they're just there for the humans.

There are two types of comments in JavaScript:

1. **Single-line Comments**: Start with two forward slashes `//`. Anything after `//` on that line is ignored by JavaScript.

```javascript
// This is a single-line comment.
let coffee = 'hot'; // This is also a comment, after the code.
```

2. **Multi-line Comments**: Start with `/*` and end with `*/`. Everything in between is a comment, even if it spans multiple lines.

```javascript
/*
  This is a multi-line comment.
  You can write as much as you want here.
  See? We're still going.
*/
let tea = 'green';
```

### Why Comment?

- **Clarification**: Comments can explain what a complex piece of code does.
- **Debugging**: Temporarily comment out parts of code to find a bug.
- **Collaboration**: Others can understand your code more easily.

### Best Practices

- **Don't State the Obvious**: Comment why you're doing something, not what you're doing. `// increments i by 1` isn't helpful when the code is `i++`.
- **Keep It Up-to-Date**: Outdated comments are worse than no comments. If you change the code, change the comments.

### Practice Time!

![8bit-ice-cream](https://github.com/nayaba/pw-lesson-03/assets/9198401/1950d029-084d-46b9-891f-34e4f85fb0bf)

Go on, open up your text editor or a CodePen, and try writing some JavaScript with plenty of comments. Define variables, make a function, and leave yourself notes on what each part does.

Here's a tiny challenge for you:

```javascript
// Change the flavor and see what happens when you run the function!
let iceCreamFlavor = 'strawberry';

function serveIceCream(flavor) {
  console.log('Serving up ' + flavor + ' ice cream!');
}

serveIceCream(iceCreamFlavor); // Don't forget to call the function!
```

See how the comments give context? Now, it's your turn. Have fun, and happy coding! 🎉🍦

[Back to the Wiki](https://github.com/nayaba/pw-wiki)
