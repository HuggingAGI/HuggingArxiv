# 探索面部表情识别的偏差至平衡：在大规模多模态基础模型中揭示识别偏差

发布时间：2024年08月27日

`LLM应用` `人工智能` `面部识别`

> From Bias to Balance: Detecting Facial Expression Recognition Biases in Large Multimodal Foundation Models

# 摘要

> 本研究聚焦于大型多模态基础模型（LMFMs）中面部表情识别（FER）系统的种族偏见。尽管深度学习进步和多样数据集的可用性，FER系统对深肤色个体的错误率仍较高。现有研究多关注传统FER模型，对LMFMs中的种族偏见理解不足。我们评估了GPT-4o、PaliGemma、Gemini和CLIP这四个领先模型在不同种族群体中面部情感检测的性能。基于CLIP嵌入训练的线性分类器在RADIATE、Tarr和Chicago Face上的准确率分别为95.9%、90.3%和99.5%。研究发现，黑人女性中愤怒被误分类为厌恶的频率是白人女性的2.1倍。本研究强调了开发更公平FER系统的必要性，并为无偏见、准确FER技术的发展奠定了基础。更多信息请访问https://kvjvhub.github.io/FERRacialBias/。

> This study addresses the racial biases in facial expression recognition (FER) systems within Large Multimodal Foundation Models (LMFMs). Despite advances in deep learning and the availability of diverse datasets, FER systems often exhibit higher error rates for individuals with darker skin tones. Existing research predominantly focuses on traditional FER models (CNNs, RNNs, ViTs), leaving a gap in understanding racial biases in LMFMs. We benchmark four leading LMFMs: GPT-4o, PaliGemma, Gemini, and CLIP to assess their performance in facial emotion detection across different racial demographics. A linear classifier trained on CLIP embeddings obtains accuracies of 95.9\% for RADIATE, 90.3\% for Tarr, and 99.5\% for Chicago Face. Furthermore, we identify that Anger is misclassified as Disgust 2.1 times more often in Black Females than White Females. This study highlights the need for fairer FER systems and establishes a foundation for developing unbiased, accurate FER technologies. Visit https://kvjvhub.github.io/FERRacialBias/ for further information regarding the biases within facial expression recognition.

[Arxiv](https://arxiv.org/abs/2408.14842)