# 为推荐系统量身定制的终身个性化低秩适应大型语言模型

发布时间：2024年08月07日

`LLM应用` `电子商务`

> Lifelong Personalized Low-Rank Adaptation of Large Language Models for Recommendation

# 摘要

> 我们专注于推荐领域的大型语言模型（LLM），这一领域近期备受关注，旨在提升推荐系统的逻辑推理和开放世界知识能力。当前方法主要通过定制输入模板或对齐语义与推荐空间，将个性化信息注入LLM。然而，存在三大限制：（1）LoRA虽为核心组件，但其参数未能充分个性化，影响性能。（2）终身个性化行为序列虽理想，但LLM需更多时间处理长文本，效率低下。（3）现有方法难以应对大数据集，LLM仅能接触部分数据。为此，我们提出RecLoRA，包含个性化LoRA模块和长-短模态检索器，提升性能且几乎不增加时间成本。同时，采用Few2Many学习策略，通过传统推荐模型放大训练空间。实验证明，RecLoRA优于现有模型。

> We primarily focus on the field of large language models (LLMs) for recommendation, which has been actively explored recently and poses a significant challenge in effectively enhancing recommender systems with logical reasoning abilities and open-world knowledge. Current mainstream efforts mainly center around injecting personalized information from recommendation models into LLMs by customizing input templates or aligning representations between semantic and recommendation spaces at the prediction layer. However, they face three significant limitations: (1) LoRA is mostly used as a core component in existing works, but personalization is not well established in LoRA parameters as the LoRA matrix shared by every user may not cater to different users' characteristics, leading to suboptimal performance. (2) Although lifelong personalized behavior sequences are ideal for personalization, their use raises effectiveness and efficiency issues since LLMs require escalating training and inference time to extend text lengths. (3) Existing approaches aren't scalable for large datasets due to training efficiency constraints. Thus, LLMs only see a small fraction of the datasets (e.g., less than 10%) instead of the whole datasets, limiting their exposure to the full training space. To address these problems, we propose RecLoRA. This model incorporates a Personalized LoRA module that maintains independent LoRAs for different users and a Long-Short Modality Retriever that retrieves different history lengths for different modalities, significantly improving performance while adding minimal time cost. Furthermore, we design a Few2Many Learning Strategy, using a conventional recommendation model as a lens to magnify small training spaces to full spaces. Extensive experiments on public datasets demonstrate the efficacy of our RecLoRA compared to existing baseline models.

[Arxiv](https://arxiv.org/abs/2408.03533)