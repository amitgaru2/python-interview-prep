# Find the common elements between two lists (with complexity analysis).

```python

# Assume two lists
x = [1, 2, 3, 4, 5]
y = [3, 4, 5, 6, 7]


# Type cast to the Set type
x = set(x)  # Time complexity: O(n)
y = set(y)  # Time complexity: O(m)


# Set intersection between the Sets
result = x & y  # Time complexity: O(n)


print(result)


# Total Time Complexity = O(n) + O(m) + O(n) = O(N)

```
