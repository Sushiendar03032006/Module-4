# Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## Program
```
data = {
    3: 323,
    2: 56,
    1: 2,
    5: 12,
    4: 24,
    6: 18
}


# Sorting the dictionary by values
sorted_items = sorted(data.items(), key=lambda item: item[1])

print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)

```

## Output:
![Screenshot 2025-05-01 102003](https://github.com/user-attachments/assets/0efd3e08-4bfb-4796-aeab-d67306329617)


## Result:
Python Program to Sort a Dictionary by Keys and Values is successfully executed.


