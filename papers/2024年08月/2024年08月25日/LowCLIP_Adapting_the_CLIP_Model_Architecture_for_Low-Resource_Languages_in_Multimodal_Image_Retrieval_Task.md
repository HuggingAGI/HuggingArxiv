# LowCLIP：针对低资源语言，优化 CLIP 模型架构以提升多模态图像检索任务的性能。

发布时间：2024年08月25日

`LLM应用` `计算机视觉`

> LowCLIP: Adapting the CLIP Model Architecture for Low-Resource Languages in Multimodal Image Retrieval Task

# 摘要

> 本研究针对阿塞拜疆语等低资源语言，探索了多模态视觉-语言模型的图像检索技术。我们结合CLIP架构，通过合成数据生成、图像增强等手段，有效平衡了计算效率与模型性能。特别是，EfficientNet0和Tiny Swin Transformer在COCO等数据集上表现卓越，通过增强技术，EfficientNet0在Flickr30k上的MAP提升至0.87，ResNet50在MSCOCO上的MAP提升至0.80，刷新了视觉-语言检索的记录。我们公开了研究细节和预训练模型，以促进该领域的深入研究。相关资源已发布于GitHub。

> This research explores the development of multimodal vision-language models for image retrieval in low-resource languages, specifically Azerbaijani. Existing vision-language models primarily support high-resource languages, and fine-tuning them remains computationally demanding. To address challenges in vision-language retrieval for low-resource languages, we integrated the CLIP model architecture and employed several techniques to balance computational efficiency with performance. These techniques include synthetic data generation through machine translation, image augmentation, and further training the attention mechanisms of transformer-based models with domain-specific data. We integrated Multilingual BERT as a text encoder with image encoders like ResNet50, EfficientNet0, Vision Transformer (ViT), and Tiny Swin Transformer. Our study found that models like EfficientNet0 and Tiny Swin Transformer perform best on the datasets they were trained on, such as COCO, Flickr30k, and Flickr8k. Augmentation techniques boosted EfficientNet0 MAP on Flickr30k from 0.84 to 0.87 and ResNet50 MAP on MSCOCO from 0.70 to 0.80, contributing to a new state of the art in vision-language retrieval. We share our configurations and results to support further research. Code and pre-trained models are available at https://github.com/aliasgerovs/azclip.

[Arxiv](https://arxiv.org/abs/2408.13909)