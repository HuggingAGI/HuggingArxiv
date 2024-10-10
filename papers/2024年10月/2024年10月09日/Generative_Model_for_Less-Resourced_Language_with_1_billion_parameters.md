# 10亿参数助力低资源语言生成模型

发布时间：2024年10月09日

`LLM应用` `多语言技术`

> Generative Model for Less-Resourced Language with 1 billion parameters

# 摘要

> 大型语言模型（LLM）是现代自然语言处理的核心。尽管如 ChatGPT、Llama 等模型在英语领域表现出色，但在低资源语言上的表现却显得浅薄。为此，我们研发了针对斯洛文尼亚语的 GaMS 1B 生成模型，通过继续预训练英语 OPT 模型，并结合 FOCUS 和 WECHSEL 方法迁移嵌入，我们打造了一款适应斯洛文尼亚语、克罗地亚语和英语的新 tokenizer。在斯洛文尼亚语的分类和句子简化任务中，GaMS 模型展现了不俗的性能，尤其在句子简化任务上，其表现甚至超越了 GPT-3.5-Turbo。

> Large language models (LLMs) are a basic infrastructure for modern natural language processing. Many commercial and open-source LLMs exist for English, e.g., ChatGPT, Llama, Falcon, and Mistral. As these models are trained on mostly English texts, their fluency and knowledge of low-resource languages and societies are superficial. We present the development of large generative language models for a less-resourced language. GaMS 1B - Generative Model for Slovene with 1 billion parameters was created by continuing pretraining of the existing English OPT model. We developed a new tokenizer adapted to Slovene, Croatian, and English languages and used embedding initialization methods FOCUS and WECHSEL to transfer the embeddings from the English OPT model. We evaluate our models on several classification datasets from the Slovene suite of benchmarks and generative sentence simplification task SENTA. We only used a few-shot in-context learning of our models, which are not yet instruction-tuned. For classification tasks, in this mode, the generative models lag behind the existing Slovene BERT-type models fine-tuned for specific tasks. On a sentence simplification task, the GaMS models achieve comparable or better performance than the GPT-3.5-Turbo model.

[Arxiv](https://arxiv.org/abs/2410.06898)