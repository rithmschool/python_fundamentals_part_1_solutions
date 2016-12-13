### Module Exercises

1. What is a module?

    A module is just a Python file. In the file, we typically define functions, classes, or variables that we then want to import in other files.

2. List three ways to import a module in Python.

    ```python
    import random
    import random as r
    from random import *
    ```

3. What is the purpose of importing?

    Importing helps us keep our code more organized and easier to reason about, by separating chunks of code into separate files. We can then import just what we need from one file into another file.

4. List three examples when you would use the `random` module.

    1. Model shuffling a deck of cards.
    2. Model rolling a pair of dice.
    3. Model flipping a coin.

5. What is an `ImportError`? 

    An `ImportError` is an error Python gives you if you try to import a module it can't find, or if you try to import something it can't find within a module.

6. When would using an `OrderedDict` be useful?

    It might be useful if you care about the ordering of the key-value pairs. For example, if you want to be sure that the keys are alphabetized, using an `OrderedDict` might be helpful.

7. When would using a `defaultdict` be useful?

    `defaultdict` could be helpful if you want to create a dictionary but want multiple values for one key. See the example in the [docs](https://docs.python.org/3/library/collections.html#collections.defaultdict) for more on this.

8. What is the purpose of the following code:

    ```python
    if __name__ == '__main__':
        pass
    ```

    The code inside of the `if` statement will only execute if the file is executed directly. If it's imported, the code inside of the `if` statement won't run.