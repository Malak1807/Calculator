<<<<<<< HEAD
# Calculator

Clean calculator made in the browser with vanilla HTML, CSS, and JavaScript.

## Features

- Basic operations: adding, subtracting, multiplying, dividing
- Parentheses for grouping operations
- Decimal point key
- Display of inputted expression, preview of resulting value
- **Keyboard functionality** - type expressions instead of pressing keys
- Backspace (DEL) to delete the last character
- All Clear (AC) for resetting the expression


## Keys Supported By the Application

 `0-9` - Digits  
 `+ - * / .` - Operations and decimal separator  
 `( )` - Parenthesis  
 `Enter` or `=` - Calculate  
 `DEL` - Backspace 

## Operation principle

Expression is accumulated in an input area where no more than 15 characters are visible (more are counted but not displayed). Hitting `=` or `Enter` causes the expression from the input to be passed into JS `eval()` which computes the value of the expression (limited to 5 significant figures), and displays the result below with a preview to the full 10 significant figures, ready for chaining into the next operation.

## Errors

Errors (like invalid expressions) return `undefined` instead of terminating program execution.
Division by zero follows JavaScript behavior and returns `Infinity`.


## Notes

- `x` on screen is equivalent to `*` for calculations.
- There is no strict expression limit; only the display window has an upper character limit of 15. Full-length expressions are always calculated properly.
- Decimal places for result precision can be adjusted in the `compute()` method by changing parameters in `toPrecision()`: 5 for result calculation, and 10 for reloading typed expression after calculations.
=======
#Calculator  
A calculator that performs basic calculations. You can press keys on your keyboard in addition to the buttons.
>>>>>>> 1dfc1d4583740506062a7cff0b4d5f01c239a8f1
