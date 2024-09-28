# TA-Cleaner：一种针对多模态对比学习的细粒度文本对齐后门防御策略

发布时间：2024年09月26日

`LLM应用` `网络安全` `人工智能`

> TA-Cleaner: A Fine-grained Text Alignment Backdoor Defense Strategy for Multimodal Contrastive Learning

# 摘要

> 预训练的多模态模型 CLIP 易受数据中毒攻击，给下游训练带来风险。微调相比重新训练，提供了更简便高效的防御方案。在监督学习中，微调防御效果显著。但在无监督和半监督领域，面对复杂攻击，现有策略 CleanCLIP 的防御效果有限。其文本增强的同义词替换不足以强化文本特征空间。为此，我们提出细粒度文本对齐清洁器 TA-Cleaner，切断后门触发器的特征连接。在每个 epoch 中，随机生成正负子文本并与图像对齐，增强文本自监督。实验表明，TA-Cleaner 在六种攻击算法和 ImageNet1K 零样本分类测试中表现优异，防御性能领先。面对新型攻击 BadCLIP，TA-Cleaner 分别将 Top-1 和 Top-10 的 ASR 降低了 52.02% 和 63.88%，优于 CleanCLIP。

> Pre-trained large models for multimodal contrastive learning, such as CLIP, have been widely recognized in the industry as highly susceptible to data-poisoned backdoor attacks. This poses significant risks to downstream model training. In response to such potential threats, finetuning offers a simpler and more efficient defense choice compared to retraining large models with augmented data. In the supervised learning domain, fine-tuning defense strategies can achieve excellent defense performance. However, in the unsupervised and semi-supervised domain, we find that when CLIP faces some complex attack techniques, the existing fine-tuning defense strategy, CleanCLIP, has some limitations on defense performance. The synonym substitution of its text-augmentation is insufficient to enhance the text feature space. To compensate for this weakness, we improve it by proposing a fine-grained \textbf{T}ext \textbf{A}lignment \textbf{C}leaner (TA-Cleaner) to cut off feature connections of backdoor triggers. We randomly select a few samples for positive and negative subtext generation at each epoch of CleanCLIP, and align the subtexts to the images to strengthen the text self-supervision. We evaluate the effectiveness of our TA-Cleaner against six attack algorithms and conduct comprehensive zero-shot classification tests on ImageNet1K. Our experimental results demonstrate that TA-Cleaner achieves state-of-the-art defensiveness among finetuning-based defense techniques. Even when faced with the novel attack technique BadCLIP, our TA-Cleaner outperforms CleanCLIP by reducing the ASR of Top-1 and Top-10 by 52.02\% and 63.88\%, respectively.

[Arxiv](https://arxiv.org/abs/2409.17601)