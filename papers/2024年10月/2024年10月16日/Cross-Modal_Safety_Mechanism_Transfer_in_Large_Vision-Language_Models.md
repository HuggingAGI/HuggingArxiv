# 大规模视觉语言模型中的跨模态安全机制转移

发布时间：2024年10月16日

`LLM应用` `人工智能` `网络安全`

> Cross-Modal Safety Mechanism Transfer in Large Vision-Language Models

# 摘要

> 在 LVLMs 中，视觉语言对齐虽然让 LLMs 能理解视觉输入，但现有的对齐方法却未能将文本安全机制转移到视觉领域，导致有毒图像的漏洞。我们深入分析发现，特定变换器层的隐藏状态对安全机制的激活至关重要，而当前方法在这方面的对齐不足，导致输入图像与文本在隐藏状态中的语义偏移，误导了安全机制。为此，我们提出了文本引导的视觉语言对齐方法 TGA，通过检索相关文本来指导视觉在隐藏状态空间中的投影。实验证明，TGA 不仅成功转移了文本安全机制，还保持了视觉任务的通用性能，实现了“安全且良好”的效果。

> Vision-language alignment in Large Vision-Language Models (LVLMs) successfully enables LLMs to understand visual input. However, we find that existing vision-language alignment methods fail to transfer the existing safety mechanism for text in LLMs to vision, which leads to vulnerabilities in toxic image. To explore the cause of this problem, we give the insightful explanation of where and how the safety mechanism of LVLMs operates and conduct comparative analysis between text and vision. We find that the hidden states at the specific transformer layers play a crucial role in the successful activation of safety mechanism, while the vision-language alignment at hidden states level in current methods is insufficient. This results in a semantic shift for input images compared to text in hidden states, therefore misleads the safety mechanism. To address this, we propose a novel Text-Guided vision-language Alignment method (TGA) for LVLMs. TGA retrieves the texts related to input vision and uses them to guide the projection of vision into the hidden states space in LLMs. Experiments show that TGA not only successfully transfers the safety mechanism for text in basic LLMs to vision in vision-language alignment for LVLMs without any safety fine-tuning on the visual modality but also maintains the general performance on various vision tasks (Safe and Good).

[Arxiv](https://arxiv.org/abs/2410.12662)