# REEF：大型语言模型的表示编码指纹

发布时间：2024年10月18日

`LLM理论` `知识产权保护` `开源软件`

> REEF: Representation Encoding Fingerprints for Large Language Models

# 摘要

> 保护开源 LLM 的知识产权至关重要，因为训练这些模型需要大量资源。我们提出了一种无需训练的 REEF 方法，通过比较特征表示的相似性来识别模型关系。REEF 不仅简单有效，还能抵御多种模型操作。这为模型所有者和第三方提供了一种便捷的知识产权保护途径。代码已开源，详见 https://github.com/tmylla/REEF。

> Protecting the intellectual property of open-source Large Language Models (LLMs) is very important, because training LLMs costs extensive computational resources and data. Therefore, model owners and third parties need to identify whether a suspect model is a subsequent development of the victim model. To this end, we propose a training-free REEF to identify the relationship between the suspect and victim models from the perspective of LLMs' feature representations. Specifically, REEF computes and compares the centered kernel alignment similarity between the representations of a suspect model and a victim model on the same samples. This training-free REEF does not impair the model's general capabilities and is robust to sequential fine-tuning, pruning, model merging, and permutations. In this way, REEF provides a simple and effective way for third parties and models' owners to protect LLMs' intellectual property together. The code is available at https://github.com/tmylla/REEF.

[Arxiv](https://arxiv.org/abs/2410.14273)