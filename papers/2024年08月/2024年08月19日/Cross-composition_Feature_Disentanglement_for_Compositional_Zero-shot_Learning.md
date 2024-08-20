# 跨组合特征解耦助力组合零-shot学习

发布时间：2024年08月19日

`LLM应用` `计算机视觉` `机器学习`

> Cross-composition Feature Disentanglement for Compositional Zero-shot Learning

# 摘要

> 在组合零-shot学习（CZSL）中，视觉特征的解耦（涉及属性和对象）表现出色。但因属性与不同对象组合时的特征发散，学习跨组合通用的解耦特征颇具挑战。为此，我们提出跨组合特征解耦方案，输入多个共享原语的组合，并确保解耦特征在各组合中通用。具体而言，我们借助组合图定义原语共享关系，并在CLIP这一成功的大型预训练视觉-语言模型上构建特定架构，引入双适配器（L-Adapter和V-Adapter）分别插入CLIP的文本和图像编码器。评估表明，该方案大幅提升CZSL性能，其组件亦经消融研究验证。

> Disentanglement of visual features of primitives (i.e., attributes and objects) has shown exceptional results in Compositional Zero-shot Learning (CZSL). However, due to the feature divergence of an attribute (resp. object) when combined with different objects (resp. attributes), it is challenging to learn disentangled primitive features that are general across different compositions. To this end, we propose the solution of cross-composition feature disentanglement, which takes multiple primitive-sharing compositions as inputs and constrains the disentangled primitive features to be general across these compositions. More specifically, we leverage a compositional graph to define the overall primitive-sharing relationships between compositions, and build a task-specific architecture upon the recently successful large pre-trained vision-language model (VLM) CLIP, with dual cross-composition disentangling adapters (called L-Adapter and V-Adapter) inserted into CLIP's frozen text and image encoders, respectively. Evaluation on three popular CZSL benchmarks shows that our proposed solution significantly improves the performance of CZSL, and its components have been verified by solid ablation studies.

[Arxiv](https://arxiv.org/abs/2408.09786)