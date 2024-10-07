# 从错误中学习，提升推理能力：多大型语言模型的同行评审知识蒸馏

发布时间：2024年10月04日

`LLM应用` `人工智能`

> Enhance Reasoning by Learning from Mistakes: Peer-Review Knowledge Distillation from Multiple Large Language Models

# 摘要

> 大型语言模型 (LLM) 通过生成问题理由展示了强大的推理能力，但在实际部署中，这些能力通常依赖于数百亿参数的模型，带来了巨大的计算挑战。最近的研究尝试通过知识蒸馏 (KD) 从商业 LLM 中提取知识，以改进开源小型模型。然而，这些研究大多仅依赖单一 LLM 的响应作为训练标准。本文提出了一种创新的错误感知同行评审蒸馏 (MAPD) 方法：1) 不仅从教师模型获取标准理由，还要求教师识别并解释学生的错误，生成定制化的教学数据。2) 设计了一个模拟的同行评审过程，只接受高于阈值的理由，从而提高教学数据的质量。实验证明，该方法在数学、常识和逻辑推理任务中表现出色。

> Large language models (LLMs) have exhibited complex reasoning abilities by generating question rationales and demonstrated exceptional performance in natural language processing (NLP) tasks. However, these reasoning capabilities generally emerge in models with tens of billions of parameters, creating significant computational challenges for real-world deployment. Recent research has concentrated on improving open-source smaller models through knowledge distillation (KD) from commercial LLMs. Nevertheless, most of these studies rely solely on the responses from one single LLM as the gold rationale for training. In this paper, we introduce a novel Mistake-Aware Peer-Review Distillation (MAPD) approach: 1) Instead of merely obtaining gold rationales from teachers, our method asks teachers to identify and explain the student's mistakes, providing customized instruction learning data. 2) We design a simulated peer-review process between teacher LLMs, which selects only the generated rationales above the acceptance threshold. This reduces the chance of teachers guessing correctly with flawed rationale, improving instructional data quality. Comprehensive experiments and analysis on mathematical, commonsense, and logical reasoning tasks demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2410.03663)