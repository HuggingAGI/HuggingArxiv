# 深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。

发布时间：2024年04月16日

`LLM应用` `天文学` `机器学习`

> Deep Learning and LLM-based Methods Applied to Stellar Lightcurve Classification

# 摘要

> 光曲线为我们揭示恒星诞生与演变的秘密提供了珍贵线索。随着机器学习技术突飞猛进，我们能有效处理这些数据，挖掘天文奥秘。本研究全面评测了基于深度学习和大型语言模型（LLM）的模型，自动对开普勒和K2任务中的变星光曲线进行分类。特别关注造父变星、RR Lyrae星和食双星，探究观测频率和相位分布对分类精度的作用。利用AutoDL优化技术，我们采用1D-Convolution+BiLSTM架构和Swin Transformer，分别实现了94%和99%的高准确率，后者在识别仅占数据集0.02%的II型造父变星时，准确率达到了83%。我们推出了StarWhisper LightCurve（LC）系列，包含三种基于LLM的模型：LLM、多模态大型语言模型（MLLM）和大型音频语言模型（LALM）。每个模型都经过精心调校和特定训练方法，以挖掘它们在处理天文数据时的潜能。StarWhisper LC系列的准确率接近90%，大幅降低了对特征工程的依赖，为简化数据处理和推动多模态模型在天文学中的应用开辟了新途径。研究还提供了两份详尽的目录，展示了相位和采样间隔对深度学习分类精度的影响，证明了在准确率损失不超过10%的前提下，观测时间和采样点可分别减少多达14%和21%。

> Light curves serve as a valuable source of information on stellar formation and evolution. With the rapid advancement of machine learning techniques, it can be effectively processed to extract astronomical patterns and information. In this study, we present a comprehensive evaluation of deep-learning and large language model (LLM) based models for the automatic classification of variable star light curves, based on large datasets from the Kepler and K2 missions. Special emphasis is placed on Cepheids, RR Lyrae, and eclipsing binaries, examining the influence of observational cadence and phase distribution on classification precision. Employing AutoDL optimization, we achieve striking performance with the 1D-Convolution+BiLSTM architecture and the Swin Transformer, hitting accuracies of 94\% and 99\% correspondingly, with the latter demonstrating a notable 83\% accuracy in discerning the elusive Type II Cepheids-comprising merely 0.02\% of the total dataset.We unveil StarWhisper LightCurve (LC), an innovative Series comprising three LLM-based models: LLM, multimodal large language model (MLLM), and Large Audio Language Model (LALM). Each model is fine-tuned with strategic prompt engineering and customized training methods to explore the emergent abilities of these models for astronomical data. Remarkably, StarWhisper LC Series exhibit high accuracies around 90\%, significantly reducing the need for explicit feature engineering, thereby paving the way for streamlined parallel data processing and the progression of multifaceted multimodal models in astronomical applications. The study furnishes two detailed catalogs illustrating the impacts of phase and sampling intervals on deep learning classification accuracy, showing that a substantial decrease of up to 14\% in observation duration and 21\% in sampling points can be realized without compromising accuracy by more than 10\%.

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/CWT.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/LS.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/model.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/Loss.png)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/GDOR.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/DSCT.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/HYB.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/EB.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/RR.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/Accuracy-Points.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_1.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_2.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_3.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_4.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_5.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_6.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/confusion_7.pdf)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/LLM.png)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/MLLM.png)

![深度学习与基于大型语言模型的技术在恒星光变曲线的分类上得到了应用。](../../../paper_images/2404.10757/LALM.png)

[Arxiv](https://arxiv.org/abs/2404.10757)