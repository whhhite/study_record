# 2020下半年学习周报/日报

## 这是什么?

因为发现自己之前学习的东西已经遗忘了很多,所以对半年来的学习进行简单的记录以及复习整理.

为了突出重点,会把学校的课程学习忽略,大部分时间还是迫不得已跟着学校上课.

> 因为过去的时间较长,而且很多东西没有记录的习惯,所以前面以周为记录单位.

## 学习记录

<details>
<summary>WEEK 1（2020.5.24）：面试进入天问之路</summary>

- [x] 面试 : 感谢sakura师傅收留了菜菜的我
</details>

<details>
<summary>WEEK 2（2020.5.25-2020.5.31）：STL源码抄写和相应漏洞查找和小作业</summary>

- [x] stl源码剖析: 观看了mooc视频

  [项目地址](https://github.com/whhhite/skr_university_learning_record/tree/master/stl)

- [ ] 待完善 : 这时候抄这个还是懵懵懂懂的,等以后会回来重新看一遍. --(week25 working)
</details>

<details>
<summary>WEEK 3（2020.6.1-2020.6.7）：RCTF & CS143 (compiler) </summary>

- [x] Lexer: 词法分析

  编写词法分析器`flex`脚本,输出对应的C++源码,再编译为`lexer`. 通过正则语法,将字符串转化为token.

  [项目地址](https://github.com/whhhite/skr_university_learning_record/tree/master/compiler/PA2)

- [x] Parser: 语法分析

  通过编写`bison`脚本,构建一个由Token简单组合起来的AST抽象语法分析树.

  [项目地址](https://github.com/whhhite/skr_university_learning_record/tree/master/compiler/PA3)

  </details>

<details>
<summary>WEEK 4（2020.6.8-2020.6.14）：CS143 Sement (语义分析)的简单逆向</summary>

- [x] Sement: 语义分析
	因为无从下手,所以和师傅们一起简单的进行逆向.
</details>

<details>
<summary>WEEK 5（2020.6.15-2020.6.21）：CS143 Sement (语义分析)抄读 </summary>

- [x] Sement: 语义分析

  将语法分析生成的AST进行二次处理,并且捕获所有剩余的错误

  [项目地址](https://github.com/whhhite/skr_university_learning_record/tree/master/compiler/PA4)

  </details>

<details>
<summary>WEEK 6（2020.6.22-2020.6.28）：第五空间CTF以及0CTF &养病</summary>
</details>

<details>
<summary>WEEK 7（2020.6.29-2020.7.5）：SCTF&AFL学习</summary>

- [x] AFL的入门学习 : [相关记录](https://github.com/whhhite/skr_university_learning_record/blob/master/afl/README.md)
</details>

<details>
<summary>WEEK 8（2020.7.6-2020.7.12）：AFL学习&学校实验ddl</summary>

- [x] AFL的略深入学习: 

  [关于Adobe的fuzz学习记录](https://github.com/whhhite/skr_university_learning_record/blob/master/afl/50%20CVEs%20in%2050%20Days%20Fuzzing%20Adobe%20Reader.md)

  [关于gdi+的fuzz学习记录](https://github.com/whhhite/skr_university_learning_record/blob/master/afl/gdi%2B.md)

  </details>

<details>
<summary>WEEK 9（2020.7.13-2020.7.19）：csapp学习以及前两个lab </summary>

- [x] csapp: 1~2章

  * [第一章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E4%B8%80%E7%AB%A0) 计算机系统漫游
  * [第二章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E4%BA%8C%E7%AB%A0) 信息的表示和处理

- [x] lab: lab1~2

  * [datalab](https://github.com/whhhite/skr_university_learning_record/blob/master/csapp/lab/datalab.md) 用位运算实现一些功能
  * [boomlab](https://github.com/whhhite/skr_university_learning_record/blob/master/csapp/lab/bomb.md) gdb实现逆向分析

  </details>

<details>
<summary>WEEK 10（2020.7.20-2020.7.26)：csapp学习以及三个lab</summary>

- [ ] csapp: 3~5章
  * [第三章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E4%B8%89%E7%AB%A0) 程序的机器级表示
  * [第四章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E4%B8%89%E7%AB%A0) 处理器体系结构
  * [第五章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E4%B8%89%E7%AB%A0) 优化程序性能
  * [第六章](https://github.com/whhhite/skr_university_learning_record/tree/master/csapp/%E7%AC%AC%E5%85%AD%E7%AB%A0) 存储器层次结构
- [ ] lab: lab3~5
  * [attack lab](https://github.com/whhhite/skr_university_learning_record/blob/master/csapp/lab/attack.md) Code injection && ROP
  * [arch lab](https://github.com/whhhite/skr_university_learning_record/blob/master/csapp/lab/archlab.md) 
  * [cache lab](https://github.com/whhhite/skr_university_learning_record/blob/master/csapp/lab/cache.md)
    </details>

<details>
<summary>WEEK 11~14（2020.7.27-2020.8.23）：回学校考试</summary>
</details>

<details>
<summary>WEEK 15（2020.8.24-2020.8.30）：电工实习</summary>
</details>

<details>
<summary>WEEK 16（2020.8.31-2020.9.6）：ucore+googlectf</summary>

- [x] ucore : lab1~2

  - [ ] [lab1](https://github.com/whhhite/skr_university_learning_record/blob/master/ucore/lab1.md) 
  - [ ] lab2 (后续笔记忘记传github丢了...后面再补) 
- [x] googlectf : [SIMD](https://github.com/whhhite/skr_university_learning_record/tree/master/CTF/2020%20googlectf)&&sprint
</details>

<details>
<summary>WEEK 17（2020.9.7-2020.9.13）：ucore</summary>

- [x] ucore : lab3
</details>


<details>
<summary>WEEK 18（2020.9.14-2020.9.20）：IOT简单学习了解+Plainctf+国赛</summary>

- [x] IOT:  简单学习
- [x] PlainCTF: reee
- [x] 国赛: 周末两天  
</details>

<details>
<summary>WEEK 19（2020.9.21-2020.9.27）：TCTF final + 小米路由器IOT相关漏洞</summary>

- [x] TCTF final :  unlimited.
- [x]  [小米CVE-2020-11959](https://github.com/whhhite/skr_university_learning_record/blob/master/iot/%E5%B0%8F%E7%B1%B3%E8%B7%AF%E7%94%B1%E5%99%A8%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95.md) : 学习记录
</details>

<details>
<summary>WEEK 20（2020.9.28-2020.10.4）：mi_lua + 看路由器学习资料</summary>

- [x] [mi_lua](https://github.com/whhhite/skr_university_learning_record/blob/master/iot/%E5%B0%8F%E7%B1%B3%E8%B7%AF%E7%94%B1%E5%99%A8%E5%AD%A6%E4%B9%A0%E8%AE%B0%E5%BD%95.md) : 简单学习
- [x] 看了点路由器相关的资料 
</details>

<details>
<summary>WEEK 21（2020.10.5-2020.10.11）：课比较多随便看了点东西</summary>
</details>

<details>
<summary>WEEK 22（2020.10.12-2020.10.18）：工控安全相关</summary>

- [x] 看了点vxworks的资料

- [x] 安全客2020季刊/第三期/工控安全部分

  > 参考资料:  https://static.anquanke.com/download/b/security-geek-2020-q3.pdf 

  Q: 为什么越来越重视工控安全

  A: 工控设备的传统通信方式(无线电和电缆)转向基于IP的系统(接入互联网).随着接入互联网的设备越来越多,逐渐的构成了工业互联网体系.但是其中的设备大多更新迭代困难,所以会存在很多安全缺陷,一旦出现安全事件,影响巨大.

  > 后续的关于工控文章(包括协议)对于本人现阶段来说有点超前,先在此mark,等以后学习了更多之后再补充. 

  </details>

<details>
<summary>WEEK 23（2020.10.19-2020.10.25）：复现了vxworks的题目 以及 ByteCTF </summary>

- [x] [复现了NOE 771固件以及分析](https://github.com/whhhite/skr_university_learning_record/blob/master/iot/%E5%85%B3%E4%BA%8E%E6%96%BD%E8%80%90%E5%BE%B7NOE%20771%E5%9B%BA%E4%BB%B6%E7%9A%84%E5%88%86%E6%9E%90.md)
- [x] 打了ByteCTF的两道题目
</details>

<details>
<summary>WEEK 24（2020.10.26-2020.10.29）：leetcode 以及算法课</summary>

- [x] leetcode: 
	因为要差不多开始准备寒假实习, 刷一下算法
	
	* 11 盛水的容器
	  * 双指针的用法.
	* 104 二叉树的最大深度
	  * 简易递归
	* 144 二叉树的前序遍历
	* 1207 独一无二的出现次数
	  * set的用法
	* 129 求根到叶子节点数字之和
	  * dfs
	
- [x] 报了个算法 体验班简单学习了一下(链表,树,以及递归) 

  * 讲链表的时候提到了跳表,.
    * 跳表的思想是二分查找. 它插入/删除/搜索都是O(logn). 
    * 原理是索引, 通过升维,用空间来换时间.
    * 缺点是维护成本比较高,空间复杂度为O(n)
    * 同时有提到Leetcode 146 LRU cache和 Redis skip list 晚点去看一下
  * 时间复杂度
    * 主定理
    * 二分查找 O(logn) 二叉树遍历 O(n) 二维矩阵 O(n) 归并排序 O(nlogn)
    * 讲题例子是爬楼梯
  * 递归
    * 四步骤
      * 终止条件
      * 获取当前数据
      * 进一步递归
      * 回溯
  
  </details>

<details>
<summary>2020.10.30 回深圳 & leetcode </summary>

* leetcode 463 岛屿的周长
  * 迭代

</details>

<details>
<summary>2020.10.31 在家休息 & leetcode </summary>
* 在家里稍微会有点懈怠, 尽量陪陪家里人

* leetcode 380 常数时间插入、删除和获取随机元素

  * 平均复杂度为O(1)下实现insert、remove、getRandom

  * 采用哈希表配合vector存储

  * remove采用置换之后调用vector的pop_back以及哈希表的erase(val)删除元素的键值对

  * random采用下标访问,且没随机种子,所以是固定的
  * 待研究: leetcode 381 题目加上允许重复.
        </details>

<details>
<summary>2020.11.1 IOT相关-DVRF配置 </summary>
* The Damn Vulnerable Router Firmware Project(路由器漏洞练习靶机):
  	对这个靶机平台进行简单学习以及配置,其中遇到了很多配置环境的坑...

* leetcode 140 单词拆分 II 

  * 没做出来 to do

  * 先去看了139 单词拆分 I  

    * 动态规划
    * 剪枝 to do

    </details>


<details>
<summary>2020.11.2 返校 & leetcode </summary>

- [x] 周末回深圳了,周一在路上花了点时间.

- [x] leetcode 349  两个数组的交集

  * 使用unordered_set, 底层是hash表实现的.
  * 要学习别人代码的精简,善于用迭代器.

  </details>

<details>
<summary>2020.11.3 STL源码解析 &  leetcode</summary>

- [x] STL源码解析 第一章
  * STL所实现的是 根据**泛性思维**架设起来的一个概念结构
    * 这个以抽象概念(abstract concepts)为主题而非以实际类(classes)为主体的机构,形成了一个严谨的接口标准.
    * 在此接口之下,任何组件都有最大的独立性,并以所谓迭代器(iterator)胶合起来,或以所谓配接器(adapter)互相配接,或以所谓仿函数(functor)动态选择某种策略
  * C++**classes**允许**自行定义型别**,**templates**允许将**型别参数化**,将两者结合并通过**traits编程技法**,形成了STL的绝佳温床.
- [x] leetcode 941 有效的山脉数组
</details>

<details>
<summary>2020.11.4 STL源码解析 &  leetcode </summary>

- [x] STL源码解析 第二章 上

  * SGI STL 的配置器采用**alloc**而非alllocator

  * 正常内存配置为

    ```
    Class Foo{...};
    Foo *pf = new Foo;
    ```

    * new含两阶段操作:
      * 调用operate new 配置内存
      * 调用Foo::Foo()构造对象内容
    * delete也含两阶段操作:
      * 调用Foo::~Foo()将对象析构
      * 调用::operator delete释放内存

  *  为了精密加工,STL allocator决定将这两阶操作区分开

    * 内存配置操作由 alloc:allocate()负责
    * 内存释放操作由alloc:deallocate()负责
    * 对象构造操作由::construct()负责
    * 对象析构操作由::destroy()负责

  * 配置器定义于<memory>之中,内含

    * #include <stl_alloc.h>                //负责内存空间的配置与释放
    * #include <stl_construct.h>        //负责对象内容的构造与析构

- [x] leetcode 57 插入区间

  * 判断

  </details>

<details>
<summary>2020.11.5 STL源码解析 &  leetcode  </summary>

- [x] STL源码解析 第二章 下

  * 晚点应该会贴个图关于constuct()与destroy()的源码
    * destroy之中有一些**泛化**与**特化**的思想
      * 一个版本为接受一个指针
      * 第二个版本为接受两个迭代器,析构中间部分
      * 第三个版本为判断**trivial destructor** 是否无关痛痒,来决定是否析构.
  * 关于stl_alloc.h
    * 双层级配置器
    * 第二层级用于配置区块过小,为了降低额外负担,采用了复杂的memory pool整理方式.
    * **simple_alloc**作为alloc的接口
    * 关于第一级配置器 **__malloc_alloc_template**的剖析
      * **oom**: out of memory
  * 关于uninitialized_copy/fill
    * "commit or rollback"  (要么构造出所有必要元素,要么不构造任何东西)
    * **POD**(Plain Old Data),标量型别或者传统的C struct型别. 可以采用最有效的复制/填写手法.

- [x] leetcode 127 单词接龙

  * push_back与**emplace_back**

    * push_back先创建元素,再将元素拷贝到容器中

    * emplace_back直接在尾部创建
    
  * 构图: 虚拟节点
      
      </details>

<details>
<summary>2020.11.6 STL源码解析 &   leetcode</summary>

- [x] STL源码解析 第三章 上

- [x] leetcode 1356 根据数字二进制下 1 的数目排序

  * 改写sort规则

  * 打表

    </details>

<details>
<summary>2020.11.7 github整理笔记& 简历编写  </summary>

- [x] 院运会混志愿时
- [x] 简历编写
- [x] github整理笔记 
</details>