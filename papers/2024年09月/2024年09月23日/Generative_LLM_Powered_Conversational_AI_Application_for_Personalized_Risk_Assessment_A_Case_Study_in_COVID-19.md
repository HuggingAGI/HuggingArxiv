# 基于生成式 LLM 的个性化风险评估对话 AI：COVID-19 案例研究

发布时间：2024年09月23日

`LLM应用` `移动应用`

> Generative LLM Powered Conversational AI Application for Personalized Risk Assessment: A Case Study in COVID-19

# 摘要

> 大型语言模型 (LLM) 在自然语言任务中表现出色，并逐渐渗透到医疗领域。我们通过流式人机对话，开发了一种无需编程的 LLM 疾病风险评估新方法。在 COVID-19 风险评估案例中，我们用少量自然语言示例微调了 Llama2-7b 和 Flan-t5-xl 等预训练 LLM，并将其与传统分类器（如逻辑回归、XGBoost、随机森林）进行对比。我们还开发了一款移动应用，利用这些微调 LLM 实现实时互动和无代码风险评估，同时提供个性化特征分析，增强评估的可解释性。实验结果显示，即使在数据有限的情况下，生成 LLM 也能超越传统分类方法，显示出强大的适应性和有效性。这项研究旨在推动生成 LLM 在无代码风险评估中的应用，并激发该领域的进一步探索。

> Large language models (LLMs) have shown remarkable capabilities in various natural language tasks and are increasingly being applied in healthcare domains. This work demonstrates a new LLM-powered disease risk assessment approach via streaming human-AI conversation, eliminating the need for programming required by traditional machine learning approaches. In a COVID-19 severity risk assessment case study, we fine-tune pre-trained generative LLMs (e.g., Llama2-7b and Flan-t5-xl) using a few shots of natural language examples, comparing their performance with traditional classifiers (i.e., Logistic Regression, XGBoost, Random Forest) that are trained de novo using tabular data across various experimental settings. We develop a mobile application that uses these fine-tuned LLMs as its generative AI (GenAI) core to facilitate real-time interaction between clinicians and patients, providing no-code risk assessment through conversational interfaces. This integration not only allows for the use of streaming Questions and Answers (QA) as inputs but also offers personalized feature importance analysis derived from the LLM's attention layers, enhancing the interpretability of risk assessments. By achieving high Area Under the Curve (AUC) scores with a limited number of fine-tuning samples, our results demonstrate the potential of generative LLMs to outperform discriminative classification methods in low-data regimes, highlighting their real-world adaptability and effectiveness. This work aims to fill the existing gap in leveraging generative LLMs for interactive no-code risk assessment and to encourage further research in this emerging field.

[Arxiv](https://arxiv.org/abs/2409.15027)