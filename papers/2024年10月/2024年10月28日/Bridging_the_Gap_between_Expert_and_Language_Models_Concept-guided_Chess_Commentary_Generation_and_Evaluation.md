# 填补专家与语言模型的鸿沟：概念引导的国际象棋评论生成及评估

发布时间：2024年10月28日

`LLM应用` `国际象棋` `决策领域`

> Bridging the Gap between Expert and Language Models: Concept-guided Chess Commentary Generation and Evaluation

# 摘要

> 深度学习专家模型在国际象棋和围棋等决策领域已展现出超越人类的表现。然而，尽管对给定决策进行解释或评论对于人类教育和模型可解释性意义重大，但相关研究尚显不足。专家模型输出精准，却难以被人类理解。另一方面，大型语言模型（LLMs）虽能生成流畅评论，却因决策能力有限而易产生幻觉。为填补专家模型与 LLMs 的鸿沟，我们以国际象棋评论为例，探讨如何通过语言阐释复杂决策过程，并着眼于评论的生成与评估。我们推出了概念引导的国际象棋评论生成（CCC）用于生成评论，以及基于 GPT 的国际象棋评论评估（GCC-Eval）用于评估。CCC 借助基于优先级的概念解释，融合了专家模型的决策优势和 LLMs 的语言流畅性。GCC-Eval 凭借专家知识，依据信息量和语言质量来评估国际象棋评论。经人类评委和 GCC-Eval 验证的实验结果显示，CCC 生成的评论准确、内容丰富且流畅。

> Deep learning-based expert models have reached superhuman performance in decision-making domains such as chess and Go. However, it is under-explored to explain or comment on given decisions although it is important for human education and model explainability. The outputs of expert models are accurate, but yet difficult to interpret for humans. On the other hand, large language models (LLMs) produce fluent commentary but are prone to hallucinations due to their limited decision-making capabilities. To bridge this gap between expert models and LLMs, we focus on chess commentary as a representative case of explaining complex decision-making processes through language and address both the generation and evaluation of commentary. We introduce Concept-guided Chess Commentary generation (CCC) for producing commentary and GPT-based Chess Commentary Evaluation (GCC-Eval) for assessing it. CCC integrates the decision-making strengths of expert models with the linguistic fluency of LLMs through prioritized, concept-based explanations. GCC-Eval leverages expert knowledge to evaluate chess commentary based on informativeness and linguistic quality. Experimental results, validated by both human judges and GCC-Eval, demonstrate that CCC generates commentary that is accurate, informative, and fluent.

[Arxiv](https://arxiv.org/abs/2410.20811)