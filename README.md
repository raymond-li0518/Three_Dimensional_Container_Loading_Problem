# Three_Dimensional_Container_Loading_Problem
  物流公司在流通过程中，需要将打包完毕的箱子装入到一个货车的车厢中，为了提高物流效率，需要将车厢尽量填满，显然，车厢如果能被100%填满是最优的，但通常认为，车厢能够填满85%，可认为装箱是比较优化的。
设车厢为长方形，其长宽高分别为L，W，H；共有n个箱子，箱子也为长方形，第i个箱子的长宽高为li，wi，hi（n个箱子的体积总和是要远远大于车厢的体积），做以下假设和要求：
1. 长方形的车厢共有8个角，并设靠近驾驶室并位于下端的一个角的坐标为（0,0,0），车厢共6个面，其中长的4个面，以及靠近驾驶室的面是封闭的，只有一个面是开着的，用于工人搬运箱子；
2. 需要计算出每个箱子在车厢中的坐标，即每个箱子摆放后，其和车厢坐标为（0,0,0）的角相对应的角在车厢中的坐标，并计算车厢的填充率。
3. 参数考虑小数点后两位；
4. 实现在线算法，也就是箱子是按照随机顺序到达，先到达先摆放；
5. 需要考虑箱子的摆放顺序，即箱子是从内到外，从下向上的摆放顺序；
6. 因箱子共有3个不同的面，而且箱子可以90度旋转，所以每个箱子有6种不同的摆放状态；
7. 算法需要实时得出结果，即每个箱子决策算法时间小于等于2秒。
