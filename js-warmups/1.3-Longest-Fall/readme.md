Description
Write a function called longestFall, which accepts an array of integers, and returns the length of the longest consecutive decrease of integers.

The only case that returns 0 is an empty array.

The default sequence length is 1, meaning if the array is non-empty, then there is always at least a sequence of length 1.

Examples

```js
longestFall([5, 3, 1, 3, 0]); // 3, 5-3-1 is the longest consecutive sequence of decreasing integers

longestFall([2, 2, 1]); // 2, 2-1 is the longest consecutive sequence of decreasing integers

longestFall([2]); // 1, 2 is the longest consecutive sequence of decreasing integers

longestFall([5, 4, 4, 4, 3, 2]); // 3, 4-3-2 is the longest

longestFall([9, 8, 7, 6, 5, 6, 4, 2, 1]); // 5, 9-8-7-6-5 is the longest

longestFall([]); // 0
```
