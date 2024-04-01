
1. Start
2. Take input an integer array nums.
3. Calculate the total sum of all elements in nums and store it in total_sum.
4. Initialize max_val to 0.
5. Iterate over each possible rotation k from 0 to n-1: 6. Initialize current_sum to 0. 7. For each element at index i in nums: 8. Calculate the contribution of nums[i] to F(k) as i * nums[i]. 9. Add this contribution to current_sum. 10. Update max_val to the maximum of max_val and current_sum.
6. Return max_val as the maximum rotate value.
7. End
