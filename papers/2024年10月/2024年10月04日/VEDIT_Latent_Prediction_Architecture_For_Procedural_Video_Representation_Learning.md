# VEDIT：一种用于程序化视频表示学习的潜在预测架构

发布时间：2024年10月04日

`Agent` `视频分析` `人工智能`

> VEDIT: Latent Prediction Architecture For Procedural Video Representation Learning

# 摘要

> 程序化视频表示学习旨在训练一个能根据当前视频预测未来的智能体，通常结合文本注释。以往研究多依赖大规模预训练，但这种计算密集型方法在噪声文本监督下的视频片段学习中是否必要和有效，尚未充分验证。我们发现，一个现成的冻结预训练视觉编码器，加上精心设计的预测模型，无需预训练或额外监督，即可在预测和规划中达到顶尖水平。我们利用公开视觉编码器的潜在嵌入空间，通过观察步骤的冻结嵌入预测未见动作，借助扩散变换器的最新进展，实现迭代去噪，学习稳健表示。实验表明，我们的模型在长期动作预测、步骤预测、任务分类和程序规划等多项任务中，显著超越现有基线，达到新高度。

> Procedural video representation learning is an active research area where the objective is to learn an agent which can anticipate and forecast the future given the present video input, typically in conjunction with textual annotations. Prior works often rely on large-scale pretraining of visual encoders and prediction models with language supervision. However, the necessity and effectiveness of extending compute intensive pretraining to learn video clip sequences with noisy text supervision have not yet been fully validated by previous works. In this work, we show that a strong off-the-shelf frozen pretrained visual encoder, along with a well designed prediction model, can achieve state-of-the-art (SoTA) performance in forecasting and procedural planning without the need for pretraining the prediction model, nor requiring additional supervision from language or ASR. Instead of learning representations from pixel space, our method utilizes the latent embedding space of publicly available vision encoders. By conditioning on frozen clip-level embeddings from observed steps to predict the actions of unseen steps, our prediction model is able to learn robust representations for forecasting through iterative denoising - leveraging the recent advances in diffusion transformers (Peebles & Xie, 2023). Empirical studies over a total of five procedural learning tasks across four datasets (NIV, CrossTask, COIN and Ego4D-v2) show that our model advances the strong baselines in long-horizon action anticipation (+2.6% in Verb ED@20, +3.1% in Noun ED@20), and significantly improves the SoTA in step forecasting (+5.0%), task classification (+3.8%), and procedure planning tasks (up to +2.28% in success rate, +3.39% in mAcc, and +0.90% in mIoU).

[Arxiv](https://arxiv.org/abs/2410.03478)