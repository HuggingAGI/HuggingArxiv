# 聚焦温度，探究知识蒸馏下的推测解码

发布时间：2024年10月14日

`LLM理论` `人工智能`

> Temperature-Centric Investigation of Speculative Decoding with Knowledge Distillation

# 摘要

> 推测解码是加速自回归语言模型推理的关键技术。它通过小模型推测标记块，再由大模型评估。尽管研究众多，生成配置对解码的影响仍不明朗，尤其是温度。本文探讨了温度对推测解码的影响。从知识蒸馏入手，我们指出高温解码的挑战，并发现一致温度下的蒸馏可能有效。我们还研究了温度超出范围的域外测试集。基于此，我们迈出加速高温推测解码的第一步。研究发现，生成配置显著影响推测解码性能，强调需开发关注多样化配置的方法。代码已公开，详见https://github.com/ozyyshr/TempSpec。

> Speculative decoding stands as a pivotal technique to expedite inference in autoregressive (large) language models. This method employs a smaller draft model to speculate a block of tokens, which the target model then evaluates for acceptance. Despite a wealth of studies aimed at increasing the efficiency of speculative decoding, the influence of generation configurations on the decoding process remains poorly understood, especially concerning decoding temperatures. This paper delves into the effects of decoding temperatures on speculative decoding's efficacy. Beginning with knowledge distillation (KD), we first highlight the challenge of decoding at higher temperatures, and demonstrate KD in a consistent temperature setting could be a remedy. We also investigate the effects of out-of-domain testing sets with out-of-range temperatures. Building upon these findings, we take an initial step to further the speedup for speculative decoding, particularly in a high-temperature generation setting. Our work offers new insights into how generation configurations drastically affect the performance of speculative decoding, and underscores the need for developing methods that focus on diverse decoding configurations. Code is publically available at https://github.com/ozyyshr/TempSpec.

[Arxiv](https://arxiv.org/abs/2410.10141)