# 201 Reading 03

## HTML Lists, Control Flow with JS, and the CSS Box Model

### HTML Lists

You should use an `unordered list` or `ul` in your HTML if you need a non-numbered bullet point style list.

In order to change the bullet style, you would use `list-style` CSS, chosing one of the compatible options.

The main different times to use an `unordered list` vs `ordered list` is when you need the list to be in a specific order & to mark them with a climbing number or roman numeral. Unordered list has completely non-distinct bullet points or dashes.

### CSS Box Model

The Story of Box Model: Margin and Padding are good friends and work together well, but they are not the same person. They both work with four sides of the content. Margin is on the outside, and is an invisible space that pushes others away from itself as they increase in size. Padding is on the inside, and creates space between the border & the content within the box.

Width & Height: The actual size of the box
Margin: The white space outside of the box
Border: Placed between the margin & the padding, this is the edge of the box
Padding: White space inside of the box between border & content

### Arrays. Operators & Expressions. Loops

You can store various data types in arrays - strings, numbers, objects, and even other arrays. (Mozilla.org)

I believe this is a valid array - despite having some null values within it. To access the items within the array, you just need to use something like `people[0]` which would return Pete, Smith, and Bill.

#### Shorthand Operators

>`<<=` is the Left Shift Assignment, which is used to move the specific amount of bits to the left.
>
>`>>=` is the Right Shift Assignment, which is the same as left but instead moves to the right.
>
>`-=` is the subtraction assignment, which subtracts the value of the right operand from the variable and assigns the result to the variable.
>
>`*=` is the multiplication assignment, which multiples the variable by the value and then assigns the result to variable.
>
>`/=` is the division assignment, which divides the variable by the value and then assigns the result to the variable.

`let a = 10;`

`let b = 'dog';`

`let c = false;`

`// evaluate this`

`(a + c) + b;`

The above code would evaluate to `(10 + false) + dog` = `false` and thats because false in the the equation so I believe it makes all results false. Plus this is also mixing strings + numbers + boolean. (I'm honestly unsure about this)

A real world example for conditional statements is if you are seeking a specific input from a user, like how many of a product would you like in your online shopping cart? The user chooses an amount available to them and it would add that specific amount.

Loops can be useful for something like a password verification. If the password is true/correct, move forward. If not, do not! This works best in a loop because we don't know how many times the user might try to enter their password.

## Things I want to know more about

What is the main use difference in for and while loops?
Could an if/else if/else statement TECHNICALLY be the same as a loop but just way more code?
