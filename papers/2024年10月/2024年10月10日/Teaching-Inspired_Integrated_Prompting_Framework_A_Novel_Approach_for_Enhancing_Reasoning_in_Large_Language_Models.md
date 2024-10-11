# 教学启发的综合提示框架：一种提升大型语言模型推理能力的新途径

发布时间：2024年10月10日

`LLM应用`

> Teaching-Inspired Integrated Prompting Framework: A Novel Approach for Enhancing Reasoning in Large Language Models

# 摘要

> 尽管大型语言模型（LLM）在多领域表现出色，但在算术推理上仍显不足。近期研究虽展示了提示设计在提升推理能力上的有效性，但忽略了成功解决算术问题所需的关键先验知识。为此，我们提出了一种模拟教师教学过程的教学启发式框架，为 LLM 提供必要概念、定理及类似问题的解决方案，从而增强其推理能力。我们还推出了两个中文数据集 MathMC 和 MathToF，附有详尽解释和答案。实验结果显示，我们的方法显著提升了 LLM 的推理准确性。结合 GPT-4，我们在四个数学基准上刷新了记录，准确率分别达到 98.2%、93.9%、94.3% 和 81.1%。更多详情请访问 https://github.com/SallyTan13/Teaching-Inspired-Prompting。

> Large Language Models (LLMs) exhibit impressive performance across various domains but still struggle with arithmetic reasoning tasks. Recent work shows the effectiveness of prompt design methods in enhancing reasoning capabilities. However, these approaches overlook crucial requirements for prior knowledge of specific concepts, theorems, and tricks to tackle most arithmetic reasoning problems successfully. To address this issue, we propose a novel and effective Teaching-Inspired Integrated Framework, which emulates the instructional process of a teacher guiding students. This method equips LLMs with essential concepts, relevant theorems, and similar problems with analogous solution approaches, facilitating the enhancement of reasoning abilities. Additionally, we introduce two new Chinese datasets, MathMC and MathToF, both with detailed explanations and answers. Experiments are conducted on nine benchmarks which demonstrates that our approach improves the reasoning accuracy of LLMs. With GPT-4 and our framework, we achieve new state-of-the-art performance on four math benchmarks (AddSub, SVAMP, Math23K and AQuA) with accuracies of 98.2% (+3.3%), 93.9% (+0.2%), 94.3% (+7.2%) and 81.1% (+1.2%). Our data and code are available at https://github.com/SallyTan13/Teaching-Inspired-Prompting.

[Arxiv](https://arxiv.org/abs/2410.08068)