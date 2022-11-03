# Two Number Sum ✩

<span style="color:blue">some *blue* text</span>

- Category: Arrays
- Difficulty: Easy 
- Successful Submissions: 155,434+

Write a function that takes in a non-empty array of distinct integers and an integer representing a
target sum. If any two numbers in the input array sum up to the target sum, the function should
return them in an array, in any order. If no two numbers sum up to the target sum, the function
should return an empty array.

Note that the target sum has to be obtained by summing two different integers in the array; you
can't add a single integer to itself in order to obtain the target sum.
You can assume that there will be at most one pair of numbers summing up to the target sum.

>**Sample Input**
><br/>array = [3, 5, -4, 8, 11, 1, −1, 6]
><br/>targetSum= 10

>**Sample Output**
<br/>[-1, 11] // the numbers could be in reverse order

### Solution

```
function twoNumberSum(array, targetSum) {
  array.map((element) => {
    firstNum = element
    array.map((e) => {
      secondNum = e
      if(e + element === targetSum) console.log("targetSum", element, e);
    })
  })
}

const array = [1, 2, 3, 4, 5, 6];
const targetSum = 10;

twoNumberSum(array, targetSum);

// Do not edit the line below.
exports.twoNumberSum = twoNumberSum;
```

- Prompt Scratchpad Solutions Video Explanation
- [Reference](https://www.algoexpert.io/questions/two-number-sum)
- [Markdown Colored Text](https://stackoverflow.com/questions/23904274/is-there-a-way-to-get-colored-text-in-githubflavored-markdown)
- [Additional Unicode](https://apps.timwhitlock.info/emoji/tables/unicode)
- [Markdown Cheat Sheet](https://support.squarespace.com/hc/en-us/articles/206543587-Markdown-cheat-sheet)
