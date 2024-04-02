Input: Take input from the user for a list of non-negative integers separated by spaces.

Conversion: Convert each integer in the input list to a string and store them in a vector of strings.

Sorting: Sort the vector of strings using a custom comparison function. The comparison function compares two strings 'a' and 'b' based on their concatenated forms ('b + a' and 'a + b'). This sorting ensures that the resulting order forms the largest number when concatenated.

Concatenation: Concatenate the sorted strings to form the final result.

Leading Zeros Removal: Remove any leading zeros from the result.

Output: If the result is not empty, return it. Otherwise, return "0" to indicate that the largest number formed is 0.
