## 红黑树的性质
* 根节点为黑色
* 叶子节点都为黑色
* 若有红色节点，则它的子节点都为黑色
* 从任意节点到叶子节点路径中的黑色节点数目都一致

## 红黑树的左旋
![left-rotate](http://hi.csdn.net/attachment/201012/29/8394323_1293614183gD0H.jpg)

对pivot节点的左旋，意思是将它变为右子节点的左子节点

## 红黑树的右旋
![left-rotate](http://hi.csdn.net/attachment/201012/29/8394323_1293614183DSC3.jpg)

对pivot节点的右旋，意思是将它变为其左子节点的右子节点

## 红黑树的插入
