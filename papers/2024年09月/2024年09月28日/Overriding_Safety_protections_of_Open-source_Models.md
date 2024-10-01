# 绕过开源模型的安全防护

发布时间：2024年09月28日

`LLM应用` `人工智能` `网络安全`

> Overriding Safety protections of Open-source Models

# 摘要

> 如今，大型语言模型（LLMs）被广泛用于解决各种领域和任务中的问题。然而，这些模型容易产生有害结果，因此需要进行安全对齐训练和红队测试以确保安全。在使用这些模型时，通常会进行微调以适应特定任务，但如果使用有害数据进行微调，可能会导致模型产生不安全响应。本文探讨了有害数据对微调的影响，以及它是否能覆盖模型的安全保护。同时，我们还研究了在安全数据上微调是否能增强模型的安全性。此外，我们分析了有害数据微调是否会导致模型不确定性增加，从而降低其有用性和可信度。实验结果显示，使用有害数据微调的开源模型，其安全保护措施会被削弱，ASR增加了35%。而有害数据微调的模型表现出高度不确定性、知识漂移和响应真实性下降。相比之下，安全数据微调的模型，ASR降低了51.68%，且在不确定性和真实性方面仅有轻微下降。本文代码已开源，详见：https://github.com/techsachinkr/Overriding_Model_Safety_Protections。

> LLMs(Large Language Models) nowadays have widespread adoption as a tool for solving issues across various domain/tasks. These models since are susceptible to produce harmful or toxic results, inference-time adversarial attacks, therefore they do undergo safety alignment training and Red teaming for putting in safety guardrails. For using these models, usually fine-tuning is done for model alignment on the desired tasks, which can make model more aligned but also make it more susceptible to produce unsafe responses, if fine-tuned with harmful data.In this paper, we study how much of impact introduction of harmful data in fine-tuning can make, and if it can override the safety protection of those models. Conversely,it was also explored that if model is fine-tuned on safety data can make the model produce more safer responses. Further we explore if fine-tuning the model on harmful data makes it less helpful or less trustworthy because of increase in model uncertainty leading to knowledge drift. Our extensive experimental results shown that Safety protection in an open-source can be overridden, when fine-tuned with harmful data as observed by ASR increasing by 35% when compared to basemodel's ASR. Also, as observed, fine-tuning a model with harmful data made the harmful fine-tuned model highly uncertain with huge knowledge drift and less truthfulness in its responses. Furthermore, for the safe fine-tuned model, ASR decreases by 51.68% as compared to the basemodel, and Safe model also shown in minor drop in uncertainty and truthfulness as compared to basemodel. This paper's code is available at: https://github.com/techsachinkr/Overriding_Model_Safety_Protections

[Arxiv](https://arxiv.org/abs/2409.19476)