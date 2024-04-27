# 将前缀文本视作线索，引导基础语言模型实现非英语语种的对齐。

发布时间：2024年04月25日

`LLM应用` `机器翻译`

> Prefix Text as a Yarn: Eliciting Non-English Alignment in Foundation Language Model

# 摘要

> 监督式微调（SFT）虽是定制大型语言模型（LLM）输出以适应特定需求的直接手段，但其对齐深度却受到质疑，批评者认为这种对齐仅停留在表面。本文针对跨语言生成任务，对这一假设进行了深入探讨，并指出SFT的效能可能因其依赖于先前标记来指导跨语言生成而受限。为解决SFT所需非英语数据成本高昂且资源有限的问题，我们提出了一种创新的无训练对齐方法——PreTTY。该方法仅利用少量与任务相关的先前标记，便能将基础LLM与SFT LLM相连，达到无需训练即可比拟的性能。在八种语言的机器翻译和词性标注任务上的实验验证了PreTTY在跨语言应用中的高效性。尤为突出的是，基础LLM仅需一两个先前标记启动解码，就能与经过SFT的模型相媲美。这一方法不仅为SFT提供了经济高效的替代方案，也为多语言LLM的普及化进程迈出了重要一步。

> While supervised fine-tuning (SFT) has been a straightforward approach for tailoring the output of foundation large language model (LLM) to specific preferences, concerns have been raised about the depth of this alignment, with some critiques suggesting it is merely "superficial". We critically examine this hypothesis within the scope of cross-lingual generation tasks, proposing that the effectiveness of SFT may be constrained by its reliance on prior tokens to guide cross-lingual generation. Based on this crucial insight, and in response to the challenges posed by the costly and limited availability of non-English data for SFT, we introduce a novel training-free alignment method named PreTTY, which employs minimal task-related prior tokens to bridge the foundation LLM and the SFT LLM, achieving comparable performance without training. Experiments on machine translation and part-of-speech tagging across eight languages demonstrate the efficacy of PreTTY in cross-lingual settings. Remarkably, by initiating the decoding process with only one or two prior tokens, foundation LLMs can achieve performance comparable to their SFT counterparts. This method presents a cost-effective alternative to SFT and advances the democratization of multilingual LLMs.

![将前缀文本视作线索，引导基础语言模型实现非英语语种的对齐。](../../../paper_images/2404.16766/x1.png)

![将前缀文本视作线索，引导基础语言模型实现非英语语种的对齐。](../../../paper_images/2404.16766/x2.png)

[Arxiv](https://arxiv.org/abs/2404.16766)