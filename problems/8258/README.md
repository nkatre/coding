# Trapping Rain Water II

Given an m x n matrix of positive integers representing the height of each unit cell in a 2D elevation map, compute the volume of water it is able to trap after raining.

Note:
Both m and n are less than 110. The height of each unit cell is greater than 0 and is less than 20,000.

Example:
```
Given the following 3x6 height map:
[
  [1,4,3,1,3,2],
  [3,2,1,3,2,4],
  [2,3,3,2,3,1]
]

Return 4.
```

![alt text](rainwater_empty.png)

The above image represents the elevation map [[1,4,3,1,3,2],[3,2,1,3,2,4],[2,3,3,2,3,1]] before the rain.

![alt text](rainwater_fill.png)

After the rain, water are trapped between the blocks. The total volume of water trapped is 4.

---

* Difficulty: Hard
* Topics: Breadth-first Search, Heap
* Companies: Google, Twitter
* LeetCode: [407. Trapping Rain Water II](https://leetcode.com/problems/trapping-rain-water-ii/description/)
