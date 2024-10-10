# 根防御策略：保障 LLM 在解码层面的安全

发布时间：2024年10月09日

`LLM应用` `人工智能` `网络安全`

> Root Defence Strategies: Ensuring Safety of LLM at the Decoding Level

# 摘要

> 大型语言模型 (LLM) 在各行业展现了巨大潜力，但随着其发展，不正确或恶意的指令提示增加了有害输出的风险。现有方法虽能应对越狱风险，但存在两大局限：一是预填充级别的有害响应判断缺乏对解码输出的利用，导致效果和鲁棒性不足；二是基于单一评估拒绝潜在有害响应，严重削弱了模型的实用性。本文深入探讨了 LLM 识别有害输出的能力，量化了其评估先前令牌危险性的水平。基于试点实验，我们设计了在解码级别的强大防御机制，通过逐步防御架构直接纠正有害查询，而非简单拒绝。引入推测性解码，既提升了可用性，又加速了安全解码的部署。实验证明，我们的方法在不减慢推理速度的前提下，显著提升了模型安全性。尤为重要的是，我们的方法充分发挥了模型辨别危险信息的能力，相比现有方法，更能保持其有用性。

> Large language models (LLMs) have demonstrated immense utility across various industries. However, as LLMs advance, the risk of harmful outputs increases due to incorrect or malicious instruction prompts. While current methods effectively address jailbreak risks, they share common limitations: 1) Judging harmful responses from the prefill-level lacks utilization of the model's decoding outputs, leading to relatively lower effectiveness and robustness. 2) Rejecting potentially harmful responses based on a single evaluation can significantly impair the model's helpfulness.This paper examines the LLMs' capability to recognize harmful outputs, revealing and quantifying their proficiency in assessing the danger of previous tokens. Motivated by pilot experiment results, we design a robust defense mechanism at the decoding level. Our novel decoder-oriented, step-by-step defense architecture corrects harmful queries directly rather than rejecting them outright. We introduce speculative decoding to enhance usability and facilitate deployment to boost secure decoding speed. Extensive experiments demonstrate that our approach improves model security without compromising reasoning speed. Notably, our method leverages the model's ability to discern hazardous information, maintaining its helpfulness compared to existing methods.

[Arxiv](https://arxiv.org/abs/2410.06809)