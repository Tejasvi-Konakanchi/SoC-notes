# Switch, Bits and Boolean Algebra
Digital Electronics handle data in bits (0 or 1).

## Switch
A switch is one of the easiest ways to represent a bit.
| Switch State | Binary Bit | Meaning    |
| ------------ | ---------- | ---------- |
| OFF          | 0          | Low, False |
| ON           | 1          | High, True |

Since Switch has two states they naturally represent a boolean variable (true or false). You can use multiple switches to represent different levels (using Truth Tables) as shown below

| Switch A | Switch B | Boolean Expression | Output | Notes |
| -------- | -------- | ------------------ | ------ | ----- |
| OFF (0)  | OFF (0)  | A AND B            | 0      |position 1|
| OFF (0)  | ON (1)   | A AND B            | 0      |position 2|
| ON (1)   | OFF (0)  | A AND B            | 0      |position 3|
| ON (1)   | ON (1)   | A AND B            | 1      |position 4|

## Truth Tables
- no.of rows = 2^(no.of variables/switches).
- Allocate T/F or 0/1, with the pattern (4 0s/1s, 2 0s 1s, 1 0s 1s).

## Boolean Algebra
- It is the set of rules, used to simplify the given logic expression without changing its functionality.
- It is used when number of variables is (3-4). It gets tedious otherwise.

