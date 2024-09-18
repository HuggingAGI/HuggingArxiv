# 利用构建的代码转换数据，提升 LLM 在多语言语音生成与识别方面的表现

发布时间：2024年09月17日

`LLM应用` `语音技术` `多语言处理`

> Enhancing Multilingual Speech Generation and Recognition Abilities in LLMs with Constructed Code-switched Data

# 摘要

> 尽管 LLM 在语音生成和识别任务中已有应用，但主要集中在单语场景，多语言和代码切换 (CS) 场景的探索较少。此外，这些任务通常分开处理，如 VALL-E 和 Qwen-Audio。本文提出多语言多任务 (MLMT) 模型，将多语言语音生成和识别任务集成于单一 LLM 中。我们还开发了一种数据构建方法，通过分割和连接不同语言的单词，使 LLM 无需 CS 数据即可具备 CS 合成能力。实验显示，我们的模型在同等数据规模下优于其他基线。此外，该方法不仅提升了 LLM 的 CS 语音合成能力，还增强了其在多语言语音生成和识别任务中的表现。

> While large language models (LLMs) have been explored in the speech domain for both generation and recognition tasks, their applications are predominantly confined to the monolingual scenario, with limited exploration in multilingual and code-switched (CS) contexts. Additionally, speech generation and recognition tasks are often handled separately, such as VALL-E and Qwen-Audio. In this paper, we propose a MutltiLingual MultiTask (MLMT) model, integrating multilingual speech generation and recognition tasks within the single LLM. Furthermore, we develop an effective data construction approach that splits and concatenates words from different languages to equip LLMs with CS synthesis ability without relying on CS data. The experimental results demonstrate that our model outperforms other baselines with a comparable data scale. Furthermore, our data construction approach not only equips LLMs with CS speech synthesis capability with comparable speaker consistency and similarity to any given speaker, but also improves the performance of LLMs in multilingual speech generation and recognition tasks.

[Arxiv](https://arxiv.org/abs/2409.10969)