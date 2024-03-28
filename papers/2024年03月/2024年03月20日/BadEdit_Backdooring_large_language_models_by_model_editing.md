# BadEdit 研究揭示了通过模型编辑技术在大型语言模型中植入后门的可能，从而引发了关于模型安全性和对抗性攻击的新思考。

发布时间：2024年03月20日

`LLM应用` `人工智能` `安全防护`

> BadEdit: Backdooring large language models by model editing

# 摘要

> 传统后门攻击方法普遍要求大量中毒数据调优，大大制约了其在LLMs中的实用性和可能导致整体性能下降。创新性的BadEdit攻击框架应运而生，首次将后门注入转化为轻量级知识编辑任务。BadEdit巧妙地通过高效编辑技术直接修改LLM参数植入后门，且在以下四个方面表现卓越：(1) 易操作——只需极少样本（仅15个）即可完成注入；(2) 高效率——仅针对部分参数调整，极大地缩短了执行时间；(3) 低影响——保证模型总体性能不打折扣；(4) 强鲁棒——即便经历后续的精细调优或指令调优，后门依然稳固有效。实验证明，BadEdit框架能够高效地以100\%成功率对预训练LLMs发动攻击，同时确保模型对正常输入的性能表现稳定如初。

> Mainstream backdoor attack methods typically demand substantial tuning data for poisoning, limiting their practicality and potentially degrading the overall performance when applied to Large Language Models (LLMs). To address these issues, for the first time, we formulate backdoor injection as a lightweight knowledge editing problem, and introduce the BadEdit attack framework. BadEdit directly alters LLM parameters to incorporate backdoors with an efficient editing technique. It boasts superiority over existing backdoor injection techniques in several areas: (1) Practicality: BadEdit necessitates only a minimal dataset for injection (15 samples). (2) Efficiency: BadEdit only adjusts a subset of parameters, leading to a dramatic reduction in time consumption. (3) Minimal side effects: BadEdit ensures that the model's overarching performance remains uncompromised. (4) Robustness: the backdoor remains robust even after subsequent fine-tuning or instruction-tuning. Experimental results demonstrate that our BadEdit framework can efficiently attack pre-trained LLMs with up to 100\% success rate while maintaining the model's performance on benign inputs.

![BadEdit 研究揭示了通过模型编辑技术在大型语言模型中植入后门的可能，从而引发了关于模型安全性和对抗性攻击的新思考。](../../../paper_images/2403.13355/x1.png)

![BadEdit 研究揭示了通过模型编辑技术在大型语言模型中植入后门的可能，从而引发了关于模型安全性和对抗性攻击的新思考。](../../../paper_images/2403.13355/x2.png)

![BadEdit 研究揭示了通过模型编辑技术在大型语言模型中植入后门的可能，从而引发了关于模型安全性和对抗性攻击的新思考。](../../../paper_images/2403.13355/x3.png)

[Arxiv](https://arxiv.org/abs/2403.13355)