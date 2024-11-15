## Processing array items one by one

This example demonstrates how to use a loop to iterate through the items in an array one by one. 


### The blocks 

- **`for each item [item] in array {<array variable>}`**
  - This block iterates through the items in an array one by one.
  - If the array has `N` items, then the loop will iterate `N` times. 
  - In each iteration, the variable `item` takes the value of an array item, 
    starting from the first item.

### What does this blockly program do?

The program displays the array items one by one in an unordered list.

It accomplishes this by using the **`for each item in array`** block to iterate through 
the array items one by one:
- In the first iteration, `item` takes the value "Apple", so the program add
`<li>Apple</li>` to the selected list.
- In the second iteration, `item` takes the value "Banana", so the program add
`<li>Banana</li>` to the selected list.
- In the third iteration, `item` takes the value "Peach", so the program add
`<li>Peach</li>` to the selected list.

