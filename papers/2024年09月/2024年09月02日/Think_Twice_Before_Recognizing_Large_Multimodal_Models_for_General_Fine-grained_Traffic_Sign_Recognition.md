# 在识别交通标志前，请三思：探讨用于细粒度识别的大型多模态模型

发布时间：2024年09月02日

`LLM应用` `人工智能`

> Think Twice Before Recognizing: Large Multimodal Models for General Fine-grained Traffic Sign Recognition

# 摘要

> 我们创新性地提出了“先思后识”策略，旨在提升细粒度交通标志识别（TSR）的准确性。面对野外复杂道路条件的挑战，尤其是数据匮乏时的跨区域TSR难题，我们的方法通过激发大型多模态模型（LMM）的深度思考能力，实现了显著的识别效果提升。我们巧妙地结合上下文、特征和差异描述，为LMM构建了精密的多思流程。通过中心坐标提示优化，上下文描述助力LMM精准定位目标交通标志，并有效排除干扰。基于少样本学习的特征描述，则大幅缩小了跨域识别的鸿沟，强化了LMM的细粒度识别力。而差异描述的应用，进一步优化了LMM在处理相似交通标志时的多模态思考能力。值得一提的是，我们的方法无需依赖繁琐的训练数据，仅需简洁明了的指令即可。经过在多个国际基准和真实世界数据集上的广泛验证，我们的方法在所有测试集上均达到了业界领先水平。

> We propose a new strategy called think twice before recognizing to improve fine-grained traffic sign recognition (TSR). Fine-grained TSR in the wild is difficult due to the complex road conditions, and existing approaches particularly struggle with cross-country TSR when data is lacking. Our strategy achieves effective fine-grained TSR by stimulating the multiple-thinking capability of large multimodal models (LMM). We introduce context, characteristic, and differential descriptions to design multiple thinking processes for the LMM. The context descriptions with center coordinate prompt optimization help the LMM to locate the target traffic sign in the original road images containing multiple traffic signs and filter irrelevant answers through the proposed prior traffic sign hypothesis. The characteristic description is based on few-shot in-context learning of template traffic signs, which decreases the cross-domain difference and enhances the fine-grained recognition capability of the LMM. The differential descriptions of similar traffic signs optimize the multimodal thinking capability of the LMM. The proposed method is independent of training data and requires only simple and uniform instructions. We conducted extensive experiments on three benchmark datasets and two real-world datasets from different countries, and the proposed method achieves state-of-the-art TSR results on all five datasets.

[Arxiv](https://arxiv.org/abs/2409.01534)