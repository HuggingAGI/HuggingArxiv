# 揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差

发布时间：2024年08月07日

`LLM理论` `人工智能` `网络安全`

> Decoding Biases: Automated Methods and LLM Judges for Gender Bias Detection in Language Models

# 摘要

> 尽管大型语言模型 (LLM) 在语言理解和文本生成方面表现卓越，但它们仍易受恶意用户的对抗性攻击，导致生成不希望的文本。此外，LLM 固有的偏见可能在交互中产生有害影响。由于偏见评估缺乏统一标准，现有方法依赖昂贵的人工模板和注释。为此，我们训练模型自动生成对抗性提示，以揭示目标 LLM 的偏见。我们提出基于 LLM 的偏见评估指标，并分析现有自动评估方法。通过深入分析模型响应的细微差别，我们识别了不同模型家族的优劣，并指出了评估方法的不足。最后，我们将这些指标与人类评估对比，验证了 LLM-as-a-Judge 指标在偏见判断上与人类一致。

> Large Language Models (LLMs) have excelled at language understanding and generating human-level text. However, even with supervised training and human alignment, these LLMs are susceptible to adversarial attacks where malicious users can prompt the model to generate undesirable text. LLMs also inherently encode potential biases that can cause various harmful effects during interactions. Bias evaluation metrics lack standards as well as consensus and existing methods often rely on human-generated templates and annotations which are expensive and labor intensive. In this work, we train models to automatically create adversarial prompts to elicit biased responses from target LLMs. We present LLM- based bias evaluation metrics and also analyze several existing automatic evaluation methods and metrics. We analyze the various nuances of model responses, identify the strengths and weaknesses of model families, and assess where evaluation methods fall short. We compare these metrics to human evaluation and validate that the LLM-as-a-Judge metric aligns with human judgement on bias in response generation.

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/bias.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/nobias.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/bias_detection_fig2.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/human_eval1.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/human_eval2.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/human_eval3.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_identity_attack_.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_insult.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_profanity.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_sentiment.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_toxicity_.png)

![揭秘偏见：自动化技术与 LLM 评判系统联手，精准检测语言模型中的性别偏差](../../../paper_images/2408.03907/combined_plot_llm_as_a_judge.png)

[Arxiv](https://arxiv.org/abs/2408.03907)