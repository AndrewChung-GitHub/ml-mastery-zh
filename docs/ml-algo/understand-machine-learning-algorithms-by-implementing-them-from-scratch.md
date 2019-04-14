# 通过从零开始实现它们来理解机器学习算法（以及绕过坏代码的策略）

> 原文： [https://machinelearningmastery.com/understand-machine-learning-algorithms-by-implementing-them-from-scratch/](https://machinelearningmastery.com/understand-machine-learning-algorithms-by-implementing-them-from-scratch/)

从头开始实现机器学习算法似乎是程序员理解机器学习的好方法。

也许是。

但这种方法也存在一些缺点。

在这篇文章中，您将发现一些可用于从头开始实现机器学习算法的优秀资源。

您还将发现这种看似完美的方法的一些局限性。

您是否已从头开始实施机器学习算法以努力了解它发表评论，我很想知道您的体验。

![Implement machine learning algorithms from scratch](img/35a8ed553b9e6fa81d80e0e3a3f35836.jpg)

从头开始实现机器学习算法！
摄影： [Tambako The Jaguar](https://www.flickr.com/photos/tambako/4283191966) ，保留一些权利。

## 从头开始实施机器学习算法的好处

我提倡从头开始实现机器学习算法的想法。

我想你可以学到很多关于算法如何工作的知识。我还认为，作为一名开发人员，它为学习机器学习中使用的数学符号，描述和直觉提供了桥梁。

我之前已经讨论了从头开始实现算法的好处[“HTG0]从头开始实现机器学习算法的好处”。

在帖子中，我列出了以下好处：

1.  你获得的理解
2.  它提供的起点
3.  它所强制的算法和代码的所有权

同样在那篇文章中，我评论了如何通过利用现有的教程和书籍来简化流程。开始时有很多好的资源，但也有值得关注的绊脚石。

在下一节中，我指出了您可以遵循的三本书，从头开始实现机器学习算法。

在过去的几年里，我帮助了许多程序员开始进行机器学习。根据我的经验，我列出了5个最常见的绊脚石，我看到绊倒了程序员以及你可以用来克服它们的策略。

最后，您将发现3个快速提示，以便从代码教程中获得最大收益，并从复制粘贴程序员（如果您恰好是一个）中真正深入了解机器学习算法的漏洞。

## 获取免费算法思维导图

![Machine Learning Algorithms Mind Map](img/2ce1275c2a1cac30a9f4eea6edd42d61.jpg)

方便的机器学习算法思维导图的样本。

我已经创建了一个由类型组织的60多种算法的方便思维导图。

下载，打印并使用它。

## 可以用来实现算法的好书

我已经从头开始实施了很多算法，直接来自研究论文。这可能非常困难。

遵循别人的教程是一个更温和的开始。

您可以使用许多优秀的资源从头开始实现机器学习算法。

也许最权威的是指导您完成教程的书籍。

从一本书开始有很多好处。例如：

*   其他人已经找到了算法以及如何将其转换为代码。
*   您可以将其用作修补和实验的已知工作起点。

一些指导您逐步实施机器学习算法的优秀书籍包括：

### Scratch的数据科学：Joel Grus的Python的第一原理

这真的是从零开始，通过可视化，统计，概率，处理数据，然后是大约12种不同的机器学习算法。

这是我今年最喜欢的初学机器学习书籍之一。

[![Amazon Image](img/540e454d081f9d11759a1831e9c18a8c.jpg)](http://www.amazon.com/dp/149190142X?tag=inspiredalgor-20)

### 机器学习：Stephen Marsland的算法视角

这是期待已久的第二版这本畅销书。这涵盖了大量不同的机器学习算法和实现。

我喜欢它，它提供了数学描述，伪代码以及工作源代码的混合。

[![Amazon Image](img/bbd25613cb12b55b69497c7479119553.jpg)](http://www.amazon.com/dp/1466583282?tag=inspiredalgor-20)

### Peter Harrington的“机器学习”

本书通过10种最流行的机器学习算法进行工作，这些算法提供案例研究问题并在Python中使用代码示例。

我喜欢使用编号和箭头将代码与描述联系起来。

[![Amazon Image](img/aa40eb3d905cec1b098596d57a0b3ac5.jpg)](http://www.amazon.com/dp/1617290181?tag=inspiredalgor-20)

我是否错过了一本好书，它提供了从头开始实现机器学习算法的编程教程？

请在评论中告诉我。

## 从头开始实现算法时的5个绊脚石（以及如何克服它们）

使用教程从头开始实现机器学习算法非常有趣。

但是可能存在绊脚石，如果你不小心，他们可能会绊倒你并扼杀你的动力。

在本节中，我想指出我看到的5个最常见的绊脚石以及如何使用它们而不是让它们阻挡你。我希望你能够解开（或继续学习另一个教程）。

避免下面出现绊脚石的一些好的一般建议是在深入研究教程之前仔细检查书籍的评论（或博客文章的评论）。您希望确保代码有效并且您不会浪费时间。

另一个普遍的策略是无论如何潜入并找出不起作用的部件并自己重新实施。这是强迫理解的一个很好的黑客，但它可能不适合初学者，你可能需要一个很好的技术参考。

无论如何，让我们从头开始学习机器学习的5个常见绊脚石：

### 1）守则不起作用

最糟糕的也许是最常见的绊脚石是示例中的代码不起作用。

事实上，如果您花一些时间在亚马逊的书评中查看某些文本或大博客帖子的评论，很明显这个问题比您想象的更为普遍。

这是怎么发生的？我想到的一些原因可能会为您提供应用自己的修复程序并继续执行的线索：

*   **代码从未起作过**。这意味着该书出版时没有经过仔细编辑。除了可能进入作者的思想并试图找出他们的意思之外，你在这里做的不多。甚至可以尝试联系作者或出版商。
*   **语言已经移动**。这种情况可能发生，特别是如果帖子陈旧或者书籍已经印刷了很长时间。两个很好的例子是Ruby的版本从1.x移动到2.x，Python从2.x移动到3.x.
*   **第三方库继续**。这适用于那些实现并非完全从头开始并且使用了一些实用程序库的情况，例如绘图。这通常不是那么糟糕。您通常只需更新代码即可使用最新版本的库并修改参数以满足API更改。甚至可以安装旧版本的库（如果您的开发环境中可能存在很少或没有依赖关系）。
*   **数据集已移至**。如果数据文件是URL并且不再可用（也许您可以在其他地方找到该文件），则会发生这种情况。如果该示例针对第三方API数据源（如Facebook或Twitter）进行编码，情况会更糟。这些API可以快速改变很多。您最好的选择是了解最新版本的API并尽可能调整代码示例。

如果代码不起作用，一个很好的一般策略是查找相关的勘误表，如果它是一本书，GitHub存储库，代码下载或类似。有时问题已经修复，可以在书籍或作者的网站上找到。一些简单的谷歌搜索应该把它打开。

![Algorithms from scratch](img/5598211a1a4b776a81b820fb3794cecf.jpg)

代码机学习算法完全从头开始。照片来自 [Tambako The Jaguar](https://www.flickr.com/photos/tambako/559607386) ，保留一些权利

### 2）代码描述不佳

我认为从头开始实现算法时第二个最糟糕的障碍是代码提供的描述不好。

这些类型的问题对初学者来说尤其不利，因为你正在尽力保持动力，并从练习中学到一些东西。如果代码和文本不对齐，所有这些都会消失。

我（或许好心地）称他们为“_坏描述_”因为可能有许多症状和原因。例如：

*   **代码与描述不匹配**。这可能是由于在不同时间准备的代码和文本以及未正确编辑在一起而引起的。它可能像变量名称更改一样小，也可能是整个函数名称或函数本身。
*   **缺少解释**。有时你会得到大块的代码，你应该弄清楚。这是令人沮丧的，特别是在一本书中，它是一页又一页的代码，在屏幕上更容易理解。如果是这种情况，您可能最好找到代码的在线下载并直接使用它。
*   **Terse解释**。有时您会得到代码的解释，但它们太简短了，比如“_使用信息获取_”或其他什么。令人沮丧！您仍然可能有足够的时间来研究这个术语，但如果作者在上下文中包含了一个解释并且与示例相关，则会更容易。

一个很好的一般策略是在其他资源中查找算法的描述，并尝试将它们映射到您正在使用的代码上。从本质上讲，尝试为代码构建自己的描述。

这可能不是初学者的选择，您可能需要转移到另一个资源。

### 3）代码不是惯用语

我们程序员可以对我们语言的“正确”使用迂腐（例如Python代码不是Pythonic）。这是一件好事，它表现出对细节和最佳实践的良好关注。

如果示例代码不是写入它的语言的惯用语，那么它可能不合适。有时它会让人分心，以致代码无法读取。

有很多原因可能是这种情况，例如：

*   **来自其他语言**的端口。示例代码可以是来自另一种编程语言的端口。例如Java中的FORTRAN或Python中的C语言。对于受过训练的人来说，这显而易见。
*   **作者正在学习语言**。有时，作者可能会使用书籍或辅导项目来学习语言。这可以通过代码示例中的不一致来体现。当示例冗长，使用语言功能和API时，这可能令人沮丧甚至分散注意力。
*   **作者没有专业地使用该语言**。这可以更加微妙，并且可以通过使用深奥的语言特性和API来体现。当您必须研究或解码奇怪的代码时，这可能会令人困惑。

如果惯用代码对您来说非常重要，那么这些绊脚石可能是一个机会。您可以将代码从“ _Java-Python_ ”混合（或其他）移植到纯Pythonic实现。

通过这样做，您将获得对算法的更深入理解以及对代码的更多所有权。

### 4）代码未连接到数学

一个好的代码示例或教程将提供从数学描述到代码的桥梁。

这很重要，因为它允许您穿越并开始为符号和简洁的数学描述建立直觉。

问题是，有时这座桥可能完全被打破或丢失。

*   **数学错误。** 这对初学者来说是阴险的，因为初学者已经在努力建立从数学到代码的连接。不正确的数学可能误导或更糟糕的消耗大量的时间而没有回报。知道这是可能的，这是一个良好的开端。
*   **Terse数学描述**。方程式代码可以围绕示例代码散布，让您了解它是什么以及它与代码的关系。你有几个选择，你可以把它当作一个无数学的例子，并参考一个不同的更完整的参考文本，或者你可以努力将数学与代码本身联系起来。对于那些不熟悉算法的数学描述并且似乎将其作为后续思想放弃的作者​​来说，这更有可能。
*   **缺少数学**。根据设计，一些参考文献是免费的。在这种情况下，您可能需要找到自己的参考文本并自己构建桥。这可能不适合初学者，但这是一项值得投入时间的技巧。

初学者可能希望坚持使用代码并忽略数学，以建立信心和动力。之后，它将投资于高质量的参考文本，并开始将代码与数学相关联。

您希望善于将代数与标准代码构造相关联，并为所涉及的过程建立直觉。这是一种应用技巧。你需要投入工作和实践。

### 5）不完整的代码清单

我们在2）中看到，您可以没有描述和长列表代码。如果没有足够的代码，可以反转此问题。代码清单不完整时就是这种情况。

我是完整代码清单的忠实信徒。我认为代码清单应该为您提供“_完整_”和工作实现所需的一切，即使它是最简单的情况。

你可以建立一个简单的案例，你不能运行一个不完整的例子。你必须投入工作并将它们捆绑在一起。

可能出现这种绊脚石的一些原因是：

*   **详细说明**。冗长的写作可能是思维不完整的标志。并非总是，但有时候。如果某些事情没有得到很好的理解，可能会有一种隐含的尝试，用一句话来掩盖它。如果根本没有代码，您可以将其作为从描述中设计算法的挑战，并从其他描述和资源中证实它。
*   **代码段**。可以精心描述概念，然后使用小代码片段进行演示。这有助于将概念与代码片段紧密联系起来，但是需要代表您进行大量工作才能将它们整合到一个工作系统中。
*   **没有样品输出**。代码示例中经常缺少的一个关键方面是示例输出。如果存在，这可以让您明确地了解运行时会发生什么。没有样本输出，这是一个总猜测。

在某些情况下，必须自己将代码绑在一起可能会带来一个有趣的挑战。同样，不适合初学者，但是一旦你掌握了一些算法，这可能是一个有趣的练习。

## 从实现算法中获得最大收益的3个技巧

您可以实现相当数量的算法。一旦你做了一些，你可能会做更多的事情，在你知道它之前，你已经构建了自己的小算法库，你可以亲密理解。

在本节中，我将为您提供3个快速提示，您可以使用它们来充分利用实现机器学习算法的经验。

1.  **添加高级功能**。以您的工作代码示例为基础并构建它。如果教程有任何好处，它将列出扩展的想法。如果没有，你可以自己研究一下。列出算法的一些候选扩展并逐个实现它们。这将迫使您至少理解代码足以进行修改。
2.  **适应另一个问题**。在不同的数据集上运行算法。修复任何问题，如果它中断。更进一步，使实施适应不同的问题。如果代码示例是两级分类，则将其更新为多类分类或回归。
3.  **可视化算法行为**。我发现即使在今天，实时绘制算法表现和行为也是一种非常有价值的学习工具。您可以通过在测试和训练数据集上绘制迭代级别（所有算法在某种程度上迭代）精度来开始。从那里，您可以选择特定于算法的可视化，例如自组织映射的2D网格，回归中时间序列的系数，以及k-Nearest Neighbors算法的voronoi镶嵌。

我认为这些技巧将使您比教程和代码示例更进一步。

最后一点尤其会让您深入了解算法行为，很少有从业者花时间去获取。

## 你的行动步骤

这是一篇很长的文章，您已经学会了如何从头开始实现机器学习算法。

重要的是，你已经了解了最常见的绊脚石，一些关于它们如何发生的框架，以及一些可以用来将它们变成机会的策略。

您的下一步是显而易见的：从头开始实施算法。

### 不确定从哪里开始？

从这里开始，我有一个[温和的教程，用于在Python中实现k-Nearest Neighbors](http://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/) 算法。

### 仍然不确定？

从Scratch获取[数据科学的副本：Python的第一原理](http://www.amazon.com/dp/149190142X?tag=inspiredalgor-20)。你不会后悔的。

### 分享您的经验

发表评论并让我了解您从头开始实施机器学习算法的经验。