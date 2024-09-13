# AdaPPA：一种针对 LLM 的自适应位置预填充越狱攻击策略

发布时间：2024年09月10日

`LLM应用` `网络安全` `人工智能`

> AdaPPA: Adaptive Position Pre-Fill Jailbreak Attack Approach Targeting LLMs

# 摘要

> 大型语言模型 (LLM) 的越狱漏洞，即通过巧妙设计的提示或后缀提取恶意内容，已引起研究界的广泛关注。然而，传统语义层面的攻击方法容易被模型识破，且忽视了模型在不同输出阶段的对齐保护差异。为此，我们提出了一种自适应位置预填充的越狱攻击方法，先利用模型的指令跟随能力输出安全内容，再通过叙事转换生成有害内容。实验证明，与现有方法相比，我们的方法在广受认可的安全模型 (Llama2) 上可将攻击成功率提升47%。代码详见：https://github.com/Yummy416/AdaPPA。

> Jailbreak vulnerabilities in Large Language Models (LLMs) refer to methods that extract malicious content from the model by carefully crafting prompts or suffixes, which has garnered significant attention from the research community. However, traditional attack methods, which primarily focus on the semantic level, are easily detected by the model. These methods overlook the difference in the model's alignment protection capabilities at different output stages. To address this issue, we propose an adaptive position pre-fill jailbreak attack approach for executing jailbreak attacks on LLMs. Our method leverages the model's instruction-following capabilities to first output pre-filled safe content, then exploits its narrative-shifting abilities to generate harmful content. Extensive black-box experiments demonstrate our method can improve the attack success rate by 47% on the widely recognized secure model (Llama2) compared to existing approaches. Our code can be found at: https://github.com/Yummy416/AdaPPA.

[Arxiv](https://arxiv.org/abs/2409.07503)