# 通过生成机器学习模型中的提示自动创作时尚图像

发布时间：2024年07月20日

`RAG` `人工智能`

> Automatic Generation of Fashion Images using Prompting in Generative Machine Learning Models

# 摘要

> 人工智能的兴起为时尚界带来了革命性的变革，重新定义了创造与创新。本研究采用两种大型语言模型及一款稳定扩散模型，探索生成个性化时尚描述的方法。我们突破传统，聚焦于零-shot、少-shot学习及思维链（CoT）等提示技术，丰富了色彩与纹理，提升了作品多样性。核心方法为检索增强生成（RAG），融入时尚智慧，确保作品紧跟潮流。评估融合定量与定性标准，彰显创意、连贯与美感。RAG与少-shot技术脱颖而出，因其生成的描述更具吸引力与相关性。代码详见https://github.com/georgiarg/AutoFashion。

> The advent of artificial intelligence has contributed in a groundbreaking transformation of the fashion industry, redefining creativity and innovation in unprecedented ways. This work investigates methodologies for generating tailored fashion descriptions using two distinct Large Language Models and a Stable Diffusion model for fashion image creation. Emphasizing adaptability in AI-driven fashion creativity, we depart from traditional approaches and focus on prompting techniques, such as zero-shot and few-shot learning, as well as Chain-of-Thought (CoT), which results in a variety of colors and textures, enhancing the diversity of the outputs. Central to our methodology is Retrieval-Augmented Generation (RAG), enriching models with insights from fashion sources to ensure contemporary representations. Evaluation combines quantitative metrics such as CLIPscore with qualitative human judgment, highlighting strengths in creativity, coherence, and aesthetic appeal across diverse styles. Among the participants, RAG and few-shot learning techniques are preferred for their ability to produce more relevant and appealing fashion descriptions. Our code is provided at https://github.com/georgiarg/AutoFashion.

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/Baseline.jpg)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/few-shot.jpg)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/CoT-model.jpg)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/RAG.jpg)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/ageStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/englishStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/occuStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/relatArtStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/fashPartStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/AIPartStats.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/1stexp.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/exAbn.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/inspAbno.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/2ndexp.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compComprehensib.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compCoherence.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compOutOccas.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compOutType.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compOutStyle.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compColOccas.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compColType.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compColStyle.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compTexOccas.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compTexType.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/compTexStyle.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/3rd.png)

![通过生成机器学习模型中的提示自动创作时尚图像](../../../paper_images/2407.14944/myresults1.jpg)

[Arxiv](https://arxiv.org/abs/2407.14944)