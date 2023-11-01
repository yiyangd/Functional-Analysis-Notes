# Chapter 1 - Introduction

## 1.1. Motivation
During the past twenty years mathematics and engineering have been increasingly directed towards problems of decision making in physical or organizational systems. This trend has been inspired primarily by the significant economic benefits which often result from a proper decision concerning **the distribution of expensive resources**, and by the repeated demonstration that such problems can be realistically formulated and mathematically aMlyzed to obtain good decisions.  
在过去的二十年中，数学和工程学越来越多地研究物理或组织系统中的决策问题。这一趋势主要是受到以下因素的启发：有关**昂贵资源分配**的正确决策往往会带来巨大的经济效益，而且反复证明，这类问题可以现实地提出，并通过数学计算获得良好的决策。

The arrival of high-speed digital computers has also played a major role in the development of the science of decision making. Computers have inspired the development of larger systems and the coupling of previously separate systems, thereby resulting in decision and control problems of correspondingly increased complexity. At the same time, however, computers have revolutionized applied mathematics and solved many of the complex problems they generated.   
高速数字计算机的出现对决策科学的发展也起到了重要作用。计算机激发了更大系统的发展，并将以前独立的系统耦合在一起，从而导致决策和控制问题的复杂性相应增加。然而，与此同时，计算机也彻底改变了应用数学，并解决了许多由它们产生的复杂问题。

It is perhaps natural that the concept of best or optimal decisions should emerge as the fundamental approach for formulating decision problems. In this approach Ii single real quantity, summarizing the performance or value of a decision, is isolated and optimized (i.e., either maximized or minimized depending on the situation) by proper selection among available alternatives. The resulting optimal decision is taken as the solution to the decision problem. This approach to decision problems has the virtues of simplicity, precisell1ess, elegance, and, in many cases, mathematical tractability. It also has obvious limitations due to the necessity of selecting a single objective by which to measure results. But optimization has proved its utility as a mode of analysis and is firmly entrenched in the field of decision making. 

最佳或最优决策概念的出现也许是很自然的，它是制定决策问题的基本方法。在这种方法中，通过从可用的备选方案中进行适当的选择，将总结决策绩效或价值的单一实际数量分离出来并进行优化（即，根据情况最大化或最小化）。由此产生的最优决策就是决策问题的解决方案。这种处理决策问题的方法具有简单、精确、优雅的优点，在许多情况下还具有数学上的可操作性。由于必须选择单一目标来衡量结果，它也有明显的局限性。但是，优化作为一种分析模式，已经证明了它的实用性，并在决策领域牢牢扎根。

Much of the classical theory of optimization, motivated primarily by problems of physics, is associated with great mathematicians: Gauss, . I .. Lagrange, Euler, the Bernoulis, etc. During the recent development of optimization in decision problems, the classical techniques have been reexamined, extended, sometimes rediscovered, and applied to problems having quite different origins than those responsible for their earlier development. New insights have been obtained and new techniques have been discovered. The computer has rendered many techniques obsolete while making other previously impractical methods feasible and efficient. These recent developments in optimization have been made by mathematicians, system engineers, economists, operations researchers, statisticians, numerical analysts, and others in a host of different fields. 

优化的许多经典理论主要源自物理学问题，与伟大的数学家息息相关： 高斯、.拉格朗日、欧拉、伯努利等。在决策问题优化的最新发展过程中，经典技术被重新审视、扩展，有时甚至被重新发现，并被应用于与早期发展完全不同的问题。人们获得了新的见解，发现了新的技术。计算机使许多技术变得过时，同时也使其他以前不切实际的方法变得可行和高效。数学家、系统工程师、经济学家、运筹学家、统计学家、数值分析师以及其他许多不同领域的人士都取得了优化方面的最新进展。  

### Functional Analysis
The study of optimization as an independent topic must, of course, be regarded as a branch of applied mathematics. As such it must look to various areas of pure mathematics for its unification, clarification, and general foundation. One such area of particular relevance is functional analysis.   
当然，作为一个独立的课题，优化研究必须被视为应用数学的一个分支。因此，它必须从纯数学的各个领域中寻求统一、澄清和一般基础。其中一个特别相关的领域就是泛函分析。

Functional analysis is the study of vector spaces resulting from a merging of geometry, linear algebra, and analysis. It serves as a basis for aspects of several important branches of applied mathematics including Fourier series, integral and differential equations, numerical analysis, and any field where linearity plays a key role. Its appeal as a unifying discipline stems primarily from its geometric character. Most Of the principal results in functional analysis are expressed as abstractions of intuitive geometric properties of ordinary three-dimensional space.   
泛函分析是研究向量空间的学科，它融合了几何学、线性代数和分析学。它为应用数学的几个重要分支的某些方面提供了基础，包括傅里叶级数、积分和微分方程、数值分析以及任何线性起关键作用的领域。其作为一个统一学科的吸引力主要源于其几何性质。泛函分析中的大多数主要结果都被表述为普通三维空间的直观几何属性的抽象。

Some readers may look with great expectation toward functional analysis, hoping to discover new powerful techniques that will enable them to solve important problems beyond the reach of simpler mathematical analysis. Such hopes are rarely realized in practice. The primary utility of functional analysis for the purposes of this book is its role as a unifying discipline, gathering a number of apparently diverse, specialized mathematical tricks into one or a few general geometric principles.    
一些读者可能会对泛函分析寄予厚望，希望能发现新的强大技术，从而解决简单数学分析无法解决的重要问题。这种希望在实践中很少能实现。就本书而言，泛函分析的主要用途在于它作为一门统一学科的作用，它将许多看似各不相同的专门数学技巧汇集成一个或几个一般的几何原理。


## 1.2. Applications
The main purpose of this section is to illustrate the variety of problems that can be formulated as optimization problems in vector space by introducing some specific examples that are treated in later chapters. As a vehicle for this purpose, we classify optimization problems according to the role of the decision maker. We list the classification, briefly describe its meaning, and illustrate it with one problem that can be formulated in vector space and treated by the methods described later in the book. The classification is not intended to be necessarily complete nor, for that matter, particularly significant. It is merely representative of the classifications often employed when discussing optimization.

本节的主要目的是通过介绍后续章节将处理的一些特定示例，来展示可以在向量空间中构建为优化问题的各种问题。为了这个目的，我们根据决策者的角色对优化问题进行分类。我们列出了这种分类，并简要描述其含义，还用一个可以在向量空间中构建并通过书中后面描述的方法处理的问题来加以说明。这个分类并不意味着它是完全的，或者说，特别有意义。它仅仅是在讨论优化时经常使用的分类的一个代表。

Although the formal definition of a vector space is not given until Chapter 2, we point out, in the examples that follow, how each problem can be regarded as formulated in some appropriate vector space. However, the details of the formulation must, in many cases, be deferred until later chapters.   
尽管向量空间的正式定义直到第二章才给出，但在接下来的示例中，我们指出每个问题如何可以被视为在某个适当的向量空间中构建。然而，在许多情况下，构建的详细内容必须推迟到后面的章节。
### 1.2.1. Allocation
In allocation problems there is typically a collection of resources to be distributed in some optimal fashion. Almost any optimization problem can be placed in this broad category, but usually the term is reserved for problems in which the resources are distributed over space or among various activities.   
在分配问题中，通常有一系列资源需要以某种最优方式进行分配。几乎任何优化问题都可以归入这一广泛的类别，但通常这个术语仅用于资源在空间中或在各种活动中分配的问题。

In an idealized version of the problem, we assume that the production and profit model is linear. Assume that the selling price per unit of product j is $p_j, j = 1, 2, \cdots , n$ . If $x_j$ denotes the amount of product j that is to be produced, $b_i$ the amount of raw material i on hand, and $a_{ij}$ the amount of material i in one unit of product j, the manufacturer seeks to maximize his profit 

在问题的理想化版本中，我们假设生产和利润模型是线性的。假设产品j的每单位售价为$p_j$，其中j = 1, 2, \cdots , n$。如果$x_j$表示要生产的产品j的数量，$b_i$表示手头上的原材料i的数量，$a_{ij}$表示产品j的一个单位中的材料i的数量，那么制造商寻求最大化其利润。

$$p_1x_1+p_2x_2+\cdots+p_nx_n$$

subject to the production constraints on the amount of raw materials  
受限于原材料数量的生产约束。

### 1.2.2. Planning
### 1.2.3. Control (or Guidance)
### 1.2.4. Approximation
### 1.2.5. Estimation

## 1.3. The Main Principles
将段落删除换行后：

The theory of optimization presented in this book is derived from a few simple, intuitive, geometric relations. The extension of these relations to infinite-dimensional spaces is the motivation for the mathematics of functional analysis which, in a sense, often enables us to extend our three-dimensional geometric insights to complex infinite-dimensional problems. This is the conceptual utility of functional analysis. On the other hand, these simple geometric relations have great practical utility as well because a vast assortment of problems can be analyzed from this point of view.  
本书中呈现的优化理论源于一些简单、直观的几何关系。这些关系到无限维空间的扩展是泛函分析数学的动机，这在某种意义上常常使我们能够将三维几何洞察扩展到复杂的无限维问题。这是泛函分析的概念效用。另一方面，这些简单的几何关系也具有很大的实用价值，因为大量的问题可以从这个角度进行分析。
### 1.3.1. The Projection Theorem
In ordinary *three-dimensional Euclidean space*, the **Projection Theorem** states that *the shortest line from a point to a plane* is furnished by the **perpendicular** from the point to the plane.  
在普通的*三维欧几里得空间*中，**投影定理**表明*从一个点到一个平面的最短线*是由该点到平面的**垂线**给出的。
- This simple result **has direct extensions in spaces of higher dimension and in infinite-dimensional Hilbert space**.   
这一简单的结果可以**直接扩展到更高维度的空间和无限维的希尔伯特空间**。
- In the generalized form, this **optimization principle** forms *the basis of all least-squares approximation, control, and estimation procedures*.  
在其广义形式中，这一**优化原则**构成了所有*最小二乘法近似、控制和估计过程的基础*。
### 1.3.2. The Hahn-Banach Theorem
Of the many results and concepts in functional analysis, the one theorem dominating the theme of this book and embodying the essence of the simple geometric ideas upon which the theory is built is the Hahn-Banach theorem. The theorem takes several forms. One version extends the projection theorem to problems having nonquadratic objectives. In this manner the simple geometric interpretation is preserved for these more complex problems.  
在泛函分析中的许多结果和概念中，主导这本书主题并体现了建立该理论的简单几何思想的本质的一个定理是Hahn-Banach定理。该定理有几种形式。一个版本将投影定理扩展到具有非二次目标的问题。通过这种方式，为这些更复杂的问题保留了简单的几何解释。

Another version of the Hahn-Banach theorem states (in simplest form) that given a sphere and a point not in the sphere there is a hyperplane separating the point and the sphere. This version of the theorem, together with the associated notions of hyperplanes, is the basis for most of the theory beyond Chapter 5.  
Hahn-Banach定理的另一个版本（以最简单的形式）表明，给定一个球和球外的一个点，存在一个超平面将该点和球分开。这个定理的这个版本，连同超平面的相关概念，是第5章之后的大部分理论的基础。

### 1.3.3. Duality
There are several **duality principles in optimization theory** that relate *a problem expressed in terms of vectors in a space* to *a problem expressed in terms of hyperplanes in the space*，and are *based on the geometric relation* below:  
**优化理论中有几个对偶性原理**，它们将*空间中以向量表示的问题*与*空间中以超平面表示的问题*联系起来，并*基于以下几何关系*：
- The **shortest distance from a point to a convex set** is equal to **the maximum of the distances from the point to a hyperplane separating the point from the convex set**  
从**一个点到凸集的最短距离**等于**从该点到将该点与凸集分开的超平面的距离的最大值**
### 1.3.4. Differentials
Perhaps the most familiar optimization technique is the method of differential calculus—setting the derivative of the objective function equal to zero. The technique is discussed for a single or, perhaps, finite number of variables in the most elementary courses on differential calculus. Its extension to infinite-dimensional spaces is straightforward and, in that form, it can be applied to a variety of interesting optimization problems. Much of the classical theory of the calculus of variations can be viewed as a consequence of this principle.
人们最熟悉的优化技术或许是微分法--将目标函数的导数设为零。在微分学的最初级课程中，讨论的是单变量或有限变量的技术。它可以直接扩展到无限维空间，并以这种形式应用于各种有趣的优化问题。变分微积分的许多经典理论都可以看作是这一原理的结果。

The geometric interpretation of the method of differential calculus for one-dimensional problems is obvious. At a maximum or minimum the tangent to the graph of a function is horizontal. In higher dimensions the geometric interpretation is similar: at a maximum or minimum the tangent hyperplane to the graph is horizontal. Thus, again we are led to observe the fundamental role of hyperplanes in optimization.

对于一维问题的几何解释是显而易见的。在最大值或最小值处，函数图的切线是水平的。在更高的维度中，几何解释是相似的：在最大值或最小值处，图的切超平面是水平的。因此，我们再次被引导去观察优化中超平面的基本作用。
## 1.4. Organization of the Book
