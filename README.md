# Q6 - Filter Numbers Greater Than 5 Using `array.filter()`

## Problem Statement

Given an array:

```javascript
const inputArr = [1, 2, 3, 9, 10, 7, 5, 4, 3];
```

Return a new array containing only the numbers greater than 5.

### Expected Output

```javascript
[9, 10, 7]
```

---

## Solution

```javascript
const inputArr = [1, 2, 3, 9, 10, 7, 5, 4, 3];

const result = inputArr.filter(num => num > 5);

console.log(result);
```

---

## Explanation

* The `filter()` method creates a new array containing elements that satisfy a given condition.
* Here, the condition is `num > 5`.
* Only the elements greater than 5 are included in the resulting array.

### Working

| Element | Condition ( > 5 ) | Included |
| ------- | ----------------- | -------- |
| 1       | False             | No       |
| 2       | False             | No       |
| 3       | False             | No       |
| 9       | True              | Yes      |
| 10      | True              | Yes      |
| 7       | True              | Yes      |
| 5       | False             | No       |
| 4       | False             | No       |
| 3       | False             | No       |

---

## Output

```javascript
[9, 10, 7]
```

---

## Conclusion

The `filter()` method is useful for extracting elements from an array that meet specific conditions. In this example, it returns all numbers greater than 5 from the given array.
