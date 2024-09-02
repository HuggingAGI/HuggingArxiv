# 三维重建结合空间记忆技术

发布时间：2024年08月28日

`Agent` `计算机视觉` `三维重建`

> 3D Reconstruction with Spatial Memory

# 摘要

> 我们推出了 Spann3R，这是一种创新方法，能够从有序或无序的图像集合中实现三维密集重建。该方法基于 DUSt3R 框架，采用 transformer 架构，无需预知场景或相机参数，即可直接从图像生成点图。与 DUSt3R 不同，Spann3R 能在全局坐标系中预测每张图像的点图，省去了复杂的全局对齐步骤。其核心在于利用外部空间内存，记录并学习所有先前的三维信息，进而预测下一帧的全局三维结构。通过利用 DUSt3R 的预训练模型，并在部分数据集上进行微调，Spann3R 在处理未见数据集时表现出色，且能实时处理有序图像集合。项目详情请访问：\url{this https URL}

> 
Abstract:We present Spann3R, a novel approach for dense 3D reconstruction from ordered or unordered image collections. Built on the DUSt3R paradigm, Spann3R uses a transformer-based architecture to directly regress pointmaps from images without any prior knowledge of the scene or camera parameters. Unlike DUSt3R, which predicts per image-pair pointmaps each expressed in its local coordinate frame, Spann3R can predict per-image pointmaps expressed in a global coordinate system, thus eliminating the need for optimization-based global alignment. The key idea of Spann3R is to manage an external spatial memory that learns to keep track of all previous relevant 3D information. Spann3R then queries this spatial memory to predict the 3D structure of the next frame in a global coordinate system. Taking advantage of DUSt3R's pre-trained weights, and further fine-tuning on a subset of datasets, Spann3R shows competitive performance and generalization ability on various unseen datasets and can process ordered image collections in real time. Project page: \url{this https URL}
    

[Arxiv](https://arxiv.org/pdf/2408.16061)