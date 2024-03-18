# [Masked Thought 研究表明，简单地对部分推理步骤进行遮蔽处理，就能有效增强语言模型在数学推理学习上的表现。]

发布时间：2024年03月04日

`LLM应用`

> Masked Thought: Simply Masking Partial Reasoning Steps Can Improve Mathematical Reasoning Learning of Language Models

> 面对推理任务，大型语言模型极易因细微误差产生连锁反应，导致性能欠佳。早先的研究尝试通过精细的人工标注、更大规模模型或自我采样等方式进行微调以改善这一状况，但成本较高。而我们另辟蹊径，提出一种无需外部资源的新方法，即对输入数据实施扰动处理。具体来说，我们在“思考链”中随机掩盖部分标记，此法在推理任务中成效显著。应用到GSM8K数据集的微调阶段，仅通过少许代码调整及零额外标注投入，就取得了比传统监督微调高出5%的精度提升。不仅如此，该方法还能与现存数据增强技术良好互补，在涵盖多种规模与质量的五个数据集以及两种基础模型上，GSM8K的精度平均提高3%，MATH的精度提高1%。我们进一步通过案例分析和量化评估揭示了这一改进背后的运作机制，提示本方法在帮助模型更好地捕获远距离依赖关系，尤其是涉及问题本质的部分，具有独特优势。此项增强有望深化模型对问题前设及前期步骤的理解。目前，我们的代码已发布在Github平台上。

> In reasoning tasks, even a minor error can cascade into inaccurate results, leading to suboptimal performance of large language models in such domains. Earlier fine-tuning approaches sought to mitigate this by leveraging more precise supervisory signals from human labeling, larger models, or self-sampling, although at a high cost. Conversely, we develop a method that avoids external resources, relying instead on introducing perturbations to the input. Our training approach randomly masks certain tokens within the chain of thought, a technique we found to be particularly effective for reasoning tasks. When applied to fine-tuning with GSM8K, this method achieved a 5% improvement in accuracy over standard supervised fine-tuning with a few codes modified and no additional labeling effort. Furthermore, it is complementary to existing methods. When integrated with related data augmentation methods, it leads to an average improvement of 3% improvement in GSM8K accuracy and 1% improvement in MATH accuracy across five datasets of various quality and size, as well as two base models. We further investigate the mechanisms behind this improvement through case studies and quantitative analysis, suggesting that our approach may provide superior support for the model in capturing long-distance dependencies, especially those related to questions. This enhancement could deepen understanding of premises in questions and prior steps. Our code is available at Github.

[Arxiv](https://arxiv.org/abs/2403.02178)