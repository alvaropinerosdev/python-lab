# English Errors

## Error Log

| Date | My mistake | Correction | Explanation |
|---|---|---|---|
| 2026-10-23 | | | |
| 2026-10-24 | I struggled to predict the output of a `while` loop using a list index. | Track the index value and check the loop condition in every iteration. | A `while` loop continues while its condition is true. List indexes start at `0`, and the index must be updated to avoid an infinite loop. |
| 2026-10-24 | I struggled to understand how to iterate over a dictionary and access its values. | Use `for key in dictionary:` to iterate over keys and `dictionary[key]` to access each value. | Iterating over a dictionary directly gives its keys, not its values. |
| 2026-10-24 | I struggled to follow a function that combines a dictionary, conditions, an accumulator, and a counter. | Trace each variable step by step and check the condition before updating the accumulator or counter. | Each variable changes only when the corresponding assignment statement executes. |

## Rules I Need to Remember

- `total = total + number` accumulates values.
- `count = count + 1` counts occurrences.
- `% 2 == 0` checks whether a number is even.
- `return` sends a value back to the caller; it does not print it.
- `print()` displays a value.
- A `for` loop iterates over items in a sequence or over keys in a dictionary.
- `dictionary[key]` accesses the value associated with a key.
- A `while` loop continues while its condition is true. Update the loop variable when necessary.
- Trace variable values one iteration at a time to predict a program's output.