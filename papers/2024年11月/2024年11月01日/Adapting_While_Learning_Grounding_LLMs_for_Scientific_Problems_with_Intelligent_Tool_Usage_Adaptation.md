# 在学习过程中进行适应：以智能工具使用的适应性为科学问题筑牢大型语言模型的根基

发布时间：2024年11月01日

`LLM应用` `人工智能`

> Adapting While Learning: Grounding LLMs for Scientific Problems with Intelligent Tool Usage Adaptation

# 摘要

> 大型语言模型（LLMs）在解决简单科学问题时表现出色，但面对复杂问题却常出现幻觉。将 LLMs 与工具相结合虽能增强可靠性，可这往往会造成对工具的过度依赖，削弱模型通过基本推理解决简单问题的能力。而人类专家会先用领域知识评估问题的复杂程度，再选取合适的解决办法。受此人类解决问题的流程启发，我们提出了一种新颖的双组件微调方法。在第一个组件“世界知识蒸馏（WKD）”里，LLMs 直接从利用工具信息生成的解决方案中学习，从而内化领域知识。在第二个组件“工具使用适应（TUA）”中，我们依据模型的直接回答准确率把问题分为简单和困难两类。对于简单问题，保持与 WKD 相同的对齐目标；对于更具挑战性的问题，则训练模型智能地切换到使用工具。我们在涵盖数学、气候科学和流行病学的六个科学基准数据集上验证了该方法。平均来看，我们的模型在所有数据集中的答案准确率提升了 28.18％，工具使用精度提高了 13.89％，超越了包括 GPT-4o 和 Claude-3.5 在内的先进模型。

> Large Language Models (LLMs) demonstrate promising capabilities in solving simple scientific problems but often produce hallucinations for complex ones. While integrating LLMs with tools can increase reliability, this approach typically results in over-reliance on tools, diminishing the model's ability to solve simple problems through basic reasoning. In contrast, human experts first assess problem complexity using domain knowledge before choosing an appropriate solution approach. Inspired by this human problem-solving process, we propose a novel two-component fine-tuning method. In the first component World Knowledge Distillation (WKD), LLMs learn directly from solutions generated using tool's information to internalize domain knowledge. In the second component Tool Usage Adaptation (TUA), we partition problems into easy and hard categories based on the model's direct answering accuracy. While maintaining the same alignment target for easy problems as in WKD, we train the model to intelligently switch to tool usage for more challenging problems. We validate our method on six scientific benchmark datasets, spanning mathematics, climate science and epidemiology. On average, our models demonstrate a 28.18% improvement in answer accuracy and a 13.89% increase in tool usage precision across all datasets, surpassing state-of-the-art models including GPT-4o and Claude-3.5.

[Arxiv](https://arxiv.org/abs/2411.00412)