# Heap - 堆

- 堆是一个完全二叉树；

- 堆中每一个节点的值都必须大于等于（或小于等于）其子树中每个节点的值。

- 对于每个节点的值都大于等于子树中每个节点值的堆，称为“大顶堆”。

- 对于每个节点的值都小于等于子树中每个节点值的堆，称为“小顶堆”

  

  这里实现了两种堆

## First

精确的时间复杂度为`(n-1)*O(logn)`，对 n-1 个节点进行了堆化