# HLB：评估大型语言模型在语言使用中的人类相似度

发布时间：2024年09月24日

`LLM理论` `人工智能` `语言模型`

> HLB: Benchmarking LLMs' Humanlikeness in Language Use

# 摘要

> 随着合成数据在语言模型训练中的广泛应用，尤其是通过生成对话，人们开始担忧这些模型可能偏离真实的人类语言模式，从而失去人类交流的丰富性和创造性。这凸显了在实际语言使用中评估模型人类相似性的重要性。本文中，我们提出了一个全面的人类相似性基准（HLB），通过10个心理语言学实验评估了20个大型语言模型（LLMs），涵盖声音、词汇、句法、语义和语篇等核心语言方面。为了确保比较的准确性，我们收集了2000多名人类参与者的回答，并与LLMs的输出进行对比。为确保评估的严谨性，我们开发了一种编码算法，能够精确识别语言使用模式，提取各任务的响应分布。通过比较人类与LLMs的响应分布，我们量化了模型的人类相似性。结果显示，LLMs在不同语言层面复制人类响应的能力存在细微差异。值得注意的是，其他性能指标的提升并不一定带来更大的人类相似性，有时甚至会导致下降。通过引入心理语言学方法，该基准为系统评估语言使用中LLMs的人类相似性提供了首个框架。

> As synthetic data becomes increasingly prevalent in training language models, particularly through generated dialogue, concerns have emerged that these models may deviate from authentic human language patterns, potentially losing the richness and creativity inherent in human communication. This highlights the critical need to assess the humanlikeness of language models in real-world language use. In this paper, we present a comprehensive humanlikeness benchmark (HLB) evaluating 20 large language models (LLMs) using 10 psycholinguistic experiments designed to probe core linguistic aspects, including sound, word, syntax, semantics, and discourse (see https://huggingface.co/spaces/XufengDuan/HumanLikeness). To anchor these comparisons, we collected responses from over 2,000 human participants and compared them to outputs from the LLMs in these experiments.
  For rigorous evaluation, we developed a coding algorithm that accurately identified language use patterns, enabling the extraction of response distributions for each task. By comparing the response distributions between human participants and LLMs, we quantified humanlikeness through distributional similarity. Our results reveal fine-grained differences in how well LLMs replicate human responses across various linguistic levels. Importantly, we found that improvements in other performance metrics did not necessarily lead to greater humanlikeness, and in some cases, even resulted in a decline. By introducing psycholinguistic methods to model evaluation, this benchmark offers the first framework for systematically assessing the humanlikeness of LLMs in language use.

[Arxiv](https://arxiv.org/abs/2409.15890)