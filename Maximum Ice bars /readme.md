Algorithm maxIceCream(costs, coins):
    1. Sort the array costs in non-decreasing order.
    2. Initialize iceCreamBars to 0.
    3. Iterate through each cost in costs:
        a. If coins is greater than or equal to the current cost:
            i. Deduct the cost from coins.
            ii. Increment iceCreamBars by 1.
        b. Otherwise, break the loop.
    4. Return iceCreamBars.


