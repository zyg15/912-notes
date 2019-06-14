伸展树知识总结
=============

> 相对于AVL树的比较。
AVL树更像是循规蹈矩，如履薄冰。而伸展树则更加潇洒，不顾小节。

> 局部性原理(locality)
类比于列表

> 逐层伸展策略与最坏情况

双层伸展策略
+ 描述
+ 效果
+ 时间复杂度

> 伸展树的实现
为了保证局部性，插入结点也需要插入到根节点。删除结点后，需要将被删除结点附近的结点移到根节点。这两个操作都可以通过伸展树的查找快速实现。