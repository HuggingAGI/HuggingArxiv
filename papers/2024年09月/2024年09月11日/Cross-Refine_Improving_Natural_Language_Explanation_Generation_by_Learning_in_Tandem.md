# 交叉精炼：通过协同学习提升自然语言解释生成的效果

发布时间：2024年09月11日

`LLM应用` `人工智能`

> Cross-Refine: Improving Natural Language Explanation Generation by Learning in Tandem

# 摘要

> 自然语言解释 (NLEs) 对于揭示大型语言模型 (LLM) 决策的推理至关重要。尽管已有多种技术用于生成 NLEs，但 LLMs 有时难以一次生成最佳解释，正如人类学习一样。为此，我们提出了 Cross-Refine 方法，通过两个 LLMs 分别扮演生成器和批评者的角色，生成初始解释并根据批评者的反馈进行改进。Cross-Refine 无需额外训练数据，我们通过三个 NLP 任务的自动和人工评估验证了其有效性。结果显示，Cross-Refine 优于仅依赖自我反馈的 Self-Refine 方法，尤其在较弱的 LLMs 上表现更为显著。此外，消融研究表明，反馈和建议在解释改进中至关重要。最后，我们在英德双语数据集上进一步验证了 Cross-Refine 的性能。

> Natural language explanations (NLEs) are vital for elucidating the reasoning behind large language model (LLM) decisions. Many techniques have been developed to generate NLEs using LLMs. However, like humans, LLMs might not always produce optimal NLEs on first attempt. Inspired by human learning processes, we introduce Cross-Refine, which employs role modeling by deploying two LLMs as generator and critic, respectively. The generator outputs a first NLE and then refines this initial explanation using feedback and suggestions provided by the critic. Cross-Refine does not require any supervised training data or additional training. We validate Cross-Refine across three NLP tasks using three state-of-the-art open-source LLMs through automatic and human evaluation. We select Self-Refine (Madaan et al., 2023) as the baseline, which only utilizes self-feedback to refine the explanations. Our findings from automatic evaluation and a user study indicate that Cross-Refine outperforms Self-Refine. Meanwhile, Cross-Refine can perform effectively with less powerful LLMs, whereas Self-Refine only yields strong results with ChatGPT. Additionally, we conduct an ablation study to assess the importance of feedback and suggestions. Both of them play an important role in refining explanations. We further evaluate Cross-Refine on a bilingual dataset in English and German.

[Arxiv](https://arxiv.org/abs/2409.07123)