# CoT 还是不 CoT？思维链主要在数学和符号推理中发挥作用。

发布时间：2024年09月18日

`LLM理论` `人工智能`

> To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic reasoning

# 摘要

> Chain-of-thought (CoT) 通过提示是引出 LLM 推理能力的主流方法。但这种“思考”对哪些任务真正有效？我们通过元分析 100 多篇论文并评估 14 个模型中的 20 个数据集，发现 CoT 主要在数学或逻辑任务上表现出色，而在其他任务上收益有限。在 MMLU 上，直接生成答案与使用 CoT 的准确性几乎相同，除非涉及符号操作。我们进一步分析发现，CoT 主要通过改进符号执行提升性能，但不如符号求解器。因此，CoT 应选择性应用以节省成本，并需探索超越提示的新范式，以更好地利用 LLM 的中间计算能力。

> Chain-of-thought (CoT) via prompting is the de facto method for eliciting reasoning capabilities from large language models (LLMs). But for what kinds of tasks is this extra ``thinking'' really helpful? To analyze this, we conducted a quantitative meta-analysis covering over 100 papers using CoT and ran our own evaluations of 20 datasets across 14 models. Our results show that CoT gives strong performance benefits primarily on tasks involving math or logic, with much smaller gains on other types of tasks. On MMLU, directly generating the answer without CoT leads to almost identical accuracy as CoT unless the question or model's response contains an equals sign, indicating symbolic operations and reasoning. Following this finding, we analyze the behavior of CoT on these problems by separating planning and execution and comparing against tool-augmented LLMs. Much of CoT's gain comes from improving symbolic execution, but it underperforms relative to using a symbolic solver. Our results indicate that CoT can be applied selectively, maintaining performance while saving inference costs. Furthermore, they suggest a need to move beyond prompt-based CoT to new paradigms that better leverage intermediate computation across the whole range of LLM applications.

[Arxiv](https://arxiv.org/abs/2409.12183)