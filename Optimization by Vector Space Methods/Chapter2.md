## Functional Analysis Note 02 | 与向量空间相关的定义与例子


### 1. Vector Spaces
#### 1.1. Definition
A **Vector Space X** is **a set of elements called vectors, together with two operations**.   
**向量空间 X** 是**一组称为向量的元素集合，并包含两种运算**。
- The **first operation is addition**, which *associates with any two vectors $x, y \in X$ a vector $x + y \in X$*, the sum of $x$ and $y$.   
**第一种运算是加法**，它*将任意两个向量 $x, y \in X$ 关联为向量 $x + y \in X$*，即 $x$ 和 $y$ 的和。
- The **second operation is scalar multiplication**, which *associates with any vector $x \in X$ and any scalar $\alpha$ a vector $\alpha x \in X$*; the scalar multiple of $x$ by $\alpha$.     
**第二种运算是标量乘法**，它*将任意向量 $x \in X$ 和任意标量 $\alpha$ 关联为向量 $\alpha x \in X$* ；即 $x$ 乘以标量 $\alpha$ 的结果。
- The set $X$ and the operations of addition and scalar multiplication are **assumed to satisfy the following axioms**:  
集合 $X$ 以及加法和标量乘法的运算**满足以下公理**：  
  1. *$x+y=y+x$* (commutative law)  
  2. *$(x+y)+z = x+(y+z)$* (associative law)
  3. There is a *Null Vector $\theta$* such that *$x+\theta = x$* for ALL $x$ in X
  4. *$\alpha(x+y) = \alpha x+\alpha y$* (distributive law)
  5. *$(\alpha+\beta)x=\alpha x+\beta x$* (distributive law)
  6. *$(\alpha \beta)x = \alpha(\beta x)$* (associative law)
  7. *$0x=\theta$*, *$1x = x$*
  8. *$x + (-x) =1x + (-1)x=(1-1)x = 0x = \theta$*




#### 1.2. Example: One-Dimensional Real Line $\mathbb{R}^1$
Perhaps the **simplest example of a vector space** is **the set of real numbers**.   
可能**最简单的向量空间**示例是**实数集**。
- It is a **real vector space with addition defined in the usual way and multiplication by (real) scalars defined as ordinary multiplication**. The **null vector** is the **real number zero**.   
它是一个**实向量空间，加法按通常方式定义，而乘以（实数）标量则定义为普通乘法**。**零向量**是**实数零**。
- The properties of *ordinary addition and multiplication of real numbers satisfy the axioms* in the definition of a vector space.   
实数的*普通加法和乘法*的性质*满足*向量空间定义中的*公理*。
- This vector space is called the **one-dimensional real coordinate space** or simply the **real line**. It is denoted by $R^1$ or simply R.  
这个向量空间被称为**一维实坐标空间**或简称为**实数线**。它表示为 $R^1$ 或简称 R。
#### 1.3. Example: N-Dimensional Real Coordinate Space $\mathbb{R}^n$
An **extension of 1-dimensional real line** is to **n-dimensional real coordinate space**. Vectors in the space *consist of sequences (n-tuples) of n real numbers* so that a typical vector has the form *$x = (x_1, x_2, \ldots, x_n)$*. The *null
vector* is defined as *$\theta = (0, 0, \ldots ,0)$*.

**1维实数线的一个扩展**是到**n维实坐标空间**。这个空间中的向量由*n个实数的序列（n元组）组成*，因此一个典型的向量具有形式 *$x = (x_1, x_2, \ldots, x_n)$*。 *零向量*被定义为*$\theta = (0, 0, \ldots ,0)$*
- If $x = (x_1, x_2, \ldots, x_n)$ and $y = (y_1, y_2, \ldots, y_n)$, the vector *$x + y$ is defined as the n-tuple whose k-th component is $x_k + y_k$*.   
如果 $x = (x_1, x_2, \ldots, x_n)$ 且 $y = (y_1, y_2, \ldots, y_n)$，则*向量 $x + y $ 定义为第 k 个分量是 $x_k + y_k$ 的 n 元组*。
- The vector *$\alpha x$*, where $\alpha$ is a (real) scalar, *is the n-tuple whose k-th component is $\alpha x_k$*.    
其中 $\alpha$ 是一个（实数）标量的*向量 $\alpha x$，是第 k 个分量是 $\alpha x_k$ 的 n 元组*。
- The axioms in the definition are verified by checking for equality among components.   
通过检查分量之间的相等性，定义中的公理被验证。
  - e.g. $x_k+0=x_k$ implies $x+\theta=x$

#### 1.4. Example: Space of ALL Infinite Real Sequences
Several Vector Spaces can be **constructed with vectors consisting of infinite sequences of real numbers**, so that a typical vector has the form:  
一些向量空间可以**由无限实数序列组成的向量构造**，因此一个典型的向量具有形式:
$$x=(x_1, x_2, \ldots, x_k, \ldots) = \{x_k\}_{k=1}^{\infty}$$
- The **collection of all infinite sequences of real numbers** forms a *vector space*,  addition and multiplication are defined componentwise as in $\mathbb{R}^n$.  
**所有无限实数序列的集合**构成了一个*向量空间*，加法和乘法和在 $\mathbb{R}^n$ 一样按分量被定义的。

**A sequence $\{x_k\}$ is said to be bounded** if there is a constant $M$ such that *$|x_k| < M$ for all $k$*.   
如果*存在一个常数 $M$ 使得对于所有的 $k$ 都有 $|x_k| < M$* ，则**序列 $\{x_k\}$ 被称为有界的**。
- The **collection of all bounded infinite sequences** forms a *vector space*    
**所有有界无限序列的集合**构成了一个*向量空间*，
  - since the *sum of two bounded sequences* or the *scalar multiple of a bounded sequence* is again *bounded*.   
因为*两个有界序列的和*或*一个有界序列的标量倍数*仍然是*有界的*。

The **collection of infinite sequences of real numbers which converge to zero** is a *vector space*,  
**收敛于零的实数无限序列的集合**是一个*向量空间*，
- since the *sum of two sequences converging to zero* or the *scalar multiple of a sequence converging to zero* also *converges to zero*.  
因为*两个收敛于零的序列之和*或*一个收敛于零的序列的标量倍数*也*收敛于零*。

#### 1.5. Example. Space of Continuous Functions on [a,b]
Consider *the interval $[a, b]$ on the real line*.   
考虑*实数线上的区间 $[a, b]$*

- Write *$x = y$ if $x(t) = y(t)$ for all $t \in [a, b]$*. The null vector $\theta$ is the function identically zero on $[a, b]$.   
如果 *对于所有的 $t \in [a, b]$，都有 $x(t) = y(t)$，则写作 $x = y$。* 零向量 $\theta$ 是在 $[a, b]$ 上恒为零的函数。
- If $x$ and $y$ are vectors in the space and $\alpha$ is a (real) scalar, write *$(x + y)(t) = x(t) + y(t)$* and *$(\alpha x)(t) = \alpha x(t)$*     
如果 $x$ 和 $y$ 是空间中的向量，且 $\alpha$ 是一个（实数）标量，写作 *$(x + y)(t) = x(t) + y(t)$* 和 *$(\alpha x)(t) = \alpha x(t)$* 
- The **collection of all real-valued continuous functions on this interval [a,b]** forms a *vector space*.   
该**区间上所有实值连续函数的集合** 构成一个*向量空间*。

The **collection of all polynomial functions defined on the interval $[a, b]$ with complex coefficients** forms a *complex vector space*.  
**定义在区间 $[a, b]$ 上并且具有复数系数的所有多项式函数的集合**构成一个*复向量空间*。
- The *sum of two polynomials*and *the scalar multiple of a polynomial* are themselves *polynomials*.  
*两个多项式的和*以及*多项式的标量乘积*本身也是*多项式*。

#### 1.6. Cartesian Product of Vector Spaces

Let *$X$ and $Y$ be vector spaces over the same field of scalars*. Then *the Cartesian product of $X$ and $Y$*, denoted *$X \times Y$*, consists of *the collection of ordered pairs $(x, y)$ with $x \in X$, $y \in Y$*.  
设 *$X$ 和 $Y$ 是在相同标量域上的向量空间*。那么 *$X$ 和 $Y$ 的笛卡尔积*，记为 *$X \times Y$* ，包含 *有序对 $(x, y)$ 的集合，其中 $x \in X$, $y \in Y$*
- Addition and scalar multiplication are defined on $X \times Y$ by   
在 $X \times Y$ 上定义加法和标量乘法：  
$$(x_1,y_1) + (x_2,y_2) = (x_1+x_2, y_1+y_2)$$   
$$\alpha (x, y) = (\alpha x, \alpha y)$$ 



### 2. Subspaces
#### 2.1. Definition
A *nonempty subset M* of a *Vector Space X* is called a **subspace of X** if **every vector of the form $\alpha x + \beta y$ is in M whenever x and y are both in M**.  
如果*向量空间 X* 中的*非空子集 M* 中**包含所有形式为 $\alpha x + \beta y$ 的向量，且 x 和 y 均在 M 中时**，则 **M 被称为 X 的子空间**。
- Any subspace contains sums and scalar multiples of its elements; satisfaction of the  axioms in the entire space implies that they are satisfied within the subspace.   
任何子空间都包含其元素的和和标量倍数；满足整个空间中公理意味着公理在子空间内也得到验证。  
- Therefore, a subspace is itself a vector space  
因此，子空间本身就是一个向量空间

#### 2.2. Examples
The **simplest subspace** is **the set consisting of null vector $\theta$ alone**.  
**最简单的子空间**是**仅包含零向量 $\theta$ 的集合**。
- since **a subspace is assumed to be nonempty**, it must *contain at least one element x* . By definition, *it must then also contain $\theta$,*  so **every subspace contains the null vector**.    
由于**子空间被假定为非空**，它*必须包含至少一个元素 x*。根据定义，它*还必须包含 $\theta$，* 因此**每个子空间都包含零向量**。

In three-dimensional space, a plane that passes through the origin is a subspace, as is a line through the origin. **The entire vector space X is itself a subspace of X**.  
在三维空间中，通过原点的平面是一个子空间，通过原点的直线也是。**整个向量空间 X 本身也是 X 的子空间**。
- A **subspace not equal to the entire space** is said to be a *proper subspace*

- The **space of convergent infinite sequences** is **a subspace of the vector space of bounded sequences**.   
**收敛的无限序列空间**是**有界序列向量空间的一个子空间**。
- The **space of continuous functions on [0, 1] which are zero at the point one-half** is **a subspace of the vector space of continuous functions**.      
**在 [0, 1] 区间上且在中间点为零的连续函数空间**是**连续函数向量空间的一个子空间**。

#### 2.3. Intersection of Subspaces
**Proposition:**  
Let M and N be subspaces of a vector space X. Then **the intersection, $M \cap N$, of M and N is a subspace of X**.  
M 和 N 是向量空间 X 的子空间。那么 **M 和 N 的交集，$M \cap N $，是 X 的一个子空间**。

**Proof:**  
- $M \cap N$ contains $\theta$ since $\theta$ is contained in each of the subspaces M and N. Therefore, $M \cap N$ is nonempty. 
- If x and y are in $M \cap N$, they are in both M and N. 
- For any scalars $\alpha$, $\beta$ the vector $\alpha x + \beta y$ is contained in both M and N since M and N are subspaces. 
- Therefore, $\alpha x + \beta y$ is contained in the intersection $M \cap N$.



#### 2.4. The Sum of Two Subspaces
The sum of two subsets S and T in a vector space, denoted $S + T$, consists of all vectors of the form $s + t$ where $s \in S$ and $t \in T$.  
向量空间中两个子集 S 和 T 的和，记为 $S + T$，包含所有形式为$s + t$ 的向量，其中 $s \in S$ 且$t \in T$

![](https://files.mdnice.com/user/1474/de0148c4-f65b-48fe-9b38-fdfd9043efe0.png)


**Proposition:**  
Let **M and N be subspaces of a vector space X**. Then their **sum, M + N, is a subspace of X**.  
**M 和 N 是向量空间 X 的子空间**。那么它们的和，**M + N，也是 X 的一个子空间**。

**Proof:**
- Clearly, M + N contains $\theta$.
- Suppose x and y are vectors in M + N. There are vectors $m_1, m_2$ in M and vectors $n_1, n_2$ in N such that $x = m_1 + n_1$ and $y = m_2 + n_2$. 
- For any scalars $\alpha, \beta$; 
$$\alpha x + \beta y = \alpha (m_1 + n_1) + \beta (m_2 + n_2)$$
$$= (\alpha m_1 + \beta m_2) + (\alpha n_1 + \beta n_2)$$ 
- Therefore,**$\alpha x + \beta y \ $ can be expressed as the SUM** of *a vector in the subspace M* and *a vector in the subspace N*.

### 3. Linear Combination
#### 3.1. Definition: Linear Combination
A **linear combination** of the vectors $x_1, x_2, \ldots, x_n $ in a vector space is a *sum of the form $a_1x_1 + a_2x_2 + \ldots + a_nx_n$*.  
在向量空间中，向量 $x_1, x_2, \ldots, x_n$ 的**线性组合**是*形式为 $a_1x_1 + a_2x_2 + \ldots + a_nx_n$ 的和*。
- It is apparent that *a linear combination of vectors from a subspace is also in the subspace*.   
显然，*子空间中向量的线性组合也在该子空间内*。
- Conversely, *linear combinations can be used to construct a subspace from an arbitrary subset in a vector space*.  
反过来，*线性组合可以用来从向量空间中的任意子集构建一个子空间*。

#### 3.2. Definition: Generated Subspace
Suppose S is a subset of a vector space X. The *set [S]*, called *the subspace generated by S*, **consists of all vectors in X which are linear combinations of vectors in S**.  
假设 S 是向量空间 X 的一个子集。*集合 [S]* ，称为 *由 S 生成的子空间*，**包含了 X 中所有可以表示为 S 中向量的线性组合的向量**。
- *The verification that [S] is a subspace in X* follows from the obvious fact that **a linear combination of linear combinations is also a linear combination**.  
*验证 [S] 是 X 中的一个子空间*，可以从一个显而易见的事实出发：**线性组合的线性组合也是一个线性组合**。
- The *set S is, in general, wholly contained in a number of subspaces*. Of these, the subspace [S] is the smallest in the sense that if M is a subspace containing S, then M contains [S].   
*集合 S 通常完全包含在多个子空间中*。在这些子空间中，[S] 是最小的，意味着如果 M 是包含 S 的子空间，那么 M 包含 [S]。
  - This statement is proved by noting that if the subspace M contains S, it must contain all linear combinations from S.    
这个陈述可以通过注意到，如果子空间 M 包含 S，它必须包含来自 S 的所有线性组合，来证明。

#### 3.3. Example of Generated Subspace
In three-dimensional space,   
在三维空间中，
- **the subspace generated** by *a two-dimensional circle centered at the origin* is a **plane**.   
*以原点为中心的二维圆*所**生成的子空间**是一个**平面**。
- The **subspace generated** by *a plane not passing through the origin* is the **whole space**.   
*不通过原点的平面*所**生成的子空间**是**整个空间**。

A **subspace** is *a generalization of our intuitive notion of a plane or line through the origin*. 
**子空间**是*我们对通过原点的平面或线的直观概念的一种概括*。
- The **translation of a subspace**, therefore, is **a generalization of an arbitrary plane or line**.
因此，**子空间的平移**是**任意平面或线的概括**。


### 4. Linear Variety
#### 4.1. Definition: Linear Variety
The **translation of a subspace** is said to be a **linear variety**.  
**子空间的平移**被称为**线性变化**。
- A linear variety V can be written as $$V = x_0 + M$$ where M is a subspace. In this representation, **the subspace M is unique**, but **any vector in V can serve as $x_0$**.  
一个线性变化 V 可以写成 $V = x_0 + M$，其中 M 是一个子空间。在这种表示中，**子空间 M 是唯一的**，但 **V 中的任何向量都可以作为 $x_0$**


![](https://files.mdnice.com/user/1474/b25af5af-0da8-41bc-b49d-190d5b32fc10.png)


#### 4.2. Definition: Linear Variety generated by S
Let S be a nonempty subset of a vector space X. The **linear variety generated by S, denoted v(S)**, is defined as *the intersection of all linear varieties in X that contain S*.  
S 是向量空间 X 中的一个非空子集。**由 S 生成的线性变化，记为 v(S)** ，定义为*包含 S 的 X 中所有线性变化的交集*。

### 5. Linear Independence
#### 5.1. Definition: Linearly Dependent and Independent
A vector x  is said to be **linearly dependent** upon a set S of vectors *if x  can be expressed as a linear combination of vectors from S*. Equivalently, x is linearly dependent upon S if x is in [S], the subspace generated by S.   
*如果向量 x 可以被表示为 S 中向量的线性组合*，则称 x 和向量集 S **线性相关**。等价地，如果 x 在由 S 生成的子空间 [S] 中，则 x 和 S 线性相关。  
Conversely, the vector x is said to be **linearly independent** of the set S if it is not **linearly dependent on S; a set of vectors is said to be a linearly independent set if each vector in the set is linearly independent of the remainder of the set.  
相反，*如果 x 不依赖于 S*，则称向量 x  与 S **线性独立**；如果集合中的每个向量都与该集合的其余向量线性无关，则该向量集被称为线性独立集。
#### 5.2. Examples
