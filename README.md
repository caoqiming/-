
正四面体魔方穷举法求最优解

这是一个用c++编写的，用穷举法求四面体魔方最优解的算法。
因为正四面体的最边上的四个角最后很简单就能还原，这个算法不考虑四个角。
使用方法：
1.将魔方放在桌面上，使得任意一面正对你。按图示所示观察每个面6个色块的颜色。注意上面三个面的顺序与底面不同，观察底面时将你对面最远的点固定住，将魔方掀起90度即可按照底面图示得到底面颜色。
2.根据程序提示输入各个面的颜色。每个颜色用一个字符表示，建议红色r，绿色g，黄色y，蓝色b，若你想输入别符号的也行，保证同一种颜色输入的是相同的符号即可。输入颜色时不需要换行也不需要空格。比如对于已经还原好的魔方你的输入可能是：yyyyyy(回车)gggggg(回车)bbbbbb(回车)rrrrrr(回车)
3.运行程序得到解，因为是穷举算法，运算速度与你的计算器性能相关。若你的电脑能够找到解则会返回一串数字。
4.根据数字旋转魔方即可还原。根据图示每个数字表示旋转相应方向上的部位。一个数字表示旋转一次，旋转方向都是该旋转的三角尖的俯视情况下的逆时针方向。两个相同的数字连着则等价于顺时针方向转一下。
5.自行还原4个角。

若找不到解可能是计算机性能有限，也可能是输入有误。
图示画的很随意，抱歉~~~~  这里稍微说明一下各个旋转数字表示的位置：
1上面的角
2对面的角
3右边的角
4左边的角
