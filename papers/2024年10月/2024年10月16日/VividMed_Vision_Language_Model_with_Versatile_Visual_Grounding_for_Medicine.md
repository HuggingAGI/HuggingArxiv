# VividMed：一款专为医学领域设计的多功能视觉语言模型，具备强大的视觉基础能力。

发布时间：2024年10月16日

`LLM应用` `计算机视觉`

> VividMed: Vision Language Model with Versatile Visual Grounding for Medicine

# 摘要

> 视觉语言模型 (VLM) 在生成视觉基础响应方面取得了显著进展，但在医疗领域的应用面临独特挑战。例如，大多数 VLM 依赖单一视觉基础方法，而复杂的医疗任务需要更多样化的解决方案。此外，大多数 VLM 仅处理 2D 图像，而医疗图像多为 3D。缺乏医疗数据进一步加剧了这些难题。为此，我们推出了 VividMed，一种专为医疗设计的多样化视觉语言模型。VividMed 不仅能生成语义分割掩码和实例级边界框，还支持 2D 和 3D 数据。我们设计了三阶段训练流程和自动数据合成管道，以应对这些挑战。VividMed 不仅在视觉基础任务中表现优异，还在视觉问答 (VQA) 和报告生成等下游任务中表现出色。消融研究证实，视觉基础能力的整合显著提升了这些任务的性能。我们的代码已公开在 https://github.com/function2-llx/MMMM。

> Recent advancements in Vision Language Models (VLMs) have demonstrated remarkable promise in generating visually grounded responses. However, their application in the medical domain is hindered by unique challenges. For instance, most VLMs rely on a single method of visual grounding, whereas complex medical tasks demand more versatile approaches. Additionally, while most VLMs process only 2D images, a large portion of medical images are 3D. The lack of medical data further compounds these obstacles. To address these challenges, we present VividMed, a vision language model with versatile visual grounding for medicine. Our model supports generating both semantic segmentation masks and instance-level bounding boxes, and accommodates various imaging modalities, including both 2D and 3D data. We design a three-stage training procedure and an automatic data synthesis pipeline based on open datasets and models. Besides visual grounding tasks, VividMed also excels in other common downstream tasks, including Visual Question Answering (VQA) and report generation. Ablation studies empirically show that the integration of visual grounding ability leads to improved performance on these tasks. Our code is publicly available at https://github.com/function2-llx/MMMM.

[Arxiv](https://arxiv.org/abs/2410.12694)