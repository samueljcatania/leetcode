# [1. Two Sum](https://leetcode.com/problems/two-sum/)

Given an array of integers `nums` and an integer `target`, return *indices of the two numbers such that they add up to `target`*.

You may assume that each input would have ***exactly* one solution**, and you may not use the *same* element twice.

You can return the answer in any order.

**Example 1:**

<pre>
<b>Input:</b> nums = [2,7,11,15], target = 9
<b>Output:</b> [0,1]
<b>Output:</b> Because nums[0] + nums[1] == 9, we return [0, 1].
</pre>

**Example 2:**

<pre>
<b>Input:</b> nums = [3,2,4], target = 6
<b>Output:</b> [1,2]
</pre>

**Example 3:**

<pre>
<b>Input:</b> nums = [3,3], target = 6
<b>Output:</b> [0,1]
</pre>

**Constraints:**

- <tt>2 <= nums.length <= 10<sup>4</sup></tt>
- <tt>-10<sup>9</sup> <= nums[i] <= 10<sup>9</sup></tt>
- <tt>-10<sup>9</sup> <= target <= 10<sup>9</sup></tt>
- **Only one valid answer exists.**
 

**Follow-up:** Can you come up with an algorithm that is less than <tt>O(n<sup>2</sup>)</tt> time complexity?
