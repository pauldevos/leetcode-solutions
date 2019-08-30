## Easy

| #    | Problem                                                                                                   | Solution                                   |   Time comp.    |  Space com.  | Notes                                          |
| :--- | --------------------------------------------------------------------------------------------------------- | :----------------------------------------- | :-------------: | :----------: | :--------------------------------------------- |
| 1    | [Two Sum](https://leetcode.com/problems/two-sum/)                                                         | [JS](js/two-sum.js)                        |     _O(n)_      |    _O(n)_    | Array, Hash Table                              |
| 7    | [Reverse Integer](https://leetcode.com/problems/reverse-integer/)                                         | [JS](js/reverse-integer.js)                |   _O(log n)_    |    _O(1)_    | Math, Array                                    |
| 9    | [Palindrome Number](https://leetcode.com/problems/palindrome-number/)                                     | [JS](js/palindrome-number.js)              |   _O(log n)_    |    _O(1)_    | Math, Array                                    |
| 13   | [Roman to Integer](https://leetcode.com/problems/roman-to-integer/)                                       | [JS](js/roman-to-integer.js)               |     _O(n)_      |    _O(1)_    | Math, String, Hash Table                       |
| 14   | [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)                             | [JS](js/longest-common-prefix.js)          | _O(n * min(s))_ |    _O(1)_    | String, Array                                  |
| 20   | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)                                     | [JS](js/valid-parentheses.js)              |     _O(n)_      |    _O(n)_    | String, Stack                                  |
| 21   | [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)                           | [JS](js/merge-two-sorted-lists.js)         |    _O(n+m)_     |    _O(1)_    | Linked List                                    |
| 26   | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | [JS](js/remove-duplicates-sorted-array.js) |     _O(n)_      |    _O(1)_    | Array, Two Pointers                            |
| 27   | [Remove Element](https://leetcode.com/problems/remove-element/)                                           | [JS](js/remove-element.js)                 |     _O(n)_      |    _O(1)_    | Array, Two Pointers                            |
| 28   | [Implement strStr()](https://leetcode.com/problems/implement-strstr/)                                     | [JS](js/implement-strStr.js)               |    _O(n*m)_     |    _O(n)_    | String, Two Pointers                           |
| 35   | [Search Insert Position](https://leetcode.com/problems/search-insert-position/)                           | [JS](js/search-insert-position.js)         |   _O(log n)_    |    _O(1)_    | Array, Binary Search                           |
| 38   | [Count and Say](https://leetcode.com/problems/count-and-say/)                                             | [JS](js/count-and-say.js)                  |        ?        |      ?       | String                                         |
| 53   | [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)                                       | [JS](js/maximum-subarray.js)               |     _O(n)_      |    _O(1)_    | Array, Dynamic Programming, Divide and Conquer |
| 58   | [Length of Last Word](https://leetcode.com/problems/length-of-last-word/)                                 | [JS](js/length-of-last-word.js)            |     _O(n)_      |    _O(1)_    | String                                         |
| 66   | [Plus One](https://leetcode.com/problems/plus-one/)                                                       | [JS](js/plus-one.js)                       |     _O(n)_      |    _O(1)_    | Array                                          |
| 67   | [Add Binary](https://leetcode.com/problems/add-binary/)                                                   | [JS](js/add-binary.js)                     |  _O(Max(n,m))_  | O(Max(n,m))_ | Math, String                                   |
| 69   | [Sqrt(x)](https://leetcode.com/problems/sqrtx/)                                                           | [JS](js/sqrt(x).js)                        |   _O(log n)_    |    _O(1)_    | Math, Binary Search                            |
| 101  | [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/)                                           | [JS](js/symmetric-tree.js)                 |     _O(n)_      |    _O(n)_    | Tree, DFS, BFS                                 |
| 104  | [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)               | [JS](js/max-depth-binary-tree.js)          |     _O(n)_      |    _O(n)_    | Tree, DFS                                      |


## Medium

| #    | Problem                                                                                                                    | Solution                                              | Time comp. |  Space com.   | Notes                                            |
| :--- | -------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------- | :--------: | :-----------: | :----------------------------------------------- |
| 2    | [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)                                                          | [JS](js/add-two-numbers.js)                           |   _O(n)_   |    _O(n)_     | Linked List, Math                                |
| 3    | [Longest Substring without Repeating Chars](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | [JS](js/longest-substring-without-repeating-chars.js) |   _O(n)_   | _O(min(n,m))_ | Hash Table, Two Pointers, String, Sliding Window |
| 8    | [String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/)                                          | [JS](js/string-to-integer-atoi.js)                    |   _O(n)_   |     _O(1)     | Math, String                                     |
| 15   | [3Sum](https://leetcode.com/problems/3sum/)                                                                                | [JS](js/3sum.js)                                      |  _O(n^2)_  |   _O(n^2)_    | Array, Two Pointers                              |
| 36   | [Valid Sudoku](https://leetcode.com/problems/valid-sudoku/)                                                                | [JS](js/valid-sudoku.js)                              |   _O(1)_   |    _O(1)_     | Hash Table                                       |

## Hard

| #    | Problem                                                                                   | Solution                                |     Time comp.     | Space com. | Notes                                     |
| :--- | ----------------------------------------------------------------------------------------- | :-------------------------------------- | :----------------: | :--------: | :---------------------------------------- |
| 4    | [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) | [JS](js/median-two-sorted-arrays.js)    | _O(log min(n, m))_ |   _O(1)_   | Array, Binary Search, Divide and Conquer  |
| 10   | [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) | [JS](js/regular-expression-matching.js) |     _O(n * m)_     | _O(n * m)_ | String, Dynamic Programming, Backtracking |