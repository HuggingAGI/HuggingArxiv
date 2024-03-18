# 针对主题模型的成员身份推断攻击及其对隐私保护的影响

发布时间：2024年03月07日

`LLM理论`

> Membership Inference Attacks and Privacy in Topic Modeling

> 近期研究表明，大型语言模型面临可泄露训练数据信息的隐私攻击风险，而类似主题模型这样的简单生成模型是否具有相同隐患尚不明确。本研究创新性地提出了一种针对潜在狄利克雷分配主题模型的攻击手段，可以精准定位训练数据中的个体成员。这一发现提示我们，生成模型的隐私风险问题并非仅限于大型神经网络模型。为了解决此类安全漏洞，我们深入研究了差分隐私（DP）在主题建模上的应用，并设计了一种融合DP词汇选择预处理步骤的私有主题建模框架。实验结果显示，该框架在有效提升隐私保护水平的同时，对模型实用性能的影响相对较小。

> Recent research shows that large language models are susceptible to privacy attacks that infer aspects of the training data. However, it is unclear if simpler generative models, like topic models, share similar vulnerabilities. In this work, we propose an attack against topic models that can confidently identify members of the training data in Latent Dirichlet Allocation. Our results suggest that the privacy risks associated with generative modeling are not restricted to large neural models. Additionally, to mitigate these vulnerabilities, we explore differentially private (DP) topic modeling. We propose a framework for private topic modeling that incorporates DP vocabulary selection as a pre-processing step, and show that it improves privacy while having limited effects on practical utility.

[Arxiv](https://arxiv.org/abs/2403.04451)