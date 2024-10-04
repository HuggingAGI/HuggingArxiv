# 《更好的呼叫SAUL》：借助生成正则化，实现流畅且一致的语言模型编辑

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Better Call SAUL: Fluent and Consistent Language Model Editing with Generation Regularization

# 摘要

> 为了确保大型语言模型始终拥有最新知识，定期更新是必要的。然而，模型编辑面临挑战，因为可能会波及与新数据无关的知识。现有最先进的方法通过识别并直接修改特定知识相关的参数来实现编辑，但这些方法计算成本高且缺乏理论支持。直接微调模型以响应编辑请求，则可能影响无关知识，导致生成质量下降。为此，我们提出SAUL，一种利用句子连接和增强随机事实进行生成正则化的简化编辑方法。实验表明，SAUL不仅在模型编辑上超越现有技术，还能保持生成质量并降低计算负担，成为一种实用且可靠的解决方案。

> To ensure large language models contain up-to-date knowledge, they need to be updated regularly. However, model editing is challenging as it might also affect knowledge that is unrelated to the new data. State-of-the-art methods identify parameters associated with specific knowledge and then modify them via direct weight updates. However, these locate-and-edit methods suffer from heavy computational overhead and lack theoretical validation. In contrast, directly fine-tuning the model on requested edits affects the model's behavior on unrelated knowledge, and significantly damages the model's generation fluency and consistency. To address these challenges, we propose SAUL, a streamlined model editing method that uses sentence concatenation with augmented random facts for generation regularization. Evaluations on three model editing benchmarks show that SAUL is a practical and reliable solution for model editing outperforming state-of-the-art methods while maintaining generation quality and reducing computational overhead.

[Arxiv](https://arxiv.org/abs/2410.02433)