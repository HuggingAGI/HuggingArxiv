# AgriCLIP：通过领域专业化的跨模型对齐，为农业和畜牧业量身定制的 CLIP

发布时间：2024年10月02日

`LLM应用` `畜牧业`

> AgriCLIP: Adapting CLIP for Agriculture and Livestock via Domain-Specialized Cross-Model Alignment

# 摘要

> 借助海量图像-文本数据，大规模视觉-语言预训练已展现出卓越的零-shot能力，并广泛应用于多个领域。然而，基于通用网络数据训练的模型在特定领域（如农业和畜牧业）表现往往不尽如人意，这主要归因于领域偏移问题。近期研究虽已针对某些领域（如医疗保健）构建了专用数据集，但为农业和畜牧业打造大规模图像-文本数据集仍是一个待解难题。此外，由于下游任务（如营养缺乏检测、畜牧品种分类）的细微特性，该领域对细粒度特征学习的需求尤为迫切。为此，我们推出了AgriCLIP，一款专为农业和畜牧业量身定制的视觉-语言基础模型。首先，我们创建了ALive数据集，通过定制提示生成策略，有效弥补了专家注释的不足，涵盖作物、畜牧和渔业三大领域，包含约60万对图像-文本数据。其次，我们设计了融合对比学习与自监督学习的训练流程，旨在捕捉全局语义与局部细粒度特征。实验结果显示，AgriCLIP在20项下游任务中表现出色，平均零-shot分类准确率较标准CLIP模型提升7.8%。ALive数据集及代码已公开于\href{https://github.com/umair1221/AgriCLIP/tree/main}{Github}，供研究者参考与应用。

> Capitalizing on vast amount of image-text data, large-scale vision-language pre-training has demonstrated remarkable zero-shot capabilities and has been utilized in several applications. However, models trained on general everyday web-crawled data often exhibit sub-optimal performance for specialized domains, likely due to domain shift. Recent works have tackled this problem for some domains (e.g., healthcare) by constructing domain-specialized image-text data. However, constructing a dedicated large-scale image-text dataset for sustainable area of agriculture and livestock is still open to research. Further, this domain desires fine-grained feature learning due to the subtle nature of the downstream tasks (e.g, nutrient deficiency detection, livestock breed classification). To address this we present AgriCLIP, a vision-language foundational model dedicated to the domain of agriculture and livestock. First, we propose a large-scale dataset, named ALive, that leverages customized prompt generation strategy to overcome the scarcity of expert annotations. Our ALive dataset covers crops, livestock, and fishery, with around 600,000 image-text pairs. Second, we propose a training pipeline that integrates both contrastive and self-supervised learning to learn both global semantic and local fine-grained domain-specialized features. Experiments on diverse set of 20 downstream tasks demonstrate the effectiveness of AgriCLIP framework, achieving an absolute gain of 7.8\% in terms of average zero-shot classification accuracy, over the standard CLIP adaptation via domain-specialized ALive dataset. Our ALive dataset and code can be accessible at \href{https://github.com/umair1221/AgriCLIP/tree/main}{Github}.

[Arxiv](https://arxiv.org/abs/2410.01407)