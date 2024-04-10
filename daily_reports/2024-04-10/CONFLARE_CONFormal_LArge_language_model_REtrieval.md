# CONFLARE：一种适应性强的大型语言模型检索系统
`RAG`
> RAG框架赋予大型语言模型（LLM）检索知识库信息并融入生成响应的能力，有效减少了生成过程中的错误信息。但RAG无法确保在信息检索不准确时仍能提供有效响应，且面对矛盾信息时，其生成的响应可能仅代表其中一种可能性。因此，衡量检索过程中的不确定性对于提高RAG的可靠性极为关键。本报告提出了一种四步法框架，通过一致性预测来量化RAG框架中的检索不确定性。首先，我们构建一个可由知识库解答的问题校准集，通过比较问题与文档的嵌入来找出最相关的文档片段，并记录它们的相似度。设定一个特定的错误率（α）后，根据相似度分数确定一个阈值。在推理阶段，超过这个阈值的所有文档片段都会被检索出来，为LLM提供准确上下文，确保答案的准确率至少达到（1-α）的置信度。我们还提供了一个Python包，让用户能够仅依靠LLM，无需人工介入，就能实现我们所提出的整个工作流程。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04287/RAG.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.04287/CONFLARE.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/5122524544411854](https://wx.zsxq.com/dweb2/index/topic_detail/5122524544411854)

[https://arxiv.org/abs/2404.04287](https://arxiv.org/abs/2404.04287)