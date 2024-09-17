# 通过 $f$-divergence 最小化，我们将文本到图像生成的对齐范式与用户偏好相结合，实现更广泛的适用性。

发布时间：2024年09月15日

`LLM理论` `人工智能` `图像处理`

> Generalizing Alignment Paradigm of Text-to-Image Generation with Preferences through $f$-divergence Minimization

# 摘要

> 直接偏好优化 (DPO) 不仅成功对齐了大型语言模型 (LLM)，还将这一技术扩展到了文本到图像模型，与人类偏好对齐，引起了广泛关注。然而，现有方法仅依赖于反向 Kullback-Leibler 散度，忽略了其他散度约束。本研究将反向 Kullback-Leibler 散度扩展至 $f$-散度，旨在提升对齐性能和生成多样性。我们提供了 $f$-散度下的对齐范式广义公式，并从梯度场角度分析了不同散度约束的影响。实验表明，Jensen-Shannon 散度在图像文本对齐、人类价值对齐和生成多样性方面实现了最佳平衡。选择合适的散度对文本到图像模型的对齐至关重要，直接影响对齐性能与生成多样性之间的平衡。

> Direct Preference Optimization (DPO) has recently expanded its successful application from aligning large language models (LLMs) to aligning text-to-image models with human preferences, which has generated considerable interest within the community. However, we have observed that these approaches rely solely on minimizing the reverse Kullback-Leibler divergence during alignment process between the fine-tuned model and the reference model, neglecting the incorporation of other divergence constraints. In this study, we focus on extending reverse Kullback-Leibler divergence in the alignment paradigm of text-to-image models to $f$-divergence, which aims to garner better alignment performance as well as good generation diversity. We provide the generalized formula of the alignment paradigm under the $f$-divergence condition and thoroughly analyze the impact of different divergence constraints on alignment process from the perspective of gradient fields. We conduct comprehensive evaluation on image-text alignment performance, human value alignment performance and generation diversity performance under different divergence constraints, and the results indicate that alignment based on Jensen-Shannon divergence achieves the best trade-off among them. The option of divergence employed for aligning text-to-image models significantly impacts the trade-off between alignment performance (especially human value alignment) and generation diversity, which highlights the necessity of selecting an appropriate divergence for practical applications.

[Arxiv](https://arxiv.org/abs/2409.09774)