# 深度学习模型的应用定制压缩

发布时间：2024年09月09日

`LLM应用` `人工智能`

> Application Specific Compression of Deep Learning Models

# 摘要

> 当前的深度学习模型压缩方法未能充分利用目标应用的信息，导致压缩后的模型性能受限。我们提出应用特定压缩（ASC）方法，通过识别并修剪对特定应用冗余的网络部分，定制化压缩模型，使其在目标应用中表现更佳。实验结果表明，ASC方法在BERT系列模型上的表现优于传统压缩方法，为特定应用提供了更高效的解决方案。

> Large Deep Learning models are compressed and deployed for specific applications. However, current Deep Learning model compression methods do not utilize the information about the target application. As a result, the compressed models are application agnostic. Our goal is to customize the model compression process to create a compressed model that will perform better for the target application. Our method, Application Specific Compression (ASC), identifies and prunes components of the large Deep Learning model that are redundant specifically for the given target application. The intuition of our work is to prune the parts of the network that do not contribute significantly to updating the data representation for the given application. We have experimented with the BERT family of models for three applications: Extractive QA, Natural Language Inference, and Paraphrase Identification. We observe that customized compressed models created using ASC method perform better than existing model compression methods and off-the-shelf compressed models.

[Arxiv](https://arxiv.org/abs/2409.05368)