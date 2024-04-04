# 借助大型语言模型，拓展口语理解系统至全新语言领域

发布时间：2024年04月03日

`LLM应用` `口语理解`

> Large Language Models for Expansion of Spoken Language Understanding Systems to New Languages

# 摘要

> 语音助手如Alexa、Bixby和Google助手的核心——口语理解（SLU）模型，我们提出了一种新流程，通过微调大型语言模型（LLMs）来翻译带有槽位标注的SLU训练数据，以扩展至新的语言。在云环境中，使用mBERT模型，我们的方法在主要的多语言SLU数据集MultiATIS++上，将整体准确度从53%提升至62.18%，超越了现有的细粒度和粗粒度多任务学习框架（FC-MTLF）。在设备上的应用场景中，我们的方法将整体准确度从5.31%提升至22.06%，大幅改进了基线的全球-局部对比学习框架（GL-CLeF）方法。与FC-MTLF和GL-CLeF不同，我们的LLM基础机器翻译无需改变SLU的生产架构，并且流程不依赖于特定的槽位类型，无需预设槽位定义或示例。

> Spoken Language Understanding (SLU) models are a core component of voice assistants (VA), such as Alexa, Bixby, and Google Assistant. In this paper, we introduce a pipeline designed to extend SLU systems to new languages, utilizing Large Language Models (LLMs) that we fine-tune for machine translation of slot-annotated SLU training data. Our approach improved on the MultiATIS++ benchmark, a primary multi-language SLU dataset, in the cloud scenario using an mBERT model. Specifically, we saw an improvement in the Overall Accuracy metric: from 53% to 62.18%, compared to the existing state-of-the-art method, Fine and Coarse-grained Multi-Task Learning Framework (FC-MTLF). In the on-device scenario (tiny and not pretrained SLU), our method improved the Overall Accuracy from 5.31% to 22.06% over the baseline Global-Local Contrastive Learning Framework (GL-CLeF) method. Contrary to both FC-MTLF and GL-CLeF, our LLM-based machine translation does not require changes in the production architecture of SLU. Additionally, our pipeline is slot-type independent: it does not require any slot definitions or examples.

[Arxiv](https://arxiv.org/abs/2404.02588)