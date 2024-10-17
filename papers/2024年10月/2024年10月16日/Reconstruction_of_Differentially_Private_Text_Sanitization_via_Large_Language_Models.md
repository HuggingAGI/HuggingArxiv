# 利用大型语言模型重建差分隐私文本净化

发布时间：2024年10月16日

`LLM理论` `网络安全` `隐私保护`

> Reconstruction of Differentially Private Text Sanitization via Large Language Models

# 摘要

> 差分隐私 (DP) 是抵御隐私泄露攻击的标准，但研究发现，大型语言模型 (LLM) 能从 DP 净化提示中重建被删除的隐私信息。我们提出了两种攻击方法（黑盒和白盒），展示了 LLM 如何通过样本文本对连接净化文本与私有训练数据。实验表明，现代 LLM 在词级和句子级 DP 上的恢复率令人担忧，如 LLaMA-2 和 Claude-3.5 的恢复率分别高达 72.18% 和 94.01%。这项研究警示，知名 LLM 已成为现有 DP 文本净化方法的新威胁。

> Differential privacy (DP) is the de facto privacy standard against privacy leakage attacks, including many recently discovered ones against large language models (LLMs). However, we discovered that LLMs could reconstruct the altered/removed privacy from given DP-sanitized prompts. We propose two attacks (black-box and white-box) based on the accessibility to LLMs and show that LLMs could connect the pair of DP-sanitized text and the corresponding private training data of LLMs by giving sample text pairs as instructions (in the black-box attacks) or fine-tuning data (in the white-box attacks). To illustrate our findings, we conduct comprehensive experiments on modern LLMs (e.g., LLaMA-2, LLaMA-3, ChatGPT-3.5, ChatGPT-4, ChatGPT-4o, Claude-3, Claude-3.5, OPT, GPT-Neo, GPT-J, Gemma-2, and Pythia) using commonly used datasets (such as WikiMIA, Pile-CC, and Pile-Wiki) against both word-level and sentence-level DP. The experimental results show promising recovery rates, e.g., the black-box attacks against the word-level DP over WikiMIA dataset gave 72.18% on LLaMA-2 (70B), 82.39% on LLaMA-3 (70B), 75.35% on Gemma-2, 91.2% on ChatGPT-4o, and 94.01% on Claude-3.5 (Sonnet). More urgently, this study indicates that these well-known LLMs have emerged as a new security risk for existing DP text sanitization approaches in the current environment.

[Arxiv](https://arxiv.org/abs/2410.12443)