## Checking if a number is positive, negative, or zero

This example demonstrates how to use an **`if-else`** block to determine whether 
a number is positive, negative, or zero. 

### The blocks

- **`{  }[=]{  }`** (In **Logic** category)
  - This is a ***logical*** block that can be used to compare two values.
    - The result of a comparison is either `true` or `false`.
  - The empty space **`{  }`** in the block can be a variable or a value.
  - A logical block is usually used with an **`if do`** block.

- **`if {logical block} do {blocks to be executed}`** (In **Logic** category)
  - This block allows a program to execute **`blocks to be executed`** only 
    if `logical block` evaluates to `true`.

  - This block can also be configured to support "if-else" or "if-elseif-else" logical statements.
    For more information, see <a href="https://github.com/google/blockly/wiki/IfElse" target="_blank">IfElse blockly block</a>.
  
- **`get the [numerical] value of input with id [<id value>]`** (In **Html** category)
  - It gets the numerical value from the `<input id="id value">` element.

  **Note**: If we need an input value for arithmetic calculations, we must select a `numerical` 
  input type instead of `text`.

### What does this blockly program do?

Whenever the "CHECK" button is clicked, the program
- gets the numerical value from the `<input>` element and store it in the variable `num`
- sets the value of the variable `numberType` to one of "Positive", "Negative", or "Zero" (based on the value of `num`)
- displays the value of the variable `numberType`