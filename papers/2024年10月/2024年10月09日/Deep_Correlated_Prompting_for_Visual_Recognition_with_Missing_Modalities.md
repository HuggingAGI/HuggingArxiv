# 深度相关提示助力视觉识别，即使模态缺失也能应对自如。

发布时间：2024年10月09日

`LLM应用` `人工智能` `数据隐私`

> Deep Correlated Prompting for Visual Recognition with Missing Modalities

# 摘要

> 大规模多模态模型凭借丰富的配对训练数据，在多项任务中表现卓越。然而，现实中的隐私和数据收集难题，常导致模型在处理缺失模态时性能下滑。为此，我们引入提示学习，将不同缺失情况视为独特输入，使预训练模型灵活应对。我们不仅简单添加提示，更深入挖掘提示与特征间的关联，精心设计指令。同时，融合各模态的互补语义，优化提示策略。实验证明，我们的方法在多种缺失场景下均优于传统方法，消融实验进一步验证了其广泛适用性和可靠性。

> Large-scale multimodal models have shown excellent performance over a series of tasks powered by the large corpus of paired multimodal training data. Generally, they are always assumed to receive modality-complete inputs. However, this simple assumption may not always hold in the real world due to privacy constraints or collection difficulty, where models pretrained on modality-complete data easily demonstrate degraded performance on missing-modality cases. To handle this issue, we refer to prompt learning to adapt large pretrained multimodal models to handle missing-modality scenarios by regarding different missing cases as different types of input. Instead of only prepending independent prompts to the intermediate layers, we present to leverage the correlations between prompts and input features and excavate the relationships between different layers of prompts to carefully design the instructions. We also incorporate the complementary semantics of different modalities to guide the prompting design for each modality. Extensive experiments on three commonly-used datasets consistently demonstrate the superiority of our method compared to the previous approaches upon different missing scenarios. Plentiful ablations are further given to show the generalizability and reliability of our method upon different modality-missing ratios and types.

[Arxiv](https://arxiv.org/abs/2410.06558)