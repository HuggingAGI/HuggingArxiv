# 细粒度人脸伪造检测：常识推理的实用指南

发布时间：2024年10月01日

`LLM应用` `人工智能`

> A Hitchhikers Guide to Fine-Grained Face Forgery Detection Using Common Sense Reasoning

# 摘要

> 人工智能的可解释性在恢复信任方面至关重要，尤其是在人脸伪造检测中，观众常难以分辨真伪。视觉与大型语言模型（VLLM）结合了计算机视觉与自然语言，通过强大的常识推理推动了众多应用。尽管在多任务中表现出色，但VLLM在人脸伪造检测中的潜力仍待挖掘，尤其是在利用语言的内在推理能力分析细微操纵区域以增强可解释性方面。为此，我们提出将人脸伪造检测转化为视觉问答（VQA）任务，以系统评估这些能力。先前的深度伪造检测基准多聚焦于简单的二元任务，忽视了细粒度检测与文本生成模型的评估。我们的多阶段方法突破了传统二元决策框架：首先评估模型在二元任务上的表现及对指令的敏感性；其次，通过多项选择VQA识别操纵区域，深入细粒度检测；再次，将细粒度检测转为开放式问题，比较多种匹配策略以优化多标签分类。最后，我们定性评估基准中VLLM的细粒度响应。通过在七个数据集上对多个流行模型进行二元、多项选择及开放式VQA的详细比较，我们的基准为这一领域提供了新的视角。

> Explainability in artificial intelligence is crucial for restoring trust, particularly in areas like face forgery detection, where viewers often struggle to distinguish between real and fabricated content. Vision and Large Language Models (VLLM) bridge computer vision and natural language, offering numerous applications driven by strong common-sense reasoning. Despite their success in various tasks, the potential of vision and language remains underexplored in face forgery detection, where they hold promise for enhancing explainability by leveraging the intrinsic reasoning capabilities of language to analyse fine-grained manipulation areas. As such, there is a need for a methodology that converts face forgery detection to a Visual Question Answering (VQA) task to systematically and fairly evaluate these capabilities. Previous efforts for unified benchmarks in deepfake detection have focused on the simpler binary task, overlooking evaluation protocols for fine-grained detection and text-generative models. We propose a multi-staged approach that diverges from the traditional binary decision paradigm to address this gap. In the first stage, we assess the models' performance on the binary task and their sensitivity to given instructions using several prompts. In the second stage, we delve deeper into fine-grained detection by identifying areas of manipulation in a multiple-choice VQA setting. In the third stage, we convert the fine-grained detection to an open-ended question and compare several matching strategies for the multi-label classification task. Finally, we qualitatively evaluate the fine-grained responses of the VLLMs included in the benchmark. We apply our benchmark to several popular models, providing a detailed comparison of binary, multiple-choice, and open-ended VQA evaluation across seven datasets. \url{https://nickyfot.github.io/hitchhickersguide.github.io/}

[Arxiv](https://arxiv.org/abs/2410.00485)