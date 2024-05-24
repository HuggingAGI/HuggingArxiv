# 仅凭文本数据，揭秘CLIP模型中的身份推断之谜

发布时间：2024年05月23日

`LLM应用

这篇论文主要关注的是在大型多模态模型（如CLIP）中检测个人身份信息（PII）泄露的问题，并提出了一种新的检测方法——文本单模态检测器（TUNI）。这种方法通过仅使用文本数据来查询目标模型，避免了传统成员推断攻击（MIAs）中需要训练影子模型的计算成本高昂的问题。因此，这项工作更偏向于LLM（大型语言模型）的应用层面，特别是在处理多模态数据时的安全性和隐私保护问题。` `数据隐私` `信息安全`

> Identity Inference from CLIP Models using Only Textual Data

# 摘要

> 随着CLIP等大规模多模态模型的普及，个人身份信息（PII）泄露的风险日益加剧。目前，检测CLIP模型训练中使用的PII身份信息的方法，需要通过包含完整PII（如姓名和面部照片）的查询来实现，这可能无意中泄露了目标模型尚未接触的图像隐私。同时，传统的成员推断攻击（MIAs）通过训练影子模型来模拟目标模型的行为，这在处理大型CLIP模型时计算成本高昂。为此，我们提出了一种创新的文本单模态检测器（TUNI），它通过仅使用文本数据来查询目标模型，并避免了影子模型的训练。TUNI首先利用CLIP模型指导的特征提取算法，从文本描述中提取特征，然后通过生成未用于训练的随机文本，并利用这些文本的特征向量来训练异常检测器。在实际应用中，每个测试文本的特征向量会被输入到异常检测器中，以判断该文本是否包含训练集中的PII。此外，若条件允许，TUNI还能通过结合与测试个体相关的真实图像来增强其检测能力。实验结果显示，TUNI在多种CLIP模型架构和数据集上的表现均优于现有方法，尽管它仅依赖文本数据。

> The widespread usage of large-scale multimodal models like CLIP has heightened concerns about the leakage of personally identifiable information (PII). Existing methods for identity inference in CLIP models, i.e., to detect the presence of a person's PII used for training a CLIP model, require querying the model with full PII, including textual descriptions of the person and corresponding images (e.g., the name and the face photo of the person). However, this may lead to potential privacy breach of the image, as it may have not been seen by the target model yet. Additionally, traditional membership inference attacks (MIAs) train shadow models to mimic the behaviors of the target model, which incurs high computational costs, especially for large CLIP models. To address these challenges, we propose a textual unimodal detector (TUNI) in CLIP models, a novel method for ID inference that 1) queries the target model with only text data; and 2) does not require training shadow models. Firstly, we develop a feature extraction algorithm, guided by the CLIP model, to extract features from a text description. TUNI starts with randomly generating textual gibberish that were clearly not utilized for training, and leverages their feature vectors to train a system of anomaly detectors. During inference, the feature vector of each test text is fed into the anomaly detectors to determine if the person's PII is in the training set (abnormal) or not (normal). Moreover, TUNI can be further strengthened integrating real images associated with the tested individuals, if available at the detector. Extensive experiments of TUNI across various CLIP model architectures and datasets demonstrate its superior performance over baselines, albeit with only text data.

[Arxiv](https://arxiv.org/abs/2405.14517)