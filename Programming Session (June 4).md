## Programming Session (June 4)

### Timings

| Section                     | Time    |
| --------------------------- | ------- |
| Basic Variables             | 10 min  |
| Basic Data Types            | 20 min  |
| Data Types Review           | 10 min  |
| Basic Functions             | 25 min  |
| Functions Activity in Spike | 20 min  |
| **Total**                   | 85  min |

### Basic Variables

If you're doing pre-algebra or algebra in school, you might have learned about variables. **Variables** are a way of assigning a value to a word, character, or name.

**They are useful** for many reasons. One reason is just to make your code more readable. Variables can help you break down your code so it's easier for yourself and others to understand. A basic example is if I'm adding the numbers 2 and 3 together in code. I can make the variables `addend1` and `addend2` so I know what the numbers 2 and three are. Variables are also useful for storing values. Let's say I do some complex calculations. I would want to store the end result in a variable so I can avoid doing those calculations the next time I need the result from them.

### Basic Data Types

**Data types** a way of restricting the possible values of a variable. **They are useful** because mostly, a variable is only going to have a value of one data type. It will reduce the amount of bugs we have in our code because we're not accidentally setting an incorrect value to a variable. For example, let's say you are making a game where you earn money. Your `money` variable will always be a number, so you can set the data type of that variable to be only a number.

**The three basic data types** are numbers, strings, and booleans. **Numbers** are fairly straightforward. 3 is a number, -0.5 is a number, but the word "ball" is not a number. **Strings** are a fancy coding term that just means text. Text of any length can be represented as a string—from one character to multiple paragraphs. **Booleans** are another fancy coding term. They are just yes/no values. For example, in your money-earning game, let's say you can buy a house. You can make a variable `doesOwnHouse` that will be a boolean—either you own a house or you don't.

### Data Types Review

**Q:** What is the data type of `0`? **A:** Number

**Q:** What is the data type of `"variable"`? **A:** String

**Q:** What is the data type of `"0"`? **A:** String

**Q:** What is the data type of `true`? **A:** Boolean

**Q:** What is the data type of `"false"`? **A:** String

### Basic Functions

**Functions** are a list of instructions assigned to a variable. An example of a function in your money-earning game is `addMoney`. This function is a list of steps (or in this case, one step): add 1 dollar to the `money` variable. This command is stored to the word `addMoney`, and in order to run the command, just execute the `addMoney` variable. **In the Spike app, functions are called "MyBlocks"**. To execute a MyBlock, just drag it from the left pane onto your code.

However, functions are slightly more complex than that. Functions can also have **arguments, parameters, inputs**, or whatever you want to call them. For sake of simplicity, lets call them inputs. Inputs are a way of defining a variable for the function to access. For example, in your money-earning game, if you earn $5, you don't want to execute `addMoney` 5 times. Instead, you make a variable called `moneyToBeAdded`. So now, `addMoney`'s steps have changed. Instead of adding 1 dollar, you add `moneyToBeAdded` dollars. This works well, but there is a better way. You can make an input to `addMoney`. Lets call it `amount`. Now, when you execute `addMoney`, you also give it a value for `amount`. It's the same thing as making a new variable, like the example above. However, it is much more concise and easy to read. Now, your `addMoney` function takes in 1 input: `amount`. The steps for `addMoney` are: add `amount` dollars to `money`.

### Functions Activity

Make the simple money-earning game described throughout the lesson. Your code should meet the following requirements:

- Have a `money` variable
- Have an `addMoney` function that takes in an `amount` input. It should add `amount` to `money` and set `money` to the resulting value