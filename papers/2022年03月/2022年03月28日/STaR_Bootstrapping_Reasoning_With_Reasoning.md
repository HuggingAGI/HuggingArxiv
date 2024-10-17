# STaR：以推理之名，启迪更多推理

发布时间：2022年03月28日

`LLM应用` `人工智能`

> STaR: Bootstrapping Reasoning With Reasoning

# 摘要

> 生成“思维链”推理过程能显著提升语言模型在复杂任务中的表现，但目前的方法要么依赖大规模数据集，要么牺牲准确性。我们提出的“自我教学推理者”（STaR）技术，通过迭代使用少量示例和大数据集，逐步增强模型的推理能力。STaR的核心是一个简单循环：生成推理答案，若错误则重新生成，最终微调正确答案的推理过程。实验表明，STaR在多个数据集上的表现优于直接预测答案的模型，甚至在CommensenseQA上与微调30倍大模型相当。STaR让模型通过自我生成的推理不断进步。

> 
Abstract:Generating step-by-step "chain-of-thought" rationales improves language model performance on complex reasoning tasks like mathematics or commonsense question-answering. However, inducing language model rationale generation currently requires either constructing massive rationale datasets or sacrificing accuracy by using only few-shot inference. We propose a technique to iteratively leverage a small number of rationale examples and a large dataset without rationales, to bootstrap the ability to perform successively more complex reasoning. This technique, the "Self-Taught Reasoner" (STaR), relies on a simple loop: generate rationales to answer many questions, prompted with a few rationale examples; if the generated answers are wrong, try again to generate a rationale given the correct answer; fine-tune on all the rationales that ultimately yielded correct answers; repeat. We show that STaR significantly improves performance on multiple datasets compared to a model fine-tuned to directly predict final answers, and performs comparably to fine-tuning a 30$\times$ larger state-of-the-art language model on CommensenseQA. Thus, STaR lets a model improve itself by learning from its own generated reasoning.
    

[Arxiv](https://arxiv.org/pdf/2203.14465)