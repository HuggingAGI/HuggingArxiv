# 在识别交通标志前，请三思：我们探讨了用于细粒度识别的大型多模态模型。

发布时间：2024年09月02日

`LLM应用` `人工智能`

> Think Twice Before Recognizing: Large Multimodal Models for General Fine-grained Traffic Sign Recognition

# 摘要

> 我们创新性地提出了“先思后认”策略，旨在提升细粒度交通标志识别的精准度。面对野外复杂多变的道路环境，尤其是数据匮乏时的跨区域识别难题，我们的方法通过激发大型多模态模型的深度思考能力，巧妙地引入了上下文、特征及差异性描述，为模型构建了多维思考路径。通过优化中心坐标提示，模型能精准定位并筛选出目标交通标志；基于少样本学习的特征描述则有效缩小了跨域识别的鸿沟；而差异性描述更是进一步磨砺了模型的多模态识别技艺。这一方法不依赖繁复的训练数据，仅需简洁明了的指令，便在多个国际数据集上展现了卓越的识别性能，刷新了行业标杆。

> We propose a new strategy called think twice before recognizing to improve fine-grained traffic sign recognition (TSR). Fine-grained TSR in the wild is difficult due to the complex road conditions, and existing approaches particularly struggle with cross-country TSR when data is lacking. Our strategy achieves effective fine-grained TSR by stimulating the multiple-thinking capability of large multimodal models (LMM). We introduce context, characteristic, and differential descriptions to design multiple thinking processes for the LMM. The context descriptions with center coordinate prompt optimization help the LMM to locate the target traffic sign in the original road images containing multiple traffic signs and filter irrelevant answers through the proposed prior traffic sign hypothesis. The characteristic description is based on few-shot in-context learning of template traffic signs, which decreases the cross-domain difference and enhances the fine-grained recognition capability of the LMM. The differential descriptions of similar traffic signs optimize the multimodal thinking capability of the LMM. The proposed method is independent of training data and requires only simple and uniform instructions. We conducted extensive experiments on three benchmark datasets and two real-world datasets from different countries, and the proposed method achieves state-of-the-art TSR results on all five datasets.

[Arxiv](https://arxiv.org/abs/2409.01534)