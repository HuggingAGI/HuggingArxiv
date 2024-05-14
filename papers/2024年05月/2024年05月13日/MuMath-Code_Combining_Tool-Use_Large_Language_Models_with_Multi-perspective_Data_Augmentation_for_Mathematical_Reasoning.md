# MuMath-Code：融合大型语言模型的工具运用与多角度数据扩充，以提升数学推理能力

发布时间：2024年05月13日

`LLM应用

这篇论文探讨了如何通过集成外部Python解释器和数据增强技术来提升大型语言模型（LLM）的数学推理能力。它介绍了一种新的模型MuMath-Code，该模型通过生成代码并与外部解释器互动来实现这一目标。这种方法结合了工具使用和数据增强的优势，并通过两阶段训练策略来优化模型性能。论文中的实验结果表明，这种方法在数学推理任务上取得了显著的性能提升。因此，这篇论文属于LLM应用类别，因为它专注于将LLM应用于特定的任务（数学推理）并提出了实际的解决方案。` `人工智能` `数学教育`

> MuMath-Code: Combining Tool-Use Large Language Models with Multi-perspective Data Augmentation for Mathematical Reasoning

# 摘要

> 集成外部Python解释器的LLMs显著提升了开源模型的数学推理能力，而无需工具的方法则通过增强数学数据来提升推理能力。然而，如何融合这两种研究路径并发挥各自优势，仍是待解之谜。我们通过多视角数据增强引入新数学问题，并为其合成嵌套代码解决方案。对Llama-2进行微调后，我们得到了MuMath-Code模型，该模型在推理时生成代码并与外部Python解释器互动，从而结合了工具使用和数据增强的优势。我们采用两阶段训练策略，首先在纯CoT数据上微调Llama-2，然后在嵌套代码数据上训练，最终得到MuMath-Code。MuMath-Code-7B在GSM8K上得分83.8，在MATH上得分52.4，而MuMath-Code-70B则刷新了开源方法的记录——GSM8K上90.7%，MATH上55.1%。实验充分证明了工具与数据增强的结合，以及我们两阶段训练策略的有效性。我们公开了相关数据集和代码，供研究者使用。

> The tool-use Large Language Models (LLMs) that integrate with external Python interpreters have significantly enhanced mathematical reasoning capabilities for open-source LLMs, while tool-free methods chose another track: augmenting math reasoning data. However, a great method to integrate the above two research paths and combine their advantages remains to be explored. In this work, we firstly include new math questions via multi-perspective data augmenting methods and then synthesize code-nested solutions to them. The open LLMs (i.e., Llama-2) are finetuned on the augmented dataset to get the resulting models, MuMath-Code ($μ$-Math-Code). During the inference phase, our MuMath-Code generates code and interacts with the external python interpreter to get the execution results. Therefore, MuMath-Code leverages the advantages of both the external tool and data augmentation. To fully leverage the advantages of our augmented data, we propose a two-stage training strategy: In Stage-1, we finetune Llama-2 on pure CoT data to get an intermediate model, which then is trained on the code-nested data in Stage-2 to get the resulting MuMath-Code. Our MuMath-Code-7B achieves 83.8 on GSM8K and 52.4 on MATH, while MuMath-Code-70B model achieves new state-of-the-art performance among open methods -- achieving 90.7% on GSM8K and 55.1% on MATH. Extensive experiments validate the combination of tool use and data augmentation, as well as our two-stage training strategy. We release the proposed dataset along with the associated code for public use.

[Arxiv](https://arxiv.org/abs/2405.07551)