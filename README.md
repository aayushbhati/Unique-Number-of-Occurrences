# Unique Number of Occurrences

## Problem Description

Given an array of integers `arr`, return `true` **if the number of occurrences of each value in the array is unique**, or `false` **otherwise**.

---

## Examples

### Example 1:

**Input:**  
`arr = [1,2,2,1,1,3]`  
**Output:**  
`true`  

**Explanation:**  
- 1 appears 3 times  
- 2 appears 2 times  
- 3 appears 1 time  
All frequencies are unique → ✅ return `true`

---

### Example 2:

**Input:**  
`arr = [1,2]`  
**Output:**  
`false`  

**Explanation:**  
- 1 appears 1 time  
- 2 appears 1 time  
Frequencies are not unique → ❌ return `false`

---

### Example 3:

**Input:**  
`arr = [-3,0,1,-3,1,1,1,-3,10,0]`  
**Output:**  
`true`  

**Explanation:**  
- -3 → 3 times  
- 0 → 2 times  
- 1 → 4 times  
- 10 → 1 time  
All frequencies are different → ✅ return `true`

---

## Constraints

- `1 <= arr.length <= 1000`  
- `-1000 <= arr[i] <= 1000`
