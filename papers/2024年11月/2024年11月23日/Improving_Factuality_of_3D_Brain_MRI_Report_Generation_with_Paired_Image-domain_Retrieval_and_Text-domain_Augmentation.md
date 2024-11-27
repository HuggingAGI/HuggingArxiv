# 借助配对的图像域检索与文本域增强，提升 3D 脑 MRI 报告生成的真实性

发布时间：2024年11月23日

`RAG` `医学影像`

> Improving Factuality of 3D Brain MRI Report Generation with Paired Image-domain Retrieval and Text-domain Augmentation

# 摘要

> 急性缺血性中风（AIS）的处理刻不容缓，干预稍有延迟数小时，就可能导致患者出现不可逆的残疾。利用磁共振成像（MRI）的扩散加权成像（DWI）在 AIS 的检测中至关重要，所以从 DWI 自动预测 AIS 一直是临床研究的重要课题。尽管文本放射学报告涵盖了图像发现中最相关的临床信息，但不同模态之间的映射难题限制了传统直接从 DWI 生成报告方法的真实性。在此，我们提出了配对图像域检索和文本域增强（PIRTA），这是一种跨模态检索增强生成（RAG）框架，用于提供更具真实性的临床解读 AIS 放射学报告。PIRTA 将跨模态映射问题转化为对具有配对真实文本放射学报告的相似 DWI 图像进行域内检索，从而降低了学习跨模态映射的难度，因为这在图像到文本生成中颇具困难。通过利用检索到的放射学报告来增强查询图像的报告生成过程，我们通过大量内部和公共数据集的实验表明，PIRTA 能够从 3D DWI 图像中精准检索到相关报告。与使用最先进的多模态语言模型进行直接图像到文本生成相比，这种方法生成的放射学报告准确性显著更高。

> Acute ischemic stroke (AIS) requires time-critical management, with hours of delayed intervention leading to an irreversible disability of the patient. Since diffusion weighted imaging (DWI) using the magnetic resonance image (MRI) plays a crucial role in the detection of AIS, automated prediction of AIS from DWI has been a research topic of clinical importance. While text radiology reports contain the most relevant clinical information from the image findings, the difficulty of mapping across different modalities has limited the factuality of conventional direct DWI-to-report generation methods. Here, we propose paired image-domain retrieval and text-domain augmentation (PIRTA), a cross-modal retrieval-augmented generation (RAG) framework for providing clinician-interpretative AIS radiology reports with improved factuality. PIRTA mitigates the need for learning cross-modal mapping, which poses difficulty in image-to-text generation, by casting the cross-modal mapping problem as an in-domain retrieval of similar DWI images that have paired ground-truth text radiology reports. By exploiting the retrieved radiology reports to augment the report generation process of the query image, we show by experiments with extensive in-house and public datasets that PIRTA can accurately retrieve relevant reports from 3D DWI images. This approach enables the generation of radiology reports with significantly higher accuracy compared to direct image-to-text generation using state-of-the-art multimodal language models.

[Arxiv](https://arxiv.org/abs/2411.15490)