# NIFTY财经新闻头条数据集解释：在

发布时间：2024年05月15日

`LLM应用

这篇论文介绍了NIFTY金融新闻标题数据集，该数据集旨在支持金融市场预测研究，特别是通过大型语言模型（LLMs）的应用。论文详细描述了数据集的设计，包括两个版本以适应不同的建模策略，并强调了其在股票价格预测等任务中的应用潜力。此外，论文还提到了数据集及其相关工具的公开可用性。这些内容表明，该论文主要关注于LLM在特定应用场景（即金融市场预测）中的实际应用，因此属于“LLM应用”分类。`

> NIFTY Financial News Headlines Dataset

# 摘要

> 我们推出了NIFTY金融新闻标题数据集，旨在助力金融市场预测研究，尤其是利用大型语言模型（LLMs）。该数据集分为两个版本，分别适用于不同的建模策略：NIFTY-LM专为LLMs的监督微调设计，采用自回归因果语言模型；而NIFTY-RL则针对对齐方法，如人类反馈强化学习，通过拒绝采样和奖励模型来调整LLMs。每个版本都提供了精心筛选的数据，包含详尽的元数据、市场指数和去重的新闻标题，以满足现代LLM框架的需求。此外，我们还展示了数据集在股票价格预测等任务中的应用，并探讨了LLM嵌入在信息获取方面的潜力。NIFTY数据集及其相关工具，如上下文长度的系统截断，已在Hugging Face上公开，网址为https://huggingface.co/datasets/raeidsaqur/NIFTY。

> We introduce and make publicly available the NIFTY Financial News Headlines dataset, designed to facilitate and advance research in financial market forecasting using large language models (LLMs). This dataset comprises two distinct versions tailored for different modeling approaches: (i) NIFTY-LM, which targets supervised fine-tuning (SFT) of LLMs with an auto-regressive, causal language-modeling objective, and (ii) NIFTY-RL, formatted specifically for alignment methods (like reinforcement learning from human feedback (RLHF)) to align LLMs via rejection sampling and reward modeling. Each dataset version provides curated, high-quality data incorporating comprehensive metadata, market indices, and deduplicated financial news headlines systematically filtered and ranked to suit modern LLM frameworks. We also include experiments demonstrating some applications of the dataset in tasks like stock price movement and the role of LLM embeddings in information acquisition/richness. The NIFTY dataset along with utilities (like truncating prompt's context length systematically) are available on Hugging Face at https://huggingface.co/datasets/raeidsaqur/NIFTY.

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/x1.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/x2.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/x3.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/small_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/medium_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/large_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/location_vs_IG.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/InformationGain.drawio.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/finance_vs_IG.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/location_vs_IG.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/Genre_vs_IG.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/small_finance.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/small_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/small_genre.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/medium_finance.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/medium_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/medium_genre.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/large_finance.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/large_location.png)

![NIFTY财经新闻头条数据集解释：在](../../../paper_images/2405.09747/large_genre.png)

[Arxiv](https://arxiv.org/abs/2405.09747)