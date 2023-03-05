## How to approach this problem?

#### Brute-Force Approach :
- Time Complexity: *O(N)*
- Space Complexity: *O(1)*

**Approach :** Looping through all the characters in the character array and swapping two elements from the end untill we reach mid element.

**Step-by-step explanation of the algorithm:**
1. First loop through the character array, till we reach mid element.
2. With each iteration we will check left end element with respective right end element and swap those elements.
3. Return the modified string.