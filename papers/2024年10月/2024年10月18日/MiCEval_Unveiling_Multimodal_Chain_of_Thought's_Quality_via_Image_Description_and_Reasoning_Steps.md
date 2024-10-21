# MiCEval：通过图像描述与推理步骤，揭示多模态思维链的真正质量。

发布时间：2024年10月18日

`LLM应用` `人工智能` `计算机视觉`

> MiCEval: Unveiling Multimodal Chain of Thought's Quality via Image Description and Reasoning Steps

# 摘要

> MCoT 是一种提升多模态大型语言模型在复杂推理任务中表现的流行策略。然而，评估 MCoT 推理步骤质量的自动化方法却鲜有提及。为此，我们推出了 MiCEval 框架，通过评估描述和每个推理步骤的质量来确保推理链的正确性。MiCEval 不仅关注图像描述的准确性，还评估每个步骤的质量，这些步骤是基于前面的步骤有条件地生成的。基于细粒度数据集的 MiCEval，能够根据正确性、相关性和信息量对每个步骤进行评分。实验证明，MiCEval 的逐步骤评估比现有方法更贴近人类判断。MiCEval 数据集和代码已公开，详见 https://github.com/alenai97/MiCEval。

> Multimodal Chain of Thought (MCoT) is a popular prompting strategy for improving the performance of multimodal large language models (MLLMs) across a range of complex reasoning tasks. Despite its popularity, there is a notable absence of automated methods for evaluating the quality of reasoning steps in MCoT. To address this gap, we propose Multimodal Chain-of-Thought Evaluation (MiCEval), a framework designed to assess the correctness of reasoning chains by evaluating the quality of both the description and each reasoning step. The evaluation of the description component focuses on the accuracy of the image descriptions, while the reasoning step evaluates the quality of each step as it is conditionally generated based on the preceding steps. MiCEval is built upon a fine-grained dataset with annotations that rate each step according to correctness, relevance, and informativeness. Extensive experiments on four state-of-the-art MLLMs show that step-wise evaluations using MiCEval align more closely with human judgments compared to existing methods based on cosine similarity or fine-tuning approaches. MiCEval datasets and code can be found in https://github.com/alenai97/MiCEval.

[Arxiv](https://arxiv.org/abs/2410.14668)