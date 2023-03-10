# How to approach this problem?

## Brute-Force Approach :
- Time Complexity: *O(NM)*
- Space Complexity: *O(1)*

> N = Size of Array, M = Size of any string inside Array

**Approach :** Run two nested loop, one through any one string inside array and other through the array itself.

### Step-by-step explanation of the algorithm:
1. First loop through the first string in the array
2. Then loop through the array
3. Check first loop should go out-of-bound or respective characters of strings shouldn't be equal, if any of the condition true, return result string(res)
4. Otherwise concatinate each characters to res, then return  

