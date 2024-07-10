# OffsetBias：借助去偏数据优化评估器调整

发布时间：2024年07月09日

`LLM应用` `人工智能` `数据科学`

> OffsetBias: Leveraging Debiased Data for Tuning Evaluators

# 摘要

> 利用 LLM 评估生成内容的质量，如通过提示调整模型或微调评判模型，已成为主流评估手段。然而，这些评估工具易受偏见影响，比如偏爱长篇大论。尽管解决这一问题至关重要，但偏见的具体表现仍待深入探究。本研究中，我们识别了六类判断模型中的固有偏见，并创建了 EvalBiasBench 作为针对这些偏见的定制测试集。同时，我们提出了去偏数据集构建法及配套的 OffsetBias 偏好集。实验显示，基于我们的数据集进行微调能大幅提升评判模型的抗偏见能力，并优化其在多场景下的表现。我们已将相关数据集和微调模型公开。

> Employing Large Language Models (LLMs) to assess the quality of generated responses, such as prompting instruct-tuned models or fine-tuning judge models, has become a widely adopted evaluation method. It is also known that such evaluators are vulnerable to biases, such as favoring longer responses. While it is important to overcome this problem, the specifics of these biases remain under-explored. In this work, we qualitatively identify six types of biases inherent in various judge models. We propose EvalBiasBench as a meta-evaluation collection of hand-crafted test cases for each bias type. Additionally, we present de-biasing dataset construction methods and the associated preference dataset OffsetBias. Experimental results demonstrate that fine-tuning on our dataset significantly enhances the robustness of judge models against biases and improves performance across most evaluation scenarios. We release our datasets and the fine-tuned judge model to public.

[Arxiv](https://arxiv.org/abs/2407.06551)