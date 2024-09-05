# SmileyLlama：调整大型语言模型，助力定向化学空间探索

发布时间：2024年09月03日

`LLM应用`

> SmileyLlama: Modifying Large Language Models for Directed Chemical Space Exploration

# 摘要

> 我们发现，大型语言模型 (LLM) 能够作为化学语言模型 (CLM) 的基础，其性能不逊于甚至超越仅基于化学 SMILES 数据训练的 CLM。借助开源 Llama LLM 上的监督微调 (SFT) 和直接偏好优化 (DPO)，我们成功训练 LLM 响应生成特定药物开发属性分子的提示。这一框架不仅让 LLM 成为化学和材料领域的聊天机器人，更使其直接转型为能按用户需求生成特定属性分子的 CLM。

> Here we show that a Large Language Model (LLM) can serve as a foundation model for a Chemical Language Model (CLM) which performs at or above the level of CLMs trained solely on chemical SMILES string data. Using supervised fine-tuning (SFT) and direct preference optimization (DPO) on the open-source Llama LLM, we demonstrate that we can train an LLM to respond to prompts such as generating molecules with properties of interest to drug development. This overall framework allows an LLM to not just be a chatbot client for chemistry and materials tasks, but can be adapted to speak more directly as a CLM which can generate molecules with user-specified properties.

[Arxiv](https://arxiv.org/abs/2409.02231)