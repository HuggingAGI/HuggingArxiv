# 通过优化思维树上的偏好，我们校准 LLM，以在科学问题评分中生成更合理的解释。

发布时间：2024年06月28日

`LLM应用` `人工智能`

> Calibrating LLMs with Preference Optimization on Thought Trees for Generating Rationale in Science Question Scoring

# 摘要

> 为了提升自动化评分系统的可解释性，我们提出了一种新框架，该框架不仅能生成更真实合理的理由，还能与基于分类器的评分系统媲美。我们通过模拟人类评估过程，利用大型语言模型生成思维树，并从中提炼出合成理由和偏好数据。通过监督微调和偏好优化两步训练，我们的框架在QWK评分上比以往提升了38%，并产出更受认可的高质量理由。这一成果展示了合成偏好数据在优化评估中的潜力。

> Generating rationales that justify scoring decisions has been a promising way to facilitate explainability in automated scoring systems. However, existing methods do not match the accuracy of classifier-based methods. Plus, the generated rationales often contain hallucinated information. To address these issues, we propose a novel framework capable of generating more faithful rationales and, more importantly, matching performance with classifier-based black-box scoring systems. We first mimic the human assessment process by querying Large Language Models (LLMs) to generate a thought tree. We then summarise intermediate assessment decisions from each thought tree path for creating synthetic rationale data and rationale preference data. Finally, we utilise the generated synthetic data to calibrate LLMs through a two-step training process: supervised fine-tuning and preference optimization. Extensive experimental results demonstrate that our framework achieves a 38% assessment performance improvement in the QWK score compared to prior work while producing higher-quality rationales, as recognised by human evaluators and LLMs. Our work sheds light on the effectiveness of performing preference optimization using synthetic preference data obtained from thought tree paths.

[Arxiv](https://arxiv.org/abs/2406.19949)