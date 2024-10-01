# 利用语言模型，我们进行不确定性引导的筛选，以寻找合成钙钛矿时更安全的溶剂。

发布时间：2024年09月30日

`LLM应用` `材料科学`

> Uncertainty-Informed Screening for Safer Solvents Used in the Synthesis of Perovskite via Language Models

# 摘要

> 预测钙钛矿合成中工业溶剂的毒性至关重要，但受限于缺乏结构化毒性数据。本文提出了一种新框架，结合语言模型自动提取数据和不确定性引导的预测模型，填补数据空白并增强预测信心。首先，我们比较了两种数据提取方法：使用BERT和ELMo等小型双向模型因其稳定输出，而GPT-3.5等大型自回归模型则因其广泛训练数据和优质响应。我们创新的“提示与验证”技术与LLM结合，精准提取并优化数据，减少误差。随后，提取数据输入预训练的多任务深度学习模型，预测溶剂毒性。基于香农熵的不确定性量化方法，利用分类模型概率，量化预测不确定性并识别数据缺口。最终，我们整理出结构化的钙钛矿溶剂数据集，并进行不确定性引导的虚拟毒性评估。此外，和弦图展示溶剂相互作用，揭示70%的相互作用与两种特定钙钛矿密切相关，有助于优先处理潜在危害。

> The challenge of accurately predicting toxicity of industrial solvents used in perovskite synthesis is a necessary undertaking but is limited by a lack of a targeted and structured toxicity data. This paper presents a novel framework that combines an automated data extraction using language models, and an uncertainty-informed prediction model to fill data gaps and improve prediction confidence. First, we have utilized and compared two approaches to automatically extract relevant data from a corpus of scientific literature on solvents used in perovskite synthesis: smaller bidirectional language models like BERT and ELMo are used for their repeatability and deterministic outputs, while autoregressive large language model (LLM) such as GPT-3.5 is used to leverage its larger training corpus and better response generation. Our novel 'prompting and verification' technique integrated with an LLM aims at targeted extraction and refinement, thereby reducing hallucination and improving the quality of the extracted data using the LLM. Next, the extracted data is fed into our pre-trained multi-task binary classification deep learning to predict the ED nature of extracted solvents. We have used a Shannon entropy-based uncertainty quantification utilizing the class probabilities obtained from the classification model to quantify uncertainty and identify data gaps in our predictions. This approach leads to the curation of a structured dataset for solvents used in perovskite synthesis and their uncertainty-informed virtual toxicity assessment. Additionally, chord diagrams have been used to visualize solvent interactions and prioritize those with potential hazards, revealing that 70% of the solvent interactions were primarily associated with two specific perovskites.

[Arxiv](https://arxiv.org/abs/2409.20512)