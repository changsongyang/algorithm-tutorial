# 堆

堆是一种特殊的基于树的满足某些特性的数据结构，整个堆中的所有父子节点的键值都会满足相同的排序条件。堆更准确地可以分为最大堆与最小堆，在最大堆中，父节点的键值永远大于或者等于子节点的值，并且整个堆中的最大值存储于根节点；而最小堆中，父节点的键值永远小于或者等于其子节点的键值，并且整个堆中的最小值存储于根节点。

<div align="center"><img src="http://dunwu.test.upcdn.net/images/data-structure/heap/heap.png!zp"/></div>

时间复杂度:

- 访问最大值 / 最小值: `O(1)`
- 插入: `O(log(n))`
- 移除最大值 / 最小值: `O(log(n))`
