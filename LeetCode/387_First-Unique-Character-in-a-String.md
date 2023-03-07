# How to approach this problem?

## Brute-Force Approach :
- Time Complexity: *O(N^2)*
- Space Complexity: *O(1)*

**Approach :** Run two nested loop and check weather it is present in whole string or not .

### Step-by-step explanation of the algorithm:
1. First loop through the string
2. Check if you don't match the character, return its index
3. else return -1.

## Optimization(Using extra space of 26 characters) :
- Time Complexity: *O(N)*
- Space Complexity: *O(1)*

**Approach :** You can use a vector of size 26 for extra space.

### Step-by-step explanation of the algorithm:
1. Create a vector of size 26, and initialize them with zero. 
2. Loop through the string and count the characters and increment the respective count in vector.
3. Check if count is 1, return index
4. if there is no count == 1, return -1; 