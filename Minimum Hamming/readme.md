Input: Take a vector of integers nums as input.

Initialize:

Initialize ans to 0 to store the total Hamming distance.
Create an array zeroOne of size 2 to count zeros and ones at each bit position.
Main Algorithm:

Iterate until all numbers in nums become zero:
Initialize zeroCount to count zeros in the current bit position.
Reset counters for zeros and ones in zeroOne.
Iterate over each integer in nums:
Increment zeroCount if the current integer is zero.
Update the counts of zeros and ones in zeroOne based on the least significant bit of the current integer.
Right shift the current integer by one bit.
Calculate the contribution of the current bit position to the total Hamming distance and add it to ans.
Output: Return the final value of ans as the total Hamming distance.
