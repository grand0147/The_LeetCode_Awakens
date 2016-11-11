# Tree
## 树的遍历
Key Concepts
> Binary Tree遍历问题有一个关键点就是当指针走到底层以后如何返回的问题

### preorder
* recursive
* iterative
需要stack, 另外可以利用更新root本身来实现遍历O(lgN)的额外空间
* Morris
不需要额外空间

### inorder
* recursive
* iterative
* Morris
實作與preordr一樣，輸出順序不同

### postorder
有一种省事的方法，即将preorder的方法将结果输入到一个stack中，然后反向输出即可
* recursive
* iterative
使用了两个指针来记录节点访问情况
* Morris
實作很不一樣


### level order traversal
用 iterative 的方式，不過使用queue来代替stack的作用