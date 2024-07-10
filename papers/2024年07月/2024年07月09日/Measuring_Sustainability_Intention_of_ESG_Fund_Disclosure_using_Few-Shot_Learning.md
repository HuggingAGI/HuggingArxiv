# 通过 Few-Shot Learning 评估 ESG 基金披露的可持续性意图

发布时间：2024年07月09日

`LLM应用` `可持续发展`

> Measuring Sustainability Intention of ESG Fund Disclosure using Few-Shot Learning

# 摘要

> 全球可持续基金领域涵盖了声称专注于环境、社会和治理（ESG）的开放式基金和交易所交易基金（ETF）。然而，这些声明的真实性需通过文本披露的审查来验证。目前，ESG产品领域缺乏强制性的可持续性法规。本文提出了一种新颖的方法和系统，旨在通过分析招股说明书中的语言具体性和透明度，对可持续基金进行分类和评分。我们利用少量样本学习技术，识别与可持续投资相关的具体、模糊或通用语言，并构建比率指标来评分和评级，以量化可持续性声明并优化产品排名。此外，我们在Hugging Face上发布了超过1K的ESG文本声明的手动注释数据集，供研究使用。实验表明，少量样本微调技术在处理未见过的ESG语言时，性能显著优于零样本模型。本文旨在为可持续基金的可持续性意图提供一种量化评估的系统化方法，帮助监管机构、投资者和顾问更有效地筛选和评估ESG基金。

> Global sustainable fund universe encompasses open-end funds and exchange-traded funds (ETF) that, by prospectus or other regulatory filings, claim to focus on Environment, Social and Governance (ESG). Challengingly, the claims can only be confirmed by examining the textual disclosures to check if there is presence of intentionality and ESG focus on its investment strategy. Currently, there is no regulation to enforce sustainability in ESG products space. This paper proposes a unique method and system to classify and score the fund prospectuses in the sustainable universe regarding specificity and transparency of language. We aim to employ few-shot learners to identify specific, ambiguous, and generic sustainable investment-related language. Additionally, we construct a ratio metric to determine language score and rating to rank products and quantify sustainability claims for US sustainable universe. As a by-product, we publish manually annotated quality training dataset on Hugging Face (ESG-Prospectus-Clarity-Category under cc-by-nc-sa-4.0) of more than 1K ESG textual statements. The performance of the few-shot finetuning approach is compared with zero-shot models e.g., Llama-13B, GPT 3.5 Turbo etc. We found that prompting large language models are not accurate for domain specific tasks due to misalignment issues. The few-shot finetuning techniques outperform zero-shot models by large margins of more than absolute ~30% in precision, recall and F1 metrics on completely unseen ESG languages (test set). Overall, the paper attempts to establish a systematic and scalable approach to measure and rate sustainability intention quantitatively for sustainable funds using texts in prospectus. Regulatory bodies, investors, and advisors may utilize the findings of this research to reduce cognitive load in investigating or screening of ESG funds which accurately reflects the ESG intention.

[Arxiv](https://arxiv.org/abs/2407.06893)