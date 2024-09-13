# EEG 语言建模助力病理检测

发布时间：2024年09月02日

`LLM应用` `脑科学`

> EEG-Language Modeling for Pathology Detection

# 摘要

> 多模态语言建模的最新突破，通过整合大型语言模型的优势，预训练出强大的多模态模型。预训练中融入自然语言显著提升了学习表示的质量，尤其在计算机视觉领域。然而，多模态语言建模在功能性脑数据，特别是病理检测方面的应用，仍是一片未被开垦的领域。本研究首次尝试基于临床报告和15000个EEG数据训练EEG-语言模型，并将多模态对齐技术引入这一新领域。我们探索了报告中哪些文本信息对模型训练最有帮助。结果显示，模型通过接触多样化的报告内容，如患者病史、EEG描述和医生解读，能学到更丰富的表示。与仅接触有限临床文本的模型相比，这些模型在根据报告检索EEG时准确率显著提高，但前提是采用对比学习方法。特别是在注释稀缺的情况下，EEG-语言模型在病理检测上的表现远超仅依赖EEG的模型，这在零样本分类和线性探测中得到了验证。综上所述，这些发现揭示了脑活动数据与临床文本结合的巨大潜力，预示着EEG-语言模型在临床应用中的重要突破。

> Multimodal language modeling constitutes a recent breakthrough which leverages advances in large language models to pretrain capable multimodal models. The integration of natural language during pretraining has been shown to significantly improve learned representations, particularly in computer vision. However, the efficacy of multimodal language modeling in the realm of functional brain data, specifically for advancing pathology detection, remains unexplored. This study pioneers EEG-language models trained on clinical reports and 15000 EEGs. We extend methods for multimodal alignment to this novel domain and investigate which textual information in reports is useful for training EEG-language models. Our results indicate that models learn richer representations from being exposed to a variety of report segments, including the patient's clinical history, description of the EEG, and the physician's interpretation. Compared to models exposed to narrower clinical text information, we find such models to retrieve EEGs based on clinical reports (and vice versa) with substantially higher accuracy. Yet, this is only observed when using a contrastive learning approach. Particularly in regimes with few annotations, we observe that representations of EEG-language models can significantly improve pathology detection compared to those of EEG-only models, as demonstrated by both zero-shot classification and linear probes. In sum, these results highlight the potential of integrating brain activity data with clinical text, suggesting that EEG-language models represent significant progress for clinical applications.

[Arxiv](https://arxiv.org/abs/2409.07480)