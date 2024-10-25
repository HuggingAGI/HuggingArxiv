# 用于高效图像传输的位置辅助语义通信：设计、实现和实验结果

发布时间：2024年10月23日

`其他` `图像传输`

> Position-Aided Semantic Communication for Efficient Image Transmission: Design, Implementation, and Experimental Results

# 摘要

> 语义通信，通过知识库（KBs）增强，在传输开销方面提供了大幅减少，并对错误具有弹性。然而，现有的方法主要依靠端到端训练来构建知识库，往往不能充分利用通信设备上可用的丰富信息。受传感和通信日益融合的推动，我们引入了一种新颖的位置辅助语义通信（PASC）框架，它将定位集成到语义传输中。这个框架特别为基于位置的图像通信而设计，例如户外相机视图图像的实时上传。通过利用位置，该框架检索相应的地图，然后采用先进的基础模型（FM）驱动的视图生成器来合成与目标图像非常相似的图像。PASC 框架进一步利用 FM 将合成图像与真实图像的偏差融合，增强语义重建。值得注意的是，该框架非常灵活，能够通过一种新颖的基于 FM 的参数优化策略适应动态内容和波动的信道条件。此外，解决了实时部署的挑战，开发了一个硬件测试平台来验证该框架。模拟和实际测试表明，所提出的 PASC 方法不仅显著提高了传输效率，而且在各种不断变化的传输场景中保持稳健。

> Semantic communication, augmented by knowledge bases (KBs), offers substantial reductions in transmission overhead and resilience to errors. However, existing methods predominantly rely on end-to-end training to construct KBs, often failing to fully capitalize on the rich information available at communication devices. Motivated by the growing convergence of sensing and communication, we introduce a novel Position-Aided Semantic Communication (PASC) framework, which integrates localization into semantic transmission. This framework is particularly designed for position-based image communication, such as real-time uploading of outdoor camera-view images. By utilizing the position, the framework retrieves corresponding maps, and then an advanced foundation model (FM)-driven view generator is employed to synthesize images closely resembling the target images. The PASC framework further leverages the FM to fuse the synthesized image with deviations from the real one, enhancing semantic reconstruction. Notably, the framework is highly flexible, capable of adapting to dynamic content and fluctuating channel conditions through a novel FM-based parameter optimization strategy. Additionally, the challenges of real-time deployment are addressed, with the development of a hardware testbed to validate the framework. Simulations and real-world tests demonstrate that the proposed PASC approach not only significantly boosts transmission efficiency, but also remains robust in diverse and evolving transmission scenarios.

[Arxiv](https://arxiv.org/abs/2410.18364)