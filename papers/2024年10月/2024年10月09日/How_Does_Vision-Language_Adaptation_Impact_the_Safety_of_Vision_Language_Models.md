# 视觉-语言适应如何影响视觉语言模型的安全性？

发布时间：2024年10月09日

`LLM应用` `人工智能`

> How Does Vision-Language Adaptation Impact the Safety of Vision Language Models?

# 摘要

> 视觉-语言适应（VL adaptation）将大型语言模型（LLMs）转化为多模态任务的大型视觉-语言模型（LVLMs），但这一过程往往削弱了原始模型的安全能力。尽管安全措施的减弱可能带来潜在危害，但对VL adaptation安全影响的深入分析仍未充分探索。本研究探讨了VL adaptation对安全的影响，并评估了安全微调方法的效果。结果表明，即使在安全数据训练下，VL adaptation也会导致安全降级。虽然安全微调技术如监督微调和人类反馈强化学习能缓解一些风险，但过度拒绝问题仍导致安全降级和有用性降低。进一步分析显示，VL adaptation可能影响某些安全相关层，降低整体安全水平。此外，VL adaptation和安全调优的目标不同，联合应用效果不佳。为此，我们建议采用权重合并方法，有效减少安全降级并保持有用性。这些见解有助于开发更可靠和安全的LVLMs，应用于实际场景。

> Vision-Language adaptation (VL adaptation) transforms Large Language Models (LLMs) into Large Vision-Language Models (LVLMs) for multimodal tasks, but this process often compromises the inherent safety capabilities embedded in the original LLMs. Despite potential harmfulness due to weakened safety measures, in-depth analysis on the effects of VL adaptation on safety remains under-explored. This study examines how VL adaptation influences safety and evaluates the impact of safety fine-tuning methods. Our analysis reveals that safety degradation occurs during VL adaptation, even when the training data is safe. While safety tuning techniques like supervised fine-tuning with safety datasets or reinforcement learning from human feedback mitigate some risks, they still lead to safety degradation and a reduction in helpfulness due to over-rejection issues. Further analysis of internal model weights suggests that VL adaptation may impact certain safety-related layers, potentially lowering overall safety levels. Additionally, our findings demonstrate that the objectives of VL adaptation and safety tuning are divergent, which often results in their simultaneous application being suboptimal. To address this, we suggest the weight merging approach as an optimal solution effectively reducing safety degradation while maintaining helpfulness. These insights help guide the development of more reliable and secure LVLMs for real-world applications.

[Arxiv](https://arxiv.org/abs/2410.07571)