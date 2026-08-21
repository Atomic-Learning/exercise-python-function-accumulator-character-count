# Task

Write a function named `character_count`{.python} with two arguments:

* `string`{.python}: a string containing some characters.
* `character`{.python}: a single character to count in the string.

Your function should return how many times `character`{.python} appears in `string`{.python} and return that value. Use the accumulator pattern to keep track of the count.

```py-cell
# Write your function here

# These calls should print 2, 4, and 0 respectively
print(character_count("A bunch of characters", "a"))
print(character_count("To be or not to be, that is the question", "e"))
print(character_count("Hello, World!", "4"))
```
