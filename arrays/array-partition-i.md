### 561. Array Partition I



**URL:** https://leetcode.com/problems/array-partition-i/

**Hint 1:** `Sort the array`

Hint X: `hint X`



#### Solution 1:

**Name:** Antonio

**Language:** Java 

```java
class Solution {
    public int arrayPairSum(int[] nums) {
        Arrays.sort(nums);
        int result = 0;
        for (int i = 0; i < nums.length; i+=2) {
            result += nums[i];
        }
        return result;
    }
}
```



#### Solution 2:

**Name:** 

**Language:**