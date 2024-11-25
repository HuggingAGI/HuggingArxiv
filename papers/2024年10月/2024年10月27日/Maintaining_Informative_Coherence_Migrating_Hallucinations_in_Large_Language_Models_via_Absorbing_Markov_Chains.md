# 保持信息的连贯性：利用吸收马尔可夫链来迁移大型语言模型中的幻觉

发布时间：2024年10月27日

`LLM应用` `信息传播`

> Maintaining Informative Coherence: Migrating Hallucinations in Large Language Models via Absorbing Markov Chains

# 摘要

> 大型语言模型（LLMs）堪称文本生成、翻译与总结的得力工具，然而它们时常产生幻觉，即在解码时难以维持上下文信息的保真度与连贯性，有时会因采样策略以及训练数据和微调差异带来的固有偏差而忽略关键细节。这些幻觉可能在网络中蔓延，影响网上传播信息的可信度。为应对此问题，我们提出了一种新颖的解码策略，借助吸收马尔可夫链来量化上下文信息的重要性，并衡量生成过程中的信息丢失程度。通过考量从首到尾标记的所有可能路径，我们的方法无需额外训练或外部数据，就能增强模型输出的可靠性。对 TruthfulQA、FACTOR 和 HaluEval 等数据集的评估凸显了我们的方法在减轻幻觉方面的卓越表现，也突显了在基于网络的应用中确保准确信息流的必要性。

> Large Language Models (LLMs) are powerful tools for text generation, translation, and summarization, but they often suffer from hallucinations-instances where they fail to maintain the fidelity and coherence of contextual information during decoding, sometimes overlooking critical details due to their sampling strategies and inherent biases from training data and fine-tuning discrepancies. These hallucinations can propagate through the web, affecting the trustworthiness of information disseminated online. To address this issue, we propose a novel decoding strategy that leverages absorbing Markov chains to quantify the significance of contextual information and measure the extent of information loss during generation. By considering all possible paths from the first to the last token, our approach enhances the reliability of model outputs without requiring additional training or external data. Evaluations on datasets including TruthfulQA, FACTOR, and HaluEval highlight the superior performance of our method in mitigating hallucinations, underscoring the necessity of ensuring accurate information flow in web-based applications.

[Arxiv](https://arxiv.org/abs/2410.20340)