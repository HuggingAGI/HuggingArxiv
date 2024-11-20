# 强化骨质疏松症检测：具备特征融合与变量聚类的可解释多模态学习框架

发布时间：2024年11月01日

`其他` `医学影像`

> Enhancing Osteoporosis Detection: An Explainable Multi-Modal Learning Framework with Feature Fusion and Variable Clustering

# 摘要

> 骨质疏松症是一种常见疾病，尤其在老年人中会加大骨折风险。早期诊断对于预防骨折、降低治疗费用以及维持行动能力极为关键。然而，医疗服务提供者面临着标记数据有限、医学图像处理困难等挑战。本研究呈现了一个全新的多模态学习框架，它融合了临床和影像数据，以提升诊断的准确性和模型的可解释性。该模型运用了三个预训练网络——VGG19、InceptionV3 和 ResNet50，从 X 射线图像中提取深度特征。这些特征通过主成分分析（PCA）进行转换，以降低维度并聚焦于最相关的部分。基于聚类的选择流程确定了最具代表性的部分，随后将其与预处理的临床数据相结合，并通过全连接网络（FCN）进行最终分类。特征重要性图表突出了关键变量，显示病史、体重指数和身高是主要影响因素，凸显了患者特定数据的重要性。尽管影像特征有一定价值，但重要性相对较低，这表明临床数据对于准确预测至关重要。此框架推动了精准且可解释的预测，增强了透明度，并为临床整合中的人工智能驱动诊断建立了信任。

> Osteoporosis is a common condition that increases fracture risk, especially in older adults. Early diagnosis is vital for preventing fractures, reducing treatment costs, and preserving mobility. However, healthcare providers face challenges like limited labeled data and difficulties in processing medical images. This study presents a novel multi-modal learning framework that integrates clinical and imaging data to improve diagnostic accuracy and model interpretability. The model utilizes three pre-trained networks-VGG19, InceptionV3, and ResNet50-to extract deep features from X-ray images. These features are transformed using PCA to reduce dimensionality and focus on the most relevant components. A clustering-based selection process identifies the most representative components, which are then combined with preprocessed clinical data and processed through a fully connected network (FCN) for final classification. A feature importance plot highlights key variables, showing that Medical History, BMI, and Height were the main contributors, emphasizing the significance of patient-specific data. While imaging features were valuable, they had lower importance, indicating that clinical data are crucial for accurate predictions. This framework promotes precise and interpretable predictions, enhancing transparency and building trust in AI-driven diagnoses for clinical integration.

[Arxiv](https://arxiv.org/abs/2411.00916)