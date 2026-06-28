# Sum of Products (SOP)
<b> How do we write a SOP expression for a given truth table? </b>
<br>
1. Identify the rows where the output is "1".
2. Represent the row in the form of a. b. c
3. Identify the next row where the output is "1" again. Add to the previous expression by connecting using a  "+".
4. Final answer should look something like F = (a . b. c) + blah blah...
5. If the value is 1, the variable is a. If the value is 0, then a' will be put in the expression.
</br>


# Product of Sum (SOP)
<b> How do we write a POS expression for a given truth table? </b>
<br>
1. Identify the rows where the output is "0".
2. Represent the row in the form of a+ b+ c
3. Identify the next row where the output is "0" again. Add to the previous expression by connecting using a  ".".
4. Final answer should look something like F = (a + b + c) . blah blah...
5. If the value is 1, the variable is a'. If the value is 0, then a will be put in the expression.
</br>