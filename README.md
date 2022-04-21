# JavaScript-Algorithms

我是瓶子君，前端进阶博客：https://github.com/sisterAn/blog

[线上版本阅读更流畅，点击阅读](https://www.pzijun.cn/)

作为一名前端，虽然在平常开发中很少写算法，但当我们需要深入前端框架、开发语言、开源库时，懂算法将大大提高我们看源码的能力。例如 ：

- virtual-dom diff 算法做了一些约定，后将原先 O(n3) 的时间复杂度降到了O(n) ，核心原理就是一个树的深度优先搜索
- babel 这些就是一些编译原理的 parser 生成抽象语法树的知识，再将抽象语法树进行转换操作生成文件
- 浏览器的 history，底层可以使用栈来实现
- webpack 中利用 tree-shaking 优化
- v8 中的调用栈、消息队列等等

这些就大量使用了算法，看懂了就能更好的了解它们的性能，更高效的解决问题，提升我们的代码质量与思维视野，进阶到更高 Level，赚更多钱💰💰💰。

所以说，学算法是每个前端进阶必备！⛽️⛽️⛽️

所以，这里我整理了一份适用于前端的数据结构与算法系列，希望能帮助你从0到1构建完整的数据结构与算法体系（**此处所有的题目均来自真实前端面试**）。

![](http://resource.muyiy.cn/image/20200616000604.png)

## 系列文章

- [前端进阶算法1：如何分析、统计算法的执行效率和资源消耗？](https://github.com/sisterAn/JavaScript-Algorithms/issues/1)
- [前端进阶算法2：从Chrome V8源码看JavaScript数组（附赠腾讯面试题）](https://github.com/sisterAn/JavaScript-Algorithms/issues/2)
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
- [前端进阶算法10：别再说你不懂topk问题了](https://github.com/sisterAn/JavaScript-Algorithms/issues/73)
- [前端进阶算法11：二叉查找树（BST树）](https://github.com/sisterAn/JavaScript-Algorithms/issues/87)
- [前端进阶算法12：数据结构与算法中的字符串](https://mp.weixin.qq.com/s/PzoR-Yl1kqAfdPExOCLikQ)
- [前端进阶算法13：一次搞定九大排序策略](https://mp.weixin.qq.com/s/fMmo2ybLWuPpZvmB6uZo_w)
- [前端进阶算法14：解读最常见的三大查找结构](https://mp.weixin.qq.com/s/8Ce63WfUAt5e2jmnN-RGJQ)
- [前端进阶算法15：95% 的算法都是基于这 6 种算法思想](https://mp.weixin.qq.com/s/gC-w-4_FfGxtfQ79mtpbFg)
- [前端进阶算法16：贪心算法套路问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/171)


想要更多更快的学习本系列，可以关注公众号「前端瓶子君」😊😊😊

## 深入掌握算法

#### 数组篇

- [图解leetcode88：合并两个有序数组](https://github.com/sisterAn/JavaScript-Algorithms/issues/3)
- [字节&leetcode1：两数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/4)
- [腾讯&leetcode15：三数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/31)
- [字节：N数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/128)
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
- [腾讯&leetcode611：有效三角形的个数](https://github.com/sisterAn/JavaScript-Algorithms/issues/93)
- [快手算法：链表求和](https://github.com/sisterAn/JavaScript-Algorithms/issues/114)
- [leetcode42：接雨水问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/122)

#### 字符串
- [字节&leetcode151：翻转字符串里的单词](https://github.com/sisterAn/JavaScript-Algorithms/issues/18)
- [图解拼多多&leetcode14：最长公共前缀（LCP）](https://github.com/sisterAn/JavaScript-Algorithms/issues/19)
- [百度：实现一个函数，判断输入是不是回文字符串](https://github.com/sisterAn/JavaScript-Algorithms/issues/20)
- [字节&Leetcode3：无重复字符的最长子串](https://github.com/sisterAn/JavaScript-Algorithms/issues/21)
- [Facebook&字节&leetcode415: 字符串相加](https://github.com/sisterAn/JavaScript-Algorithms/issues/32)
- [腾讯&leetcode43：字符串相乘](https://github.com/sisterAn/JavaScript-Algorithms/issues/105)
- [腾讯&剑指Offer：字符串转换整数 (atoi)](https://github.com/sisterAn/JavaScript-Algorithms/issues/132)

#### 栈
- [字节&leetcode155：最小栈（包含getMin函数的栈）](https://github.com/sisterAn/JavaScript-Algorithms/issues/23)
- [图解腾讯&哔哩哔哩&leetcode20：有效的括号](https://github.com/sisterAn/JavaScript-Algorithms/issues/25)
- [leetcode1047：删除字符串中的所有相邻重复项](https://github.com/sisterAn/JavaScript-Algorithms/issues/26)
- [leetcode1209：删除字符串中的所有相邻重复项 II](https://github.com/sisterAn/JavaScript-Algorithms/issues/27)
- [面试真题：删除字符串中出现次数 >= 2 次的相邻字符](https://github.com/sisterAn/JavaScript-Algorithms/issues/28)

#### 队列
- [腾讯&剑指offer09：用两个栈实现队列](https://github.com/sisterAn/JavaScript-Algorithms/issues/34)
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
- [腾讯&leetcode104：二叉树的最大深度](https://github.com/sisterAn/JavaScript-Algorithms/issues/42)
- [字节&腾讯leetcode236：二叉树的最近公共祖先](https://github.com/sisterAn/JavaScript-Algorithms/issues/43)
- [剑指Offer&leetcode110：平衡二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/44)
- [字节&leetcode112：路径总和](https://github.com/sisterAn/JavaScript-Algorithms/issues/45)
- [剑指Offer&leetcode101：对称二叉树](https://github.com/sisterAn/JavaScript-Algorithms/issues/53)
- [字节一面：给定一个二叉树, 找到该树中两个指定节点间的最短距离](https://github.com/sisterAn/JavaScript-Algorithms/issues/82)
- [腾讯&leetcode230：二叉搜索树中第K小的元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/86)
- [二叉树的左右子树交换](https://github.com/sisterAn/JavaScript-Algorithms/issues/141)

### 堆
- [腾讯&字节等：最小的k个数](https://github.com/sisterAn/JavaScript-Algorithms/issues/59)
- [leetcode347：前 K 个高频元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/61)
- [字节&leetcode215：数组中的第K个最大元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/62)
- [剑指Offer&leetcode295：数据流的中位数](https://github.com/sisterAn/JavaScript-Algorithms/issues/63)

### 图
- [leetcode997：找到小镇的法官](https://github.com/sisterAn/JavaScript-Algorithms/issues/65)
- [leetcode207：课程表问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/66)
- [剑指Offer&Bigo：旋转矩阵](https://github.com/sisterAn/JavaScript-Algorithms/issues/57)
- [腾讯&leetcode：螺旋矩阵 II](https://github.com/sisterAn/JavaScript-Algorithms/issues/134)
- [字节&剑指 Offer 29：顺时针打印矩阵](https://github.com/sisterAn/JavaScript-Algorithms/issues/119)

### 排序算法
- [腾讯&字节：介绍一下快排原理以及时间复杂度，并实现一个快排](https://github.com/sisterAn/JavaScript-Algorithms/issues/70)
- [字节&阿里&网易&leetcode384：打乱数组（洗牌算法）](https://github.com/sisterAn/JavaScript-Algorithms/issues/74)
- [阿里五面：说下希尔排序的过程？ 希尔排序的时间复杂度和空间复杂度又是多少？](https://github.com/sisterAn/JavaScript-Algorithms/issues/75)
- [腾讯&leetcode148：排序链表](https://github.com/sisterAn/JavaScript-Algorithms/issues/79)
- [字节算法题：扑克牌问题（反向推导题）](https://github.com/sisterAn/JavaScript-Algorithms/issues/80)
- [腾讯&leetcode611：有效三角形的个数](https://github.com/sisterAn/JavaScript-Algorithms/issues/93)

### 查找算法
- [腾讯：简述二分查找算法与时间复杂度，并实现一个二分查找算法](https://github.com/sisterAn/JavaScript-Algorithms/issues/83)
- [腾讯&字节&leetcode34：在排序数组中查找元素的第一个和最后一个位置](https://github.com/sisterAn/JavaScript-Algorithms/issues/84)
- [腾讯&leetcode230：二叉搜索树中第K小的元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/86)
- [腾讯&leetcode875：爱吃香蕉的珂珂](https://github.com/sisterAn/JavaScript-Algorithms/issues/109)

### 动态规划
- [字节&leetcode70：爬楼梯问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/90)
- [字节&leetcode746：使用最小花费爬楼梯](https://github.com/sisterAn/JavaScript-Algorithms/issues/91)
- [字节二面&leetcode53：最大子序和](https://github.com/sisterAn/JavaScript-Algorithms/issues/94)
- [腾讯&leetcode121：买卖股票的最佳时机](https://github.com/sisterAn/JavaScript-Algorithms/issues/96)
- [腾讯&leetcode647：回文子串](https://github.com/sisterAn/JavaScript-Algorithms/issues/107)
- [腾讯&leetcode5：最长回文子串](https://github.com/sisterAn/JavaScript-Algorithms/issues/121)
- [阿里&网易&leetcode64：最小路径和](https://github.com/sisterAn/JavaScript-Algorithms/issues/139)

### 贪心算法
- [字节&leetcode122：买卖股票的最佳时机 II](https://github.com/sisterAn/JavaScript-Algorithms/issues/97)
- [字节&leetcode455：分发饼干](https://github.com/sisterAn/JavaScript-Algorithms/issues/115)
- [腾讯&leetcode659：分割数组为连续子序列](https://github.com/sisterAn/JavaScript-Algorithms/issues/117)

### 回溯算法
- [百度&leetcode46：全排列问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/102)
- [腾讯&leetcode22：括号生成](https://github.com/sisterAn/JavaScript-Algorithms/issues/112)

### 编程题
- [携程&蘑菇街&bilibili：手写数组去重、扁平化函数](https://github.com/sisterAn/JavaScript-Algorithms/issues/30)
- [腾讯：不产生新数组，删除数组里的重复元素](https://github.com/sisterAn/JavaScript-Algorithms/issues/135)
- [蘑菇街：按照以下要求，写一个数组（包含对象等类型元素）去重函数](https://github.com/sisterAn/JavaScript-Algorithms/issues/136)
- [网易&美团：实现一个 findIndex 函数](https://github.com/sisterAn/JavaScript-Algorithms/issues/137)
- [字节：模拟实现 Array.prototype.splice](https://github.com/sisterAn/JavaScript-Algorithms/issues/138)
- [字节编程题：实现一个add方法](https://github.com/sisterAn/JavaScript-Algorithms/issues/103)
- [百度：模版渲染](https://github.com/sisterAn/JavaScript-Algorithms/issues/36)
- [百度：什么是浅拷贝和深拷贝？有什么区别？如何实现 Object 的深拷贝](https://github.com/sisterAn/JavaScript-Algorithms/issues/55)
- [阿里&字节：手写 async/await 的实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/56)
- [编程题：用最简洁代码实现 indexOf 方法](https://github.com/sisterAn/JavaScript-Algorithms/issues/58)
- [阿里编程题：实现一个方法，拆解URL参数中queryString](https://github.com/sisterAn/JavaScript-Algorithms/issues/64)
- [字节：输出以下代码运行结果，为什么？如果希望每隔 1s 输出一个结果，应该如何改造？注意不可改动 square 方法](https://github.com/sisterAn/JavaScript-Algorithms/issues/69)
- [字节：修改以下 print 函数，使之输出 0 到 99，或者 99 到 0](https://github.com/sisterAn/JavaScript-Algorithms/issues/101)
- [阿里异步串行编程题：按照以下要求，实现 createFlow 函数 ](https://github.com/sisterAn/JavaScript-Algorithms/issues/106)
- [百度&阿里编程题：模拟实现一个 localStorage](https://github.com/sisterAn/JavaScript-Algorithms/issues/108)
- [美团编程题：编写一个算法解析以下符号，转换为json树的结构](https://github.com/sisterAn/JavaScript-Algorithms/issues/111)
- [阿里：如何判断两个变量相等](https://github.com/sisterAn/JavaScript-Algorithms/issues/116)
- [蘑菇街：找出字符串中连续出现最多的字符和个数](https://github.com/sisterAn/JavaScript-Algorithms/issues/118)
- [字节&剑指 Offer 29：顺时针打印矩阵](https://github.com/sisterAn/JavaScript-Algorithms/issues/119)
- [编程题：以下输出顺序多少 (setTimeout 与 promise 顺序) ](https://github.com/sisterAn/JavaScript-Algorithms/issues/120)
- [腾讯算法题 ](https://github.com/sisterAn/JavaScript-Algorithms/issues/124)
- [腾讯：64匹马，8个赛道，找出跑最快的4匹马](https://github.com/sisterAn/JavaScript-Algorithms/issues/125)
- [华为：一个字符串里出现最多的字符是什么，以及出现次数](https://github.com/sisterAn/JavaScript-Algorithms/issues/126)
- [字节：N数之和](https://github.com/sisterAn/JavaScript-Algorithms/issues/128)
- [编程之美&百度&腾讯：黑球、白球各100，问最后剩下一个是黑球的概率](https://github.com/sisterAn/JavaScript-Algorithms/issues/129)
- [给你一个数组[2,1,2,4,3]，你返回数组 [4,2,4,−1,−1]](https://github.com/sisterAn/JavaScript-Algorithms/issues/142)
- [腾讯：字符串的数字相加](https://github.com/sisterAn/JavaScript-Algorithms/issues/143)
- [找出一个字符串中的不匹配括号的位置，以json形式输出，位置index从0开始](https://github.com/sisterAn/JavaScript-Algorithms/issues/144)
- [基础题，直接写出答案](https://github.com/sisterAn/JavaScript-Algorithms/issues/146)


### 手写源码
- [字节：模拟实现 new 操作符](https://github.com/sisterAn/JavaScript-Algorithms/issues/71)
- [解析 call/apply 原理，并手写 call/apply 实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/78)
- [解析 bind 原理，并手写 bind 实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/81)
- [手写 Promise 源码实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/85)
- [百度：手写parseInt的实现，要求简单一些，把字符串型的数字转化为真正的数字即可，但不能使用JS原生的字符串转数字的API，比如Number()](https://github.com/sisterAn/JavaScript-Algorithms/issues/89)
- [百度：什么是浅拷贝和深拷贝？有什么区别？如何实现 Object 的深拷贝](https://github.com/sisterAn/JavaScript-Algorithms/issues/55)
- [高频：手写一个节流函数 throttle](https://github.com/sisterAn/JavaScript-Algorithms/issues/92)
- [高频：手写一个防抖函数 debounce](https://github.com/sisterAn/JavaScript-Algorithms/issues/95)
- [腾讯：介绍 setTimeout 实现机制与原理](https://github.com/sisterAn/JavaScript-Algorithms/issues/98)
- [阿里&字节：手写 async/await 的实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/56)
- [async await 和 promise 的关系](https://github.com/sisterAn/JavaScript-Algorithms/issues/149)
- [阿里等：实现一个 vue 的双向绑定](https://github.com/sisterAn/JavaScript-Algorithms/issues/100)
- [手写 axios 实现](https://github.com/sisterAn/JavaScript-Algorithms/issues/104)
- [手写一个发布-订阅模式](https://github.com/sisterAn/JavaScript-Algorithms/issues/110)
- [网易&美团：实现一个 findIndex 函数](https://github.com/sisterAn/JavaScript-Algorithms/issues/137)
- [字节：模拟实现 Array.prototype.splice](https://github.com/sisterAn/JavaScript-Algorithms/issues/138)
- [介绍 Redux 原理，并手写一个 Redux](https://github.com/sisterAn/JavaScript-Algorithms/issues/140)
- [手写 useState 实现](https://github.com/sisterAn/blog/issues/130)

### 基础题
- [字节：使用 CSS 画一个三角形](https://github.com/sisterAn/JavaScript-Algorithms/issues/123)
- [网易：请描述一下 cookies、 sessionStorage和localstorage区别](https://github.com/sisterAn/JavaScript-Algorithms/issues/127)
- [腾讯：HTTP 、 HTTPS 、 HTTP2 的区别？](https://github.com/sisterAn/JavaScript-Algorithms/issues/131)
- [字节&平安：CSS 实现文本的单行和多行溢出省略效](https://github.com/sisterAn/JavaScript-Algorithms/issues/130)
- [腾讯：简述一下用户访问网站的过程（缓存，DNS查询，建立链接，请求，响应，收到页面，解析DOM树，显示内容，首屏加载完成，可交互）](https://github.com/sisterAn/JavaScript-Algorithms/issues/133)
- [介绍一下浏览器缓存策略](https://github.com/sisterAn/JavaScript-Algorithms/issues/150)
- [es6 及 es6+ 的能力集，你最常用的，这其中最有用的，都解决了什么问题](https://github.com/sisterAn/JavaScript-Algorithms/issues/147)
- [react 与 vue 的技术栈对比，说下区别](https://github.com/sisterAn/JavaScript-Algorithms/issues/148)
- [react16新增了哪些生命周期、有什么作用，为什么去掉某些15的生命周期](https://github.com/sisterAn/JavaScript-Algorithms/issues/153)
- [前端性能优化](https://github.com/sisterAn/JavaScript-Algorithms/issues/152)
- [http 301 302 307之间的区别](https://github.com/sisterAn/JavaScript-Algorithms/issues/154)

