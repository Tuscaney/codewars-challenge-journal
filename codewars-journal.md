### Challenge 1: Remove String Spaces (8kyu)

- **Link:** https://www.codewars.com/kata/57eae20f5500ad98e50002c5
- **Description:** Write a function that removes all spaces from a string.
- **My Solution:**
  ```js
  function noSpace(x) {
    return x.replace(/\s/g, '');
  }

- What I Learned:
This challenge helped reinforce using regular expressions in JavaScript. The \s matches whitespace, and the g flag removes all occurrences. I originally considered using a loop or split/join, but .replace() with regex was simpler and more efficient.

- Other Notes:
It's great to see how concise string manipulation can be using built-in methods.

### Challenge 2: Sum of Positive (8kyu)

- **Link:** https://www.codewars.com/kata/5715eaedb436cf5606000381
- **Description:**  
  Given an array of numbers, return the sum of all positive numbers. If no positive numbers exist, return 0.

- **My Solution:**
  ```js
  function positiveSum(arr) {
    return arr.filter(n => n > 0).reduce((sum, n) => sum + n, 0);
  }

- What I Learned:
This challenge helped me practice array methods. I used .filter() to extract positive numbers and .reduce() to calculate the sum. It reminded me that chaining methods can keep code concise and readable.

- Other Notes:
I originally considered looping manually, but using built-in methods made the solution shorter and more elegant.