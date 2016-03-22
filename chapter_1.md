#第一章作业之课后1.3题
##概述
这题是计算跳伞这项运动下落速度随时间的函数变化，及计算速度随时间的变化曲线，并找出平衡速度。
##计算思路
1.运用欧拉方法，先展开速度时间关系式  

2.将体重所给的求导式子带入到1中的展开式中  

3.写程序
##过程
总时间t_total  

时间分段长度dt  

分段数n=t_total/dt  

常数a,b  

计算v  

i从1循环到n，每次增加dt的时间  

每次的速度增加近似认为是匀加速  

每次的位移增加近似看成匀加速运动  

把每一次的t、v分别储存在三个数组中  

将v-t曲线绘制出来  
##结果
程序链接:[chapter1.py]( https://github.com/CrossV/computationalphysics_N2013301020067/blob/master/chapter1.png)

效果图：![alt text](https://github.com/CrossV/computationalphysics_N2013301020067/blob/master/chapter1.png)  

##分析
*由python数据可知，一段时间后，速度达到平衡点约为9.9999.....m/s，但由于系统误差，即：每次时间段不是无限小。导致小数点后第八位开始是不断变化的，即速度不是完全不变的。但是结果在误差范围之内。*  
另外，感谢13级59号同学。

