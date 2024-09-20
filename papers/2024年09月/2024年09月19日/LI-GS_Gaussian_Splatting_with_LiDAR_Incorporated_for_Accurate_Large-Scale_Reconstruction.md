# LI-GS：融合 LiDAR 的高斯喷射技术，实现大规模精确重建

发布时间：2024年09月19日

`Agent` `机器人` `地理信息系统`

> LI-GS: Gaussian Splatting with LiDAR Incorporated for Accurate Large-Scale Reconstruction

# 摘要

> 在机器人领域，大规模3D重建至关重要。3D高斯喷射（3DGS）已展示出实现精确物体级重建的潜力，但在户外和无界场景中确保几何精度仍是一大挑战。为此，我们推出了LI-GS系统，结合LiDAR和高斯喷射技术，大幅提升大规模场景的几何精度。我们采用2D高斯表面作为地图表示，增强表面对齐，并创新地将LiDAR点云转换为平面约束的多模态高斯混合模型（GMMs）。GMMs在初始化和优化阶段均发挥作用，确保场景全程得到充分且连续的监督，同时避免过拟合。此外，GMMs在网格提取中消除伪影，提升整体几何质量。实验结果显示，我们的方法在大规模3D重建中表现卓越，分别比基于LiDAR和基于高斯的方法提高了52.6%和68.7%的精度。

> Large-scale 3D reconstruction is critical in the field of robotics, and the potential of 3D Gaussian Splatting (3DGS) for achieving accurate object-level reconstruction has been demonstrated. However, ensuring geometric accuracy in outdoor and unbounded scenes remains a significant challenge. This study introduces LI-GS, a reconstruction system that incorporates LiDAR and Gaussian Splatting to enhance geometric accuracy in large-scale scenes. 2D Gaussain surfels are employed as the map representation to enhance surface alignment. Additionally, a novel modeling method is proposed to convert LiDAR point clouds to plane-constrained multimodal Gaussian Mixture Models (GMMs). The GMMs are utilized during both initialization and optimization stages to ensure sufficient and continuous supervision over the entire scene while mitigating the risk of over-fitting. Furthermore, GMMs are employed in mesh extraction to eliminate artifacts and improve the overall geometric quality. Experiments demonstrate that our method outperforms state-of-the-art methods in large-scale 3D reconstruction, achieving higher accuracy compared to both LiDAR-based methods and Gaussian-based methods with improvements of 52.6% and 68.7%, respectively.

[Arxiv](https://arxiv.org/abs/2409.12899)