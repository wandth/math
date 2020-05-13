- [向量](#%e5%90%91%e9%87%8f)
  - [向量加减法](#%e5%90%91%e9%87%8f%e5%8a%a0%e5%87%8f%e6%b3%95)
    - [加法](#%e5%8a%a0%e6%b3%95)
      - [三角形法则](#%e4%b8%89%e8%a7%92%e5%bd%a2%e6%b3%95%e5%88%99)
      - [平行四边形法则](#%e5%b9%b3%e8%a1%8c%e5%9b%9b%e8%be%b9%e5%bd%a2%e6%b3%95%e5%88%99)
    - [减法](#%e5%87%8f%e6%b3%95)
  - [二维基向量](#%e4%ba%8c%e7%bb%b4%e5%9f%ba%e5%90%91%e9%87%8f)
  - [向量张成的空间](#%e5%90%91%e9%87%8f%e5%bc%a0%e6%88%90%e7%9a%84%e7%a9%ba%e9%97%b4)
  - [左右手坐标系](#%e5%b7%a6%e5%8f%b3%e6%89%8b%e5%9d%90%e6%a0%87%e7%b3%bb)
  - [点乘 (dot product)](#%e7%82%b9%e4%b9%98-dot-product)
    - [点乘几何意义](#%e7%82%b9%e4%b9%98%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
  - [叉乘](#%e5%8f%89%e4%b9%98)
- [线性变换](#%e7%ba%bf%e6%80%a7%e5%8f%98%e6%8d%a2)
  - [含义](#%e5%90%ab%e4%b9%89)
  - [求解表达式](#%e6%b1%82%e8%a7%a3%e8%a1%a8%e8%be%be%e5%bc%8f)
  - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
- [矩阵](#%e7%9f%a9%e9%98%b5)
  - [基本定义](#%e5%9f%ba%e6%9c%ac%e5%ae%9a%e4%b9%89)
  - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89-1)
    - [向量左乘矩阵的几何意义](#%e5%90%91%e9%87%8f%e5%b7%a6%e4%b9%98%e7%9f%a9%e9%98%b5%e7%9a%84%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
    - [矩阵乘法的几何意义](#%e7%9f%a9%e9%98%b5%e4%b9%98%e6%b3%95%e7%9a%84%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
    - [证明](#%e8%af%81%e6%98%8e)
  - [矩阵的行列式（det）](#%e7%9f%a9%e9%98%b5%e7%9a%84%e8%a1%8c%e5%88%97%e5%bc%8fdet)
    - [基本定义](#%e5%9f%ba%e6%9c%ac%e5%ae%9a%e4%b9%89-1)
    - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89-2)
  - [矩阵的秩（rank）](#%e7%9f%a9%e9%98%b5%e7%9a%84%e7%a7%a9rank)
    - [基本定义](#%e5%9f%ba%e6%9c%ac%e5%ae%9a%e4%b9%89-2)
    - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89-3)
  - [线性空间（向量空间）](#%e7%ba%bf%e6%80%a7%e7%a9%ba%e9%97%b4%e5%90%91%e9%87%8f%e7%a9%ba%e9%97%b4)
  - [矩阵的核](#%e7%9f%a9%e9%98%b5%e7%9a%84%e6%a0%b8)
    - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89-4)
  - [线性空间的基](#%e7%ba%bf%e6%80%a7%e7%a9%ba%e9%97%b4%e7%9a%84%e5%9f%ba)
    - [线性表示](#%e7%ba%bf%e6%80%a7%e8%a1%a8%e7%a4%ba)
    - [线性相关](#%e7%ba%bf%e6%80%a7%e7%9b%b8%e5%85%b3)
    - [线性无关](#%e7%ba%bf%e6%80%a7%e6%97%a0%e5%85%b3)
    - [线性空间基的定义](#%e7%ba%bf%e6%80%a7%e7%a9%ba%e9%97%b4%e5%9f%ba%e7%9a%84%e5%ae%9a%e4%b9%89)
    - [性质](#%e6%80%a7%e8%b4%a8)
    - [坐标](#%e5%9d%90%e6%a0%87)
    - [坐标转换](#%e5%9d%90%e6%a0%87%e8%bd%ac%e6%8d%a2)
    - [线性变换在不同基下的表示](#%e7%ba%bf%e6%80%a7%e5%8f%98%e6%8d%a2%e5%9c%a8%e4%b8%8d%e5%90%8c%e5%9f%ba%e4%b8%8b%e7%9a%84%e8%a1%a8%e7%a4%ba)
  - [矩阵分解](#%e7%9f%a9%e9%98%b5%e5%88%86%e8%a7%a3)
    - [特征向量和特征值](#%e7%89%b9%e5%be%81%e5%90%91%e9%87%8f%e5%92%8c%e7%89%b9%e5%be%81%e5%80%bc)
    - [特征向量和特征值的几何意义](#%e7%89%b9%e5%be%81%e5%90%91%e9%87%8f%e5%92%8c%e7%89%b9%e5%be%81%e5%80%bc%e7%9a%84%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
    - [特征方程的由来](#%e7%89%b9%e5%be%81%e6%96%b9%e7%a8%8b%e7%9a%84%e7%94%b1%e6%9d%a5)
    - [矩阵分解的基本定义](#%e7%9f%a9%e9%98%b5%e5%88%86%e8%a7%a3%e7%9a%84%e5%9f%ba%e6%9c%ac%e5%ae%9a%e4%b9%89)
    - [几何意义](#%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89-5)
    - [正交矩阵](#%e6%ad%a3%e4%ba%a4%e7%9f%a9%e9%98%b5)
    - [标淮正交基](#%e6%a0%87%e6%b7%ae%e6%ad%a3%e4%ba%a4%e5%9f%ba)
    - [正交矩阵的几何意义](#%e6%ad%a3%e4%ba%a4%e7%9f%a9%e9%98%b5%e7%9a%84%e5%87%a0%e4%bd%95%e6%84%8f%e4%b9%89)
  - [变换矩阵](#%e5%8f%98%e6%8d%a2%e7%9f%a9%e9%98%b5)
    - [标准形式](#%e6%a0%87%e5%87%86%e5%bd%a2%e5%bc%8f)
    - [缩放矩阵](#%e7%bc%a9%e6%94%be%e7%9f%a9%e9%98%b5)
    - [镜像矩阵](#%e9%95%9c%e5%83%8f%e7%9f%a9%e9%98%b5)
    - [旋转矩阵](#%e6%97%8b%e8%bd%ac%e7%9f%a9%e9%98%b5)
    - [位移矩阵](#%e4%bd%8d%e7%a7%bb%e7%9f%a9%e9%98%b5)
    - [仿射变换](#%e4%bb%bf%e5%b0%84%e5%8f%98%e6%8d%a2)
      - [缩放](#%e7%bc%a9%e6%94%be)
      - [旋转](#%e6%97%8b%e8%bd%ac)
      - [平移](#%e5%b9%b3%e7%a7%bb)
    - [逆变换](#%e9%80%86%e5%8f%98%e6%8d%a2)
    - [组合变换](#%e7%bb%84%e5%90%88%e5%8f%98%e6%8d%a2)
    - [3D 变换矩阵](#3d-%e5%8f%98%e6%8d%a2%e7%9f%a9%e9%98%b5)
      - [缩放](#%e7%bc%a9%e6%94%be-1)
      - [平移](#%e5%b9%b3%e7%a7%bb-1)
      - [旋转](#%e6%97%8b%e8%bd%ac-1)
        - [绕 $x$ 轴旋转](#%e7%bb%95-math-xmlns%22httpwwww3org1998mathmathml%22semanticsmrowmixmimrowannotation-encoding%22applicationx-tex%22xannotationsemanticsmathx-%e8%bd%b4%e6%97%8b%e8%bd%ac)
        - [绕 $y$ 轴旋转](#%e7%bb%95-math-xmlns%22httpwwww3org1998mathmathml%22semanticsmrowmiymimrowannotation-encoding%22applicationx-tex%22yannotationsemanticsmathy-%e8%bd%b4%e6%97%8b%e8%bd%ac)
        - [绕 $z$ 轴旋转](#%e7%bb%95-math-xmlns%22httpwwww3org1998mathmathml%22semanticsmrowmizmimrowannotation-encoding%22applicationx-tex%22zannotationsemanticsmathz-%e8%bd%b4%e6%97%8b%e8%bd%ac)
        - [绕着  $n$ 轴旋转 $\alpha$ 度（罗德里格斯旋转公式）](#%e7%bb%95%e7%9d%80-math-xmlns%22httpwwww3org1998mathmathml%22semanticsmrowminmimrowannotation-encoding%22applicationx-tex%22nannotationsemanticsmathn-%e8%bd%b4%e6%97%8b%e8%bd%ac-math-xmlns%22httpwwww3org1998mathmathml%22semanticsmrowmi%ce%b1mimrowannotation-encoding%22applicationx-tex%22alphaannotationsemanticsmath%ce%b1-%e5%ba%a6%e7%bd%97%e5%be%b7%e9%87%8c%e6%a0%bc%e6%96%af%e6%97%8b%e8%bd%ac%e5%85%ac%e5%bc%8f)
          - [罗德里格斯旋转矩阵 推导](#%e7%bd%97%e5%be%b7%e9%87%8c%e6%a0%bc%e6%96%af%e6%97%8b%e8%bd%ac%e7%9f%a9%e9%98%b5-%e6%8e%a8%e5%af%bc)
- [参考](#%e5%8f%82%e8%80%83)

# 向量
## 向量加减法

### 加法
#### 三角形法则

![](https://gitee.com/freedom_man/FigureBed/raw/master/SnipasteTwoVercorSum.jpg)

已知非零向量 $\vec{a}$，$\vec{b}$，在平面内任取一点 $A$，作$\vec{AB} = \vec{a}$，$\vec{BC} = \vec{b}$，则向量$\vec{AC}$ 叫做$\vec{a}$ 和 $\vec{b}$ 的和， 记作 $\vec{a} + \vec{b}$
即：
$$\vec{a} + \vec{b} = \vec{AB} + \vec{BC}  = \vec{AC} $$

> 首尾相接的的若干向量之和，等于起始向量的起点指向末尾向量的终点的向量
#### 平行四边形法则
![]()
以同一点$O$为起点的两个已知向量 $\vec{a}$，$\vec{b}$ 为邻边作 $▱ OACB$，则$O$为起点的对角线$\vec{OC}$ 就是$\vec{a}$ 和 $\vec{b}$ 的和， 记作 $\vec{a} + \vec{b}$
即：
$$\vec{a} + \vec{b} = \vec{OA} + \vec{OB}  = \vec{OC} $$

### 减法
**注：**$\vec{a} - \vec{b} = \vec{a} + (-\vec{b})$

![](https://gitee.com/freedom_man/FigureBed/raw/master/twoVectorMinus.png)
向量减法的推导
$$\vec{a}-\vec{b}=\vec{a}+(-\vec{b})=\overrightarrow{A C}+\overrightarrow{A D}=\overrightarrow{A E}=\overrightarrow{B C}$$
即：$\vec{AC} + \vec{AB} = \vec{BC}$

因此，可得：从同一点出发的两个向量 $\vec{a}$，$\vec{b}$ ，$\vec{a} - \vec{b}$就可以表示为从向量 $\vec{b}$ 的终点指向向量 $\vec{a}$ 终点的向量

![](https://gitee.com/freedom_man/FigureBed/raw/master/twoVectorMinusTwo.jpg)

## 二维基向量

在平面系统中有一对基向量 $\vec{i} = (1, 0)$ ， $\vec{j} = (0, 1)$ 用它们的线性组合（加法和数乘）来表示任意的向量，也就是任意向量  $\vec{v} = (x, y) = x\vec{i} + y\vec{j}$

如图用基向量来表示 $\vec{v} = (2, 3) = 2\vec{i} + 3\vec{j}$

![](..\\..\\FigureBed\\v2-d47d0f9bde87bbd27ca12bc10fbecdd6_720w.jpg)

> 基向量是取值是任意的，只要他们线性无关
## 向量张成的空间
在二维平面中，选取 2 个向量（二维基向量），它们所有可能的线性组合叫做向量张成的空间

在平面中
- 如果这对基向量线性无关，则它们张成的空间就是整个平面
- 如果它们线性相关，则张成的空间就是它们所在的直线
- 如果它们是零向量，则它们张成的空间就是原点

## 左右手坐标系

![](https://gitee.com/freedom_man/FigureBed/raw/master/rightAndLeftCoordinate.png)

旋转正方向要遵循 ：**左右手法则**

![](https://gitee.com/freedom_man/FigureBed/raw/master/leftHandAndRightHand.png)
向量是由 n 个实数组成的一个$n*1$(**n 行 1 列**) 或$1*n$(**1 行 n 列**) 的有序数组

## 点乘 (dot product)
是对这两个向量对应位一一相乘之后求和的操作，点乘的结果是一个标量

若
- $\mathbf{\mathbf{a}}=\left[a_{1}, a_{2}, \dots a_{n}\right]$
- $\mathbf{\mathbf{\mathbf{b}}}=\left[b_{1}, b_{2}, \ldots b_{n}\right]$

则：
$$\mathbf{\mathbf{a}} \bullet \mathbf{\mathbf{\mathbf{b}}}=\sum_{i=1}^{n} a_{i} b_{i}=a_{1} b_{1}+a_{2} b_{2}+\dots+a_{n} b_{n}$$

> $\mathbf{\mathbf{a}}$ 的行数与 $\mathbf{\mathbf{\mathbf{b}}}$ 的列数相同

### 点乘几何意义
点乘的几何意义是可以用来表征或计算两个向量之间的**夹角**，以及 $\mathbf{b}$ 在 ${\mathbf{a}}$ 方向上的投影

$$\mathbf{a} \bullet \mathbf{b}=|\mathbf{a}||\mathbf{b}| \cos \theta$$

对于单位向量来说：$\cos \theta=\hat{a} \cdot \hat{b}$

推导过程如下，首先看一下向量组成：
![](https://gitee.com/freedom_man/FigureBed/raw/master/mathDotProductGraphic.png)
1. 定义向量：

$$\mathbf{c} = \mathbf{\mathbf{a}} -\mathbf{b}  \tag{1.1}$$

2. 依据余弦定理

$$\mathbf{c}^{2}=\mathbf{a}^{2}+\mathbf{b}^{2}-2|\mathbf{a} \| \mathbf{b}| \cos \theta$$

3. 则由 $公式 1.1$ 可以推导出

$$\begin{aligned}
(\mathbf{a}-\mathbf{b}) \cdot(\mathbf{a}-\mathbf{b}) &=\mathbf{a}^{2}+\mathbf{b}^{2}-2 \mathbf{a} \cdot \mathbf{b} \\
&=\mathbf{a}^{2}+\mathbf{b}^{2}-2|\mathbf{a}||\mathbf{b}| \cos \theta
\end{aligned}$$

4. 即：
$$\mathbf{a} \bullet \mathbf{b}=|\mathbf{a}||\mathbf{b}| \cos \theta$$

5. 从而可知 $\mathbf{a}$ 和 $\mathbf{b}$ 的夹角$\theta$：

$$\theta=\operatorname{arccos}\left(\frac{\mathbf{a} \bullet \mathbf{b}}{|\mathbf{a}||\mathbf{b}|}\right)$$

6. 进一步判断这两个向量是否是同一方向，是否垂直等方向关系
具体对应关系为：

$$
\begin{cases}
\mathbf{a}·\mathbf{b}>0 \longmapsto 0^{\circ} < \theta < 90^{\circ}\\
\mathbf{a}·\mathbf{b}=0 \longmapsto \theta = 90^{\circ}\\
\mathbf{a}·\mathbf{b}<0 \longmapsto 90^{\circ} < \theta < 180^{\circ}
\end{cases}
$$

## 叉乘
![](https://gitee.com/freedom_man/FigureBed/raw/master/crossProductGif.gif)
$$
\mathbf{c}=\begin{cases}
direction&:\mathbf{c} \bot \mathbf{a}  \quad \mathbf{c} \bot \mathbf{b}，且、mathbf{c}的方向由右手法则确定 \\
norm &:|\mathbf{a}||\mathbf{b}|sin\theta \times n
\end{cases}
$$

- $n$ 是与 $\mathbf{a}$ 和 $\mathbf{b}$ 都成直角的的单位向量
- $|\mathbf{a}|$ 是 $\mathbf{a}$ 的大小
- $|\mathbf{b}|$ 是 $\mathbf{b}$ 的大小

对于 $\mathbf{a}$ 和 $\mathbf{b}$ ：
$$\begin{aligned}
&\mathbf{a}=\left(x_{1}, y_{1}, z_{1}\right)\\
&\mathbf{b}=\left(x_{2}, y_{2}, z_{2}\right)
\end{aligned}
$$

$\mathbf{\mathbf{a}}$ 和 $\mathbf{\mathbf{\mathbf{b}}}$ 的叉乘公式为：

若：
$$\begin{aligned}
&\mathbf{a}=a_{x} i+a_{y} j+a_{z}k\\
&\mathbf{b}=b_{x} i+b_{y} j+b_{z}k\\
\end{aligned}$$

则：
$
\begin{aligned}
\mathbf{a} \times \mathbf{b} \\
& =\left|\begin{array}{lll}
\mathrm{i} & \mathrm{j} & \mathrm{k} \\
x_{1} & y_{1} & z_{1} \\
x_{2} & y_{2} & z_{2}
\end{array}\right| \\
& =\left(y_{1} z_{2}-y_{2} z_{1}\right) i-\left(x_{1} z_{2}-x_{2} z_{1}\right) j+\left(x_{1} y_{2}-x_{2} y_{1}\right) k
\end{aligned}
$

叉积：
$$\mathbf{\mathbf{a}} \times \mathbf{\mathbf{\mathbf{b}}}=\left(a_{x}, a_{y}, a_{z}\right) \times\left(b_{x}, b_{y}, b_{z}\right)=\left(a_{y} b_{z}-a_{z} b_{y}, a_{z} b_{x}-a_{x} b_{z}, a_{x} b_{y}-a_{y} b_{x}\right)$$

叉乘几何意义
- 在三维几何中，$\mathbf{a}$ 和 $\mathbf{\mathbf{b}}$ 的叉乘结果是一个向量，更为熟知的叫法是法向量，该向量垂直于$\mathbf{a}$ 和 $\mathbf{\mathbf{b}}$ 构成的平面。
![](https://gitee.com/freedom_man/FigureBed/raw/master/crossProductGraphic.png)

- 在二维空间中，$\mathbf{\mathbf{a}} \times \mathbf{\mathbf{\mathbf{b}}}$等于由 $\mathbf{a}$ 和 $\mathbf{\mathbf{b}}$ 构成的平行四边形的面积

# 线性变换

## 含义
所谓变换就是一个函数，这个函数接收一个向量作为输入（需要变换的向量），输出一个新的向量（变换后的向量）：$\vec{u} = L(\vec{v})$  ， $L$ 就是一个变换

在几何上的意义就是把一个向量“变形”成另一个向量，比如旋转、缩放、斜切等

线性变换的严格定义如下，变换需满足
$$ \begin{array}{c}
L(\vec{v}+\vec{u})=L(\vec{v})+L(\vec{u}) \tag{1} \\
L(c \vec{v})=c L(\vec{v})
\end{array} $$

即**可加性**和**等比例**（一阶齐次），则变换 $L$ 就是线性变换。
在几何上需满足
- 所有起点位于原点的向量经过变换后起点仍然处于原点（故平移不是线性变换）
- 所有在同一直线上且等距的点变换后仍处于同一直线且等距

## 求解表达式
我们在二维空间 $R_2$ 来求解一下函数 $L$ 的表达式（可将结论推广到任意维）。令
$
\vec{i}\ =\ \left( \begin{array}{c}
	1\\
	0\\
\end{array} \right)
$，$\vec{j}\ =\ \left( \begin{array}{c}
	0\\
	1\\
\end{array} \right)$ 为 $R_2$ 的一组基。如果有任意线性变换 $L$ ，将它作用于任意向量 $
\vec{v}\ =\ \left( \begin{array}{c}
	x\\
	y\\
\end{array} \right)$，即 $L(\vec{v})$，可用基向量表示为 $\vec{v} = (x, y) = x\vec{i} + y\vec{j}$

由线性变换的性质
$$L(\vec{v})=L(x \vec{i}+y \vec{j})=L(x \vec{i})+L(y \vec{j})=x L(\vec{i})+y L(\vec{j})$$

我们来关注一下结论：
$$ L(\vec{v}) = x L(\vec{i})+y L(\vec{j}) \tag{1} $$

再进一步，我们定义两个新的基向量：$\vec{k} = L(\vec{i})$，$\vec{l} = L(\vec{j})$
接下来我们对 (1) 式进行变形
$$ L(\vec{v})=x \vec{k}+y \vec{l}=(\vec{k}, \vec{l})\left(\begin{array}{l}
x \\
y
\end{array}\right) \tag{2} $$
若令  $
\vec{k}\ =\ \left( \begin{array}{c}
	a\\
	c\\
\end{array} \right)
$，$
\vec{l}\ =\ \left( \begin{array}{c}
	b\\
	d\\
\end{array} \right)
$那么我们可以构造一个矩阵
$$ A_t=(\vec{k},\vec{l}) =\ \left(\begin{matrix}
a& b \\
c& d \\
\end{matrix}\right)
$$

对 (2) 式进一步计算
$$L(\vec{v})=x \vec{k}+y \vec{l}=(\vec{k}, \vec{l})\left(\begin{array}{l}
x \\
y
\end{array}\right)=\left(\begin{array}{ll}
a & b \\
c & d
\end{array}\right)\left(\begin{array}{l}
x \\
y
\end{array}\right)=A_{t}\left(\begin{array}{l}
x \\
y
\end{array}\right)=A_{t} \vec{v}$$

我们只需要关注一下结果
$$L(\vec{v}) = A_{t} \vec{v}$$

其中
$$
A_t=(\vec{k},\vec{l}) =\ \left(\begin{matrix}
a& b \\
c& d \\
\end{matrix}\right)
$$
也就是说线性变换即输入向量**左乘**一个矩阵，该矩阵是原基向量$
\vec{i}\ =\ \left( \begin{array}{c}
	1\\
	0\\
\end{array} \right)$，$\vec{j}\ =\ \left( \begin{array}{c}
	0\\
	1\\
\end{array} \right)$  进行线性变换后的基向量构成的：
$$
A_t=(\vec{k},\vec{l}) = (L(\vec{i}),L(\vec{j}))
$$

如果上面这段描述读起来有点懵逼，我们在几何上来看线性变换
## 几何意义
如图，对于蓝色的向量$\vec{v}\ =\ \left( \begin{array}{c}
	2\\
	3\\
\end{array} \right)$  ，它是由 2 个$\vec{i}\ =\ \left( \begin{array}{c}
	1\\
	0\\
\end{array} \right)$  和 3 个 $\vec{j}\ =\ \left( \begin{array}{c}
	0\\
	1\\
\end{array} \right)$ 加起来的即
$$\vec{v} = 2\vec{i} + 3\vec{j}$$
现在我们想要得到一个线性变换，使得任意输入向量顺时针旋转 60°，也就是对于任意输入向量，输出向量是它顺时针旋转 60°后的结果

我加了一个动画来看看这个线性变换作用于平面上所有向量（想象蓝色的向量就是任意一个向量）的效果：
<img src="https://pic2.zhimg.com/50/v2-662ef2ddb71de67048965ad538164fd1_hd.gif" data-caption="" data-size="normal" data-rawwidth="214" data-rawheight="190" data-thumbnail="https://pic2.zhimg.com/50/v2-662ef2ddb71de67048965ad538164fd1_hd.jpg" class="content_image" width="214"/>
线性变换后，蓝色的向量经过旋转变成了新的向量$\vec{u}$，红色的向量（基向量）经过线性变换变成了新向量$\vec{k}$，$\vec{j}$，而 $\vec{u} = 2\vec{k} + 3\vec{j}$ ，其旋转后的表达式仍然不变，也就是说我们有
$$L(\vec{v})=\vec{u}=2 \vec{k}+3 \vec{j}=(\vec{k}, \vec{j})\left(\begin{array}{l}
2 \\
3
\end{array}\right)=(\vec{k}, \vec{j}) \vec{v}=A_{t} \vec{v}$$

要找到线性变换的变换矩阵，就是看线性变换后的两个基向量跑到哪去了

所以**我们可以把矩阵看做是一个线性变换的表示，该矩阵的列就是原基向量线性变换后的表达式**

# 矩阵
## 基本定义
由$m \times n$个数$a_{ij}$ 排成的 $m$ 行 $n$ 列的数，简称 $m \times n$ 矩阵
记作：
$$\mathbf{A}=\left(\begin{array}{cccc}
a_{11} & a_{12} & \dots & a_{1 n} \\
a_{21} & a_{22} & \dots & a_{2 n} \\
a_{31} & a_{32} & \dots & a_{3 n} \\
\dots & \dots & \dots & \dots \\
a_{m 1} & a_{m 2} & \dots & a_{m n}

\end{array}\right)$$

这  $m \times n$ 个数称为矩阵$\mathbf{A}$的元素，简称为元

数 $a_{ij}$ 位于矩阵 $\mathbf{A}$ 的第$i$ 行第 $j$ 列，称为矩 $\mathbf{A}$ 的$(i,j)$元，以数为 $a_{ij}$ 元的矩阵可记为 $(a_{ij})$ 或  $(a_{ij}m \times n)$ ，$m \times n$矩阵$\mathbf{A}$ 也记作 $\mathbf{A_{mn}}$

若 $m = n$，则矩阵 $\mathbf{A}$ 又称为 $n$ 阶方阵，记作 $\mathbf{A_{n}}$

## 几何意义
矩阵的几何意义就是线性变换

对于任意矩阵 $\mathbf{A} =\ \left(\begin{matrix}
a& b \\
c& d \\
\end{matrix}\right)$ 可看做是一个线性变换，该线性变换将原基向量 $\vec{i} = \left(\begin{array}{l}
2 \\
3
\end{array}\right)$，$\vec{j} = \left(\begin{array}{l}
0 \\
1
\end{array}\right)$  在平面上变换成了新的一对基向量$\vec{k} = \left(\begin{array}{l}
a \\
c
\end{array}\right)$，$\vec{l} = \left(\begin{array}{l}
b \\
d
\end{array}\right)$

### 向量左乘矩阵的几何意义
**对该向量进行矩阵所表示的线性变换**

### 矩阵乘法的几何意义
**将多个线性变换复合成一个线性变换**

### 证明
若有矩阵 $\mathbf{A_1}$，$\mathbf{A_2}$ 和任意向量 $\vec{v}$ ，将向量进行 $\mathbf{A_1}$ 所表示的线性变换得到变换后的向量 $\vec{u} = \mathbf{A_1} \vec{v}$，再对 $\vec{u}$ 进行矩阵 $\mathbf{A_2}$ 所表示的线性变换，得到变换后的向量 $\vec{w} = \mathbf{A_2} \vec{u}$，所以有
$$
\vec{w} = \mathbf{A_2} \vec{u} = \mathbf{A_2}(\mathbf{A_1} \vec{v}) = (\mathbf{A_1} \mathbf{A_2})\vec{v} = \mathbf{A}\vec{v}
$$

其中 $\mathbf{A} = \mathbf{A_2} \mathbf{A_1}$，也就是对原向量 $\vec{v}$ 进行线性变换 $\mathbf{A}$ 的结果等同于先进行线性变换 $\mathbf{A_1}$ 再进行线性变换 $\mathbf{A_2}$

证明了矩阵乘法就是将多个线性变换 $\mathbf{A_1}$，$\mathbf{A_2}$  复合成一个线性变换 $\mathbf{A}$

## 矩阵的行列式（det）
### 基本定义
只有方阵才有行列式，记作 $det(\mathbf{A})$ 或 $|\mathbf{A}|$

若  $\mathbf{A} = \left( \begin{matrix}
a & b \\
c & d \\
\end{matrix} \right)$，$|\mathbf{A}| = \left| \begin{matrix}
a & b \\
c & d \\
\end{matrix} \right| = ad - bc$

### 几何意义
n 维空间中的物体进行**矩阵所表示的线性变换**后其**体积的缩放比例**

考虑二维平面下的线性变换比较直观，如图，原基向量 $\vec{i} = (1,0)$，$\vec{j} = (0, 1)$若将 $\vec{i}$，$\vec{j}$ 形成的平行四边形面积（二维空间的体积就是面积）记作 $\mathbf{S_{ij}}$，那么很明显在变换前这个平行四边形就是一个边长为 1 的正方形，有 $\mathbf{S_{ij}} = 1$
<img src="https://pic2.zhimg.com/50/v2-79c437f961b47cdb73d546e38ac1cd60_hd.jpg" data-caption="" data-size="normal" data-rawwidth="312" data-rawheight="268" data-default-watermark-src="https://pic1.zhimg.com/50/v2-d983f205ea618f45d4f1e9d84cae34af_hd.jpg" class="content_image" width="312"/>

若某线性变换将它们变成了 $\vec{i} = (2, 0)$，$\vec{j} = (3, 3)$ 也就是该线性变换的变换矩阵为 $\mathbf{A} = \left(
\begin{matrix}
  2 & 3\\
  0 & 3
\end{matrix} \right)$，此时平行四边形的面积根据底乘高为 $\mathbf{S^\prime_{ij}}$
![]([  ](https://pic3.zhimg.com/50/v2-5f3db15651ba38b5c502636532d3578b_hd.jpg))

那么矩阵 $\mathbf{A}$ 所表示的线性变换使得变换后的面积变为了原来的 $\dfrac{\mathbf{S^\prime_{ij}}} {\mathbf{S_{ij}}} = 6$ 倍，所以
$$
|\mathbf{A}| = \left|
\begin{matrix}
  2 & 3 \\
  0 & 3
\end{matrix}
\right|=6
$$
这就是行列式的几何意义

若行列式为 0，则表示该线性变换将会使 $n$ 维空间下的物体压缩到 $m(m<=n-1)$ 维空间下去，同时线性方程组 $\mathbf{A} \vec{x} = \vec{b}$ 无解，因为  $\mathbf{A}$ 是 $N$ 维方阵，$\vec{x}$是 $N$ 维列向量，而  $\mathbf{A}$ 所表示的线性变换会让 $\vec{x}$ 被压缩到更低纬度下去，即列向量 $\vec{b}$  的维度小于 $\vec{x}$ 的维度，所以你找不到这样的 $\vec{x}$ 能满足方程

## 矩阵的秩（rank）
### 基本定义
矩阵进行初等行变换后不全为 0 的行数，矩阵的秩记作 $R(A)$ 或 $Rank(A)$

### 几何意义
本质上就是 $n$ 维向量在进行该矩阵所表示的线性变换后变成 $rank(A)$ 维的向量

若矩阵满秩，则该矩阵的的线性变换不会使输入向量降维

## 线性空间（向量空间）
线性空间的定义满足以下条件的集合就是线性空间，而该集合里面的元素叫做“向量”。

如果 $R$ 表示所有实数的集合（ $R$ 里面每一个元素都是实数且 $R$包含了所有可能的实数），这时我们寻找一个集合 $V$ ，这个集合 $V$ 中的任意两个元素 $\alpha,\beta 
\in V$ 都能找到另一个元素 $\gamma \in V$ 能表示为这两个元素的和，记作 $\gamma = \alpha + \beta$；且对于任意实数 $\lambda \in R$，和任意元素 $\alpha \in V$ ，都能找到对应的元素 $\delta \in V$ 作为 $\lambda$ 和 $\alpha$ 之积，记作 $\delta = \lambda \alpha$ 
那么 $V$ 就称为数域 $R$上的线性空间

且这两个运算（和、积）须满足以下八条性质

对于任意的 $\alpha, \beta, \gamma \in V, \lambda, \mu \in R$
1. $\alpha+\beta=\beta+\alpha$
2. $(\alpha+\beta)+\gamma=\alpha+(\beta+\gamma)$
3. 在 V 中存在零元素 $\theta \in V,$ 有 $\alpha+\theta=\alpha$
4. 在 V 中存在 的负元素 $\delta,$ 使得 $\alpha+\delta=\theta$
5. $1 \alpha=\alpha$
6. $\lambda(\mu \alpha)=(\lambda \mu) \alpha$
7. $(\lambda+\mu) \alpha=\lambda \alpha+\mu \alpha$
8. $\lambda(\alpha+\beta)=\lambda \alpha+\lambda \beta$

本质：对任意的 $\alpha, \beta \in V, \lambda, \mu \in R$ 都有 $\lambda \alpha+\mu \beta \in V,$ 则集合 $V$ 是线性空间。

任何元素，自己定义出它们之间的加法和数乘，满足以上本质的，都可以叫做 "向量"

## 矩阵的核
设 $A_{m \times n}$ 是一个固定矩阵，则集合 $V=\left\{x \in R^{n} | A x=0\right\}$ 是线性空间

证明

任意 $x_{1}, x_{2} \in V, a, b \in R$
证明 $a x_{1}+b x_{2} \in V$，即$A\left(a x_{1}+b x_{2}\right)=0$

$$A\left(a x_{1}+b x_{2}\right)=A\left(a x_{1}\right)+A\left(b x_{2}\right)=a A x_{1}+b A x_{2}=a 0+b 0=0$$

所以 $a x_{1}+b x_{2} \in V$ 得证

我们称这样的 $V$ 称为矩阵 $A$ 的核（方程组 $A x=0$ 的解空间）

### 几何意义
一个向量的集合，集合中任意元素进行矩阵所表示的**线性变换**，都会被压缩成**零向量**，且集合中包含了所有满足该条件的向量

这个集合就是矩阵的核。

## 线性空间的基
### 线性表示
对于任意的 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}, \beta \in V$ 若存在一组实款 $k_{1}, k_{2}, \ldots, k_{n} \in R$ 满足
$k_{1} \alpha_{1}+k_{2} \alpha_{2}+\cdots+k_{n} \alpha_{n}=\beta,$ 则称 $\beta$ 可以由 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 维性表示

### 线性相关
对于任意的 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n} \in V$ 若存在一组不全为 0 的实数 $k_{1}, k_{2}, \ldots, k_{n} \in R$ 满足
$k_{1} \alpha_{1}+k_{2} \alpha_{2}+\cdots+k_{n} \alpha_{n}=\theta,$ 则 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 线性相关

线性相关 $\Leftrightarrow$ 至少存在一个向是可以被其余向是线性表示

> 任意 $n+1$个 $n$维向量一定线性相关

### 线性无关
对于任意的 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n} \in V$, 若满足 $k_{1} \alpha_{1}+k_{2} \alpha_{2}+\cdots+k_{n} \alpha_{n}=\theta$， 则必有
$k_{1}=k_{2}=\cdots=k_{n}=0$， 则 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 维性无关

例：证明向量 $\overrightarrow{x_{1}}=(3,4), \overrightarrow{x_{2}}=(1,0)$ 线性无关

证：设 $k_{1} \overrightarrow{x_{1}}+k_{2} \overrightarrow{x_{2}}=\theta$

我们有
$\left(3 k_{1}, 4 k_{1}\right)+\left(k_{2}, 0\right)=(0,0)$

因此
$\Rightarrow\left\{\begin{aligned} 3 k_{1}+k_{2} &=0 \\ 4 k_{1} &=0 \end{aligned} \Rightarrow\left\{\begin{array}{l}k_{1}=0 \\ k_{2}=0\end{array}\right.\right.$
得证

### 线性空间基的定义

在线性空间 $V$ 中，如果存在 n 个元素 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 满足：
1. $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 线性无关
2. $V$ 中任一元素 $\alpha$ 都可以由 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 线性表示

那么， $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 称为线性空间 $\mathbf{V}$ 的一个基，  $n$（基的个数）称为线性空间 $\mathbf{V}$ 的维数

空间 $\mathbf{V}$ 称为由基 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 张成的线性空间，记作 $\mathbf{V} = span\{\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}\}$

### 性质
$\mathbf{V} = \{x|x=c_{1} \alpha_{1}+c_{2} \alpha_{2}+\cdots+c_{n} \alpha_{n}\}$，其中 $c_i$为任意的实数， $i = 1,2,\ldots,n$

例：
方程组 $Ax = 0$ 的基础解系 $x_{i}(i=1, \ldots n-r)$ 为其解空间的一组基
方程的解：$x=c_{1} x_{1}+c_{2} x_{2}+\cdots+c_{n-r} x_{n-r}$ 其中 $c_{i}$ 为任意实数

### 坐标
若 $\mathbf{V}$ 是一个线性空间， $\alpha_{1}, \alpha_{2}, \ldots \alpha_{n}$ 是线性空间的一组基

对于 $\alpha \in \mathbf{V}$, 如果有 $\alpha=x_{1} \alpha_{1}+x_{2} \alpha_{2}+\cdots+x_{n} \alpha_{n}$， 那么其表示系数所构成的 $n$ 维实向量（$x_{1}, x_{2}, \ldots, x_{n}$ ）称为 $\alpha$ 在基 $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ 下的坐标

所以，线性空间的元素称为向量

例：
二维实向量空间 $R^{2}=\{(x, y) | x, y \in R\}$ 是一个线性空间，向量组$\{(1,0),(0,1)\}, \{(1,0),(1,1)\}$ 分别都是 $R^{2}$ 的一组基

向量 $(5,3)$ 可以表 示成 $(5,3)=5(1,0)+3(0,1)$ 或者 $(5,3)=2(1,0)+3(1,1)$

那么 $(5,3)$ 在基 $\{(1,0),(0,1)\}$ 下的坐标是 $(5,3)$ 在基 $\{(1,0),(1,1)\}$ 下的坐标是 $(2,3)$

### 坐标转换
对于二维实向量空间的一对基 $A=\left\{\left(\begin{array}{l}1 \\ 0\end{array}\right),\left(\begin{array}{l}0 \\ 1\end{array}\right)\right\}$，和另一组基$B=\left\{\left(\begin{array}{l}a \\ b\end{array}\right),\left(\begin{array}{l}c \\ d\end{array}\right)\right\}$

它们的坐标之间转换
- 若 $\vec{v}$在 $\mathbf{A}$ 下的坐标为 $(x, y)$，那么 $\mathbf{B}$的坐标是：？？？
- 若 $\vec{v}$在 $\mathbf{B}$ 下的坐标为 $(x, y)$，那么 $\mathbf{A}$的坐标是：？？？

从线性变换的角度来看就相当好理解了：我们可以把坐标的转换看做一个线性变换

若有一线性变换矩阵 $\mathbf{T} = \left( \begin{matrix}
  a & c \\
  b & d
\end{matrix}  \right)$ ，基 $A$ 下的一向量施加该线性变换后变为了

$$\vec{u}=T \vec{v}=\left(\begin{array}{ll}
a & c \\
b & d
\end{array}\right) \vec{v}=x\left(\begin{array}{l}
a \\
b
\end{array}\right)+y\left(\begin{array}{l}
c \\
d
\end{array}\right)$$
这个向量就是基 $B$ 下的坐标为 $(x,y)$ 的向量

这里看起来似乎就是：基 $A$ 的向量要转换为基 $B$ 下的坐标，只要乘以基 $B$ 的基所构成的线性变换矩阵即可

但这就搞反了。基 $A$ 下的向量 $\vec{v} = \left(\begin{array}{l} x \\ y \end{array} \right)$ 乘以线性变换矩阵得到的结果仍然是基 $A$ 下的坐标，只是向量确实变成了基 $B$ 下的向量 $\vec{u} = \left(\begin{array}{l} x \\ y \end{array} \right)$ ，所以这个线性变换应该理解为：基 $A$ 下的坐标对基 $B$ 下的同一坐标误解的修正。看起来有点抽象

具体来讲的话就是，基 $B$ 下的坐标 $(x,y)$，实际上指的是向量 $\vec{u} = x \left( \begin{array}{l}
    a \\
    b
\end{array} \right) +  y \left( \begin{array}{l}
    c \\
    d
\end{array} \right)$ ，在基 $A$ 下同一个向量指的是  $\vec{u}=T \vec{v}=\left(\begin{array}{ll} a & c \\ b & d \end{array}\right) \vec{v}$，这个向量是基 $A$ 下的 $(x,y)$ 进行线性变换后的结果，即要求基 $B$ 的坐标在基 $A$ 下的表示，只需要让基 $A$ 下的同一坐标左乘线性变换矩阵即可

所以线性变换指的是基 $B$ 到基 $A$ 的转换而不是基 $A$ 到基 $B$ 的转换。

结论：
若在基 $B=\left\{\left(\begin{array}{l}a \\ b\end{array}\right),\left(\begin{array}{c}c \\ d\end{array}\right)\right\}$ 下一向量的坐标为 $\left(\begin{array}{l}x \\ y\end{array}\right),$ 则它在基
$A=\left\{\left(\begin{array}{l}1 \\ 0\end{array}\right),\left(\begin{array}{l}0 \\ 1\end{array}\right)\right\}$ 下的坐标为

$$\left(\begin{array}{ll}
a & c \\ 
b & d\end{array}\right)
\left(\begin{array}{l}
x \\
y
\end{array}\right)
$$

既然$B$->$A$是坐标左乘线性变换矩阵, 那么$A$->$B$就很容易推出是左乘线性变换矩阵的逆

若在基 $A=\left\{\left(\begin{array}{l}1 \\ 0\end{array}\right),\left(\begin{array}{l}0 \\ 1\end{array}\right)\right\}$ 下一向量的坐标为 $\left(\begin{array}{l}x \\ y\end{array}\right),$ 则它在基
$B=\left\{\left(\begin{array}{l}a \\ b\end{array}\right),\left(\begin{array}{l}c \\ d\end{array}\right)\right\}$ 下的坐标为:
$$\left(\begin{array}{ll}
a & c \\
b & d
\end{array}\right)^{-1}
\left(\begin{array}{l
}x \\
y\end{array}\right)
$$

### 线性变换在不同基下的表示
上面探讨了向量坐标在不同基下的表示，接下来看看不同坐标下的线性变换有什么不一样

若在基 $A$ 中有一线性变换 $L$，这里 $L$ 是一个矩阵，那么这个 $$L 在基 $B$ 下的表达式是什么？

首先考虑基 $B$ 中一向量 $\vec{v}$ ，先将它转换为基 $A$ 下的坐标，若坐标转换矩阵（即基 $B$ 的一对基组合成的矩阵）为 $P$，则基 $B$->基 $A$ 的转换，得到基 $A$ 下的同一向量的坐标为：$P\vec{v}$

然后进行基 $A$ 的线性变换 $L$，得到线性变换后的向量：$LP\vec{v}$

这是基 $A$ 下的向量，最后将该线性变换后的基 $A$ 下的向量再转换回基 $B$：$P^{-1}LP \vec{v}$

所以基 $A$ 下一线性变换 $L$ 在基 $B$ 下对应的线性变换为：$L^{'} = P^{-1}LP$

即基 $B$ 下向量要做一个和基 $A$ 下的线性变换 $L$ 效果一样（比如都是旋转 90°）的线性变换，则只需让基 $B$ 下的坐标左乘 $L^{'} = P^{-1}LP$ 即可

## 矩阵分解
### 特征向量和特征值
基本定义
设 $A_{m \times n}$ , 如果有数 $i$ 和 $n$ 维非零列向量 $\vec{x}$，使 $Ax = \lambda_ix\left( i = 1,2,\ldots, n\right)$ ，则称 $\lambda_i$ 为矩阵 $A$ 的特征值, 非零列向量 $x$ 为矩阵 $A$ 的对应于特征值 $i$ 的特征向量
注：
- $A$ 是方阵
- 特征向量 $x$ 是非零列向量
- 属于每一个特征值 $\lambda_i$ 的特征向量不唯一，有无数个
- 一个特征向量只能属于一个特征值

特征值
$\lambda_i$ 是关于 $\lambda$ 的多项式 $\left| A-\lambda I_n \right|=0$ 的根，记作 $\lambda_1,\lambda_2,\ldots, \lambda_n$

特征向量
属于 $\lambda_i$ 的特征向量是线性方程组 $\left( A-\lambda_i I_n \right)x = 0$ 的解

### 特征向量和特征值的几何意义
从线性变换的角度来看，特征值和特征向量非常好理解。根据特征方程：
$$Ax = \lambda_ix\left( i = 1,2,\ldots, n\right)$$

把 $A$ 看做一个线性变换，该线性变换的效果和向量数乘一样，说明该线性变换：**会让某些向量保持原有的方向不变，仅在原来的方向上进行了拉伸。这些向量就是特征向量，拉伸的倍数就是特征值**

所以一个矩阵的特征向量就是以这个矩阵为线性变换后，那些只在原来方向上进行了拉伸

由于在一个方向上的向量有无数多个，所以每一个特征值对应的特征向量有无数多个，而一个特征向量仅对应一个特征值

### 特征方程的由来
特征方程 $\left| A-\lambda I_n \right|=0$ 用来求解特征值和特征向量，那么这个是怎么来的呢？

由特征向量的几何意义：
$$Ax = \lambda x \Longrightarrow Ax - \lambda x = 0\Longrightarrow Ax-I\lambda x = 0 \Longrightarrow \left( A-\lambda I\right)x = 0$$

因为 $A-\lambda I$ 的结果是一个矩阵，看做线性变换的话，该矩阵使得向量 $x$ 压缩成了一个数 0

根据行列式的几何意义，只有当矩阵的行列式为 0 的时候，线性变换才会压缩向量的维度（这里被压缩成了 0 维），所以得到 $\left| A-\lambda I_n \right|=0$

### 矩阵分解的基本定义
设 $\left\{x_{i 1}, x_{i 2}, \ldots, x_{i m}\right\}$ 是方程组 $\left(A-\lambda_{i} I_{n}\right) x=0$ 解空间的基, 定义矩阵 $P_{n \times n}=\left[x_{11}, x_{12}, \ldots, x_{1 m}, x_{21}, x_{22}, \ldots\right]$ 那么, 我们可以把方阵A分解成
$$P^{-1} A P=
\left(\begin{array}{cccc}
\lambda_{1} & 0 & \dots & 0 \\
0 & \lambda_{2} & \dots & 0 \\
\dots & \dots & \dots & 0 \\
0 & \dots & 0 & \lambda_{n}
\end{array}\right)$$

$$
A=
P\left(\begin{array}{cccc}
\lambda_{1} & 0 & \dots & 0 \\
0 & \lambda_{2} & \dots & 0 \\
\dots & \dots & \dots & 0 \\
0 & \dots & 0 & \lambda_{n}
\end{array}\right) P^{-1}
$$
我们称这样的分解为特征分解(相似对角化)

### 几何意义
同样按线性变换的角度来看

在之前提到了同一个线性变换在不同基下的表示，把问题先简化到二维的情况，得出结论再推广到高维

对于一个 $2 \times 2$ 矩阵 $A$，如果我们知道它的两个线性无关的特征向量为 $\vec{v_1} = \left( \begin{array}{l}  x_1 \\ y_1 \end{array}\right) \vec{v_2} \left( \begin{array}{l}  x_2 \\ y_2 \end{array}\right)$ ，我们把这一对特征向量看做是新的一对基，称为特征基。其构成一个新的 2x2 矩阵  
$$P = \left( \begin{matrix}
    x_1 & x_2 \\
    y_1 & y_2
\end{matrix}\right)$$

那么如果把矩阵 $A$ 看做一个线性变换，无论它是怎样的一个变换效果，其对于它的两个线性无关的特征向量仅仅是一个拉伸效果而已（根据特征向量的定义 $Ax = \lambda x$ ），所以如果我们把其中一对线性无关的特征向量作为新的基向量（特征基），那么在该新的基下，由于原线性变换的效果仅仅是对这对特征基进行了拉伸，那么用特征基表示的所有向量在进行线性变换时也就是拉伸了而已，所以这个线性变换用矩阵来表示一定是一个对角矩阵！

根据上一章的不同基下的线性变换的表示，矩阵 A 在其特征基下 的线性变换表示为：
$$
A^{\prime}=P^{-1} A P=
\left(\begin{array}{ll}
x_{1} & x_{2} \\
y_{1} & y_{2}
\end{array}\right)^{-1} A
\left(\begin{array}{ll}
x_{1} & x_{2} \\
y_{1} & y_{2}
\end{array}\right)
$$
该矩阵必然是对角的才能保证其线性变换的效果仅仅是一个拉伸效果，且拉伸的倍数就是这对特征基对应的特征值，所以有
$$
A^{\prime}=P^{-1} A P=\left(\begin{array}{cc}
\lambda_{1} & 0 \\
0 & \lambda_{2}
\end{array}\right)
$$
这就是相似对角化的几何意义

当然如果一个矩阵找不到两个线性无关的特征向量, 那么该矩阵无 法进行相似对角化


### 正交矩阵
满足 $A A^{T}=I_{n}\left(A^{-1}=A^{T}\right)$ 的n阶方阵称为正交矩此
### 标淮正交基
n个n维向量 $x_{1}, x_{2}, \ldots, x_{n} \in R^{n}$ 若满足如下性质
$$
\left\{\begin{array}{ll}
x_{i} x_{j}=1 & \text { 当 } i=j \text { 时 } \\
x_{i} x_{j}=0 & \text { 当 } i \neq j \text { 时 }
\end{array}\right.
$$
则称 $x_{1}, x_{2}, \ldots, x_{n} \in R^{n}$ 为一组标准正交基

说白了，标准正交基就是$n$维向量空间中的一組 ($n$个) 旦相垂直且长度为一的向量, 这些向量 (列向量) 排起来构成一个$n \times n$的方阵就是正交矩阵

例:
$\{(1,0,0),(0,1,0),(0,0,1)\}$ 为三维向量空间 $R^{3}$ 的一组标准正交基

性质: 若 $A=\left[x_{1}, x_{2}, \ldots, x_{n}\right]$ 为n阶正交矩阵 $\Leftrightarrow\left\{x_{1}, x_{2}, \ldots, x_{n} \in R^{n}\right\}$

### 正交矩阵的几何意义

正交矩阵所表示的线性变换就是一个旋转变换!

旋转短阵 $A=\left(\begin{array}{cc}\cos \theta & -\sin \theta \\ \sin \theta & \cos \theta\end{array}\right)$ 就是一个正交矩阵(计算机图形学里的旋转矩阵)，它的两个列向量 $\left(\begin{array}{c}\cos \theta \\ \sin \theta\end{array}\right)$ 和 $\left(\begin{array}{c}-\sin \theta \\ \cos \theta\end{array}\right)$ 就是一对标准正交基

根据线性变换的性质，由于 $\left(\begin{array}{c}1 \\ 0\end{array}\right)$ 和 $\left(\begin{array}{l}0 \\ 1\end{array}\right)$ 是一对已知的标准正交基, 把它们同时旋转任意角度 $\theta$也能满足互相垂直且长度为一的条件，所以它们旋转后的新基组成的矩阵就是旋转 知阵 $A=\left(\begin{array}{cc}\cos \theta & -\sin \theta \\ \sin \theta & \cos \theta\end{array}\right),$ 是一个正交矩阵

正交矩阵的性质
1. 若$A$是正交短阵, $\left\{x_{1}, x_{2}, \ldots, x_{n} \in R^{n}\right\}$ 是一组标准正交基, 那么 $\left\{A x_{1}, A x_{2}, \ldots, A x_{n} \in R^{n}\right\}$ 也是一组标准正交基
    > 用几何意义来理解, 把 $A$ 看做旋转变换就很好理解了，任意的标准正交基一起旋转后还是标准正交基
2. 对直角坐标系做旋转变换, 新旧坐标之间关系是一个正交变换，即存在一个正交矩阵$A$，使得原来坐标的点 $x=x_{1}, x_{2}, \ldots, x_{n}$ 在新的坐标系下的坐标为 $y=A x \quad$ 
    > 这个就是几何意义的体现
3. 正交变换保持内积、长度、距离不变, 即任意的n维向量 $x, y \in R^{n}$,有
    - 内积不变 $(x, y)=(A x, A y)$
    - 长度不变 $\|x\|_{2}=\|A x\|_{2}$ （取 $y=x$ ）
    - 距离不变 $\|x-y\|_{2}=\|A x-A y\|_{2}$ （取 $x=x-y$）


## 变换矩阵

### 标准形式
|       | Rot Rgt | Rot up | Rot Fwd | Translation |
| :---: | :-----: | :----: | :-----: | :---------: |
|   x   |    1    |   0    |    0    |      0      |
|   y   |    0    |   1    |    0    |      0      |
|   z   |    0    |   0    |    1    |      0      |
|   w   |    0    |   0    |    0    |      1      |

### 缩放矩阵
![]()
若物体的原坐标为$(x, y)$，经过缩放操作后记为$x^{\prime},y^{\prime}$，也就是：
$$\begin{aligned}
&x^{\prime}=s x\\
&y^{\prime}=s y
\end{aligned}$$
可记为
$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
s & 0 \\
0 & s
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]$$

### 镜像矩阵
水平镜像：
$$\begin{aligned}
&x^{\prime}=-x\\
&y^{\prime}=y
\end{aligned}$$
也就是：
$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{cc}
-1 & 0 \\
0 & 1
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]$$

###　斜切矩阵
![]()
- 垂直位移永远是 0
- 水平位移
    - $y(0) = 0$
    - $y(a) = 1$
$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
1 & a \\
0 & 1
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]$$

### 旋转矩阵
![]()
> 默认是围绕原点旋转
> 默认是逆时针旋转

![](https://gitee.com/freedom_man/FigureBed/raw/master/251933285905256.jpg)
$$\mathbf{R}_{\theta}=\left[\begin{array}{cc}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{array}\right] \tag{2.1}$$

**推导过程**
$$\begin{aligned}
x^{\prime}
&=r * \cos (\alpha+\beta) \\
&=r * \cos (\beta) * \cos (\alpha)-r * \sin (\beta) * \sin (\alpha) \\
&=x * \cos (\alpha)-y * \sin (\alpha)
\end{aligned}$$

$$\begin{aligned}
y^{\prime} &=r * \sin (\alpha+\beta) \\
&=r * \cos (\beta) * \sin (\alpha)+r * \sin (\beta) * \cos (\alpha) \\
&=x * \sin (\alpha)+y * \cos (\alpha)
\end{aligned}$$
从而可得 $2.1$
**共同点：**
$$
\begin{aligned}
&x^{\prime}=a x+b y\\
&y^{\prime}=c x+d y
\end{aligned}
$$
转换为矩阵形式可写为：
$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
a & b \\
c & d
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]$$

也就是：
$$\mathbf{x}^{\prime}=\mathbf{M} \mathbf{x}$$

### 位移矩阵
![]()
$$\begin{aligned}
&x^{\prime}=x+t_{x}\\
&y^{\prime}=y+t_{y}
\end{aligned}$$

因为这种形式无法被一般的二维矩阵乘法所代表

所以，只能采用如下的形式

$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
a & b \\
c & d
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]+\left[\begin{array}{l}
t_{x} \\
t_{y}
\end{array}\right]$$

因此可知，平移变换并不是线性变换，从而平移变换成了一个无法用线性变换解释的一个特例

但若将二维向量增加一个维度变成三维向量

对于任意的
- $2D point = (x, y, 1)^{\top}$
- $2D vector = (x, y, 0)^{\top}$

因此，位移矩阵可变为

$$\left(\begin{array}{l}
x^{\prime} \\
y^{\prime} \\
w^{\prime}
\end{array}\right)=\left(\begin{array}{lll}
1 & 0 & t_{x} \\
0 & 1 & t_{y} \\
0 & 0 & 1
\end{array}\right) \cdot\left(\begin{array}{l}
x \\
y \\
1
\end{array}\right)=\left(\begin{array}{c}
x+t_{x} \\
y+t_{y} \\
1
\end{array}\right)$$

他变成了一个齐次坐标 (n 维的向量用一个 n+1 维向量来表示）

至于 2 维的点用 1 表示，2 维的向量用 0 表示可以做如下理解
- **vector + vector = vector**
- **vector + point = point**（含义：一个点，沿着向量移动，任然是一个点）
- **point - point = vector**

- **point + point =？？**
这个公式，其含义如下：
$$\left(\begin{array}{l}
x \\
y \\
1
\end{array}\right)+\left(\begin{array}{l}
x \\
y \\
z
\end{array}\right)=\left(\begin{array}{l}
2 x \\
2 y \\
2
\end{array}\right)=\left(\begin{array}{c}
\dfrac{2 x}{2} \\
\dfrac{2 y}{2} \\
1
\end{array}\right)$$

也就是：

$$\left(\begin{array}{l}
x \\
y \\
w
\end{array}\right) \text { is the } 2 \mathrm{D} \text { point }\left(\begin{array}{c}
x / w \\
y / w \\
1
\end{array}\right), w \neq 0$$

### 仿射变换
仿射映射 = 线性映射 + 位移
$$\left[\begin{array}{l}
x^{\prime} \\
y^{\prime}
\end{array}\right]=\left[\begin{array}{ll}
a & b \\
c & d
\end{array}\right]\left[\begin{array}{l}
x \\
y
\end{array}\right]+\left[\begin{array}{l}
t_{x} \\
t_{y}
\end{array}\right]$$

对于其次坐标来说

$$\left(\begin{array}{l}
x^{\prime} \\
y^{\prime} \\
w^{\prime}
\end{array}\right)=\left(\begin{array}{lll}
1 & 0 & t_{x} \\
0 & 1 & t_{y} \\
0 & 0 & 1
\end{array}\right) \cdot\left(\begin{array}{l}
x \\
y \\
1
\end{array}\right)=\left(\begin{array}{c}
x+t_{x} \\
y+t_{y} \\
1
\end{array}\right)$$

#### 缩放
$$\mathbf{S}\left(s_{x}, s_{y}\right)=\left(\begin{array}{ccc}
s_{x} & 0 & 0 \\
0 & s_{y} & 0 \\
0 & 0 & 1
\end{array}\right)$$

#### 旋转
$$\mathbf{R}(\alpha)=\left(\begin{array}{ccc}
\cos \alpha & -\sin \alpha & 0 \\
\sin \alpha & \cos \alpha & 0 \\
0 & 0 & 1
\end{array}\right)$$

#### 平移
$$\mathbf{T}\left(t_{x}, t_{y}\right)=\left(\begin{array}{ccc}
1 & 0 & t_{x} \\
0 & 1 & t_{y} \\
0 & 0 & 1
\end{array}\right)$$

### 逆变换
![]()

### 组合变换

$$T_{(1,0)} \cdot R_{45}\left[\begin{array}{l}
x \\
y \\
1
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 1 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]\left[\begin{array}{ccc}
\cos 45^{\circ} & -\sin 45^{\circ} & 0 \\
\sin 45^{\circ} & \cos 45^{\circ} & 0 \\
0 & 0 & 1
\end{array}\right]\left[\begin{array}{l}
x \\
y \\
1
\end{array}\right]$$

也就是
$$A_{n}\left(\ldots A_{2}\left(A_{1}(\mathbf{x})\right)\right)=\mathbf{A}_{n} \cdots \mathbf{A}_{2} \cdot \mathbf{A}_{1} \cdot\left(\begin{array}{l}x \\ y \\ 1\end{array}\right)$$

$$<----------------$$
预乘以 n 个矩阵以获得物体的变换矩阵
> 注意：矩阵是左乘

### 3D 变换矩阵
齐次坐标情况下
- $3D point = (x,y,z,1)^{\top}$
- $3D vector = (x,y,z,0)^{\top}$

$4*4$ 矩阵的仿射变换
$$
\left(\begin{array}{l}x^{\prime} \\ y^{\prime} \\ z^{\prime} \\ 1\end{array}\right)=\left(\begin{array}{llll}a & b & c & t_{x} \\ d & e & f & t_{y} \\ g & h & i & t_{z} \\ 0 & 0 & 0 & 1\end{array}\right) \cdot\left(\begin{array}{l}x \\ y \\ z \\ 1\end{array}\right)
$$

- $t_x$，$t_y$，$t_z$表示平移变换

#### 缩放
$$\mathbf{S}\left(s_{x}, s_{y}, s_{z}\right)=\left(\begin{array}{cccc}s_{x} & 0 & 0 & 0 \\ 0 & s_{y} & 0 & 0 \\ 0 & 0 & s_{z} & 0 \\ 0 & 0 & 0 & 1\end{array}\right)$$

#### 平移
$$\mathbf{T}\left(t_{x}, t_{y}, t_{z}\right)=\left(\begin{array}{cccc}1 & 0 & 0 & t_{x} \\ 0 & 1 & 0 & t_{y} \\ 0 & 0 & 1 & t_{z} \\ 0 & 0 & 0 & 1\end{array}\right)$$

#### 旋转
##### 绕 $x$ 轴旋转
$$\mathbf{R}_{x}(\alpha)=\left(\begin{array}{cccc}
1 & 0 & 0 & 0 \\
0 & \cos \alpha & -\sin \alpha & 0 \\
0 & \sin \alpha & \cos \alpha & 0 \\
0 & 0 & 0 & 1
\end{array}\right)$$

##### 绕 $y$ 轴旋转
$$\mathbf{R}_{y}(\alpha)=\left(\begin{array}{cccc}
\cos \alpha & 0 & \sin \alpha & 0 \\
0 & 1 & 0 & 0 \\
-\sin \alpha & 0 & \cos \alpha & 0 \\
0 & 0 & 0 & 1
\end{array}\right)$$

##### 绕 $z$ 轴旋转
$$\mathbf{R}_{z}(\alpha)=\left(\begin{array}{cccc}
\cos \alpha & -\sin \alpha & 0 & 0 \\
\sin \alpha & \cos \alpha & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1
\end{array}\right)$$

##### 绕着  $n$ 轴旋转 $\alpha$ 度（罗德里格斯旋转公式）

$$ \mathbf{R}(\mathbf{n}, \alpha)=\cos (\alpha) \mathbf{I}+(1-\cos (\alpha)) \mathbf{n} \mathbf{n}^{T}+\sin (\alpha) \underbrace{\left(\begin{array}{ccc}
0 & -n_{z} & n_{y} \\
n_{z} & 0 & -n_{x} \\
-n_{y} & n_{x} & 0
\end{array}\right)}_{\mathbf{N}} $$

###### 罗德里格斯旋转矩阵 推导

[x]TODO























































# 参考
- https://www.zhihu.com/question/21082351
