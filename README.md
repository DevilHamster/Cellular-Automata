# Cellular-Automata

本项目是一个用于在Grasshopper平台上运行元胞自动机的插件。

使用需知：

1.本插件的特点在于可以不受元胞形状限制(元胞可以是非平面、非闭合曲线，其形状可以是非规则多边形，边数越少计算越快)

2.使用时需要传入元胞单元格(有序排列的单元格可以缩短计算时间)以及迭代次数。在允许计算的条件下程序将生成每次迭代中表现为“存活”的元胞索引

3.这是一个基于几何逻辑(而非矩阵逻辑)的元胞自动机，其运算承载力有限，应尽可能将元胞总数控制在10000以内

4.程序支持使用Von及Moor型的邻居划分方式，暂时只支撑森林火灾计算模型和生命游戏模型。

5.元胞自动机的相关概念和知识可见https://zhuanlan.zhihu.com/p/39451507，对本插件的使用可参照实例文件。

6.这是本人接触C#编程以来开发的第一个功能较为完整的Grasshopper插件。程序恐怕不会再做添加和更新，仅作为学习记录和思维参考用。
