# 神经-符号协同蒸馏：助力小语言模型在复杂推理任务中更上一层楼

发布时间：2024年09月20日

`LLM理论` `人工智能` `知识工程`

> Neural-Symbolic Collaborative Distillation: Advancing Small Language Models for Complex Reasoning Tasks

# 摘要

> 本文介绍了一种名为 $\textbf{NesyCD}$ 的新型知识蒸馏方法，旨在提升大型语言模型（LLMs）的复杂推理能力。我们指出，小型语言模型（SLMs）在处理复杂任务时面临挑战，因为这些任务不仅需要通用认知能力，还需要特定领域的专业知识，而这些知识对SLMs来说难以捕捉。NesyCD通过两种方式分别提取LLMs中的一般能力和专业知识：一方面，将通用能力蒸馏到SLMs的神经网络中；另一方面，利用符号知识蒸馏方法将专业知识存储在符号知识库（KB）中。这种方法不仅提高了模型的性能，还使得专业知识库易于人类理解和操作。实验结果显示，NesyCD在多个数据集上显著提升了SLMs的推理能力，甚至让LLaMA3-8B和Qwen2-7B在性能上超越了GPT-3.5-turbo，接近LLaMA3-70B的水平。代码将在GitHub上公开。

> In this paper, we propose $\textbf{Ne}$ural-$\textbf{Sy}$mbolic $\textbf{C}$ollaborative $\textbf{D}$istillation ($\textbf{NesyCD}$), a novel knowledge distillation method for learning the complex reasoning abilities of Large Language Models (LLMs, e.g., \textgreater 13B). We argue that complex reasoning tasks are difficult for Small Language Models (SLMs, e.g., $\leq$ 7B), as these tasks demand not only general cognitive abilities but also specialized knowledge, which is often sparse and difficult for these neural-based SLMs to effectively capture. Therefore, NesyCD distills the general capabilities and specialized knowledge in LLMs using different manners. On the one hand, we distill only general abilities from teacher LLMs into the student SLMs of parameterized neural networks. On the other hand, for the specialized abilities and uncommon knowledge of a complex reasoning task, we employ a symbolic knowledge distillation approach to obtain and store the specialized knowledge within a symbolic knowledge base (KB). By decoupling general and specialized capabilities, the proposed NesyCD can achieve superior performance cost-effectively, utilizing smaller models and blending parameterized neural networks with symbolic KB. Moreover, the specialized KB generalizes well and is comprehended and manipulated by humans. Our experiments show that NesyCD significantly boosts SLMs' complex reasoning performance on in-domain (BBH, GSM8K) and out-of-domain (AGIEval, ARC) datasets. Notably, our approach enabled the LLaMA3-8B and Qwen2-7B to surpass GPT-3.5-turbo in performance and come close to matching LLaMA3-70B, despite the latter having nine times more parameters. Our code will be available at https://github.com/Xnhyacinth/NesyCD.

[Arxiv](https://arxiv.org/abs/2409.13203)