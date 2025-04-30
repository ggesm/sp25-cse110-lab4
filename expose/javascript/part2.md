# Part 2 Questions

1. At line 12, the value `3` will be printed. The variable `i` was declared with `var` so there are no blocks and `i` can remain outside the for loop. It prints the value `3` because after the loop finishes `i` has the value of `3`.
   
2. At line 13, the value `150` is printed because the last loop iteration is for the price `300` and the value of `discountedPrice` is `150`.

3. At line 14, the value `150` will be printed because the last loop iteration is for the price `300` and the value of `finalPrice` is `150`.

4. The function should return: `[50, 100, 150]`. There is no error that is stopping the code from runnning so each price will go through the for loop and output the discounted price that was `0.5`. It will go through each price on the list and apply the 0.5 discount and adds that discounted value into a new list. After all the prices are done then it will return the new list.

5. At line 12, there is an error because `i` is declared using `let` and it is inside the for loop block and cannot access anything outside that block. Line 12 is outside of the code block so it will throw an error.

6. At line 13, there is an error because `discountedPrice` is declared using `let` and it is inside the for loop block and cannot access anything outside that block. Line 13 is outside of the code block so it will throw an error

7. At line 14, the value `150` will be printed because the last loop iteration is for the price `300` and the value of `finalPrice` is `150`. It does not cause an error because finalPrice is not declared using `let` so it is accessible throughout the entire function. 

8. The function should return: `[50, 100, 150]`. `let` doesn't stop the function from running properly so there are no errors that are stopping the code from running. 

9. At line 11, there is an error because `i` is declared using `let` and it is inside the for loop block and cannot access anything outside that block. Line 11 is outside of the code block so it will throw an error.

10. At line 12, the value `3` will be printed because `length` is declared with `const` so you can access it anywhere in the function. You can't reassign it but you can read its value without any issues. 

11. The function should return: `[50, 100, 150]`. `let` and `const` don't stop the function from running properly so there are no errors that are stopping the code from running.

12. A. `student.name`<br>
    B. `student["Grad Year"]`<br>
    C. `student.greeting()`<br>
    D. `student["Favorite Teacher"].name`<br>
    E. `student.courseLoad[0]`<br>

13. A. Output: `32`<br>
    Explanation: The `+` operator with a string causes string concatenation.<br><br>
    B. Output: `1`<br>
    Explanation: The `-` operator only works with numbers so `3` is converted to an integer and `3 - 2 = 1`<br><br>
    C. Output: `3`<br>
    Explanation: `null` is equal to `0` when adding it to `3` so `3 + 0 = 3`<br><br>
    D. Output: `3null`<br>
    Explanation: The `+` operator with a string causes string concatenation.<br><br>
    E. Output: `4`<br>
    Explanation: `true` is equal to `1` when adding it to `3` so `1 + 3 = 4`<br><br>
    F. Output: `0`<br>
    Explanation: Both `false` and `null` are equal to `0` and when adding them together you get `0`<br><br>
    G. Output: `3undefined`<br>
    Explanation: The `+` operator with a string causes string concatenation.<br><br>
    H. Output: `NaN` <br>
    Explanation: The `-` operator only works with numbers so `3` is converted to an integer and `undefined` is represented as `NaN`, so `3 - NaN = NaN`<br><br>

14. A. Output: `true`<br>
    Explanation: `2` is turned into a number because `1` is a number then `2 > 1` is `true`<br><br>
    B. Output: `false`<br>
    Explanation: Both values are strings so a lexicographical comparison is done amd it does it in order of the characters so `'2'` comes after `'1'` in character order so `'2' < '12'` is `false`<br><br>
    C. Output: `true`<br>
    Explanation: `==` changes types because there is number, then `'2'` becomes `2` so `2 == 2` is `true`<br><br>
    D. Output: `false`<br>
    Explanation: `===` checks both balue and type and it sees that `2` is number and `'2'` is a string so it is `false` <br><br>
    E. Output: `false`<br>
    Explanation: `true` is equal to `1` when comparing it to a number so `1 == 2` is `false`<br><br>
    F. Output: `true`<br>
    Explanation: `Boolean(2)` equals to `true` because it is not `0` and both sides are the same type and value so it is `true`<br><br>

15. The difference between `==` and `===` is that `==` checks if the values are the same after changing types if needed, while `===` checks if both value and type are exactly the same.