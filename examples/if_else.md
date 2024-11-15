## Checking if a number is positive, negative, or zero

This example demonstrates how to use an **`if-else`** block to check if 
a number is positive, negative, or zero. 

### The blocks

- **`if {<condition>} do`**
  - This block allows us to conditionally execute some blocks.
  - It must be used with a "condition" block that evaluates to either `true` or `false`.
  - The blocks specified after the `do` part will only get executed if the condition evaluates to `true`.



  
- **`get the [numerical] value of input with id [<id value>]`** 
  - It gets the numerical value from an `<input>` element identified by the
    attribute `id="<id value>"`.

  **Note**: If we need an input value for arithmetic calculation, we have to select `numerical` 
  instead of `text`.
      
- **`change [<variable name>] by {value}`**
  - It increases the value of the named variable by the specified value.

### What does this blockly program do?

Whenever the SUM button is clicked, the program
- gets the numerical values in the `<input>` elements, and store them in
  variables **`num1`** and **`num2`**, and
- increases the value of **`num1`** by the value of **`num2`** 
  (to calculate **`num1`** + **`num2`**), and
- shows the calculated sum in `<span id="sum">`.
