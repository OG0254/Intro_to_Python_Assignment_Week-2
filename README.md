# Python Built-in-Data Structures

## Overview
This script demonstrates various list operations in Python, including:
- Creating a list
- Adding elements
- Inserting elements
- Extending with another list
- Removing elements
- Sorting
- Finding an element's index

---

## Code

```python
# 1. Create an empty list
my_list = []

# 2. Append the elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# 3. Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# 4. Extend with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# 5. Remove the last element
my_list.pop()

# 6. Sort the list in ascending order
my_list.sort()

# 7. Find and print the index of the value 30
print(my_list.index(30))
```

---

## Step-by-Step Execution

| Step | Operation                               | Resulting List                     |
|------|-----------------------------------------|--------------------------------------|
| 1    | Create empty list                       | `[]`                                 |
| 2    | Append 10, 20, 30, 40                   | `[10, 20, 30, 40]`                   |
| 3    | Insert 15 at index 1                    | `[10, 15, 20, 30, 40]`               |
| 4    | Extend with `[50, 60, 70]`               | `[10, 15, 20, 30, 40, 50, 60, 70]`   |
| 5    | Remove last element                     | `[10, 15, 20, 30, 40, 50, 60]`       |
| 6    | Sort in ascending order                 | `[10, 15, 20, 30, 40, 50, 60]`       |
| 7    | Find index of `30`                      | `3` (printed output)                 |

---

## Expected Output
```
3
```

---

## How to Run
1. Save the script `name_you_want.py`.
2. Run the file in terminal or command prompt:
   ```bash
   python name_you_want.py
   ```

---

## Notes
- **`append()`** adds a single element to the end of the list.
- **`insert()`** places an element at a specific index.
- **`extend()`** adds multiple elements from another list.
- **`pop()`** removes and returns the element at the given index (last by default).
- **`sort()`** sorts the list in place in ascending order by default. **POINT TO NOTE** if it was in descending order it would be **`sort(reverse=True)`**
- **`index()`** finds the first occurrence of a value and returns its position.
