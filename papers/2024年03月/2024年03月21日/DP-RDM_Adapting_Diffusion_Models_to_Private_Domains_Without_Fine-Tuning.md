# DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。

发布时间：2024年03月21日

`Agent` `图像生成` `隐私保护`

> DP-RDM: Adapting Diffusion Models to Private Domains Without Fine-Tuning

# 摘要

> 文本转图像扩散模型存在记忆特定样本的问题，可能再现训练中接触过的完美图像复制品，这带来一定风险。为此，我们创新研发了首个具有差异隐私（DP）保护功能的增强检索生成算法，它不仅能够在确保严格隐私保障的同时产出高质量图像样本，而且无需对目标领域内的检索数据集进行微调。我们借助已训练好的小型公开数据集上的文本到图像扩散模型，并精心设计了DP检索机制，将来自私有检索数据集中的样本与文本提示相结合。这个名为“DP-RDM”的差异隐私增强检索扩散模型，可以利用最前沿的生成模型技术，在严格遵守DP规范的基础上生成高品质图像样本。实际应用中，在MS-COCO数据集上测试显示，即使面对高达$10,000$次查询请求，DP-RDM在隐私预算为$ε=10$的情况下仍然能够生成图像样本，并且相较于仅依赖公开检索数据集的方法，其FID得分提高了3.5点。

> Text-to-image diffusion models have been shown to suffer from sample-level memorization, possibly reproducing near-perfect replica of images that they are trained on, which may be undesirable. To remedy this issue, we develop the first differentially private (DP) retrieval-augmented generation algorithm that is capable of generating high-quality image samples while providing provable privacy guarantees. Specifically, we assume access to a text-to-image diffusion model trained on a small amount of public data, and design a DP retrieval mechanism to augment the text prompt with samples retrieved from a private retrieval dataset. Our \emph{differentially private retrieval-augmented diffusion model} (DP-RDM) requires no fine-tuning on the retrieval dataset to adapt to another domain, and can use state-of-the-art generative models to generate high-quality image samples while satisfying rigorous DP guarantees. For instance, when evaluated on MS-COCO, our DP-RDM can generate samples with a privacy budget of $ε=10$, while providing a $3.5$ point improvement in FID compared to public-only retrieval for up to $10,000$ queries.

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x2.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x3.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x4.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x5.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x6.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x7.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x8.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x9.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/shutterstock_dprdm.adapt005.n_agg_omitq_knn_17_nq_100_sig_0.07_sr_0.01_gs_2.0_ddim_100_eps_10.0top12.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/mscoco_faceblurred_dprdm.adapt005.n_agg_keep_pubr_0.5_knn_20_nq_100_sig_0.04_sr_0.0013217926025390625_gs_2.0_ddim_100_eps_10.0top12.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x10.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x11.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x12.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x13.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x14.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x15.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x16.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x17.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/x18.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/cifar10_dprdm.adapt005.n_agg_omitq_knn_23_nq_1000_sig_0.05_sr_0.01_gs_1.25_ddim_100_eps_10.0.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/imagenet_faceblurred_dprdm.adapt005.n_agg_omitq_knn_4_nq_1_sig_0.00_sr_1.0_gs_2.0_ddim_100shutterstock_top12.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/imagenet_faceblurred_dprdm.adapt005.n_agg_omitq_knn_4_nq_1_sig_0.00_sr_1.0_gs_2.0_ddim_100coco_top6.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/shutterstock_dprdm.adapt005.n_agg_omitq_knn_17_nq_100_sig_0.07_sr_0.01_gs_2.0_ddim_100_eps_10.0bot6.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/mscoco_faceblurred_dprdm.adapt005.n_agg_keep_pubr_0.5_knn_20_nq_100_sig_0.04_sr_0.0013217926025390625_gs_2.0_ddim_100_eps_10.0bot6.jpg)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/default.D.png)

![DP-RDM 方法能够在不进行微调的前提下，成功地将扩散模型应用于专属领域。](../../../paper_images/2403.14421/agg_sig0.2_agg_sig0.2.D.png)

[Arxiv](https://arxiv.org/abs/2403.14421)