# <算法导论> 学习笔记

    算法的精华在于分析和比较，难点在于算法相关的证明。至于实现，这更多是对算法步骤的记忆，或者是伪代码的翻译过程。

1. 算法基础

循环不变式主要用来帮助我们理解算法的正确性。关于循环不变式，我们需要证明三条性质：
 - 初始化：循环的第一次迭代之前，它为真。
 - 保持：如果循环的某次迭代之前它为真，那么下次迭代之前它仍为真。
 - 终止：在循环终止时，不变式为我们提供一个有用的性质，该性质有助于证明算法是正确的。

分析算法：
 - 输入规模
 - 运行时间
 - 最坏情况与平均情况分析
 - 增长量级

分治法：
    许多算法在结构上是递归的。
    分治模式在每层递归时都有三个步骤：
    a. 分解原问题为若干子问题。
    b. 解决这些子问题，递归地求解各子问题。
    c. 合并这些子问题的解成原问题的解。
    
比如归并排序。

2. 分治策略

2.1 最大子数组问题

暴力方法：O（n^2）
分治法：O（nlgn）

2.2 矩阵乘法

暴力方法：O（n^3）
分治法：O（n^lg7）

2.3 求解递归式
 - 代入法
 - 递归树法
 - 主方法

3. 排序

![排序算法比较](img/排序算法比较.png)


4. 数据结构
 - 散列表
 - 红黑树
 
5. 动态规划

    设计步骤：

    a. 刻画一个最优解的结构特征
    b. 递归地定义最优解的值。
    c. 计算最优解的值，通常采用自底向上的方法。
    d. 利用计算出的信息构造一个最优解。

    `钢条切割`

    `矩阵链乘法`

    `最长公共子序列`

    `最优二叉搜索树`

