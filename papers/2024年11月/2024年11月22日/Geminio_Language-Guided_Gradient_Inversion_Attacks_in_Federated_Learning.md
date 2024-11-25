# Geminio：联邦学习中的语言引导式梯度反转攻击

发布时间：2024年11月22日

`LLM应用` `联邦学习` `隐私攻击`

> Geminio: Language-Guided Gradient Inversion Attacks in Federated Learning

# 摘要

> 连接视觉与语言的基础模型进展显著，催生了众多丰富生活的应用。然而，其被滥用从而带来新威胁的潜在可能，在很大程度上尚未被探究。此文指出，在联邦学习（FL）中，视觉语言模型（VLMs）能被用以突破梯度反转攻击（GIAs）的长期局限，即 FL 服务器会依据受害客户端共享的梯度来重构私有数据样本。当下的 GIAs 在重构高分辨率图像时面临难题，尤其当受害者拥有大量本地数据批次时。虽说将重构重点置于有价值样本而非整个批次颇具前景，但现有方法欠缺灵活性，无法让攻击者指定目标数据。本文引入了 Geminio，这是首个将 GIAs 转化为具有语义意义的针对性攻击的方法。Geminio 带来了全新的隐私攻击体验：攻击者能用自然语言描述他们眼中有价值的数据类型，Geminio 会优先重构，聚焦于那些高价值样本。这是借助预训练的 VLM 来引导恶意全局模型的优化达成的，当与受害者共享并由其优化时，该模型仅保留与攻击者指定查询相匹配的样本梯度。大量实验表明，Geminio 在精准定位和重构目标样本方面成效显著，在 FL 下的复杂数据集和大批次规模中成功率颇高，且对现有防御手段具有抵御能力。

> Foundation models that bridge vision and language have made significant progress, inspiring numerous life-enriching applications. However, their potential for misuse to introduce new threats remains largely unexplored. This paper reveals that vision-language models (VLMs) can be exploited to overcome longstanding limitations in gradient inversion attacks (GIAs) within federated learning (FL), where an FL server reconstructs private data samples from gradients shared by victim clients. Current GIAs face challenges in reconstructing high-resolution images, especially when the victim has a large local data batch. While focusing reconstruction on valuable samples rather than the entire batch is promising, existing methods lack the flexibility to allow attackers to specify their target data. In this paper, we introduce Geminio, the first approach to transform GIAs into semantically meaningful, targeted attacks. Geminio enables a brand new privacy attack experience: attackers can describe, in natural language, the types of data they consider valuable, and Geminio will prioritize reconstruction to focus on those high-value samples. This is achieved by leveraging a pretrained VLM to guide the optimization of a malicious global model that, when shared with and optimized by a victim, retains only gradients of samples that match the attacker-specified query. Extensive experiments demonstrate Geminio's effectiveness in pinpointing and reconstructing targeted samples, with high success rates across complex datasets under FL and large batch sizes and showing resilience against existing defenses.

[Arxiv](https://arxiv.org/abs/2411.14937)