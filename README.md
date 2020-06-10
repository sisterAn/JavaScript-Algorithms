# JavaScript-Algorithms

我是瓶子君，公众号「前端瓶子君」作者，前端进阶博客：https://github.com/sisterAn/blog

前端还要学算法？必须学，而且必须狠狠地学。现在去大厂面试，数据结构与算法已经是标配，要是不会的话，那基本与大厂无缘了。

作为一名前端，虽然在平常开发中很少写算法，但当我们需要深入前端框架、开发语言、开源库时，懂算法将大大提高我们看源码的能力。例如 ：

- virtual-dom diff 算法做了一些约定，后将原先 O(n3) 的时间复杂度降到了O(n) ，核心原理就是一个树的深度优先搜索
- babel 这些就是一些编译原理的 parser 生成抽象语法树的知识，再将抽象语法树进行转换操作生成文件
- 浏览器的 history，底层可以使用栈来实现
- webpack 中利用 tree-shaking 优化
- v8 中的调用栈、消息队列等等

这些就大量使用了算法，看懂了就能更好的了解它们的性能，更高效的解决问题，提升我们的代码质量与思维视野，进阶到更高 Level，赚更多钱💰💰💰。

所以说，学算法是每个前端进阶必备！⛽️⛽️⛽️

现在市面上的算法资料很多，但针对前端的算法资料少之又少，所以，这里我整理了一份适用于前端的数据结构与算法系列，希望能帮助你从0到1构建完整的数据结构与算法体系。

本系列预估一共有40多篇：

- [前端进阶算法1：如何分析、统计算法的执行效率和资源消耗？](https://github.com/sisterAn/JavaScript-Algorithms/issues/1)
- [前端进阶算法2：从Chrome V8源码看JavaScript数组（附赠腾讯面试题）](https://github.com/sisterAn/JavaScript-Algorithms/issues/2)
- [瓶子君前端算法集训营第一期开营啦，免费哟](https://mp.weixin.qq.com/s/dQu7Re-DesCr6S8He3AOfQ)
- [前端进阶算法3：从浏览器缓存淘汰策略和Vue的keep-alive学习LRU算法](https://github.com/sisterAn/JavaScript-Algorithms/issues/9)
- [前端进阶算法4：链表原来如此简单（+leetcode刷题）](https://github.com/sisterAn/JavaScript-Algorithms/issues/12)
- [10 问 10 答，带你快速入门前端算法](https://mp.weixin.qq.com/s/i8NbR1LjqhQEPxOILPSacA)
- [视频面试超高频在线编程题，搞懂这些足以应对大部分公司](https://mp.weixin.qq.com/s/1LnvjVWpKA-RuUGsh23bSw)
- [前端进阶算法5：全方位解读前端用到的栈结构（调用栈、堆、垃圾回收等）](https://github.com/sisterAn/JavaScript-Algorithms/issues/24)
- [前端进阶算法：常见算法题及完美题解](https://mp.weixin.qq.com/s/_pDPaf-GBLsMCNp_-MsWfg)
- [前端进阶算法6：一看就懂的队列及配套算法题](https://github.com/sisterAn/JavaScript-Algorithms/issues/35)
- [前端进阶算法7：头条正在面的哈希表问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/49)
- [前端进阶算法8：小白都可以看懂的树与二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/39)
- [前端进阶算法9：看完这篇，再也不怕堆排序、Top K、中位数问题面试了](https://github.com/sisterAn/JavaScript-Algorithms/issues/60)


想要更多更快的学习本系列，可以关注公众号「前端瓶子君」😊😊😊

## 深入掌握算法

#### 数组篇

- [图解leetcode88：合并两个有序数组](https://github.com/sisterAn/JavaScript-Algorithms/issues/3)
- [字节&leetcode1：两数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/4)
- [腾讯&leetcode15：三数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/31)
- [腾讯：数组扁平化、去重、排序 ](https://github.com/sisterAn/JavaScript-Algorithms/issues/5)
- [leetcode349：给定两个数组，编写一个函数来计算它们的交集](https://github.com/sisterAn/JavaScript-Algorithms/issues/6)
- [华为&leetcode146：设计和实现一个LRU（最近最少使用）缓存机制](https://github.com/sisterAn/JavaScript-Algorithms/issues/7)
- [阿里算法题：编写一个函数计算多个数组的交集](https://github.com/sisterAn/JavaScript-Algorithms/issues/10)

#### 链表
- [leetcode21：合并两个有序链表](https://github.com/sisterAn/JavaScript-Algorithms/issues/11)
- [有赞&leetcode141：判断一个单链表是否有环](https://github.com/sisterAn/JavaScript-Algorithms/issues/13)
- [图解leetcode206：反转链表](https://github.com/sisterAn/JavaScript-Algorithms/issues/14)
- [leetcode876：求链表的中间结点](https://github.com/sisterAn/JavaScript-Algorithms/issues/15)
- [leetcode19：删除链表倒数第 n 个结点](https://github.com/sisterAn/JavaScript-Algorithms/issues/16)
- [图解字节&leetcode160：编写一个程序，找到两个单链表相交的起始节点](https://github.com/sisterAn/JavaScript-Algorithms/issues/17)

#### 字符串
- [字节&leetcode151：翻转字符串里的单词](https://github.com/sisterAn/JavaScript-Algorithms/issues/18)
- [图解拼多多&leetcode14：最长公共前缀（LCP）](https://github.com/sisterAn/JavaScript-Algorithms/issues/19)
- [百度：实现一个函数，判断输入是不是回文字符串](https://github.com/sisterAn/JavaScript-Algorithms/issues/20)
- [字节&Leetcode3：无重复字符的最长子串](https://github.com/sisterAn/JavaScript-Algorithms/issues/21)
- [Facebook&字节&leetcode415: 字符串相加](https://github.com/sisterAn/JavaScript-Algorithms/issues/32)

#### 栈
- [字节&leetcode155：最小栈（包含getMin函数的栈）](https://github.com/sisterAn/JavaScript-Algorithms/issues/23)
- [图解腾讯&哔哩哔哩&leetcode20：有效的括号](https://github.com/sisterAn/JavaScript-Algorithms/issues/25)
- [leetcode1047：删除字符串中的所有相邻重复项](https://github.com/sisterAn/JavaScript-Algorithms/issues/26)
- [leetcode1209：删除字符串中的所有相邻重复项 II](https://github.com/sisterAn/JavaScript-Algorithms/issues/27)
- [面试真题：删除字符串中出现次数 >= 2 次的相邻字符](https://github.com/sisterAn/JavaScript-Algorithms/issues/28)

#### 队列
- [剑指offer09：用两个栈实现队列](https://github.com/sisterAn/JavaScript-Algorithms/issues/34)
- [leetcode239：滑动窗口最大值问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/33)
- [字节&leetcode151：翻转字符串里的单词](https://github.com/sisterAn/JavaScript-Algorithms/issues/18)
- [字节&Leetcode3：无重复字符的最长子串](https://github.com/sisterAn/JavaScript-Algorithms/issues/21)

#### 哈希表
- [腾讯&leetcode349：给定两个数组，编写一个函数来计算它们的交集](https://github.com/sisterAn/JavaScript-Algorithms/issues/6)
- [字节&leetcode1：两数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/4)
- [腾讯&leetcode15：三数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/31)
- [leetcode380：常数时间插入、删除和获取随机元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/48)
- [剑指Offer：第一个只出现一次的字符](https://github.com/sisterAn/JavaScript-Algorithms/issues/50)

#### 二叉树

##### 二叉树的遍历
- [字节&leetcode144：二叉树的前序遍历](https://github.com/sisterAn/JavaScript-Algorithms/issues/37)
- [字节&leetcode94：二叉树的中序遍历](https://github.com/sisterAn/JavaScript-Algorithms/issues/38)
- [字节&leetcode145：二叉树的后序遍历](https://github.com/sisterAn/JavaScript-Algorithms/issues/40)
- [leetcode102：二叉树的层序遍历](https://github.com/sisterAn/JavaScript-Algorithms/issues/47)
- [字节&leetcode107：二叉树的层次遍历](https://github.com/sisterAn/JavaScript-Algorithms/issues/46)

##### 重构二叉树
- [leetcode105：从前序与中序遍历序列构造二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/41)

##### 二叉树进阶
- [leetcode105：从前序与中序遍历序列构造二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/41)
- [leetcode105：从前序与中序遍历序列构造二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/41)
- [腾讯&leetcode104：二叉树的最大深度](https://github.com/sisterAn/JavaScript-Algorithms/issues/42)
- [字节&腾讯leetcode236：二叉树的最近公共祖先](https://github.com/sisterAn/JavaScript-Algorithms/issues/43)
- [剑指Offer&leetcode110：平衡二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/44)
- [字节&leetcode112：路径总和](https://github.com/sisterAn/JavaScript-Algorithms/issues/45)
- [剑指Offer&leetcode101：对称二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/53)

### 堆
- [腾讯&字节等：最小的k个数](https://github.com/sisterAn/JavaScript-Algorithms/issues/59)
- [leetcode347：前 K 个高频元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/61)
- [字节&leetcode215：数组中的第K个最大元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/62)
- [剑指Offer&leetcode295：数据流的中位数](https://github.com/sisterAn/JavaScript-Algorithms/issues/63)

### 图
- [剑指Offer&Bigo：旋转矩阵](https://github.com/sisterAn/JavaScript-Algorithms/issues/57)

#### 编程题
- [携程&蘑菇街&bilibili：手写数组去重、扁平化函数](https://github.com/sisterAn/JavaScript-Algorithms/issues/30)
- [百度：模版渲染](https://github.com/sisterAn/JavaScript-Algorithms/issues/36)
- [百度：什么是浅拷贝和深拷贝？有什么区别？如何实现 Object 的深拷贝](https://github.com/sisterAn/JavaScript-Algorithms/issues/54)
- [阿里&字节：手写 async/await 的实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/56)
- [编程题：用最简洁代码实现 indexOf 方法](https://github.com/sisterAn/JavaScript-Algorithms/issues/58)


## 从0到1构建完整的数据结构与算法体系

前端算法集训营第一期免费开营啦🎉🎉🎉，免费哟！

在这里，瓶子君不仅介绍算法，还将算法与前端各个领域进行结合，包括浏览器、HTTP、V8、React、Vue源码等。

在这里，你可以每天学习一道大厂算法题（阿里、腾讯、百度、字节等等）或 leetcode，瓶子君都会在第二天解答哟！


扫码关注公众号【前端瓶子君】，回复【算法】，拉你进前端算法集训营
![](http://resource.muyiy.cn/image/20200424231501.png)
