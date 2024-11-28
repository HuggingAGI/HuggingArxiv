# 用于双模态显著目标检测的深度傅里叶嵌入网络

发布时间：2024年11月27日

`其他` `计算机视觉` `图像处理`

> Deep Fourier-embedded Network for Bi-modal Salient Object Detection

# 摘要

> 深度学习的迅猛发展极大地提高了结合 RGB 和热图像的显著目标检测水平。然而，现有的基于深度学习的模型存在两大主要缺陷。其一，具有二次复杂度的基于 Transformer 的模型，其计算和内存需求令人难以承受，尤其在处理高分辨率双模态特征融合时。其二，即便学习收敛至理想解，预测结果与真实值之间仍存在频率差异。为此，我们提出了一个纯粹基于快速傅里叶变换的模型，名为深度傅里叶嵌入网络（DFENet），用于学习 RGB 和热图像的双模态信息。一方面，快速傅里叶变换能够以低复杂度高效获取全局依赖关系。受此启发，我们设计了模态协调感知注意力，通过多维表示增强来弥合 RGB 和热模态之间的频率差距。为在解码时获取可靠的详细信息，我们设计了频率分解边缘感知模块（FEM），通过深度分解低层级特征来明晰对象边缘。此外，我们在每个解码器层配备了所提出的傅里叶残差通道注意力块，优先考虑高频信息的同时，对齐通道全局关系。另一方面，我们提出了共聚焦频率损失（CFL），以引导 FEM 缩小频率差距。CFL 通过交叉引用傅里叶域中的双模态边缘信息，在边缘频率重建过程中对硬频率进行动态加权。这种对边缘特征的频率级优化进一步提升了最终像素级预测的质量。在四个双模态显著目标检测基准数据集上开展的大量实验表明，我们提出的 DFENet 胜过现有的十二个前沿模型。

> The rapid development of deep learning provides a significant improvement of salient object detection combining both RGB and thermal images. However, existing deep learning-based models suffer from two major shortcomings. First, the computation and memory demands of Transformer-based models with quadratic complexity are unbearable, especially in handling high-resolution bi-modal feature fusion. Second, even if learning converges to an ideal solution, there remains a frequency gap between the prediction and ground truth. Therefore, we propose a purely fast Fourier transform-based model, namely deep Fourier-embedded network (DFENet), for learning bi-modal information of RGB and thermal images. On one hand, fast Fourier transform efficiently fetches global dependencies with low complexity. Inspired by this, we design modal-coordinated perception attention to fuse the frequency gap between RGB and thermal modalities with multi-dimensional representation enhancement. To obtain reliable detailed information during decoding, we design the frequency-decomposed edge-aware module (FEM) to clarify object edges by deeply decomposing low-level features. Moreover, we equip proposed Fourier residual channel attention block in each decoder layer to prioritize high-frequency information while aligning channel global relationships. On the other hand, we propose co-focus frequency loss (CFL) to steer FEM towards minimizing the frequency gap. CFL dynamically weights hard frequencies during edge frequency reconstruction by cross-referencing the bi-modal edge information in the Fourier domain. This frequency-level refinement of edge features further contributes to the quality of the final pixel-level prediction. Extensive experiments on four bi-modal salient object detection benchmark datasets demonstrate our proposed DFENet outperforms twelve existing state-of-the-art models.

[Arxiv](https://arxiv.org/abs/2411.18409)