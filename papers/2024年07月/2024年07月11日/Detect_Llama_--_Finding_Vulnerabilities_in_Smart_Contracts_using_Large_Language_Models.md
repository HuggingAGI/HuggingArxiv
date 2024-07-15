# Detect Llama：利用大型语言模型，精准定位智能合约中的潜在漏洞。

发布时间：2024年07月11日

`LLM应用` `软件开发`

> Detect Llama -- Finding Vulnerabilities in Smart Contracts using Large Language Models

# 摘要

> 本文探讨了一个假设：尽管 OpenAI 的 GPT-4 表现不俗，但通过微调开源模型，我们能在智能合约漏洞检测上超越它。我们微调了 Meta 的 Code Llama 中的两个模型及一个 17k 提示的数据集，即 Detect Llama - Foundation 和 Detect Llama - Instruct，同时也微调了 OpenAI 的 GPT-3.5 Turbo 模型（GPT-3.5FT）。接着，我们评估了这些模型及一个随机基准模型，在我们开发的测试集上与 GPT-4 和 GPT-4 Turbo 的检测能力进行对比，涵盖八个漏洞及两个最常被识别的漏洞及其加权 F1 分数。结果显示，在二元分类（即，该智能合约是否存在漏洞？）中，GPT-3.5FT 和 Detect Llama - Foundation 分别以 $0.776$ 和 $0.68$ 的 F1 分数领先于 GPT-4 和 GPT-4 Turbo 的 $0.66$ 和 $0.675$。在单个漏洞识别的评估中，GPT-3.5FT 和 Detect Llama - Foundation 在所有漏洞的加权 F1 分数（分别为 $0.61$ 和 $0.56$，对比 GPT-4 的 $0.218$ 和 GPT-4 Turbo 的 $0.243$）及最常被识别的两个漏洞的加权 F1 分数（GPT-3.5FT 为 $0.719$，Detect Llama - Foundation 为 $0.674$，对比 GPT-4 的 $0.363$ 和 GPT-4 Turbo 的 $0.429$）方面均显著优于 GPT-4 和 GPT-4 Turbo。

> In this paper, we test the hypothesis that although OpenAI's GPT-4 performs well generally, we can fine-tune open-source models to outperform GPT-4 in smart contract vulnerability detection. We fine-tune two models from Meta's Code Llama and a dataset of 17k prompts, Detect Llama - Foundation and Detect Llama - Instruct, and we also fine-tune OpenAI's GPT-3.5 Turbo model (GPT-3.5FT). We then evaluate these models, plus a random baseline, on a testset we develop against GPT-4, and GPT-4 Turbo's, detection of eight vulnerabilities from the dataset and the two top identified vulnerabilities - and their weighted F1 scores.
  We find that for binary classification (i.e., is this smart contract vulnerable?), our two best-performing models, GPT-3.5FT and Detect Llama - Foundation, achieve F1 scores of $0.776$ and $0.68$, outperforming both GPT-4 and GPT-4 Turbo, $0.66$ and $0.675$. For the evaluation against individual vulnerability identification, our top two models, GPT-3.5FT and Detect Llama - Foundation, both significantly outperformed GPT-4 and GPT-4 Turbo in both weighted F1 for all vulnerabilities ($0.61$ and $0.56$ respectively against GPT-4's $0.218$ and GPT-4 Turbo's $0.243$) and weighted F1 for the top two identified vulnerabilities ($0.719$ for GPT-3.5FT, $0.674$ for Detect Llama - Foundation against GPT-4's $0.363$ and GPT-4 Turbo's $0.429$).

[Arxiv](https://arxiv.org/abs/2407.08969)