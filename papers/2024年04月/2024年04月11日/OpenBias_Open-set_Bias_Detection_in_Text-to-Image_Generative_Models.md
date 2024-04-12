# OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。

发布时间：2024年04月11日

`LLM应用` `计算机视觉` `偏见检测
</example>`

> OpenBias: Open-set Bias Detection in Text-to-Image Generative Models

# 摘要

> 文本到图像的生成模型日益普及，走向大众。面对这些模型的广泛应用，确保其安全性与公正性至关重要，以免传播和固化偏见。然而，现有研究多聚焦于已知偏见的封闭集检测，限制了对新问题的探索。本文挑战了开放集偏见检测的难题，介绍了OpenBias这一新流程，它无需预设偏见集，就能独立识别和衡量偏见的严重程度。OpenBias分为三步：首先，借助大型语言模型（LLM），根据一组标题推测出潜在偏见；接着，目标生成模型依据这些标题生成图像；最后，通过视觉问答模型来确认并评估这些偏见的实际存在与影响范围。我们对Stable Diffusion 1.5、2和XL的运作机制进行了深入分析，揭示了一些前所未有的新偏见。通过一系列定量实验，我们验证了OpenBias与现行封闭集偏见检测方法和人类判断的一致性。

> Text-to-image generative models are becoming increasingly popular and accessible to the general public. As these models see large-scale deployments, it is necessary to deeply investigate their safety and fairness to not disseminate and perpetuate any kind of biases. However, existing works focus on detecting closed sets of biases defined a priori, limiting the studies to well-known concepts. In this paper, we tackle the challenge of open-set bias detection in text-to-image generative models presenting OpenBias, a new pipeline that identifies and quantifies the severity of biases agnostically, without access to any precompiled set. OpenBias has three stages. In the first phase, we leverage a Large Language Model (LLM) to propose biases given a set of captions. Secondly, the target generative model produces images using the same set of captions. Lastly, a Vision Question Answering model recognizes the presence and extent of the previously proposed biases. We study the behavior of Stable Diffusion 1.5, 2, and XL emphasizing new biases, never investigated before. Via quantitative experiments, we demonstrate that OpenBias agrees with current closed-set bias detection methods and human judgement.

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x1.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x2.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x3.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x4.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x5.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/785580.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/194273.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/619417.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/622215.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/483795.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/341725.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/51129.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/618785.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/30718.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x6.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/user_study.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x7.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x8.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/x9.png)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/51129.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/51129.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/51129.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/618785.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/618785.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/618785.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/30718.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/30718.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/30718.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/622215.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/622215.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/622215.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/483795.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/483795.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/483795.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/341725.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/341725.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/341725.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/785580.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/785580.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/785580.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/194273.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/194273.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/194273.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/619417.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/619417.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/619417.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/220603.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/220603.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/220603.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/405245.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/405245.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/405245.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/110695.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/110695.jpg)

![OpenBias 旨在揭示文本到图像生成模型中的开放集偏差问题，为这一领域的研究和改进提供了新的视角。](../../../paper_images/2404.07990/110695.jpg)

[Arxiv](https://arxiv.org/abs/2404.07990)