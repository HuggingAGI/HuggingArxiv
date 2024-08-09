# 优化指令交互式翻译的协调性

发布时间：2024年08月08日

`LLM应用` `人工智能` `数据处理`

> Better Alignment with Instruction Back-and-Forth Translation

# 摘要

> 我们创新性地提出了“指令来回翻译”方法，旨在为大型语言模型（LLM）构建基于世界知识的高质量合成数据。通过利用网络语料库中的文档，我们采用Li等人（2023a）的回译技术生成并精选合成指令，并根据原始文档重写响应，以提升其质量。实验表明，使用这些（回译指令，重写响应）对进行微调，在AlpacaEval评测中胜率显著高于其他常见指令数据集。此外，我们发现LLM重写的响应在质量上超越了直接蒸馏方法，且两者在嵌入空间中的文本分布存在显著差异。深入分析进一步证实，我们的回译指令在质量上优于其他合成指令，而响应则更为多样化和复杂。总体而言，“指令来回翻译”方法巧妙融合了网络信息的多样性与数量，同时确保了响应的高质量，这对于实现有效的模型对齐至关重要。

> We propose a new method, instruction back-and-forth translation, to construct high-quality synthetic data grounded in world knowledge for aligning large language models (LLMs). Given documents from a web corpus, we generate and curate synthetic instructions using the backtranslation approach proposed by Li et al.(2023a), and rewrite the responses to improve their quality further based on the initial documents. Fine-tuning with the resulting (backtranslated instruction, rewritten response) pairs yields higher win rates on AlpacaEval than using other common instruction datasets such as Humpback, ShareGPT, Open Orca, Alpaca-GPT4 and Self-instruct. We also demonstrate that rewriting the responses with an LLM outperforms direct distillation, and the two generated text distributions exhibit significant distinction in embedding space. Further analysis shows that our backtranslated instructions are of higher quality than other sources of synthetic instructions, while our responses are more diverse and complex than those obtained from distillation. Overall we find that instruction back-and-forth translation combines the best of both worlds -- making use of the information diversity and quantity found on the web, while ensuring the quality of the responses which is necessary for effective alignment.

[Arxiv](https://arxiv.org/abs/2408.04614)