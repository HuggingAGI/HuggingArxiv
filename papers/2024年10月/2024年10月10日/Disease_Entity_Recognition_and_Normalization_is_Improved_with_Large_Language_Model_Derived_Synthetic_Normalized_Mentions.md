# 借助大型语言模型生成的合成规范化提及，疾病实体的识别与规范化得到了显著提升。

发布时间：2024年10月10日

`LLM应用` `人工智能`

> Disease Entity Recognition and Normalization is Improved with Large Language Model Derived Synthetic Normalized Mentions

# 摘要

> 背景：临床命名实体识别和规范化系统可利用标注语料库和知识图谱进行学习。然而，不常见概念在训练语料库中提及少，且在大型知识图谱中缺乏详细描述或同义词。这导致疾病实体识别和规范化任务的高质量训练示例较少。大型语言模型生成合成训练示例可提升这些任务的性能。方法：我们微调 LLaMa-2 13B Chat LLM，生成包含 UMLS 疾病语义组概念规范化提及的合成语料库。我们评估了 DER 和 DEN 的整体和分布外性能，无论是否使用合成数据增强。使用 4 种策略评估 3 个疾病语料库的性能，分别用 BioBERT、SapBERT 和 KrissBERT 评估 DER 和 DEN。结果：合成数据显著提升了 DEN，所有训练语料库中 SapBERT 和 KrissBERT 的总体准确率提高 3-9 分，OOD 数据提高 20-55 分。DER 总体性能小幅提升 1-2 分，仅一个数据集显示 OOD 改善。结论：LLM 生成的规范化疾病提及可提升 DEN，消融研究显示性能提升部分归因于 OOD 性能改善。该方法对 DER 的改进有限。我们公开发布了软件和数据集。

> Background: Machine learning methods for clinical named entity recognition and entity normalization systems can utilize both labeled corpora and Knowledge Graphs (KGs) for learning. However, infrequently occurring concepts may have few mentions in training corpora and lack detailed descriptions or synonyms, even in large KGs. For Disease Entity Recognition (DER) and Disease Entity Normalization (DEN), this can result in fewer high quality training examples relative to the number of known diseases. Large Language Model (LLM) generation of synthetic training examples could improve performance in these information extraction tasks.
  Methods: We fine-tuned a LLaMa-2 13B Chat LLM to generate a synthetic corpus containing normalized mentions of concepts from the Unified Medical Language System (UMLS) Disease Semantic Group. We measured overall and Out of Distribution (OOD) performance for DER and DEN, with and without synthetic data augmentation. We evaluated performance on 3 different disease corpora using 4 different data augmentation strategies, assessed using BioBERT for DER and SapBERT and KrissBERT for DEN.
  Results: Our synthetic data yielded a substantial improvement for DEN, in all 3 training corpora the top 1 accuracy of both SapBERT and KrissBERT improved by 3-9 points in overall performance and by 20-55 points in OOD data. A small improvement (1-2 points) was also seen for DER in overall performance, but only one dataset showed OOD improvement.
  Conclusion: LLM generation of normalized disease mentions can improve DEN relative to normalization approaches that do not utilize LLMs to augment data with synthetic mentions. Ablation studies indicate that performance gains for DEN were only partially attributable to improvements in OOD performance. The same approach has only a limited ability to improve DER. We make our software and dataset publicly available.

[Arxiv](https://arxiv.org/abs/2410.07951)