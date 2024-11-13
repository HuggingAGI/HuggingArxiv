# 高斯万物：用于 3D 生成的交互式点云潜在扩散

发布时间：2024年11月12日

`其他` `3D 生成` `计算机图形学`

> GaussianAnything: Interactive Point Cloud Latent Diffusion for 3D Generation

# 摘要

> 虽然 3D 内容生成已经取得了显著的进步，但现有的方法在输入格式、潜在空间设计和输出表示方面仍然面临挑战。本文介绍了一种新颖的 3D 生成框架，解决了这些挑战，提供了具有交互式点云结构潜在空间的可扩展、高质量的 3D 生成。我们的框架采用了一个变分自编码器（VAE），以多视图的带姿态的 RGB-D（深度）-N（法线）渲染作为输入，使用独特的潜在空间设计来保留 3D 形状信息，并结合了一个级联的潜在扩散模型，以改进形状 - 纹理的解耦。所提出的方法，GaussianAnything，支持多模态条件的 3D 生成，允许点云、标题和单/多视图图像输入。值得注意的是，新提出的潜在空间自然地实现了几何 - 纹理的解耦，从而允许 3D 感知编辑。实验结果表明，我们的方法在多个数据集上是有效的，在文本和图像条件的 3D 生成方面都优于现有的方法。

> While 3D content generation has advanced significantly, existing methods still face challenges with input formats, latent space design, and output representations. This paper introduces a novel 3D generation framework that addresses these challenges, offering scalable, high-quality 3D generation with an interactive Point Cloud-structured Latent space. Our framework employs a Variational Autoencoder (VAE) with multi-view posed RGB-D(epth)-N(ormal) renderings as input, using a unique latent space design that preserves 3D shape information, and incorporates a cascaded latent diffusion model for improved shape-texture disentanglement. The proposed method, GaussianAnything, supports multi-modal conditional 3D generation, allowing for point cloud, caption, and single/multi-view image inputs. Notably, the newly proposed latent space naturally enables geometry-texture disentanglement, thus allowing 3D-aware editing. Experimental results demonstrate the effectiveness of our approach on multiple datasets, outperforming existing methods in both text- and image-conditioned 3D generation.

[Arxiv](https://arxiv.org/abs/2411.08033)