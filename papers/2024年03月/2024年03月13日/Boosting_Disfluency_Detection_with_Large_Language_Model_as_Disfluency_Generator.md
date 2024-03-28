# 通过将大型语言模型用作不流畅生成器，我们能够显著提升对不流畅性的检测效果。这项研究旨在借助LLM的力量，探索其在模拟和识别语言表达中的不流畅性方面的潜力，从而改进不流畅检测技术。

发布时间：2024年03月13日

`LLM应用`

> Boosting Disfluency Detection with Large Language Model as Disfluency Generator

# 摘要

> 当前的不流畅检测技术高度依赖高昂且稀有的人工标注数据，针对此困境，部分研究尝试运用启发式或统计特征手段模拟生成不流畅句子，虽能在一定程度上提升检测效果，但此类句子往往偏离真实语境，制约了模型的整体优化。为此，本研究创新性地提出一种基于大型语言模型（LLM）的轻量级数据增强方案，利用LLM卓越的生成与语义理解能力，按特定提示生成贴近实际、多样化的不流畅句子作为扩充数据，且无需对LLM进行微调。此外，我们采用了一种考虑不确定性的数据筛选策略，以提升所生成句子的质量，并用这些高质量数据训练小规模检测模型以取得更好的表现。实验证明，借助少量经过LLM强化生成的数据，就能显著提升检测性能，进而极大增强了该方法的成本效益。

> Current disfluency detection methods heavily rely on costly and scarce human-annotated data. To tackle this issue, some approaches employ heuristic or statistical features to generate disfluent sentences, partially improving detection performance. However, these sentences often deviate from real-life scenarios, constraining overall model enhancement. In this study, we propose a lightweight data augmentation approach for disfluency detection, utilizing the superior generative and semantic understanding capabilities of large language model (LLM) to generate disfluent sentences as augmentation data. We leverage LLM to generate diverse and more realistic sentences guided by specific prompts, without the need for fine-tuning the LLM. Subsequently, we apply an uncertainty-aware data filtering approach to improve the quality of the generated sentences, utilized in training a small detection model for improved performance. Experiments using enhanced data yielded state-of-the-art results. The results showed that using a small amount of LLM-generated enhanced data can significantly improve performance, thereby further enhancing cost-effectiveness.

[Arxiv](https://arxiv.org/abs/2403.08229)