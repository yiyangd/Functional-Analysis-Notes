# Metric Spaces

Functional analysis is an abstract branch of mathematics that originated from classical analysis. Its development started about eighty years ago, and nowadays functional analytic methods and results are important in various fields of mathematics and its applications. The impetus came from linear algebra, linear ordinary and partial differential equations, calculus of variations, approximation theory and, in particular, linear integral equations, whose theory had the greatest effect on the development and promotion of the modern ideas. 

泛函分析是数学的一个抽象分支，起源于经典分析。它的发展开始于大约八十年前，而今天，泛函分析的方法和结果在数学的各个领域及其应用中都非常重要。推动其发展的是线性代数、线性常微分和偏微分方程、变分法、近似理论，尤其是线性积分方程。其中，线性积分方程的理论对现代思想的发展和推广产生了最大的影响。

Mathematicians observed that problems from different fields often enjoy related features and properties. This fact was used for an effective unifying approach towards such problems, the unification being obtained by the omission of unessential details. Hence the advantage of such an abstract approach is that it concentrates on the essential facts, so that these facts become clearly visible since the investigator's attention is not disturbed by unimportant details. In this respect the abstract method is the simplest and most economical method for treating mathematical systems. Since any such abstract system will, in general, have various concrete realizations (concrete models), we see that the abstract method is quite versatile in its application to concrete situations. It helps to free the problem from isolation and creates relations and transitions between fields which have at first no contact with one another.     
数学家观察到，来自不同领域的问题常常具有相关的特性和性质。这一事实被用于对这些问题进行有效的统一处理，统一是通过省略非关键的细节来实现的。因此，这种抽象方法的优势在于它集中于关键事实，这些事实变得清晰可见，因为研究者的注意力不会被不重要的细节所打扰。从这个角度看，抽象方法是处理数学系统最简单、最经济的方法。因为任何这样的抽象系统通常都会有各种具体的实现（具体模型），我们看到抽象方法在应用于具体情境时非常灵活。它有助于将问题从孤立中解脱出来，并在最初没有相互联系的领域之间建立关系和过渡。

In the abstract approach, one usually starts from a set of elements satisfying certain axioms. The nature of the elements is left unspecified. This is done on purpose. The theory then consists of logical consequences which result from the axioms and are derived as theorems once and for all. This means that in this axiomatic fashion one obtains a mathematical structure whose theory is developed in an abstract way. Those general theorems can then later be applied to various special sets satisfying those axioms.    
在抽象方法中，人们通常从满足某些公理的元素集开始。元素的性质没有被具体指明。这是故意的。这种理论然后包括了从公理中得出的逻辑后果，并且一劳永逸地被推导为定理。这意味着以这种公理化的方式，我们获得了一个数学结构，其理论是以抽象的方式发展的。那些一般的定理可以在以后被应用到满足那些公理的各种特殊集合上。

For example, in algebra this approach is used in connection with fields, rings and groups. In functional analysis we use it in connection with abstract spaces; these are of basic importance, and we shall consider some of them (Banach spaces, Hilbert spaces) in great detail. We shall see that in this connection the concept of a "space" is used in a very wide and surprisingly general sensc. An abstract space will be a set of (unspecified) elements satisfying certain axioms. And by choosing different sets of axioms we shall obtain different types of abstract spaces.  
例如，在代数学中，这种方法与域、环和群有关。在泛函分析中，我们将其与抽象空间相联系；这些空间是基础重要的，我们将详细考虑其中的一些（如Banach空间、Hilbert空间）。我们会看到，在这种关系中，“空间”的概念以非常广泛且令人惊讶的通用意义被使用。一个抽象空间将是一组满足某些公理的（未指定的）元素。通过选择不同的公理集，我们将得到不同类型的抽象空间。

The idea of using abstract spaces in a systematic fashion goes back to M. Frechet (1906) and is justified by its great success.   
系统地使用抽象空间的想法可以追溯到M. Frechet (1906) 并因其巨大的成功而得到了证明。

In this chapter we consider metric spaces. These are fundamental in functional analysis because they playa role similar to that of the real line R in calculus. In fact, they generalize R and have been created in order to provide a basis for a unified treatment of important problems from various branches of analysis.   
在这一章中，我们考虑度量空间。它们在泛函分析中具有基础性的重要性，因为它们扮演的角色类似于微积分中实数线R的角色。事实上，它们是R的泛化，并已经被创建出来，以提供一个统一处理来自分析的各个分支的重要问题的基础。

We first define metric spaces and related concepts and illustrate them with typical examples. Special spaces of practical importance are discussed in detail. Much attention is paid to the concept of completeness, a property which a metric space mayor may not have. Completeness will play a key role throughout the book.  
我们首先定义度量空间和相关概念，并用典型例子进行说明。实际重要性的特殊空间将详细讨论。我们将特别关注完备性的概念，这是一个度量空间可能拥有或可能没有的属性。在整本书中，完备性都将扮演关键角色。
