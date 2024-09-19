# 解码时尚：高效微调 LLM，实现图像引导的个性化服装推荐

发布时间：2024年09月18日

`LLM应用` `电子商务`

> Decoding Style: Efficient Fine-Tuning of LLMs for Image-Guided Outfit Recommendation with Preference

# 摘要

> 个性化服装推荐面临复杂挑战，需兼顾时尚兼容性与趋势意识。本文提出新框架，利用大型语言模型 (LLM) 的强大表达力，通过微调和直接反馈克服其“黑箱”与静态局限。我们采用多模态大型语言模型 (MLLM) 进行图像描述，弥合物品视觉与文本间的鸿沟，使 LLM 能从精选时尚图中提取风格与色彩，奠定个性化推荐基础。LLM 在开源 Polyvore 数据集上高效微调，提升推荐时尚装束能力。引入负例直接偏好机制，强化 LLM 决策，形成自我增强的 AI 反馈环，持续优化推荐以顺应时尚潮流。框架在 Polyvore 数据集上评估，展现其在填空与互补物品检索任务中的卓越成效。评估显示，框架能生成时尚且紧跟潮流的服装建议，通过直接反馈不断精进。结果表明，所提框架显著超越基础 LLM，打造更和谐服装。性能提升凸显框架通过精准建议提升购物体验的潜力，证实其优于传统基于 LLM 的服装生成。

> Personalized outfit recommendation remains a complex challenge, demanding both fashion compatibility understanding and trend awareness. This paper presents a novel framework that harnesses the expressive power of large language models (LLMs) for this task, mitigating their "black box" and static nature through fine-tuning and direct feedback integration. We bridge the item visual-textual gap in items descriptions by employing image captioning with a Multimodal Large Language Model (MLLM). This enables the LLM to extract style and color characteristics from human-curated fashion images, forming the basis for personalized recommendations. The LLM is efficiently fine-tuned on the open-source Polyvore dataset of curated fashion images, optimizing its ability to recommend stylish outfits. A direct preference mechanism using negative examples is employed to enhance the LLM's decision-making process. This creates a self-enhancing AI feedback loop that continuously refines recommendations in line with seasonal fashion trends. Our framework is evaluated on the Polyvore dataset, demonstrating its effectiveness in two key tasks: fill-in-the-blank, and complementary item retrieval. These evaluations underline the framework's ability to generate stylish, trend-aligned outfit suggestions, continuously improving through direct feedback. The evaluation results demonstrated that our proposed framework significantly outperforms the base LLM, creating more cohesive outfits. The improved performance in these tasks underscores the proposed framework's potential to enhance the shopping experience with accurate suggestions, proving its effectiveness over the vanilla LLM based outfit generation.

[Arxiv](https://arxiv.org/abs/2409.12150)