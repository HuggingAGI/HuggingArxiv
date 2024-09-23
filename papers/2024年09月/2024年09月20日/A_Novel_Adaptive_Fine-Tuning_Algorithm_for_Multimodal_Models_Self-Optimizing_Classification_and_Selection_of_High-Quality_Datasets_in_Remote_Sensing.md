# 一种创新的多模态模型自适应微调算法，专为遥感领域设计，能够自我优化分类并精选高质量数据集。

发布时间：2024年09月20日

`LLM应用` `人工智能`

> A Novel Adaptive Fine-Tuning Algorithm for Multimodal Models: Self-Optimizing Classification and Selection of High-Quality Datasets in Remote Sensing

# 摘要

> 我们设计了一种自适应微调算法，专为多模态大型模型量身定制。该算法通过两个阶段的截断，首先将海量数据映射到语义向量空间，并利用MiniBatchKMeans算法自动聚类，确保每个簇内数据的高语义相似性。随后，计算多模态模型向量空间中原始数据与扰动数据间的平移差异，以此作为数据泛化能力的度量，进而筛选出高泛化潜力的数据进行训练。我们利用此算法，在两块3090 GPU上，仅用GeoChat多模态遥感数据集的三分之一，成功训练了InternLM-XComposer2-VL-7B模型。实验结果显示，我们的算法性能超越了当前最先进的基线。经实验验证，使用我们优化选择的数据集训练的模型，在各项遥感指标上仅比全数据集训练的模型性能下降1%，同时训练时间大幅缩短68.2%，通用能力得以显著保留。此外，该模型在UCMerced和AID评估数据集上的得分分别为89.86和77.19，较GeoChat数据集分别提升了5.43和5.16分，而在LRBEN评估数据集上的平均下降仅为0.91分。

> We propose an adaptive fine-tuning algorithm for multimodal large models. The core steps of this algorithm involve two stages of truncation. First, the vast amount of data is projected into a semantic vector space, and the MiniBatchKMeans algorithm is used for automated clustering. This classification ensures that the data within each cluster exhibit high semantic similarity. Next, we process the data in each cluster, calculating the translational difference between the original and perturbed data in the multimodal large model's vector space. This difference serves as a generalization metric for the data. Based on this metric, we select the data with high generalization potential for training. We applied this algorithm to train the InternLM-XComposer2-VL-7B model on two 3090 GPUs using one-third of the GeoChat multimodal remote sensing dataset. The results demonstrate that our algorithm outperforms the state-of-the-art baselines. various baselines. The model trained on our optimally chosen one-third dataset, based on experimental validation, exhibited only 1% reduction in performance across various remote sensing metrics compared to the model trained on the full dataset. This approach significantly preserved general-purpose capabilities while reducing training time by 68.2%. Furthermore, the model achieved scores of 89.86 and 77.19 on the UCMerced and AID evaluation datasets, respectively, surpassing the GeoChat dataset by 5.43 and 5.16 points. It only showed a 0.91-point average decrease on the LRBEN evaluation dataset.

[Arxiv](https://arxiv.org/abs/2409.13345)