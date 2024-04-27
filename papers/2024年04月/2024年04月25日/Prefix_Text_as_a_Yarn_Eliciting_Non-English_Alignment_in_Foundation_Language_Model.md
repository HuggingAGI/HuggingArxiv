# 将前缀文本视作引线：在基础语言模型中激发非英语的对应关系

发布时间：2024年04月25日

`LLM应用` `机器翻译`

> Prefix Text as a Yarn: Eliciting Non-English Alignment in Foundation Language Model

# 摘要

> 有监督的微调（SFT）虽然一直是定制大型语言模型（LLM）输出以满足特定需求的直接方式，但其对齐深度却受到质疑，有批评声音认为这种对齐不过是“表面功夫”。本文针对跨语言生成任务，对这一假设进行了深入探讨，并指出SFT的有效性可能受限于其对先前标记的依赖，这些标记用于指导跨语言生成。针对SFT面临的非英语数据获取成本高昂和资源有限的挑战，我们提出了一种创新的无需训练的对齐方法——PreTTY。PreTTY利用极少的任务相关先前标记，将基础LLM与SFT LLM相连接，无需训练即可达到相似的性能。在八种语言的机器翻译和词性标注实验中，证明了PreTTY在跨语言环境中的有效性。令人瞩目的是，基础LLM仅需一两个先前标记启动解码过程，就能达到与SFT版本相媲美的性能。这一方法不仅为SFT提供了一种经济高效的替代方案，也促进了多语言LLM的普及。

> While supervised fine-tuning (SFT) has been a straightforward approach for tailoring the output of foundation large language model (LLM) to specific preferences, concerns have been raised about the depth of this alignment, with some critiques suggesting it is merely "superficial". We critically examine this hypothesis within the scope of cross-lingual generation tasks, proposing that the effectiveness of SFT may be constrained by its reliance on prior tokens to guide cross-lingual generation. Based on this crucial insight, and in response to the challenges posed by the costly and limited availability of non-English data for SFT, we introduce a novel training-free alignment method named PreTTY, which employs minimal task-related prior tokens to bridge the foundation LLM and the SFT LLM, achieving comparable performance without training. Experiments on machine translation and part-of-speech tagging across eight languages demonstrate the efficacy of PreTTY in cross-lingual settings. Remarkably, by initiating the decoding process with only one or two prior tokens, foundation LLMs can achieve performance comparable to their SFT counterparts. This method presents a cost-effective alternative to SFT and advances the democratization of multilingual LLMs.

![将前缀文本视作引线：在基础语言模型中激发非英语的对应关系](../../../paper_images/2404.16766/x1.png)

![将前缀文本视作引线：在基础语言模型中激发非英语的对应关系](../../../paper_images/2404.16766/x2.png)

[Arxiv](https://arxiv.org/abs/2404.16766)