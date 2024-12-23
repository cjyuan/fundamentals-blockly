## Variables

### Preparation ###
You may want to study the following example to prepare for this exercise.
- <a href="../examples.html#example_using_variables" target=_blank>Using variables</a>

---

Suppose we have a value that represents the number of times a user clicks on a given button. Every time a user clicks on this button then this value increases by 1. We will need to keep track of this value so that we can update it. 

We can give this value a label like `click_count` and refer to `click_count` when we need to get the number of clicks. In programming, we call this label a variable. 

ℹ️ A **variable** is a label for some value.
ℹ️ The **state** is any data that gets updated during the running of a program. We use variables to refer to the state in our program.

In this exercise, we're going to create a variable `click_count` and update it when a user clicks on a particular button.
 

We'll start with a button (`<button>`) that a user has clicked 0 times, in the static html.

1. Add an `at the start` block. Inside we are going to add a variable that will keep track of the number of times a user clicks on the button.

2. In the Variables menu, click `create variable...` to create a variable called `click_count`

3. From the Variables menu, create a `set click_count to` block and place it inside the `at the start`

4. Set the value to 0 (from the Values menu)

When a user clicks on the button, we are going to do two things: 
- increase the value of `click_count` by 1
- and change the text of the button to the new value of `click_count`.HTML

5. Add a `when the element with id ... is clicked` block. 

6. Inside this block, add a `change click_count by 1` block from the Variables menu.

7. Add the necessary blocks to set the text content of the button to the value of `click_count`. (You can get this value by selecting the `click_count` block from the Variables menu)

A common pattern will be first setting a variable in the `at the start` block and then modifying it with a `when the element with id ... is clicked` block. We call the first setting of the variable "initialisation".