# Part I: Foundations of Programming

Before getting started, make sure that you have a JavaScript console open (like <a href="http://www.repl.it/languages/javascript" target="_blank">repl.it</a>), so you can complete these exercises.

## Exercises

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2
   ```
   ```js
   3 * 5
   ```
   ```js
   5 / 4 - 13
   ```
   Notice that the order of presedence, the division happend before, the subtraction.
   ```js
   5000 * 234
   ```
   ```js
   1073 / 57 + 200
   ```
   Again, [PEMDAS](https://en.wikipedia.org/wiki/Order_of_operations) determins the order of operations.

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1
   ```
   ```js
   (3 + 2) * (4 - 1)
   ```
   You can override the order of operations, by useing the [Grouping Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping)
   
3. Calculate how old you are in minutes using the console.
   ```js
       
      // You can use the following outline as a template
      ((( years * 364 ) + days ) * numberOfHoursInADay * numberOfMinuetesInAnHour )
   
   ```

4. What is the percentage of people in the class with brown hair? Use the
   console to find out.

5. Try the following expressions in the console:

   ```js
   6 % 2
   ```
   ```js
   42 % 10
   ```
   ```js
   5 % 2
   ```
   ```js
   6 % 3
   ```
   ```js
   7 % 4
   ```
   ```js
   100 % 12
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?

6. Try the following:

   ```js
   3 % 2
   ```
   ```js
   4 % 2
   ```
   ```js
   5 % 2
   ```
   ```js
   6 % 2
   ```

   What do the results tell you about the first operand to the modulus operator?

#### Strings

1. Write a string that represents your full name.

2. Write a string that represents your favorite food.

3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   + Your parents' full names
   + Your home town and state

4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?
   ```
