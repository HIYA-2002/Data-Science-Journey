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
