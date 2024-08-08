# 基于逻辑谬误的论证生成框架

发布时间：2024年08月07日

`LLM理论`

> A Logical Fallacy-Informed Framework for Argument Generation

# 摘要

> 尽管 LLM 表现卓越，但在生成逻辑合理的论点上仍显不足，可能引发错误信息传播等风险。关键问题在于 LLM 对逻辑谬误的忽视。为此，我们推出 FIPO 框架，通过偏好优化引导 LLM 避免逻辑谬误。FIPO 通过分类损失细化谬误识别。实验表明，FIPO 使谬误减少 17.5%，且人类评估显示，其生成的论点质量远超传统方法。这凸显了模型识别逻辑谬误的重要性，以提升论点生成的有效性。

> Despite the remarkable performance of Large Language Models (LLMs), they still struggle with generating logically sound arguments, resulting in potential risks such as spreading misinformation. An important factor contributing to LLMs' suboptimal performance in generating coherent arguments is their oversight of logical fallacies. To address this issue, we introduce FIPO, a fallacy-informed framework that leverages preference optimization methods to steer LLMs toward logically sound arguments. FIPO includes a classification loss, to capture the fine-grained information on fallacy categories. Our results on argumentation datasets show that our method reduces the fallacy errors by up to 17.5%. Furthermore, our human evaluation results indicate that the quality of the generated arguments by our method significantly outperforms the fine-tuned baselines, as well as prior preference optimization methods, such as DPO. These findings highlight the importance of ensuring models are aware of logical fallacies for effective argument generation.

[Arxiv](https://arxiv.org/abs/2408.03618)