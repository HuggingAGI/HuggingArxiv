# 语言模型能够自行延展从而生成长文本

发布时间：2024年10月31日

`LLM应用` `模型训练`

> Language Models can Self-Lengthen to Generate Long Texts

# 摘要

> 近期，大型语言模型（LLMs）的发展显著提升了其处理长上下文的能力，然而在生成长且连贯的输出方面，仍存在明显差距。这一局限源于训练的不足，预训练缺少长文本生成的有效指引，而训练后的数据主要是短的查询-响应对。当下的诸如指令回译和行为模仿等方法，面临着数据质量、版权问题以及专有模型使用受限等挑战。在本文中，我们推出了一个创新的迭代训练框架，名为 Self-Lengthen，它仅依靠 LLMs 自身的知识和技能，无需辅助数据或专有模型。该框架包含两个角色：生成器和扩展器。生成器生成初始响应，随后由扩展器进行拆分和拓展。这一过程会产生新的、更长的响应，用于对生成器和扩展器进行迭代训练。通过这一过程，模型逐步被训练以应对越来越长的响应。在针对基准的实验和人工评估中显示，当应用于顶级开源 LLMs 如 Qwen2 和 LLaMA3 时，Self-Lengthen 在长文本生成方面优于现有的方法。我们的代码在 https://github.com/QwenLM/Self-Lengthen 公开可用。

> Recent advancements in Large Language Models (LLMs) have significantly enhanced their ability to process long contexts, yet a notable gap remains in generating long, aligned outputs. This limitation stems from a training gap where pre-training lacks effective instructions for long-text generation, and post-training data primarily consists of short query-response pairs. Current approaches, such as instruction backtranslation and behavior imitation, face challenges including data quality, copyright issues, and constraints on proprietary model usage. In this paper, we introduce an innovative iterative training framework called Self-Lengthen that leverages only the intrinsic knowledge and skills of LLMs without the need for auxiliary data or proprietary models. The framework consists of two roles: the Generator and the Extender. The Generator produces the initial response, which is then split and expanded by the Extender. This process results in a new, longer response, which is used to train both the Generator and the Extender iteratively. Through this process, the models are progressively trained to handle increasingly longer responses. Experiments on benchmarks and human evaluations show that Self-Lengthen outperforms existing methods in long-text generation, when applied to top open-source LLMs such as Qwen2 and LLaMA3. Our code is publicly available at https://github.com/QwenLM/Self-Lengthen.

[Arxiv](https://arxiv.org/abs/2410.23933)