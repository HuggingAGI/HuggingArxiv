# MM-Path：多模态、多粒度的路径表示学习 -- 扩展版

发布时间：2024年11月27日

`其他` `智能交通` `路径表示学习`

> MM-Path: Multi-modal, Multi-granularity Path Representation Learning -- Extended Version

# 摘要

> 在智能交通的众多领域里，开发高效的路径表示愈发关键。虽说预训练的路径表示学习模型性能有所提升，可它们大多聚焦于单一模态数据（如道路网络）的拓扑结构，却忽视了与路径相关图像（像遥感图像）的几何及上下文特征。和人类的理解相似，整合多模态信息能提供更全面的视角，提升表示的准确性与泛化能力。然而，信息粒度的差异阻碍了基于道路网络的路径（道路路径）和基于图像的路径（图像路径）的语义对齐，多模态数据的异质性也给有效融合与利用带来巨大挑战。本文中，我们提出了一种新颖的多模态、多粒度路径表示学习框架（MM-Path），能够通过整合道路路径和图像路径的模态来学习通用路径表示。为强化多模态数据的对齐，我们研发了一种多粒度对齐策略，将节点、道路子路径和道路路径与对应的图像块进行系统关联，保证详细的局部信息和更广泛的全局上下文同步。为有效应对多模态数据的异质性，我们引入了一个基于图的跨模态残差融合组件，旨在全面融合不同模态和粒度的信息。最后，我们在两个大规模的真实世界数据集上开展了两个下游任务的大量实验，验证了所提出的 MM-Path 的有效性。此为被 KDD 2025 录用的论文的扩展版。

> Developing effective path representations has become increasingly essential across various fields within intelligent transportation. Although pre-trained path representation learning models have shown improved performance, they predominantly focus on the topological structures from single modality data, i.e., road networks, overlooking the geometric and contextual features associated with path-related images, e.g., remote sensing images. Similar to human understanding, integrating information from multiple modalities can provide a more comprehensive view, enhancing both representation accuracy and generalization. However, variations in information granularity impede the semantic alignment of road network-based paths (road paths) and image-based paths (image paths), while the heterogeneity of multi-modal data poses substantial challenges for effective fusion and utilization. In this paper, we propose a novel Multi-modal, Multi-granularity Path Representation Learning Framework (MM-Path), which can learn a generic path representation by integrating modalities from both road paths and image paths. To enhance the alignment of multi-modal data, we develop a multi-granularity alignment strategy that systematically associates nodes, road sub-paths, and road paths with their corresponding image patches, ensuring the synchronization of both detailed local information and broader global contexts. To address the heterogeneity of multi-modal data effectively, we introduce a graph-based cross-modal residual fusion component designed to comprehensively fuse information across different modalities and granularities. Finally, we conduct extensive experiments on two large-scale real-world datasets under two downstream tasks, validating the effectiveness of the proposed MM-Path. This is an extended version of the paper accepted by KDD 2025.

[Arxiv](https://arxiv.org/abs/2411.18428)