# Data Structures' Analogies


## list vs tuple
S.N. | list | tuple
--- | --- | ---
1 | mutable | immutable


## list vs set
S.N. | list | set
--- | --- | ---
1 | mutable | mutable
2 | members are ordered | members are unordered
3 | can contain duplicate members | all unique members
4 | set operations are impractical | best suited for set operations
5 | membership check operation `in` takes `O(n)` complexity | membership check operation `in` takes `O(1)` complexity
6 | any data types could be a member | only hashable types could be a member
