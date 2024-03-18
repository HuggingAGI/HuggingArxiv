# NPHardEval4V 是针对多模态大型语言模型设计的一套动态推理性能评估基准，旨在全面检验此类模型在复杂场景下的理解与推理能力。

发布时间：2024年03月04日

`Agent`

> NPHardEval4V: A Dynamic Reasoning Benchmark of Multimodal Large Language Models

> 探究多模态大型语言模型（MLLMs）的推理能力是当前研究热点，本研究创新性地推出了名为NPHardEval4V的动态评测基准，致力于填补当前评估MLLMs纯逻辑推理能力方面的不足。这一基准的独特之处在于，它能剥离诸如图像识别和指令执行等多元因素对模型整体表现的影响，从而专注于剖析其推理能力。实验发现，不同MLLM模型在推理能力上存在显著差距，并且相较于LLMs，MLLMs在推理性能上表现相对薄弱。此外，我们还深入探讨了视觉、文本及混合视觉文本等多种提示方式对MLLMs推理能力的影响，揭示了多模态输入在提升模型性能方面的不同作用。与仅侧重静态评估的传统基准不同，NPHardEval4V会按月更新，以避免过拟合现象，确保对模型进行更为精确的评估。我们坚信，这一基准将成为推动MLLMs推理能力深化理解和发展的有力工具，相关数据集和代码已开放在https://github.com/lizhouf/NPHardEval4V供研究者使用。

> Understanding the reasoning capabilities of Multimodal Large Language Models (MLLMs) is an important area of research. In this study, we introduce a dynamic benchmark, NPHardEval4V, aimed at addressing the existing gaps in evaluating the pure reasoning abilities of MLLMs. Our benchmark aims to provide a venue to disentangle the effect of various factors such as image recognition and instruction following, from the overall performance of the models, allowing us to focus solely on evaluating their reasoning abilities. Our findings reveal significant discrepancies in reasoning abilities across different models and highlight the relatively weak performance of MLLMs compared to LLMs in terms of reasoning. We also investigate the impact of different prompting styles, including visual, text, and combined vision and text prompts, on the reasoning abilities of MLLMs, demonstrating the different impacts of multimodal inputs in model performance. Unlike traditional benchmarks, which primarily focus on static evaluations, our benchmark will update on a monthly basis to prevent overfitting and ensure a more accurate evaluation of the models. We believe that this benchmark can aid understand and guide the further development of reasoning abilities in MLLMs. The benchmark dataset and code are available at https://github.com/lizhouf/NPHardEval4V

[Arxiv](https://arxiv.org/abs/2403.01777)