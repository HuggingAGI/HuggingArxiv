# 在有限计算资源下，开发并双语评估日本医疗大型语言模型

发布时间：2024年09月18日

`LLM应用` `人工智能`

> Development and bilingual evaluation of Japanese medical large language model within reasonably low computational resources

# 摘要

> 近期，大型语言模型（LLM）的成功和规模法则推动了更大模型的普及。特别是在医疗领域，出于安全考虑，本地运行的 LLM 需求激增。然而，大多数优质开源 LLM 的参数高达 70B，给用户带来了沉重的 GPU 成本。为此，我们基于最新的 7B 模型开发了医疗适应方案，使其在低资源环境下也能高效运行。通过在日语和英语的医疗问答基准测试中，我们发现其性能与或超越了现有十倍参数的医疗 LLM。此外，对日语医疗数据集的微调显著提升了模型的双语表现，验证了跨语言知识转移的有效性。我们期待这项研究能为临床机构提供经济实惠的 LLM 解决方案，助力其在本地实际应用。评估代码已公开，详见 https://huggingface.co/stardust-coder/jmedllm-7b-v1。

> The recent success of large language models (LLMs) and the scaling law has led to a widespread adoption of larger models. Particularly in the healthcare industry, there is an increasing demand for locally operated LLMs due to security concerns. However, the majority of high quality open-source LLMs have a size of 70B parameters, imposing significant financial burdens on users for GPU preparation and operation. To overcome these issues, we present a medical adaptation based on the recent 7B models, which enables the operation in low computational resources. We compare the performance on medical question-answering benchmarks in two languages (Japanese and English), demonstrating that its scores reach parity with or surpass those of currently existing medical LLMs that are ten times larger. We find that fine-tuning an English-centric base model on Japanese medical dataset improves the score in both language, supporting the effect of cross-lingual knowledge transfer. We hope that this study will alleviate financial challenges, serving as a stepping stone for clinical institutions to practically utilize LLMs locally. Our evaluation code is available at https://huggingface.co/stardust-coder/jmedllm-7b-v1.

[Arxiv](https://arxiv.org/abs/2409.11783)