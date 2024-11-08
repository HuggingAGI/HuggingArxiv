# 去噪扩散概率模型的六个简单步骤

发布时间：2024年02月06日

`其他` `机器学习` `深度生成模型`

> Denoising Diffusion Probabilistic Models in Six Simple Steps

# 摘要

> 摘要：去噪扩散概率模型（DDPMs）是一类非常流行的深度生成模型，已成功应用于包括图像和视频生成、蛋白质和材料合成、天气预报以及偏微分方程的神经替代等各种问题。尽管它们无处不在，但很难找到一个简单、全面、清晰和明确的关于 DDPMs 的介绍。研究论文中必要的简洁解释无法阐明为制定 DDPM 所采取的所有不同设计步骤，并且所呈现步骤的基本原理经常被省略以节省空间。此外，阐述通常从变分下界的角度呈现，这是不必要的，并且可以说是有害的，因为它模糊了该方法起作用的原因，并提出了在实践中表现不佳的泛化。另一方面，采用连续时间限制的观点是美丽和通用的，但它们的入门门槛很高，因为它们需要随机微分方程和概率流的背景知识。在本说明中，我们将 DDPM 的制定提炼为六个简单的步骤，每个步骤都有明确的基本原理。我们假设读者熟悉机器学习中的基本主题，包括基本概率建模、高斯分布、最大似然估计和深度学习。

> 
Abstract:Denoising Diffusion Probabilistic Models (DDPMs) are a very popular class of deep generative model that have been successfully applied to a diverse range of problems including image and video generation, protein and material synthesis, weather forecasting, and neural surrogates of partial differential equations. Despite their ubiquity it is hard to find an introduction to DDPMs which is simple, comprehensive, clean and clear. The compact explanations necessary in research papers are not able to elucidate all of the different design steps taken to formulate the DDPM and the rationale of the steps that are presented is often omitted to save space. Moreover, the expositions are typically presented from the variational lower bound perspective which is unnecessary and arguably harmful as it obfuscates why the method is working and suggests generalisations that do not perform well in practice. On the other hand, perspectives that take the continuous time-limit are beautiful and general, but they have a high barrier-to-entry as they require background knowledge of stochastic differential equations and probability flow. In this note, we distill down the formulation of the DDPM into six simple steps each of which comes with a clear rationale. We assume that the reader is familiar with fundamental topics in machine learning including basic probabilistic modelling, Gaussian distributions, maximum likelihood estimation, and deep learning.
    

[Arxiv](https://arxiv.org/pdf/2402.04384)