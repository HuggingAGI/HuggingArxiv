# GEMeX：一个用于胸部 X 光诊断的大规模、具备可接地性和可解释性的医学 VQA 基准

发布时间：2024年11月25日

`LLM应用` `计算机视觉`

> GEMeX: A Large-Scale, Groundable, and Explainable Medical VQA Benchmark for Chest X-ray Diagnosis

# 摘要

> 医疗视觉问答（VQA）是融合计算机视觉与自然语言处理的关键技术，能自动回应有关医学影像的临床问询。但当下的医疗 VQA 数据集有两大明显局限：其一，答案往往缺少视觉和文本阐释，难以满足患者及初级医生的理解需求；其二，所提供的问题格式通常较单一，无法充分体现临床场景中的多元需求。这些局限给可靠且用户友好的 Med-VQA 系统的开发带来重大挑战。为应对这些挑战，我们推出用于胸部 X 光诊断的大规模、可落地且可解释的医疗 VQA 基准（GEMeX），包含若干创新部分：其一，多模态解释机制，为每个问答对提供详尽的视觉和文本解释，增强答案的可理解性；其二，四种不同的问题类型，即开放式、封闭式、单选题和多选题，更能反映多样的临床需要。我们在 GEMeX 上评估了 10 个有代表性的大型视觉语言模型，发现它们表现欠佳，凸显了数据集的复杂性。不过，用训练集对基线模型进行微调后，我们看到性能显著提升，表明了数据集的有效性。该项目可在 www.med-vqa.com/GEMeX 访问。

> Medical Visual Question Answering (VQA) is an essential technology that integrates computer vision and natural language processing to automatically respond to clinical inquiries about medical images. However, current medical VQA datasets exhibit two significant limitations: (1) they often lack visual and textual explanations for answers, which impedes their ability to satisfy the comprehension needs of patients and junior doctors; (2) they typically offer a narrow range of question formats, inadequately reflecting the diverse requirements encountered in clinical scenarios. These limitations pose significant challenges to the development of a reliable and user-friendly Med-VQA system. To address these challenges, we introduce a large-scale, Groundable, and Explainable Medical VQA benchmark for chest X-ray diagnosis (GEMeX), featuring several innovative components: (1) A multi-modal explainability mechanism that offers detailed visual and textual explanations for each question-answer pair, thereby enhancing answer comprehensibility; (2) Four distinct question types, open-ended, closed-ended, single-choice, and multiple-choice, that better reflect diverse clinical needs. We evaluated 10 representative large vision language models on GEMeX and found that they underperformed, highlighting the dataset's complexity. However, after fine-tuning a baseline model using the training set, we observed a significant performance improvement, demonstrating the dataset's effectiveness. The project is available at www.med-vqa.com/GEMeX.

[Arxiv](https://arxiv.org/abs/2411.16778)