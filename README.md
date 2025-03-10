# Python List Operations 🚀  

## 📌 Project Description  
This project demonstrates various **Python list operations**, including:  
- Creating an empty list  
- Appending elements  
- Inserting an element at a specific position  
- Extending a list with another list  
- Removing the last element  
- Sorting the list in ascending order  
- Finding the index of a specific element  

These are **essential Python concepts** for working with lists and understanding data manipulation.

---

---

## 🛠 Technologies Used  
- **Python** 🐍 (Version 3.x)  
- Standard Python libraries  

---

## 📖 Code Explanation  

```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend my_list with [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element from my_list
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of value 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)

# Print the final list
print("Final my_list:", my_list)


