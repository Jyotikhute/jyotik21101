1. To keep the maximum product ending at the current index, the minimum product ending at the current index (to handle negative values), and the maximum product found thus far, respectively, initialize the three variables max_prod, min_prod, and max_so_far. Start them out with the array's first entry.
2. Iterate through the array starting from the second element.
3. Replace max_prod and min_prod if the current element is negative, as a maximum product can be obtained by multiplying a negative value by the minimum product. Modify max_prod to equal the product of max_prod and the current element, as well as the maximum of the current element. Make min_prod equal to the product of min_prod and the current element, and the minimum of the current element. Adjust max_so_far such that it equals the maximum of max_prod and max_so_far. Give back max_so_far, which is a subarray's maximum product.

This algorithm runs in linear time, O(n), where n is the size of the input array.
