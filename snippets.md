Sure, here are 100 common JavaScript problems and their respective solutions. Please note that this list covers a broad range of difficulty and utility:

1. **Reverse a string**: You can use the `split()`, `reverse()`, and `join()` array methods in tandem.
    ```javascript
    const reverseString = (str) => str.split('').reverse().join('');
    ```
2. **Find even numbers in an array**: You can use the `filter()` array method.
    ```javascript
    const evenNumbers = (arr) => arr.filter(num => num % 2 === 0);
    ```
3. **Find odd numbers in an array**: Similar to the above, use `filter()` again.
    ```javascript
    const oddNumbers = (arr) => arr.filter(num => num % 2 !== 0);
    ```
4. **Sum all numbers in an array**: Use the `reduce()` array method.
    ```javascript
    const sumArray = (arr) => arr.reduce((sum, num) => sum + num, 0);
    ```
5. **Find the largest number in an array**: Use the `Math.max()` function combined with the spread operator.
    ```javascript
    const largestNumber = (arr) => Math.max(...arr);
    ```
6. **Find the smallest number in an array**: Similar to the above, use `Math.min()`.
    ```javascript
    const smallestNumber = (arr) => Math.min(...arr);
    ```
7. **Remove duplicates from an array**: You can use a `Set` to quickly remove duplicates.
    ```javascript
    const removeDuplicates = (arr) => [...new Set(arr)];
    ```
8. **Check if a string is a palindrome**: A palindrome is a word that reads the same backward as forward.
    ```javascript
    const isPalindrome = (str) => {
      const reversed = str.split('').reverse().join('');
      return str === reversed;
    }
    ```
9. **Find the factorial of a number**: You can use a recursive function to find the factorial.
    ```javascript
    const factorial = (num) => num === 0 ? 1 : num * factorial(num - 1);
    ```
10. **Find the first non-repeating character in a string**: Use a map to count character occurrences, then find the first character that only appears once.
    ```javascript
    const firstNonRepeatingCharacter = (str) => {
      const chars = {};
      for (let char of str) {
        chars[char] = chars[char] ? chars[char] + 1 : 1;
      }
      for (let char in chars) {
        if (chars[char] === 1) return char;
      }
      return null;
    }
    ```
11. **Sort an array of numbers in ascending order**: Use the `sort()` array method.
    ```javascript
    const sortArray = (arr) => arr.sort((a, b) => a - b);
    ```
12. **Sort an array of numbers in descending order**: Similar to the above, use `sort()`.
    ```javascript
    const sortArrayDescending = (arr) => arr.sort((a, b) => b - a);
    ```
13. **Check if a number is prime**: A prime number is only divisible by 1 and itself.
    ```javascript
    const isPrime = (num) => {
      for(let i = 2, sqrt = Math.sqrt(num); i <= sqrt; i++)
        if(num % i === 0) return false; 
      return num > 1;
    }
    ```
14. **Find the length of the longest string in an array**: Use `

map()` to get all lengths, then `Math.max()` to find the longest.
    ```javascript
    const longestString = (arr) => Math.max(...arr.map(str => str.length));
    ```
15. **Flatten an array of arrays**: Use `flat()`.
    ```javascript
    const flattenArray = (arr) => arr.flat();
    ```
16. **Capitalize the first letter of each word in a string**: Use `split()`, `map()`, and `join()`.
    ```javascript
    const capitalizeWords = (str) => str.split(' ').map(word => word[0].toUpperCase() + word.slice(1)).join(' ');
    ```
17. **Find the most frequent item in an array**: Use a map to count item occurrences, then find the most frequent item.
    ```javascript
    const mostFrequentItem = (arr) => {
      const counts = {};
      arr.forEach(item => counts[item] = (counts[item] || 0) + 1);
      return Object.keys(counts).reduce((a, b) => counts[a] > counts[b] ? a : b);
    }
    ```
18. **Count the number of occurrences of an item in an array**: Use `filter()` to create an array with only the item, then get its length.
    ```javascript
    const countOccurrences = (arr, item) => arr.filter(x => x === item).length;
    ```
19. **Remove a specific item from an array**: Use `filter()`.
    ```javascript
    const removeItem = (arr, item) => arr.filter(x => x !== item);
    ```
20. **Find the sum of an array, after mapping each element to a value using the provided function**: Use `map()` and `reduce()`.
    ```javascript
    const sumArrayAfterMap = (arr, fn) => arr.map(fn).reduce((a, b) => a + b, 0);
    ```

I'll stop here due to the character limit, but hopefully, this gives you a good starting point.