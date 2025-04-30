# Part 1 Questions

1. `value added: 20`

2. `final result: 20`
   
3. You should not use `var` because it does not follow block rules and can used outside the place that it was written, which can cause bugs. 
   
4. `value added: 20`

5. Nothing is printed. The code returns an error because `result` is declared using `let` inside the `if` block and cannot access anything outside that block. Line 13 is outside of the code block so it will throw an error.

6. Nothing is printed. The code returns an error because `result` is declared using `const` and when you use `const` you can't change the value of the variable. When line 7: `result = num1 + num2;` runs it causes an error because the value of `result` can't change.

7. Nothing is printed. There is an error for line 7 so nothing gets printed for line 13. But there is still an error with line 13 because `result` is still blocked since it's outside of the `if` block.