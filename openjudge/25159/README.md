# P1060:走迷宫之二
------

总时间限制: 1000ms 内存限制: 65536kB

### 描述

一个字符矩阵代表一个迷宫。'.'是可以走的空地，'#’是不能走的墙壁。迷宫入口在左上角，出口在右下角。
只能往上下左右四个方向的空地走。出口和入口一定是空地。问从入口到出口有多少种不同的不走回头路的
走法，走法不存在则输出0

### 输入

第一行是整数n,m,( 0 < m ,n <= 10)表示迷宫字符矩阵有n行m列。接下来就是n行m列的字符矩阵。

### 输出

所有不走回头路的走法总数

### 样例输入
```
6 8
.#######
........
.#.#.##.
.#....#.
.####.#.
........
```
### 样例输出
```
7
```
### 来源

Guo Wei
