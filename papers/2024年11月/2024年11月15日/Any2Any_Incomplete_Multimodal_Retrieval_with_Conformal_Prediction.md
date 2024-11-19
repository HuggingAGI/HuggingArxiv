# Any2Any：借助保形预测的不完整多模态检索

发布时间：2024年11月15日

`Agent` `机器人` `多模态检索`

> Any2Any: Incomplete Multimodal Retrieval with Conformal Prediction

# 摘要

> 自主智能体借助整合诸如视觉、音频和激光雷达等多模态输入来感知和解读周边环境，这些感知模式为诸如机器人中的位置识别等检索任务提供支持。然而，当下的多模态检索系统在部分数据因传感器故障或无法获取而缺失时会遭遇难题，比如无声视频或缺少RGB信息的激光雷达扫描。我们提出了Any2Any这一全新的检索框架，以应对查询和参考实例均存在不完整模态的情况。和以往局限于两种模态插补的方法不同，Any2Any能够处理任意数量的模态，且无需训练生成模型。它通过跨模态编码器计算成对相似度，并运用包含保形预测的两阶段校准过程来对齐相似度。Any2Any能够在多模态数据集（如文本-激光雷达和文本-时间序列）中实现有效检索。其在KITTI数据集上达成了35%的Recall@5，与具备完整模态的基线模型水平相当。

> Autonomous agents perceive and interpret their surroundings by integrating multimodal inputs, such as vision, audio, and LiDAR. These perceptual modalities support retrieval tasks, such as place recognition in robotics. However, current multimodal retrieval systems encounter difficulties when parts of the data are missing due to sensor failures or inaccessibility, such as silent videos or LiDAR scans lacking RGB information. We propose Any2Any-a novel retrieval framework that addresses scenarios where both query and reference instances have incomplete modalities. Unlike previous methods limited to the imputation of two modalities, Any2Any handles any number of modalities without training generative models. It calculates pairwise similarities with cross-modal encoders and employs a two-stage calibration process with conformal prediction to align the similarities. Any2Any enables effective retrieval across multimodal datasets, e.g., text-LiDAR and text-time series. It achieves a Recall@5 of 35% on the KITTI dataset, which is on par with baseline models with complete modalities.

[Arxiv](https://arxiv.org/abs/2411.10513)