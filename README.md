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
	
	* 11
	* 104
	* 144
	* 1207
	* 129
	
- [x] 报了个算法 体验班简单学习了一下(链表,树,以及递归) 

  </details>

<details>
<summary>2020.10.30 回深圳 & leetcode </summary>

- [x] 路上花费了点时间
- [x] leetcode 463
</details>

<details>
<summary>2020.10.31 在家休息 & leetcode </summary>

- [x] 在家里稍微会有点懈怠, 尽量陪陪家里人
- [x] leetcode 380/381
</details>

<details>
<summary>2020.11.1 IOT相关-DVRF配置 </summary>

- [x] The Damn Vulnerable Router Firmware Project(路由器漏洞练习靶机):
	对这个靶机平台进行简单学习以及配置,其中遇到了很多配置环境的坑...
- [x] leetcode 140  单词拆分 II 
</details>


<details>
<summary>2020.11.2 返校 & leetcode </summary>

- [x] 周末回深圳了,周一在路上花了点时间.
- [x] leetcode 349
</details>

<details>
<summary>2020.11.3 STL源码解析 &  leetcode</summary>

- [x] STL源码解析 第一章
- [x] leetcode 941
</details>

<details>
<summary>2020.11.4 STL源码解析 &  leetcode </summary>

- [x] STL源码解析 第二章
- [x] leetcode 57
</details>

<details>
<summary>2020.11.5 STL源码解析 &  leetcode  </summary>

- [x] STL源码解析 第三章
- [x] leetcode 127
</details>

<details>
<summary>2020.11.6 STL源码解析 &   leetcode</summary>

- [x] STL源码解析 第四章
- [x] leetcode 1356
</details>

<details>
<summary>2020.11.7 github整理笔记& 简历编写  </summary>

</details>