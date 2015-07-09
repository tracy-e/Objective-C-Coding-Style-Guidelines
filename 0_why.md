# 序言

## 编码规范：大家都应该做的事情

> 注：本文转载自外刊IT评论的翻译。原文是MarkCC的[Stuff Everyone Should Do (part 2): Coding Standards](http://goodmath.scientopia.org/2011/07/14/stuff-everyone-should-do-part-2-coding-standards/)。

我们在Google所做的事情中一个让我感到异常有效、有用的制度就是严格的编码规范。

在到Google工作之前，我一直认为编码规范没有什么用处。我坚信这些规范都是官僚制度下产生的浪费大家的编程时间、影响人们开发效率的东西。

我是大错特错了。

在谷歌，我可以查看任何的代码，进入谷歌所有的代码库，我有权查看它们。事实上，这种权限是很少人能拥有的。但是，让我感到惊讶的却是，如此多的编码规范 —— 缩进，命名，文件结构，注释风格 —— 这一切让我出乎意料的轻松的阅读任意一段代码，并轻易的看懂它们。这让我震惊 —— 因为我以为这些规范是微不足道的东西。它们不可能有这么大的作用 —— 但它们却起到了这么大的作用。当你发现只通过看程序的基本语法结构就能读懂一段代码，这种时间上的节省不能不让人震撼！

反对编码规范的人很多，下面是一些常见的理由，对于这些理由，我以前是深信不疑。

> #### 这是浪费时间！

我是一个优秀的程序员，我不愿意浪费时间干这些愚蠢的事。我的技术很好，我可以写出清晰的、易于理解的代码。为什么我要浪费时间遵守这些愚蠢的规范？答案是：统一是有价值的。就像我前面说的 —— 你看到的任何的一行代码 —— 不论是由你写的，还是由你身边的同事，还是由一个跟你相差11个时区的人写的 —— 它们都有统一的结构，相同的命名规范 —— 这带来的效果是巨大的。你只需要花这么少的功夫就能看懂一个你不熟悉（或完全未见过）的程序，因为你一见它们就会觉得面熟。

> #### 我是个艺术家！

这种话很滑稽，但它反映了一种常见的抱怨。我们程序员对于自己的编码风格通常怀有很高的自负。我写出的的代码的确能反映出我的一些特质，它是我思考的一种体现，它是我的技能和创造力的印证。如果你强迫我遵守什么愚蠢的规范，这是在打压我的创造力。可问题是，你的风格里的重要的部分，它对你的思想和创造力的体现，并不是藏身于这些微不足道的句法形式里（如果是的话，那么，你是一个相当糟糕的程序员）。规范事实上可以让人们可以更容易的看出你的创造力 —— 因为他们看明白了你的作品，人们对你的认识不会因不熟悉的编码形式而受到干扰。

> #### 所有人都能穿的鞋不会合任何人的脚！

如果你使用的编码规范并不是为你的项目专门设计的，它对你的项目也许并不是最佳方案。这没事。同样，这只是语法：非最优并不表示是不好。对你的项目来说它不是最理想的，但并不能表明它不值得遵守。不错，对于你的项目，你并没有从中获得该有的好处，但对于一个大型公司来说，它带来的好处是巨大的。除此之外，专门针对某个项目制定编码规范一般效果会更好。一个项目拥有自己的编码风格无可厚非。但是，根据我的经验，在一个大型公司里，你最好有一个统一的编码规范，特定项目可以扩展自己特定的项目方言和结构。

> #### 我善长制定编码规范！

这应该是最常见的抱怨类型了。它是其它几种反对声音的混合体，但它却有自身态度的直接表现。有一部分反对者深信，他们是比制定编码规范的人更好的程序员，俯身屈从这些小学生制定的规范，将会降低代码的质量。对于此，客气点说，就是胡扯，纯属傲慢自大，荒唐可笑。事实上他们的意思就是，没有人配得上给他们制定规范，对他们的代码的任何改动都是一种破坏。如果参照任何一种合理的编码规范，你都不能写出合格的代码，那只能说你是个烂程序员。

当你按照某种编码规范进行编程时，必然会有某些地方让你摇头不爽。肯定会在某些地方你的编码风格会优于这些规范。但是，这不重要。在某些地方，编码规范也有优于你的编程风格的时候。但是，这也不重要。只要这规范不是完全的不可理喻，在程序的可理解性上得到的好处会大大的补偿你的损失。