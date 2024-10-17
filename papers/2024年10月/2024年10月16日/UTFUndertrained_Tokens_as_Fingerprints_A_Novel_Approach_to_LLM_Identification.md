# UTF: 利用未充分训练的 Token 作为指纹，开创了一种识别 LLM 的新途径。

发布时间：2024年10月16日

`LLM应用` `身份验证`

> UTF:Undertrained Tokens as Fingerprints A Novel Approach to LLM Identification

# 摘要

> 指纹识别 LLM 对于验证所有权、确保真实性和防止滥用至关重要。传统方法通常需要大量计算或白盒访问。本文介绍的 UTF 方法，通过利用未充分训练的标记，实现高效指纹识别。我们通过监督微调，将特定输入-输出对嵌入模型，使其在特定输入下生成预定输出，从而嵌入唯一指纹。UTF 方法对模型性能影响小，无需白盒访问，且在微调和随机猜测中表现更优。

> Fingerprinting large language models (LLMs) is essential for verifying model ownership, ensuring authenticity, and preventing misuse. Traditional fingerprinting methods often require significant computational overhead or white-box verification access. In this paper, we introduce UTF, a novel and efficient approach to fingerprinting LLMs by leveraging under-trained tokens. Under-trained tokens are tokens that the model has not fully learned during its training phase. By utilizing these tokens, we perform supervised fine-tuning to embed specific input-output pairs into the model. This process allows the LLM to produce predetermined outputs when presented with certain inputs, effectively embedding a unique fingerprint. Our method has minimal overhead and impact on model's performance, and does not require white-box access to target model's ownership identification. Compared to existing fingerprinting methods, UTF is also more effective and robust to fine-tuning and random guess.

[Arxiv](https://arxiv.org/abs/2410.12318)