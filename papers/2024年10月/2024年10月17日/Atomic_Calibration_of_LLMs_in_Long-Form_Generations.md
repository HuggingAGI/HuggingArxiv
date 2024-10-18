# 长篇生成中 LLM 的原子校准

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Atomic Calibration of LLMs in Long-Form Generations

# 摘要

> 大型语言模型（LLM）常因幻觉问题而影响实际应用。置信度校准，即评估模型预测的不确定性，对提升 LLM 的可信度至关重要。现有研究多聚焦于短任务，提供单一的响应级置信分数（宏观校准）。然而，对于长文本生成，这种方法显得力不从心，因其内容复杂且可能混杂准确与不准确信息。为此，我们提出原子校准，通过将长文本分解为原子声明，实现细粒度的事实校准。我们将置信度引出方法分为判别型与生成型，并证明两者结合能有效提升校准效果。实验表明，原子校准不仅适用于长文本生成，还能优化宏观校准结果，并揭示 LLM 生成过程中置信度的变化模式。

> Large language models (LLMs) often suffer from hallucinations, posing significant challenges for real-world applications. Confidence calibration, which estimates the underlying uncertainty of model predictions, is essential to enhance the LLMs' trustworthiness. Existing research on LLM calibration has primarily focused on short-form tasks, providing a single confidence score at the response level (macro calibration). However, this approach is insufficient for long-form generations, where responses often contain more complex statements and may include both accurate and inaccurate information. Therefore, we introduce atomic calibration, a novel approach that evaluates factuality calibration at a fine-grained level by breaking down long responses into atomic claims. We classify confidence elicitation methods into discriminative and generative types and demonstrate that their combination can enhance calibration. Our extensive experiments on various LLMs and datasets show that atomic calibration is well-suited for long-form generation and can also improve macro calibration results. Additionally, atomic calibration reveals insightful patterns in LLM confidence throughout the generation process.

[Arxiv](https://arxiv.org/abs/2410.13246)