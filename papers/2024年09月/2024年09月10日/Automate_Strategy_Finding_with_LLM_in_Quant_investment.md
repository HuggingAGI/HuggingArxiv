# 利用 LLM 在量化投资中自动寻找策略

发布时间：2024年09月10日

`Agent` `量化投资`

> Automate Strategy Finding with LLM in Quant investment

# 摘要

> 尽管深度学习在金融交易领域取得了显著进展，但现有模型仍面临不稳定和高不确定性的挑战，限制了其实际应用。我们提出了一种结合大型语言模型（LLM）和多代理架构的新框架，用于量化股票投资和阿尔法挖掘。该框架通过集成LLM生成多样化的阿尔法，并利用多代理系统动态评估市场状况，解决了现有模型的不足。我们的框架首先从多模态金融数据中提取预测信号，然后通过集成学习构建多样化的交易代理池，最后利用动态权重机制根据实时市场条件优化策略。实验结果显示，该框架在中国股票市场上显著优于现有最先进模型，证明了LLM与多代理架构结合的有效性。这项研究不仅为量化投资策略提供了新的思路，也为金融交易中整合先进机器学习技术设定了新标准，具有广泛的应用前景。

> Despite significant progress in deep learning for financial trading, existing models often face instability and high uncertainty, hindering their practical application. Leveraging advancements in Large Language Models (LLMs) and multi-agent architectures, we propose a novel framework for quantitative stock investment in portfolio management and alpha mining. Our framework addresses these issues by integrating LLMs to generate diversified alphas and employing a multi-agent approach to dynamically evaluate market conditions. This paper proposes a framework where large language models (LLMs) mine alpha factors from multimodal financial data, ensuring a comprehensive understanding of market dynamics. The first module extracts predictive signals by integrating numerical data, research papers, and visual charts. The second module uses ensemble learning to construct a diverse pool of trading agents with varying risk preferences, enhancing strategy performance through a broader market analysis. In the third module, a dynamic weight-gating mechanism selects and assigns weights to the most relevant agents based on real-time market conditions, enabling the creation of an adaptive and context-aware composite alpha formula. Extensive experiments on the Chinese stock markets demonstrate that this framework significantly outperforms state-of-the-art baselines across multiple financial metrics. The results underscore the efficacy of combining LLM-generated alphas with a multi-agent architecture to achieve superior trading performance and stability. This work highlights the potential of AI-driven approaches in enhancing quantitative investment strategies and sets a new benchmark for integrating advanced machine learning techniques in financial trading can also be applied on diverse markets.

[Arxiv](https://arxiv.org/abs/2409.06289)