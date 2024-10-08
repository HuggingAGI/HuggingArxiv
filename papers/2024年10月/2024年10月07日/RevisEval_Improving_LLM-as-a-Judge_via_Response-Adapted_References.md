# RevisEval：通过自适应参考文献提升 LLM 作为评判者的表现

发布时间：2024年10月07日

`LLM应用` `文本生成`

> RevisEval: Improving LLM-as-a-Judge via Response-Adapted References

# 摘要

> 近年来，LLM-as-a-Judge 已成为评估文本生成质量的高效替代方案，但与人工评估相比，其可靠性仍有差距。主要原因在于评估过程中缺乏引导。借鉴经典文本评估中的参考文献，我们提出了 RevisEval，一种通过响应适应性参考的新评估范式。RevisEval 的核心在于，理想的参考文献应与待评估文本保持相关性。具体来说，RevisEval 利用 LLM 的修订能力，自适应地调整响应文本，并将其作为参考进行评估。实验证明，RevisEval 在 NLG 任务和开放式指令遵循任务中，优于传统的无参考和基于参考的评估方法。此外，响应适应性参考还能提升 BLEU 和 BERTScore 等经典指标，甚至与 LLM-as-a-Judge 相媲美。我们还详细分析了 RevisEval 在减少偏差、推理成本和参考相关性方面的有效性。

> With significant efforts in recent studies, LLM-as-a-Judge has become a cost-effective alternative to human evaluation for assessing the text generation quality in a wide range of tasks. However, there still remains a reliability gap between LLM-as-a-Judge and human evaluation. One important reason is the lack of guided oracles in the evaluation process. Motivated by the role of reference pervasively used in classic text evaluation, we introduce RevisEval, a novel text generation evaluation paradigm via the response-adapted references. RevisEval is driven by the key observation that an ideal reference should maintain the necessary relevance to the response to be evaluated. Specifically, RevisEval leverages the text revision capabilities of large language models (LLMs) to adaptively revise the response, then treat the revised text as the reference (response-adapted reference) for the subsequent evaluation. Extensive experiments demonstrate that RevisEval outperforms traditional reference-free and reference-based evaluation paradigms that use LLM-as-a-Judge across NLG tasks and open-ended instruction-following tasks. More importantly, our response-adapted references can further boost the classical text metrics, e.g., BLEU and BERTScore, compared to traditional references and even rival the LLM-as-a-Judge. A detailed analysis is also conducted to confirm RevisEval's effectiveness in bias reduction, the impact of inference cost, and reference relevance.

[Arxiv](https://arxiv.org/abs/2410.05193)