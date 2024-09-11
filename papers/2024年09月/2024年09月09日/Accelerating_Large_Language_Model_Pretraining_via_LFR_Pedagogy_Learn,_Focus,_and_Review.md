# 利用 LFR 教学法加速 LLM 预训练：学习、专注、复习

发布时间：2024年09月09日

`LLM理论` `人工智能`

> Accelerating Large Language Model Pretraining via LFR Pedagogy: Learn, Focus, and Review

# 摘要

> 传统上，LLM 的预训练依赖于从海量数据集中随机抽取数据块的自回归建模。借鉴人类学习中的间隔重复技巧，我们提出假设：随机数据采样导致高昂的训练成本和易遗忘的低质量模型。为此，我们创新性地提出了 LFR（学习、聚焦、回顾）教学法，一种动态训练新模式，根据模型的学习进度，系统性地间隔聚焦并反复回顾复杂数据块。LFR 通过记录各数据块的困惑度，频繁重温高困惑度块，有效防止遗忘。我们在 OpenWebText 数据集上，使用 LFR 对 GPT-2 模型（124M - 1.5B）进行预训练，并在语言建模、问答、翻译和问题解决等下游任务中测试，结果显示，LFR 不仅显著降低了困惑度，提高了准确性，还实现了 20 倍的预训练速度提升，超越了基准 OpenAI 模型。

> Large Language Model (LLM) pretraining traditionally relies on autoregressive language modeling on randomly sampled data blocks from web-scale datasets. We take inspiration from human learning techniques like spaced repetition to hypothesize that random data sampling for LLMs leads to high training cost and low quality models which tend to forget data. In order to effectively commit web-scale information to long-term memory, we propose the LFR (Learn, Focus, and Review) pedagogy, a new dynamic training paradigm which focuses and repeatedly reviews complex data blocks at systematic intervals based on the model's learning pace and progress. LFR records the model perplexities for different data blocks and frequently revisits blocks with higher perplexity which are more likely to be forgotten. We pretrain the GPT-2 models (124M - 1.5B) from scratch on the OpenWebText dataset using LFR. We test on downstream tasks from the language modeling, question answering, translation, and problem solving domains to achieve consistently lower perplexity and higher accuracy than the baseline OpenAI models, while obtaining a 20x pretraining speed-up.

[Arxiv](https://arxiv.org/abs/2409.06131)