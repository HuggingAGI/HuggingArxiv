# NoVo：通过 LLM 中的注意力头规范投票，消除幻觉

发布时间：2024年10月11日

`LLM应用` `人工智能`

> NoVo: Norm Voting off Hallucinations with Attention Heads in Large Language Models

# 摘要

> 大型语言模型 (LLM) 中的幻觉问题在关键应用中尤为突出，尤其是在事实准确性至关重要的场景下。尽管表示编辑和阅读方法在减少幻觉方面有所进展，但它们依赖专用工具和领域内样本训练的特性，使其难以扩展且易过拟合，限制了其在多样化数据集上的表现。本文介绍了一种轻量级方法——Norm Voting (NoVo)，通过挖掘注意力头范数的潜力，显著提升零-shot 多项选择题 (MCQ) 的事实准确性。NoVo 首先利用仅 30 个随机样本的高效算法，自动筛选出与真实相关的头范数，轻松应对多样化数据集。随后，这些头范数通过简单投票算法，大幅提升预测准确性。在 TruthfulQA MC1 上，NoVo 以至少 19 个准确性点的优势，超越了现有最先进方法。NoVo 在 20 个多样化数据集上的泛化能力显著，超过 90% 的数据集表现优异，远超现有表示编辑和阅读方法。此外，NoVo 还为微调策略和文本对抗防御带来了新的希望。NoVo 在头范数上的成功应用，为 LLM 的可解释性、鲁棒性和可靠性开辟了新篇章。

> Hallucinations in Large Language Models (LLMs) remain a major obstacle, particularly in high-stakes applications where factual accuracy is critical. While representation editing and reading methods have made strides in reducing hallucinations, their heavy reliance on specialised tools and training on in-domain samples, makes them difficult to scale and prone to overfitting. This limits their accuracy gains and generalizability to diverse datasets. This paper presents a lightweight method, Norm Voting (NoVo), which harnesses the untapped potential of attention head norms to dramatically enhance factual accuracy in zero-shot multiple-choice questions (MCQs). NoVo begins by automatically selecting truth-correlated head norms with an efficient, inference-only algorithm using only 30 random samples, allowing NoVo to effortlessly scale to diverse datasets. Afterwards, selected head norms are employed in a simple voting algorithm, which yields significant gains in prediction accuracy. On TruthfulQA MC1, NoVo surpasses the current state-of-the-art and all previous methods by an astounding margin -- at least 19 accuracy points. NoVo demonstrates exceptional generalization to 20 diverse datasets, with significant gains in over 90\% of them, far exceeding all current representation editing and reading methods. NoVo also reveals promising gains to finetuning strategies and building textual adversarial defence. NoVo's effectiveness with head norms opens new frontiers in LLM interpretability, robustness and reliability.

[Arxiv](https://arxiv.org/abs/2410.08970)