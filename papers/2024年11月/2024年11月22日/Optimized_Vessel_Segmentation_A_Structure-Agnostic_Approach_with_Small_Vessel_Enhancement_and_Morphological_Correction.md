# 优化血管分割：一种实现小血管增强与形态学校正的结构无关式方法

发布时间：2024年11月22日

`其他` `血管分割`

> Optimized Vessel Segmentation: A Structure-Agnostic Approach with Small Vessel Enhancement and Morphological Correction

# 摘要

> 准确的血管分割对于各类临床评估和术后分析意义重大。然而，血管成像存在诸多固有难题，像稀疏性、精细度高、对比度低、数据分布多变以及对保持拓扑结构的迫切需求，这让通用血管分割变得极为复杂。尽管针对特定解剖区域已开发出专门的分割方法，但其对定制模型的过度依赖限制了其广泛适用性和通用性。医学成像中引入的通用分割模型通常难以处理关键的血管特征，比如分割结果的连通性。为克服这些局限，我们提出了一个优化的血管分割框架：一种与结构无关的方法，融合了小血管增强和形态学校正，用于多模态血管分割。为训练和验证此框架，我们整合了一个涵盖 17 个数据集的综合多模态数据集，并将我们的模型与六种基于 SAM 的方法和 17 个专家模型进行了对比测试。结果显示，我们的方法分割精度出色、泛化能力强，连通性提升了 34.6%，彰显出其临床潜力。一项消融研究进一步证实了所提改进的有效性。本工作发表后，我们会在 github 上发布代码和数据集。

> Accurate segmentation of blood vessels is essential for various clinical assessments and postoperative analyses. However, the inherent challenges of vascular imaging, such as sparsity, fine granularity, low contrast, data distribution variability, and the critical need for preserving topological structure, making generalized vessel segmentation particularly complex. While specialized segmentation methods have been developed for specific anatomical regions, their over-reliance on tailored models hinders broader applicability and generalization. General-purpose segmentation models introduced in medical imaging often fail to address critical vascular characteristics, including the connectivity of segmentation results. To overcome these limitations, we propose an optimized vessel segmentation framework: a structure-agnostic approach incorporating small vessel enhancement and morphological correction for multi-modality vessel segmentation. To train and validate this framework, we compiled a comprehensive multi-modality dataset spanning 17 datasets and benchmarked our model against six SAM-based methods and 17 expert models. The results demonstrate that our approach achieves superior segmentation accuracy, generalization, and a 34.6% improvement in connectivity, underscoring its clinical potential. An ablation study further validates the effectiveness of the proposed improvements. We will release the code and dataset at github following the publication of this work.

[Arxiv](https://arxiv.org/abs/2411.15251)