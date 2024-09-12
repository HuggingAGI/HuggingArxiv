# 通过错误信息洞察 LLM 中的知识漂移

发布时间：2024年09月11日

`LLM理论` `人工智能` `信息安全`

> Understanding Knowledge Drift in LLMs through Misinformation

# 摘要

> LLM 在数字生态中的应用广泛，但其可靠性在面对错误信息时尤为关键。我们研究发现，最先进的 LLM 在 QnA 场景中遇到虚假信息时，容易出现事实错误，导致 *知识漂移*，严重损害模型可信度。通过熵、困惑度和标记概率等指标，我们评估了模型响应的不确定性，发现错误回答时，不确定性可飙升至 56.6%。而反复接触相同错误信息，不确定性又会下降 52.8%，可能改变模型信念，偏离原始知识。这些发现揭示了 LLM 的鲁棒性与脆弱性，为开发更可靠的 LLM 应用提供了方向。代码已公开，详见 https://github.com/afastowski/knowledge_drift。

> Large Language Models (LLMs) have revolutionized numerous applications, making them an integral part of our digital ecosystem. However, their reliability becomes critical, especially when these models are exposed to misinformation. We primarily analyze the susceptibility of state-of-the-art LLMs to factual inaccuracies when they encounter false information in a QnA scenario, an issue that can lead to a phenomenon we refer to as *knowledge drift*, which significantly undermines the trustworthiness of these models. We evaluate the factuality and the uncertainty of the models' responses relying on Entropy, Perplexity, and Token Probability metrics. Our experiments reveal that an LLM's uncertainty can increase up to 56.6% when the question is answered incorrectly due to the exposure to false information. At the same time, repeated exposure to the same false information can decrease the models uncertainty again (-52.8% w.r.t. the answers on the untainted prompts), potentially manipulating the underlying model's beliefs and introducing a drift from its original knowledge. These findings provide insights into LLMs' robustness and vulnerability to adversarial inputs, paving the way for developing more reliable LLM applications across various domains. The code is available at https://github.com/afastowski/knowledge_drift.

[Arxiv](https://arxiv.org/abs/2409.07085)