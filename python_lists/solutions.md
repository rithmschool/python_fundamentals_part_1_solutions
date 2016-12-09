# Lists and Dictionaries

### List Comprehension

Write the following Python code to do the following (complete ALL of these using `list comprehension`)

1. Given a list `[1,2,3,4]` print out all the values in the list - `[print(val) for val in [1,2,3,4]]`
2. Given a list `[1,2,3,4]` print out all the values in the list multiplied by 20 `[print(val*20) for val in [1,2,3,4]]`
3. Given a list `["Elie", "Tim", "Matt"]`, return a new list with only the first letter (`["E", "T", "M"]`) - `[person[0] for person in ["Elie", "Tim", "Matt"]]`
4. Given a list `[1,2,3,4,5,6]` return a new list of all the even values `[val for val in [1,2,3,4,5,6] if val % 2 == 0]`
5. Given two lists `[1,2,3,4]` and `[3,4,5,6]`, return a new list that is the intersection of the two `[3,4]` - `[val for val in [1,2,3,4] if val in [3,4,5,6]]`
6. Given a list of words `["Elie", "Tim", "Matt"]` return a new list with each word reversed and in lower case `['eile', 'mit', 'ttam']` (google how to reverse a string in python for help)
7. Given two strings "first" and "third", return a new string with all the similar letters `"".join([char for char in "first" if char in "third"])`
8. For all the numbers between 1 and 100, return a list with all the numbers that are divisible by 12 - `[val for val in range(0,101) if val % 12 == 0]`
9. Given the string "amazing", return a list with all the vowels removed `['m', 'z', 'n', 'g']` - `[char for char in "amazing" if char not in ["a", "e", "i", "o", "u"]]`
10. Generate a list with the value `[[0, 1, 2], [0, 1, 2], [0, 1, 2]]` - `[[i for i in range(0,3)] for num in range(0,3)]`
11. Generate a list with the value: 
```py
[
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9],
 [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
 ]
```

`[[i for i in range(0,10)] for num in range(0,10)]`

