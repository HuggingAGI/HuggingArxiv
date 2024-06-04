# 胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究

发布时间：2024年05月31日

`LLM应用

这篇论文探讨了基于Transformer架构的大型语言模型在图像处理领域的应用，特别是通过视觉Transformer（ViT）模型在胸部X光图像的多标签分类任务中的表现。论文通过对比ViT模型与传统的CNNs和ResNet在处理医学图像数据集上的性能，展示了ViT模型在特定应用场景下的优越性。因此，这篇论文属于LLM应用分类，因为它关注的是大型语言模型在特定领域（医学图像处理）的实际应用和效果评估。` `图像处理`

> A Comparative Study of CNN, ResNet, and Vision Transformers for Multi-Classification of Chest Diseases

# 摘要

> 得益于其可扩展性和处理大量数据的能力，采用Transformer架构的大型语言模型已成为强大的工具。Dosovitskiy等人进一步发展了这一架构，推出了视觉Transformer（ViT），使其能够应用于图像处理。基于这一创新，我们利用NIH胸部X光数据集（包含10万张正面X光图像）对两种ViT模型进行了微调：一种基于ImageNet预训练，另一种全新训练。我们的研究对比了这些模型与CNNs和ResNet在14种疾病多标签分类任务中的表现。通过精准的准确性评估，我们发现预训练的ViT模型在这一领域表现卓越，显示出其在胸部X光图像中准确诊断多种肺部疾病的巨大潜力。

> Large language models, notably utilizing Transformer architectures, have emerged as powerful tools due to their scalability and ability to process large amounts of data. Dosovitskiy et al. expanded this architecture to introduce Vision Transformers (ViT), extending its applicability to image processing tasks. Motivated by this advancement, we fine-tuned two variants of ViT models, one pre-trained on ImageNet and another trained from scratch, using the NIH Chest X-ray dataset containing over 100,000 frontal-view X-ray images. Our study evaluates the performance of these models in the multi-label classification of 14 distinct diseases, while using Convolutional Neural Networks (CNNs) and ResNet architectures as baseline models for comparison. Through rigorous assessment based on accuracy metrics, we identify that the pre-trained ViT model surpasses CNNs and ResNet in this multilabel classification task, highlighting its potential for accurate diagnosis of various lung conditions from chest X-ray images.

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/model1.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/model2.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/input_image.jpeg)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/Patches.jpeg)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/train_accuracy.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/validation_accuracy.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/roc_curve.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/ROC_CNN.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/attention.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/resnet.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/cnn.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/Vit-v2_loss.jpeg)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/vit-v2.png)

![胸部疾病多分类：CNN、ResNet 与 Vision Transformers 的比较研究](../../../paper_images/2406.00237/VITV1.png)

[Arxiv](https://arxiv.org/abs/2406.00237)