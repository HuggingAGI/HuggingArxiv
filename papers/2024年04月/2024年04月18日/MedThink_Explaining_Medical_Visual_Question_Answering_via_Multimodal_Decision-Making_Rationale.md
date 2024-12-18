# MedThink：揭示医学视觉问答背后的多模决策机制

发布时间：2024年04月18日

`分类：LLM应用` `人工智能`

> MedThink: Explaining Medical Visual Question Answering via Multimodal Decision-Making Rationale

# 摘要

> 医学视觉问答（MedVQA）是一项前沿的医疗任务，它通过语言回答来解析医学图像，极大提升了医疗诊断的速度和准确性。尽管如此，现有 MedVQA 系统的模型透明度和可解释性不足，这限制了对其决策机制的理解。为克服这一难题，我们引入了一种半自动化的标注流程，以优化数据准备，并开发了两个新的基准数据集：R-RAD 和 R-SLAKE。这两个数据集不仅包含了由多模态大型语言模型和人工标注生成的医学决策理由，还涵盖了现有 MedVQA 数据集（VQA-RAD 和 SLAKE）中的问题-答案对。此外，我们构建了一个创新框架，它通过整合医学决策理由来微调轻量级预训练生成模型。该框架采用三种策略来生成决策结果及其理由，清晰地揭示了推理过程中的医学决策流程。实验结果表明，我们的模型在 R-RAD 数据集上达到了 83.5% 的准确率，在 R-SLAKE 数据集上达到了 86.3% 的准确率，均显著超过了当前的最佳水平。相关数据集和代码将向公众开放。

> Medical Visual Question Answering (MedVQA), which offers language responses to image-based medical inquiries, represents a challenging task and significant advancement in healthcare. It assists medical experts to swiftly interpret medical images, thereby enabling faster and more accurate diagnoses. However, the model interpretability and transparency of existing MedVQA solutions are often limited, posing challenges in understanding their decision-making processes. To address this issue, we devise a semi-automated annotation process to streamlining data preparation and build new benchmark MedVQA datasets R-RAD and R-SLAKE. The R-RAD and R-SLAKE datasets provide intermediate medical decision-making rationales generated by multimodal large language models and human annotations for question-answering pairs in existing MedVQA datasets, i.e., VQA-RAD and SLAKE. Moreover, we design a novel framework which finetunes lightweight pretrained generative models by incorporating medical decision-making rationales into the training process. The framework includes three distinct strategies to generate decision outcomes and corresponding rationales, thereby clearly showcasing the medical decision-making process during reasoning. Extensive experiments demonstrate that our method can achieve an accuracy of 83.5% on R-RAD and 86.3% on R-SLAKE, significantly outperforming existing state-of-the-art baselines. Dataset and code will be released.

[Arxiv](https://arxiv.org/abs/2404.12372)