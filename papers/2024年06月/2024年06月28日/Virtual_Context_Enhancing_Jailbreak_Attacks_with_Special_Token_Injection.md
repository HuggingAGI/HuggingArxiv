# 虚拟上下文：利用特殊标记注入提升越狱攻击效果

发布时间：2024年06月28日

`LLM应用` `网络安全` `人工智能安全`

> Virtual Context: Enhancing Jailbreak Attacks with Special Token Injection

# 摘要

> 针对大型语言模型的越狱攻击，旨在诱导模型生成违法或不道德的内容，严重威胁模型安全。目前，这类攻击面临两大难题：防御措施导致成功率低下，以及制作特定攻击指令的高成本。本文提出的“虚拟上下文”技术，利用了以往在模型安全领域被忽视的特殊标记，有效提升了越狱攻击的效率。该技术不仅大幅提高了现有攻击手段的成功率，而且对目标模型的背景知识要求极低，使得在黑盒环境下也能高效运作，无需额外投入。实验表明，“虚拟上下文”能将四种主流越狱方法的成功率提升约40%，且在保持原有恶意行为的基础上，仍能产生显著的越狱效果。我们的研究强调了特殊标记在越狱攻击中的重要性，并建议将其纳入安全测试，以全面提升大型语言模型的安全性。

> Jailbreak attacks on large language models (LLMs) involve inducing these models to generate harmful content that violates ethics or laws, posing a significant threat to LLM security. Current jailbreak attacks face two main challenges: low success rates due to defensive measures and high resource requirements for crafting specific prompts. This paper introduces Virtual Context, which leverages special tokens, previously overlooked in LLM security, to improve jailbreak attacks. Virtual Context addresses these challenges by significantly increasing the success rates of existing jailbreak methods and requiring minimal background knowledge about the target model, thus enhancing effectiveness in black-box settings without additional overhead. Comprehensive evaluations show that Virtual Context-assisted jailbreak attacks can improve the success rates of four widely used jailbreak methods by approximately 40% across various LLMs. Additionally, applying Virtual Context to original malicious behaviors still achieves a notable jailbreak effect. In summary, our research highlights the potential of special tokens in jailbreak attacks and recommends including this threat in red-teaming testing to comprehensively enhance LLM security.

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x1.png)

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x2.png)

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x3.png)

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x4.png)

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x5.png)

![虚拟上下文：利用特殊标记注入提升越狱攻击效果](../../../paper_images/2406.19845/x6.png)

[Arxiv](https://arxiv.org/abs/2406.19845)