# How to approach this problem?

## Brute-Force Approach :
- Time Complexity: *O(N)*
- Space Complexity: *O(1)*

**Approach :** Looping through all the characters in the character array and swapping two elements from the end untill we reach mid element.

### Step-by-step explanation of the algorithm:
1. First loop through the character array, till we reach mid element.
2. With each iteration we will check left end element with respective right end element and swap those elements.
3. Return the modified string.

## Optimization(Two-Pointer Approach) :
- Time Complexity: *O(N)*
- Space Complexity: *O(1)*

**Approach :** The entire logic for reversing a string is based on 
using the opposite directional two-pointer approach!

### Step-by-step explanation of the algorithm:
1. Initialize two pointers: left pointing to the first character of the string and right pointing to the last character of the string.
2. While left < right, swap the characters at indices left and right and increment left and decrement right.
3. Return the modified string