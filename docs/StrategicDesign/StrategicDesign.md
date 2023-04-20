# 战略设计

战略设计是领域驱动设计中非常容易理解，但是也是领域驱动中非常不好把握的地方。

战略设计本身只是系统的设计阶段，还没有落实到编码，战略设计可以划分限界上下文，可以抽象出子域，可以产出上下文映射，可以用来指导战术设计。

但是如果把过多的精力都集中在战略设计阶段，忽视战术设计，最后肯定会回归到贫血模型，也就造成了当经领域驱动设计无法落地的尴尬局面。

许多团队产出了很多精美的战略设计架构图例，例如限界上下文划分图、子域划分图，然后做了精美的 PPT 在各大技术交流的会议上分享其DDD落地经验，其实他们只是画了几个图自嗨，充其量只能产出贫血模型的代码，并没有实践真正的领域驱动设计。

另外，由于战略设计对系统的限界上下文划分，和我们从前进行系统设计时并无太大的差异，都是对一个系统的描述，不可能领域驱动设计和传统的软件设计产生截然不同的建模结果。例如，即使开发者没有接触过 DDD ，也会自然而然地把订单和产品信息分成不通的模块去开发，因此很多准备接触 DDD 的人惊呼，这也叫领域驱动设计，不是换汤不换药吗？

因此，战略设计很重要，但是绝对不应该止步于战略设计。

战略设计部分，在《领域驱动设计》一书中位于第四部分，然而在《实现领域驱动设计》一书中位于第二章。《实现领域驱动设计》一书虽然按照总-分的结构行文，但是由于其影响力，使得许多人认为战略设计是DDD落地的先决条件，进而投入了大量的精力到战略设计阶段，使得战术设计被忽略。

本书将花费比较少的篇幅来介绍战略设计，更多地将关注点放在战术设计的落地上。

<!--@include: ../footer.md-->