# Comprehending Comprehensions

* [Slides](https://docs.google.com/presentation/d/1oWCqL31WKv7x6UtATHvhELUgFx8Z12QPCeXubAjaw7Q/edit?usp=sharing)
* [Code Snippetes from the talk](https://github.com/Pradhvan/Talks/blob/main/ComprehendingComprehensions/Comprehending%20Comprehensions.ipynb)

### Additional Reading

* [Overusing list comprehensions and generator expressions in Python](https://treyhunner.com/2019/03/abusing-and-overusing-list-comprehensions-in-python/)
* [Iterator,Iterables & the IteratorProtocol](https://blogs.dgplug.org/pradhvan/iterator-iterables-and-the-iteratorprotocal)
* [Exploring Generators in Python](https://blogs.dgplug.org/pradhvan/exploring-generators-in-python)


### Problem Statement to practice

Write a function that accepts two lists-of-lists of numbers and returns one list-of-lists with each of the corresponding numbers in the two given lists-of-lists added together. Hint: List Comprehensions might come in handy today.

It should work something like this:

```Python
>>> matrix1 = [[1, -2], [-3, 4]]
>>> matrix2 = [[2, -1], [0, -1]]
>>> add(matrix1, matrix2)
[[3, -3], [-3, 3]]
>>> matrix1 = [[1, -2, 3], [-4, 5, -6], [7, -8, 9]]
>>> matrix2 = [[1, 1, 0], [1, -2, 3], [-2, 2, -2]]
>>> add(matrix1, matrix2)
[[2, -1, 3], [-3, 3, -3], [5, -6, 7]]
>>> matrix1 = [[1, 9], [7, 3]]
>>> matrix2 = [[5, -4], [3, 3]]
>>> matrix3 = [[2, 3], [-3, 1]]
>>> add(matrix1, matrix2, matrix3)
[[8, 8], [7, 7]]
```


### Credits

* [Trey Hunner's](https://treyhunner.com/) and [https://www.pythonmorsels.com/](https://www.pythonmorsels.com/)
* [Rodrigo](https://twitter.com/mathsppblog) book [Comprehending Comprehensions](https://mathspp.gumroad.com/l/comprehending-comprehensions)
