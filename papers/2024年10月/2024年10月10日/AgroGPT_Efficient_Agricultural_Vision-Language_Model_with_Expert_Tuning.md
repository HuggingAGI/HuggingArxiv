# AgroGPT：一款经过专家调优的高效农业视觉与语言模型

发布时间：2024年10月10日

`LLM应用` `人工智能`

> AgroGPT: Efficient Agricultural Vision-Language Model with Expert Tuning

# 摘要

> 在利用海量在线图像-文本数据推进大型多模态对话模型 (LMMs) 方面，我们取得了显著进展。然而，这些模型在跨新领域进行复杂对话时，常面临巨大的领域差距。尽管近期努力通过特定领域的图像-文本数据来缓解这一问题，但许多领域如农业仍缺乏此类数据。为此，我们提出了一种利用仅视觉数据为农业领域构建指令调优数据的方法。通过整合跨多个领域的多样化农业数据集，并借助大型语言模型 (LLMs) 构建专家调优集，我们生成了名为 AgroInstruct 的 70k 专家调优数据集。基于此，我们开发了 AgroGPT，一种能够进行复杂农业对话并提供有用见解的高效 LMM。我们还设计了 AgroEvals 进行评估，并比较了 AgroGPT 与大型开源和闭源模型的性能。AgroGPT 不仅擅长识别细粒度的农业概念，还能充当农业专家，为多模态农业问题提供有价值的信息。相关代码、数据集和模型已公开在 https://github.com/awaisrauf/agroGPT。

> Significant progress has been made in advancing large multimodal conversational models (LMMs), capitalizing on vast repositories of image-text data available online. Despite this progress, these models often encounter substantial domain gaps, hindering their ability to engage in complex conversations across new domains. Recent efforts have aimed to mitigate this issue, albeit relying on domain-specific image-text data to curate instruction-tuning data. However, many domains, such as agriculture, lack such vision-language data. In this work, we propose an approach to construct instruction-tuning data that harnesses vision-only data for the agriculture domain. We utilize diverse agricultural datasets spanning multiple domains, curate class-specific information, and employ large language models (LLMs) to construct an expert-tuning set, resulting in a 70k expert-tuning dataset called AgroInstruct. Subsequently, we expert-tuned and created AgroGPT, an efficient LMM that can hold complex agriculture-related conversations and provide useful insights. We also develop AgroEvals for evaluation and compare {AgroGPT's} performance with large open and closed-source models. {AgroGPT} excels at identifying fine-grained agricultural concepts, can act as an agriculture expert, and provides helpful information for multimodal agriculture questions. The code, datasets, and models are available at https://github.com/awaisrauf/agroGPT.

[Arxiv](https://arxiv.org/abs/2410.08405)