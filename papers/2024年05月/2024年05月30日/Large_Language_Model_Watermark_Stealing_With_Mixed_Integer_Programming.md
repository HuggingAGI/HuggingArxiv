# 混合整数规划在大型语言模型中窃取水印的策略

发布时间：2024年05月30日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）水印技术的理论问题，包括其脆弱性和攻击方法。它不仅分析了现有水印技术的局限性，还提出了一种新的攻击方法，并对其进行了系统评估。这些内容更多地涉及LLM的理论层面，特别是关于安全性和防御机制的研究，而不是直接的应用或Agent行为。因此，将其归类为LLM理论是合适的。` `版权保护` `人工智能安全`

> Large Language Model Watermark Stealing With Mixed Integer Programming

# 摘要

> 大型语言模型（LLM）水印技术，作为一种新兴手段，展现出了解决版权争议、监控AI文本生成及防止滥用的潜力。该技术通过生成密钥将词汇划分为绿色与红色列表，并对绿色列表中的令牌进行概率提升的扰动，以便在绿色令牌比例超标时，识别出AI生成的文本。然而，研究表明，使用多密钥的水印方法易受攻击，如令牌修改、同义词替换及文本改写，且密钥越多，鲁棒性越低。因此，采用较少或单一密钥的先进水印方案，在抵御文本编辑和改写方面表现更佳。本文提出了一种针对最新LLM水印方案的绿色列表窃取攻击，并系统评估了其脆弱性。我们将此攻击定义为带有约束的混合整数编程问题，并在全面威胁模型下进行评估，包括攻击者无先验知识、无法接触水印检测API及对LLM参数或水印机制一无所知的极端情况。实验证明，我们的攻击能成功窃取绿色列表，并在所有情况下移除水印。

> The Large Language Model (LLM) watermark is a newly emerging technique that shows promise in addressing concerns surrounding LLM copyright, monitoring AI-generated text, and preventing its misuse. The LLM watermark scheme commonly includes generating secret keys to partition the vocabulary into green and red lists, applying a perturbation to the logits of tokens in the green list to increase their sampling likelihood, thus facilitating watermark detection to identify AI-generated text if the proportion of green tokens exceeds a threshold. However, recent research indicates that watermarking methods using numerous keys are susceptible to removal attacks, such as token editing, synonym substitution, and paraphrasing, with robustness declining as the number of keys increases. Therefore, the state-of-the-art watermark schemes that employ fewer or single keys have been demonstrated to be more robust against text editing and paraphrasing. In this paper, we propose a novel green list stealing attack against the state-of-the-art LLM watermark scheme and systematically examine its vulnerability to this attack. We formalize the attack as a mixed integer programming problem with constraints. We evaluate our attack under a comprehensive threat model, including an extreme scenario where the attacker has no prior knowledge, lacks access to the watermark detector API, and possesses no information about the LLM's parameter settings or watermark injection/detection scheme. Extensive experiments on LLMs, such as OPT and LLaMA, demonstrate that our attack can successfully steal the green list and remove the watermark across all settings.

[Arxiv](https://arxiv.org/abs/2405.19677)