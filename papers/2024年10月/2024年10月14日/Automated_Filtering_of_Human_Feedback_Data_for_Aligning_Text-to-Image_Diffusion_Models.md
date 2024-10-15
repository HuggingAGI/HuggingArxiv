# 自动化筛选人类反馈数据，优化文本到图像扩散模型的对齐效果

发布时间：2024年10月14日

`LLM应用` `人工智能` `图像生成`

> Automated Filtering of Human Feedback Data for Aligning Text-to-Image Diffusion Models

# 摘要

> 通过人类反馈微调文本到图像扩散模型，能有效使模型行为与人类意图对齐。然而，由于反馈数据集庞大且嘈杂，这一过程常因收敛缓慢而受阻。为此，我们推出了FiFA，一种自动数据过滤算法，通过直接偏好优化（DPO）提升模型微调效果。该算法通过优化问题，精选数据以最大化偏好边际、文本质量和多样性。偏好边际帮助识别高信息价值样本，应对数据噪声；文本质量由大型语言模型把关，防止有害内容；多样性则通过k近邻熵估计提升泛化能力。最终，所有要素融入优化过程，自动筛选重要数据，无需人工介入，适用于任何大规模数据集。实验显示，FiFA不仅大幅提升训练稳定性和性能，还使人类偏好度提升17%，同时节省了99%的GPU时间。

> Fine-tuning text-to-image diffusion models with human feedback is an effective method for aligning model behavior with human intentions. However, this alignment process often suffers from slow convergence due to the large size and noise present in human feedback datasets. In this work, we propose FiFA, a novel automated data filtering algorithm designed to enhance the fine-tuning of diffusion models using human feedback datasets with direct preference optimization (DPO). Specifically, our approach selects data by solving an optimization problem to maximize three components: preference margin, text quality, and text diversity. The concept of preference margin is used to identify samples that contain high informational value to address the noisy nature of feedback dataset, which is calculated using a proxy reward model. Additionally, we incorporate text quality, assessed by large language models to prevent harmful contents, and consider text diversity through a k-nearest neighbor entropy estimator to improve generalization. Finally, we integrate all these components into an optimization process, with approximating the solution by assigning importance score to each data pair and selecting the most important ones. As a result, our method efficiently filters data automatically, without the need for manual intervention, and can be applied to any large-scale dataset. Experimental results show that FiFA significantly enhances training stability and achieves better performance, being preferred by humans 17% more, while using less than 0.5% of the full data and thus 1% of the GPU hours compared to utilizing full human feedback datasets.

[Arxiv](https://arxiv.org/abs/2410.10166)