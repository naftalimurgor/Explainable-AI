## **Python Data Structures & Types Cheatsheet for ML/DL**

---

## **1. Basic Data Types**
| Type | Description | Example |
|------|------------|---------|
| `int` | Integer numbers | `x = 10` |
| `float` | Decimal numbers | `y = 3.14` |
| `bool` | Boolean values | `flag = True` |
| `str` | String (text) | `name = "ML"` |

```python
# Checking data types
print(type(10))        # <class 'int'>
print(type(3.14))      # <class 'float'>
print(type(True))      # <class 'bool'>
print(type("ML"))      # <class 'str'>
```

---

## **2. Lists (Dynamic Arrays)**
- Mutable, ordered collection.
- Useful for storing datasets.

```python
nums = [1, 2, 3, 4, 5]
nums.append(6)  # Add element
nums.pop()      # Remove last element
nums[0] = 10    # Modify element
print(nums[:3]) # Slicing

# List comprehension (Fast processing)
squared = [x**2 for x in nums if x % 2 == 0]
```

---

## **3. Tuples (Immutable)**
- Ordered but **unchangeable** (good for fixed data).

```python
point = (4, 5)
print(point[0])  # Accessing elements
# point[1] = 10  # ❌ Error: Tuples are immutable
```

---

## **4. Sets (Unique Elements)**
- Unordered, no duplicates, fast lookups.

```python
unique_nums = {1, 2, 3, 3, 4}
unique_nums.add(5)
print(unique_nums)  # {1, 2, 3, 4, 5}
```

---

## **5. Dictionaries (Key-Value Pairs)**
- Fast lookups (`O(1)` time complexity).

```python
model_info = {"name": "ResNet", "accuracy": 92.5}
print(model_info["name"])
model_info["dataset"] = "ImageNet"  # Adding new key-value
```

---

## **6. Numpy Arrays (Fast ML Data Handling)**
- Used for ML data structures.
- Supports fast mathematical operations.

```python
import numpy as np

arr = np.array([1, 2, 3, 4])
print(arr.shape)  # (4,) -> 1D array

matrix = np.array([[1, 2], [3, 4]])
print(matrix.shape)  # (2,2)

# Operations
print(arr + 10)  # Element-wise addition
print(matrix.T)  # Transpose
```

---

## **7. Pandas DataFrame (Tabular Data)**
- Used for ML datasets.

```python
import pandas as pd

data = {"Feature1": [1, 2, 3], "Feature2": [4, 5, 6]}
df = pd.DataFrame(data)

print(df.head())  # View first rows
print(df.describe())  # Summary stats
```

---

## **8. PyTorch Tensor (Deep Learning)**
- Similar to NumPy but supports GPU acceleration.

```python
import torch

tensor = torch.tensor([[1.0, 2.0], [3.0, 4.0]])
print(tensor.shape)  # (2,2)

# Convert to NumPy
numpy_array = tensor.numpy()
```

---

## **9. TensorFlow Tensor**
- Used in Deep Learning models.

```python
import tensorflow as tf

tensor = tf.constant([[1.0, 2.0], [3.0, 4.0]])
print(tensor.shape)  # (2,2)
```

---

### **Quick Data Type Conversion**
```python
float_num = float(10)  # int → float
string_num = str(10)   # int → str
int_list = list((1, 2, 3))  # tuple → list
```

---

This should be a solid **quick reference** for ML/DL work! 🚀
