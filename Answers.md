
1. The word frequencies are the same.

2. When using the size of `HashMap` and `MyHashMap` `MyHashMap` and `TreeMap` had the best time performance of 359 ms. `HashMap` had time of 360.

3. `Math.floorMod` ensures that no matter if the hashCode is positive or negative, if the second number is positive, the answer will be positive,
while `%` will always be negative if the first number is negative - which may happen when dealing with hashCodes. This is more reliable for a hash table index since the index always needs to be a positive number.

4. O(n). If you would keep track of the size as nodes were added to the linkedlist then size would just have to return a size variable.

5.
    - How does this implementation compare to one where you would directly use your linked `Node` class from the earlier assignment?
     Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
