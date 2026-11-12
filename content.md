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

# Sample solution
Click below to reveal the sample solution.

>[!HIDDEN]
>
> Within the function we initialise a counter to 0 and then loop through each character in the string. If the character matches the target, we increment the counter.
> ```py-cell
> def character_count(string, character):
>     count = 0
>     for letter in string:
>         if letter == character:
>             count = count + 1
>     return count
> ```
>
> ## Test the function
>
> ```py-cell
> print(character_count("A bunch of characters", "a"))
> print(character_count("To be or not to be, that is the question", "e"))
> print(character_count("Hello, World!", "4"))
> ```
