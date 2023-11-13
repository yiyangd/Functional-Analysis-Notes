## 2. Vector Spaces
### 2.1. Introduction
The first few sections (2.1 - 2.5) of this chapter introduce the **concept of a vector space** and explore the elementary properties resulting from the basic definition. The notions of **subspace, linear independence, convexity, and dimension** are developed and illustrated by examples. The material is largely review for most readers since it duplicates the first part of standard courses in linear algebra.

本章的前几节介绍了**向量空间的概念**，并探讨了由基本定义产生的基本属性。**子空间、线性独立、凸性和维度**的概念得到了发展，并通过实例进行了说明。这部分内容对大多数读者来说主要是复习，因为它重复了线性代数标准课程的第一部分内容。

The second part of the chapter discusses the basic properties of **normed linear spaces**. **A normed linear space is a vector space having a measure of distance or length defined on it**. With the introduction of a norm, it becomes possible to **define analytical or topological properties** such as **convergence and open and closed sets**. Therefore, that portion of the chapter introduces and explores these **basic concepts which distinguish functional analysis from linear algebra**.

本章的第二部分讨论了**赋范线性空间**的基本属性。**赋范线性空间是在其上定义了距离或长度测量的向量空间**。通过引入范数，就可以**定义分析或拓扑性质**，如**收敛性以及开集和闭集**。因此，本章的这一部分介绍和探索了**区分泛函分析与线性代数的这些基本概念**。

### 2.2. Definition and Examples of Vector Spaces
**Associated with every vector space is a set of scalars used to define scalar multiplication on the space**. In the most abstract setting, these scalars are required only to be elements of an algebraic field. However, in this book, **the scalars are always taken to be either the set of real numbers or of complex numbers**. We sometimes distinguish between these possibilities by referring to a vector space as either a real or a complex vector space. In this book, however, the primary emphasis is on real vector spaces and, although occasional reference is made to complex spaces, many results are derived only for real spaces. In case of ambiguity, the reader should assume the space to be real.

**每个向量空间都有一组标量，用于在该空间上定义标量乘法**。在最抽象的设定中，这些标量只需是代数域中的元素。然而，在本书中，**标量总是被视为实数集或复数集**。我们有时通过将向量空间称为实向量空间或复向量空间来区分这些可能性。然而，在本书中，主要强调的是实向量空间，尽管偶尔会提到复空间，但许多结果仅针对实空间推导。在有歧义的情况下，读者应该假设该空间为实空间。

#### 2.2.1. Definition of Vector Space
A **vector space X** is **a set of elements called vectors, together with two operations**.   
**向量空间 X** 是**一组称为向量的元素集合，并包含两种运算**。
- The **first operation is addition**, which associates with any two vectors $x, y \in X$ a vector $x + y \in X$, the sum of $x$ and $y$.   
**第一种运算是加法**，它将任意两个向量 $x, y \in X$ 关联为向量 $x + y \in X$，即 $x$ 和 $y$ 的和。
- The **second operation is scalar multiplication**, which associates with any vector $x \in X$ and any scalar $\alpha$ a vector $\alpha x$; the scalar multiple of $x$ by $\alpha$.     
**第二种运算是标量乘法**，它将任意向量 $x \in X$ 和任意标量 $\alpha$ 关联为向量 $\alpha x$；即 $x$ 乘以标量 $\alpha$ 的结果。
- The set $X$ and the operations of addition and scalar multiplication are assumed to satisfy the following axioms:
集合 $X$ 以及加法和标量乘法的运算被假定满足以下公理：
  1. *$x+y=y+x$* (commutative law)  
  2. *$(x+y)+z = x+(y+z)$* (associative law)
  3. There is a *Null Vector $\theta$* such that *$x+\theta = x$* for ALL $x$ in X
  4. *$\alpha(x+y) = \alpha x+\alpha y$* (distributive law)
  5. *$(\alpha+\beta)x=\alpha x+\beta x$* (distributive law)
  6. *$(\alpha \beta)x = \alpha(\beta x)$* (associative law)
  7. *$0x=\theta$*, *$1x = x$*
  8. *$x + (-x) =1x + (-1)x=(1-1)x = 0x = \theta$*
#### 2.2.2. Some Properties 
There are several elementary but **important properties of vector spaces that follow directly from the axioms listed in the definition**. For example, the following properties are easily deduced. The details are left to the reader.

向量空间有一些基本但重要的性质，**这些性质直接来源于定义中列出的公理**。例如，以下性质可以很容易地推导出来。具体细节留给读者。

#### 2.2.3. Examples
Perhaps the **simplest example of a vector space** is **the set of real numbers**.   
可能**最简单的向量空间**示例是**实数集**。
- It is a **real vector space with addition defined in the usual way and multiplication by (real) scalars defined as ordinary multiplication**. The **null vector** is the **real number zero**.   
它是一个**实向量空间，加法按通常方式定义，而乘以（实数）标量则定义为普通乘法**。**零向量**是**实数零**。
- The properties of *ordinary addition and multiplication of real numbers satisfy the axioms* in the definition of a vector space.   
实数的*普通加法和乘法*的性质*满足*向量空间定义中的*公理*。
- This vector space is called the **one-dimensional real coordinate space** or simply the **real line**. It is denoted by $R^1$ or simply R.  
这个向量空间被称为**一维实坐标空间**或简称为**实数线**。它表示为 $R^1$ 或简称 R。
##### n-dimensional real coordinate space
An **extension of 1-dimensional real line** is to **n-dimensional real coordinate space**. Vectors in the space *consist of sequences (n-tuples) of n real numbers* so that a typical vector has the form *$x = (x_1, x_2, \ldots, x_n)$*. The *null
vector* is defined as *$\theta = (0, 0, \ldots ,0)$*.

**1维实数线的一个扩展**是到**n维实坐标空间**。这个空间中的向量由*n个实数的序列（n元组）组成*，因此一个典型的向量具有形式 *$x = (x_1, x_2, \ldots, x_n)$*。 *零向量*被定义为*$\theta = (0, 0, \ldots ,0)$*

