没有特地为FB准备，不变应万变，一样复习的

1）做leetcode oj, 这是最重要的。。。即使面试没有一模一样的题目，但练完100题
之后，写代码的速度、bug的数量都会和练之前有质的不同
另外自己多总结，比如哪些有linear解，哪些是指数复杂度，哪些是DP，哪些用stack
等。
如果思考的再深入些，可以想到更多，比如可以总结出什么样的二维DP一定可以把空间
复杂度由O(n^2)降至O(n)

2）看本版面经，题目一模一样的概率不大，但是看了面经心里踏实，知道大概流程是
怎么回事，题目大概是什么类型

3）对于lc oj没有覆盖的，自己做些功课，列一些我暂时能想起来的：

3a，简单常见的算法，自己写一遍，比如快速排序，merge排序，桶排序，quick 
selection等等

3b，对于常用数据结构，虽然c++或java里可以从库直接拿来用，但是自己写一遍这些
数据结构的实现能加深理解，例如hashtable, heap, threadsafeblockingqueue, BST
的插入删除等。
而且有些面试题，你还是要自己写，比如LRU cache里的双向链表什么的，写写基本的
数据结构总有好处

3c，面经里经常出现的高频题，而OJ里没有的，例如：influencer(线性解法)，max/
min of sliding window(线性解法)，序列化/反序列化一颗二叉树等

3d，如果有时间，可以写些题目的扩展，比如八皇后的非递归解法，快排的非递归解法
，merge sort的非递归解法等。
其实经常考到的树的iterator、广义表的iterator不也是递归改循环吗

4）设计题，OO设计就是看看例子，看看design pattern
系统设计题，我也很弱，就不多说误导大家了，但感觉经常用到：
hashmap（如果很大，内存放不下怎么办）/reverse indexing/ consistent hashing/ 
trie/ stream algorithm(版上经常说的一个min heap、一个max heap那种题属于这类
，k most frequent的近似解也属于这类) /bloom filter/ load balancer
另外再看看多线程编程，比如reader/writer lock如何实现，有些人喜欢问多线程的设
计题

想到的就这么多，希望对大家有帮助
