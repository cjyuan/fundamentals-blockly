## Array: The Basics

This example gives an overview of ***array*** and demonstrates how to 
- create an **array** 
- get a random element from an array

### Overview

An array is a container that stores data sequentially.

Here is a conceptual view of an array that stores three string values:

`["Apple", "Banana", "Peach"]`

We say "Apple" is the first ***item*** and "Banana" is the second item in the array.
"Peach" is the third item and is also the last item in the array.

We use the terms ***size*** or ***length*** to describe the number of items in an array.
In this example, the size of the array is three.


### The blocks (from the Arrays category)
- **`set [<variable name>] to : create array with {values}`**
  - This combination of blocks creates an array and stores the array in the named variable.
  - When creating an array, we need to manually assign a value to each item in the array.
  - We can adjust the initial size of an array in the following way
    - Step 1: Click the "cog" icon in the **`create array with`** block to activate an array configuration interface
    - Step 2: Drag **`item`** in or out the **`array`** block to adjust the array size
    - Step 3: Click the "cog" icon again to close the configuration interface
      
- **`get a random item from the array {<array variable>}`**
  - It gets a random item from the specified array.

### What does this blockly program do?

It creates an array variable named `fruits` with three items and then displays 
a random value selected from `fruits`.

Note: You need to click the "RUN" button several times to see the random effect.


