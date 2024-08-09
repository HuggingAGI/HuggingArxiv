# ComKD-CLIP：为对比语言-图像预训练模型提供全面知识蒸馏的解决方案

发布时间：2024年08月07日

`LLM应用` `计算机视觉` `人工智能`

> ComKD-CLIP: Comprehensive Knowledge Distillation for Contrastive Language-Image Pre-traning Model

# 摘要

> CLIP通过对比学习技术在图像与文本的语义整合上表现卓越，广泛应用于多模态任务。然而，大型CLIP模型在资源受限环境下难以部署，小型模型又常无法达到实际应用的性能要求。为此，我们提出ComKD-CLIP方法，通过综合知识蒸馏技术，将大型CLIP模型的知识迁移至小型模型，同时保持性能并大幅减少参数。ComKD-CLIP包含图像特征对齐（IFAlign）和教育注意力（EduAttention）两大核心机制，前者确保学生模型精确学习教师模型的图像特征提取能力，后者则帮助学生模型掌握教师模型整合文本与图像特征的技巧。此外，ComKD-CLIP还能优化蒸馏过程，确保学生模型精准吸收教师知识。实验结果显示，该方法在11个数据集上均表现优异。

> Contrastive Language-Image Pre-training (CLIP) excels in integrating semantic information between images and text through contrastive learning techniques. It has achieved remarkable performance in various multimodal tasks. However, the deployment of large CLIP models is hindered in resource-limited environments, while smaller models frequently fall short of meeting performance benchmarks necessary for practical applications. In this paper, we propose a novel approach, coined as ComKD-CLIP: Comprehensive Knowledge Distillation for Contrastive Language-Image Pre-traning Model, which aims to comprehensively distill the knowledge from a large teacher CLIP model into a smaller student model, ensuring comparable performance with significantly reduced parameters. ComKD-CLIP is composed of two key mechanisms: Image Feature Alignment (IFAlign) and Educational Attention (EduAttention). IFAlign makes the image features extracted by the student model closely match those extracted by the teacher model, enabling the student to learn teacher's knowledge of extracting image features. EduAttention explores the cross-relationships between text features extracted by the teacher model and image features extracted by the student model, enabling the student model to learn how the teacher model integrates text-image features. In addition, ComKD-CLIP can refine the knowledge distilled from IFAlign and EduAttention leveraging the results of text-image feature fusion by the teacher model, ensuring student model accurately absorbs the knowledge of teacher model. Extensive experiments conducted on 11 datasets have demonstrated the superiority of the proposed method.

[Arxiv](https://arxiv.org/abs/2408.04145)