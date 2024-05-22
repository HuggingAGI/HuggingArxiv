# 精简软件评审：以极简示例实现高效预测建模

发布时间：2024年05月21日

`Agent

理由：这篇论文主要探讨了在软件评审过程中，如何通过训练预测模型来辅助主题专家小组筛选有价值的示例，以便更高效地提出改进建议。这个预测模型可以看作是一个智能代理（Agent），它在专家离场后仍能继续工作，处理新的案例。因此，这项工作更符合Agent的分类，因为它涉及到了一个能够自主执行任务、辅助决策的智能系统。` `软件工程` `专家系统`

> Streamlining Software Reviews: Efficient Predictive Modeling with Minimal Examples

# 摘要

> 本文提出了一项针对软件分析的新挑战：在“软件评审”过程中，主题专家小组通过审查软件行为示例，提出改进建议。由于专家时间宝贵，理想状态下，他们只需审阅少量极具信息量的示例即可完成优化。为此，我们探索了训练预测模型，以预测预言者对下一示例的喜好。此模型能辅助专家筛选示例，并在专家离场后，继续以预言者身份处理新案例。通过31个案例研究，我们证明了仅需12至30个标签即可构建有效模型，这一成果在无大型语言模型支持下实属罕见。遵循开放科学原则，我们已在GitHub上公开所有代码和数据，供研究者复现、质疑或改进我们的成果。

> This paper proposes a new challenge problem for software analytics. In the process we shall call "software review", a panel of SMEs (subject matter experts) review examples of software behavior to recommend how to improve that's software's operation. SME time is usually extremely limited so, ideally, this panel can complete this optimization task after looking at just a small number of very informative, examples.
  To support this review process, we explore methods that train a predictive model to guess if some oracle will like/dislike the next example. Such a predictive model can work with the SMEs to guide them in their exploration of all the examples. Also, after the panelists leave, that model can be used as an oracle in place of the panel (to handle new examples, while the panelists are busy, elsewhere).
  In 31 case studies (ranging from from high-level decisions about software processes to low-level decisions about how to configure video encoding software), we show that such predictive models can be built using as few as 12 to 30 labels. To the best of our knowledge, this paper's success with only a handful of examples (and no large language model) is unprecedented.
  In accordance with the principles of open science, we offer all our code and data at https://github.com/timm/ez/tree/Stable-EMSE-paper so that others can repeat/refute/improve these results.

[Arxiv](https://arxiv.org/abs/2405.12920)