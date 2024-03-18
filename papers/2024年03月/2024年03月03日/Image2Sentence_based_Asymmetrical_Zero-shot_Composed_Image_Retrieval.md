# [Image2Sentence 技术驱动的非对称零样本图像组合检索方法，旨在实现仅通过文本描述即可检索未见过的组合图像。](https://arxiv.org/abs/2403.01431)

发布时间：2024年03月03日

`Agent`

> Image2Sentence based Asymmetrical Zero-shot Composed Image Retrieval

> CIR 任务旨在依据用户意图描述的文本和查询图像精准检索目标图像。当前方法虽已凭借先进VL模型在 CIR 中取得长足进步，但依然面临两大挑战：匮乏的有标注训练三元组及在资源有限环境部署大型VL模型时的困境。为此，我们创新性地提出Image2Sentence驱动的不对称零样本组合图像检索方案——ISA，巧妙运用VL模型，并仅依靠无标注图像完成组合学习。此方案中，我们设计出新颖的自适应词元学习器，可在VL模型的词嵌入空间内将图像转化为能够灵活捕捉关键视觉特征的句子，并将其与文本修饰语深度融合。同时，我们构思了一种不对称架构，使得轻量级模型负责处理查询端，而大型VL模型部署于图库端。通过应用全局对比蒸馏和局部对齐正则化技术，确保轻量级模型与VL模型在执行CIR任务时保持良好对齐。实验证明，所提出的ISA方案在真实检索场景下表现更优，有效提升了检索精度和效率。

> The task of composed image retrieval (CIR) aims to retrieve images based on the query image and the text describing the users' intent. Existing methods have made great progress with the advanced large vision-language (VL) model in CIR task, however, they generally suffer from two main issues: lack of labeled triplets for model training and difficulty of deployment on resource-restricted environments when deploying the large vision-language model. To tackle the above problems, we propose Image2Sentence based Asymmetric zero-shot composed image retrieval (ISA), which takes advantage of the VL model and only relies on unlabeled images for composition learning. In the framework, we propose a new adaptive token learner that maps an image to a sentence in the word embedding space of VL model. The sentence adaptively captures discriminative visual information and is further integrated with the text modifier. An asymmetric structure is devised for flexible deployment, in which the lightweight model is adopted for the query side while the large VL model is deployed on the gallery side. The global contrastive distillation and the local alignment regularization are adopted for the alignment between the light model and the VL model for CIR task. Our experiments demonstrate that the proposed ISA could better cope with the real retrieval scenarios and further improve retrieval accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2403.01431)