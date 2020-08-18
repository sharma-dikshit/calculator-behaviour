# Division

## Scenario : Division by zero

- Given : A working calculator.
- When : Enter the first number and then the division operator
  then zero and then press ans.
- Then : Display "Cannot divide by zero" as answer.

## Scenario : Divide zero by any number

- Given : A working calculator.
- When : Enter zero and then the division operator
  then any number other than zero and then press ans.
- Then : Display "zero" as answer.

## Scenario : One of the numbers is negative

- Given : A working calculator.
- When : Enter the first number (positive) and then the division operator
  then a negative number and then press ans.
- Then : Display the result of the division.

## Scenario : Both the numbers are negative

- Given : A working calculator.
- When : Enter the first negative number and then the division operator
  then the second negative number and then press ans.
- Then : Display the result of the division.

## Scenario : Both the numbers are zero

- Given : A working calculator.
- When : Enter the first number (zero) and then the division operator
  then enter the second number (zero) and then press ans.
- Then : Display error message "not defined".

## Scenario : Decimal value capping

- Given : A working calculator.
- When : Enter the first number and then the division operator
  then the second number and then press ans.
- Then : Display the result of the division with n digits after the decimal point.

## Scenario : Pressing division operator more than once

- Given : A working calculator.
- When : Enter the first number and then the division operator
  and then division operator agin and then the second number and then press ans.
- Then : Display the result of the division.

## Scenario : Second operand not present

- Given : A working calculator.
- When : Enter the first number and then the division operator
  and then press ans.
- Then : Maintain the last state and wait for the second operand.

## Scenario : Division of more than two number

- Given : A working calculator.
- When : Enter first "number", and enter "division" operator, and then
 enter second "number", and press "equals".
- Then : Display "divided number" as the intermediate result.
- When : Again press "division" operator, then enter third "number",
 then press "equal".
- Then : Use intermediate result as first number and add third number with 
  this as second number and display the final "divided number" as result.

## Scenario : Division of any/all operands being fractions

- Given : A working calculator.
- When : Enter the first number/fractiom and then the division operator,
  then enter the second number/fraction and then press ans.
- Then : Display result of the division.
