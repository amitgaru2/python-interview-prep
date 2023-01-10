# Data Structures' Analogies


## list vs tuple
S.N. | list | tuple
--- | --- | ---
1 | mutable | immutable
2 | [1, 2, 3, 4] | (1, 2, 3, 4)


## list vs set
S.N. | list | set
---  | ---  | ---
1 | mutable | mutable
2 | members are ordered | members are unordered
3 | can contain duplicate members | all unique members
4 | set operations are impractical | best suited for set operations
5 | membership check operation `in` takes `O(n)` complexity | membership check operation `in` takes `O(1)` complexity
6 | any data types could be a member | only hashable types could be a member
7 | removing of a member `pop` takes `O(n)` complexity | removing of a member `pop/remove` takes `O(1)` complexity
8 | [1, 2, 3, 4] | {1, 2, 3, 4}


## list vs dict
S.N | list | dict
--- | ---  | ---
1 | mutable | mutable
2 | members are ordered | members are unordered
3 | can contain duplicate members | all unique keys
4 | membership check operation `in` takes `O(n)` complexity | membership check operation `in` takes `O(1)` complexity
5 | any data types could be a member | only hashable types could be a key
6 | removing of a member `pop` takes `O(n)` complexity | removing of a member `pop/del` takes `O(1)` complexity
7 | [1, 2, 3, 4] | {1: 1, 2: 2, 3: 3, 4: 4}
