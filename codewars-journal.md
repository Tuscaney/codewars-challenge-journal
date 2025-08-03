### Challenge 1: Remove String Spaces (8kyu)

- **Link:** https://www.codewars.com/kata/57eae20f5500ad98e50002c5
- **Description:** Write a function that removes all spaces from a string.
- **My Solution:**
  ```js
  function noSpace(x) {
    return x.replace(/\s/g, '');
  }

What I Learned:
This challenge helped reinforce using regular expressions in JavaScript. The \s matches whitespace, and the g flag removes all occurrences. I originally considered using a loop or split/join, but .replace() with regex was simpler and more efficient.

Other Notes:
It's great to see how concise string manipulation can be using built-in methods.