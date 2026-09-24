## Python

**Topic:** Lists and loops

**What I learned:**
- A list stores many items in one variable.
- A `for` loop goes through each item one by one.
- `append()` adds an item to the end of a list.
- `len()` tells how many items are in a list.

**Practice code:**
```python
numbers = [4, 9, 15, 22, 7]

even_numbers = []

for num in numbers:
    if num % 2 == 0:
        even_numbers.append(num)

print("Even numbers:", even_numbers)
print("Count:", len(even_numbers))
```

**What this does:**
Goes through each number. Checks if it is even. Adds even numbers to a new list. Prints the list and how many there are.

**Mistake I made:**
I forgot the colon `:` at the end of the `for` line. Python gave a syntax error.

**Next:** Learn list comprehension, a shorter way to write this loop.
