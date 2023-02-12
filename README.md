# Two-Sum-Leetcode-C-

**Intuition**
Solve Using Brute Force ~

**Approach**
-Run two loops one i and next j
- now cheak weather the sum of nums[i]+nums[j] is equal to tthe target or not
-* if equal to the target then return the index value of both that number else return the empty index
-* Please Upvote

**Complexity**
**Time complexity:**
o(n)

**Space complexity:**
o(n)

**Code**
class Solution {
public:
    int i;
    int j;
    vector<int> twoSum(vector<int>&nums, int target)
{
 for(i=0;i<nums.size();i++)
 for(j=i+1;j<nums.size();j++)
 if(nums[i]+nums[j]==target)
 {
     return {i,j};
 }
  return {};
 }
};
