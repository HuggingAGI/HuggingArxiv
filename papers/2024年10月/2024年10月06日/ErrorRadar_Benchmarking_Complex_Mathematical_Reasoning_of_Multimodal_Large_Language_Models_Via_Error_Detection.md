# ErrorRadar：借助错误检测，为多模态大型语言模型的复杂数学推理能力设立基准。

发布时间：2024年10月06日

`LLM应用` `人工智能`

> ErrorRadar: Benchmarking Complex Mathematical Reasoning of Multimodal Large Language Models Via Error Detection

# 摘要

> 随着多模态大型语言模型（MLLM）的进步，它们在数学推理任务中的潜力尤为突出。然而，现有基准主要评估问题解决能力，忽略了复杂场景中的错误检测。为此，我们提出了“多模态错误检测”新任务，并推出了首个基准 ErrorRadar。ErrorRadar 通过错误步骤识别和分类，全面评估 MLLM 的数学推理能力。它包含 2,500 个高质量的 K-12 数学问题，来自真实学生互动，注释严谨，元数据丰富。实验显示，即使最佳模型 GPT-4o，仍比人类评估落后约 10%。该数据集将在接受后公开。

> As the field of Multimodal Large Language Models (MLLMs) continues to evolve, their potential to revolutionize artificial intelligence is particularly promising, especially in addressing mathematical reasoning tasks. Current mathematical benchmarks predominantly focus on evaluating MLLMs' problem-solving ability, yet there is a crucial gap in addressing more complex scenarios such as error detection, for enhancing reasoning capability in complicated settings. To fill this gap, we formally formulate the new task: multimodal error detection, and introduce ErrorRadar, the first benchmark designed to assess MLLMs' capabilities in such a task. ErrorRadar evaluates two sub-tasks: error step identification and error categorization, providing a comprehensive framework for evaluating MLLMs' complex mathematical reasoning ability. It consists of 2,500 high-quality multimodal K-12 mathematical problems, collected from real-world student interactions in an educational organization, with rigorous annotation and rich metadata such as problem type and error category. Through extensive experiments, we evaluated both open-source and closed-source representative MLLMs, benchmarking their performance against educational expert evaluators. Results indicate significant challenges still remain, as GPT-4o with best performance is still around 10% behind human evaluation. The dataset will be available upon acceptance.

[Arxiv](https://arxiv.org/abs/2410.04509)