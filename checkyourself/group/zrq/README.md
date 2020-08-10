#  自检清单

## 0x00

- [x] 每周 1 篇技术博客: [丑数算法](https://adorabledevil.github.io/_posts/2020-08-02-%E8%93%9D%E6%A1%A5%E6%9D%AF-%E4%B8%91%E6%95%B0%E7%AE%97%E6%B3%95/)
- [x] 10 个问题
1. What is `丑数` 

把只包含质因子2,3和5的数称作丑数（Ugly Number）.例如6、8都是丑数,但7、14不是,因为它们包含质因子7. 习惯上我们把1当做是第一个丑数.

前20个丑数为：1, 2, 3, 4, 5, 6, 8, 9, 10, 12, 15, 16, 18, 20, 24, 25, 27, 30, 32, 36.

2. ...

- [x] 代码时间打卡



![image](https://gitee.com/adorabledevil/picture-storage/raw/master/8.2%E4%BB%A3%E7%A0%81%E6%97%B6%E9%97%B4.png)






## 0x01
- [x] 每周 1 篇技术博客: [背包问题](https://adorabledevil.github.io/_posts/2020-08-09-%E8%83%8C%E5%8C%85%E9%97%AE%E9%A2%98/)
- [x] 10 个问题
1. **背包问题**


[背包问题详解](https://adorabledevil.github.io/_posts/2020-08-09-%E8%83%8C%E5%8C%85%E9%97%AE%E9%A2%98/)


2. 什么是正则表达式

正则表达式(regular expression)描述了一种字符串匹配的模式（pattern），可以用来检查一个串是否含有某种子串、将匹配的子串替换或者从某个串中取出符合某个条件的子串等。
>
例如第七届蓝桥杯第7题
>
只由 x ( ) | 组成的正则表达式:((xx|xxx)x|(x|xx))xx 能接受的最长字符串是： xxxxxx，长度是6。
>
|代表左右两边取字符串长的一组。
>
()表示优先级
>
其余可看作乘的方式算在一起，所以((xx|xxx)x|(x|xx))xx能接受的最长字符串长度是6。


3. STL整理之``set``

set是 C++ STL 中提供的容器，set是数学上的集合——具有唯一性，即每个元素只出现一次，而 multiset 则是可重集，两者的内部实现是一棵红黑树，它们支持的函数基本相同。set用于判断一个集合内元素的有无。
```cpp
set.insert(x)
```
在 set 中插入元素，返回插入地址的迭代器和是否插入成功的 bool 并成的 pair ，时间复杂度为 ![](https://www.zhihu.com/equation?tex=O%28log+n%29)

PS：set 在进行插入的时候是不允许有重复的键值的，如果新插入的键值与原有的键值重复则插入无效（multiset 可以重复）
```cpp
set.find(x)
```
在 set 中查找值为 x 的元素，并返回指向该元素的迭代器，若不存在，返回 set.end()，时间复杂度为 ![](https://www.zhihu.com/equation?tex=O%28log+n%29)

- [x] 代码时间打卡



![image](https://gitee.com/adorabledevil/picture-storage/raw/master/%E7%AC%AC%E4%BA%8C%E5%91%A8%E4%BB%A3%E7%A0%81%E6%89%93%E5%8D%A1.png)

参考链接:
<br>
1.https://zhuanlan.zhihu.com/p/39963474
<br>
2.https://www.runoob.com/regexp/regexp-syntax.html

## 0x02