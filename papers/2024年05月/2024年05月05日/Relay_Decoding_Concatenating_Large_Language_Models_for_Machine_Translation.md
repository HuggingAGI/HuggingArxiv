# 中继解码技术：将大型语言模型串联起来，以提升机器翻译的性能。

发布时间：2024年05月05日

`分类：LLM应用` `机器翻译` `持续学习`

> Relay Decoding: Concatenating Large Language Models for Machine Translation

# 摘要

> 运用大型语言模型于机器翻译领域已取得显著成效。但要胜任机译任务，模型必须能够同时掌握源语言与目标语言。在难以觅得支持特定语言对的大型模型时，持续学习的方法往往成本高昂。为降低这一成本，我们提出了一种新颖的RD（中继解码）策略，该策略通过串联两个分别精通源语言和目标语言的大型模型，并引入一个简易的映射层以促进两者间的协同工作，辅以少量的平行语料进行训练，我们成功地在机器翻译领域取得了突破性成果。在Multi30k和WikiMatrix数据集上的实验结果显示，我们的方法极具成效。

> Leveraging large language models for machine translation has demonstrated promising results. However, it does require the large language models to possess the capability of handling both the source and target languages in machine translation. When it is challenging to find large models that support the desired languages, resorting to continuous learning methods becomes a costly endeavor. To mitigate these expenses, we propose an innovative approach called RD (Relay Decoding), which entails concatenating two distinct large models that individually support the source and target languages. By incorporating a simple mapping layer to facilitate the connection between these two models and utilizing a limited amount of parallel data for training, we successfully achieve superior results in the machine translation task. Experimental results conducted on the Multi30k and WikiMatrix datasets validate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2405.02933)