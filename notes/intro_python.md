# Python for Data Science – Day 0

✅ Watched: Python for Data Science - freeCodeCamp

## 🧠 Takeaways:
> Learned that Python automatically infers data types, but I tested edge cases like type(5/2) → float, while 5//2 → int. I used this to debug why a for loop wasn’t working as expected with range.

> Tested that variable names can't start with numbers or most special characters (like #, @), but _var1 works.

> Used round(3.14159, 2) → 3.14  but doesn’t affect internal precision—important for financial data.

### 🧠 Python Built-in Function: `divmod()`

- Tried `divmod(28, 5)` → returns `(5, 3)`
  - `5` is the quotient, `3` is the remainder
- Tested on other values:
  - `divmod(10, 3)` → `(3, 1)`
  - `divmod(15, 5)` → `(3, 0)`
- Found useful when I need **both** values at once without doing:
  ```python
  quotient = x // y
  remainder = x % y

# Python for Data Science – Day 1

✅ Watched: Python for Data Science - freeCodeCamp

## 🧠 Takeaways:
## Type Checking

- `isinstance()` function is used to verify the data type of a variable.
isinstance(5, int)        # True  
isinstance(5.0, float)    # True  
isinstance("5", int)      # False

## Exponents and Modular Arithmetic

- `pow(x, y)` returns x raised to the power y.
- `pow(x, y, z)` returns (x^y) % z — efficient for large numbers.
  
pow(2, 3)       # Output: 8

pow(2, 3, 5)    # Output: 3, since 2^3 = 8 and 8 % 5 = 3

## Taking User Input

input() is used to take user input as a string.

It always returns a str, even if the user types a number.

To work with numbers, type conversion is necessary:

name = input("Enter your name: ")
age = int(input("Enter your age: "))  # Converts to int

## Conditional Logic: if, elif, else

- `if`: checks first condition
- `elif`: optional checks if previous `if`/`elif` failed
- `else`: optional fallback
- Use comparison operators: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Combine conditions with `and`, `or`, `not`

