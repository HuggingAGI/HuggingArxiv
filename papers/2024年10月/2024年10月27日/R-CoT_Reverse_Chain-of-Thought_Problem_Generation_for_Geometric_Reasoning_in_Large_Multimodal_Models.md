# R-CoT：大型多模态模型中几何推理的反向思维链问题生成方式

发布时间：2024年10月27日

`LLM应用` `数据生成`

> R-CoT: Reverse Chain-of-Thought Problem Generation for Geometric Reasoning in Large Multimodal Models

# 摘要

> 现有的大型多模态模型（LMMs）因缺少优质的图像-文本配对数据，在数学几何推理上表现不佳。当下的几何数据生成手段，不是运用预设模板来生成几何数据，就是利用大型语言模型（LLMs）重新阐述问题与答案（Q&A），这无可避免地制约了数据的准确性和多样性。为合成更优质的数据，我们提出了一个两阶段的反向思维链（R-CoT）几何问题生成流程。首先，引入 GeoChain 来生成高保真几何图像以及相应的凸显几何元素间关系的描述。接着，设计一种反向问答方法，基于这些描述逐步推理，并从推理结果反向生成问题。实验显示，所提方法在多个 LMM 基线模型上有显著且一致的提升，在 2B、7B 和 8B 设定中创下新的性能纪录。特别要指出的是，R-CoT-8B 在 MathVista 上比之前最先进的开源数学模型高出 16.6％，在 GeoQA 上高出 9.2％，同时在两个数据集上平均也比闭源模型 GPT-4o 超出 13％。相关代码可在 https://github.com/dle666/R-CoT 获取。

> Existing Large Multimodal Models (LMMs) struggle with mathematical geometric reasoning due to a lack of high-quality image-text paired data. Current geometric data generation approaches, which apply preset templates to generate geometric data or use Large Language Models (LLMs) to rephrase questions and answers (Q&A), unavoidably limit data accuracy and diversity. To synthesize higher-quality data, we propose a two-stage Reverse Chain-of-Thought (R-CoT) geometry problem generation pipeline. First, we introduce GeoChain to produce high-fidelity geometric images and corresponding descriptions highlighting relations among geometric elements. We then design a Reverse A&Q method that reasons step-by-step based on the descriptions and generates questions in reverse from the reasoning results. Experiments demonstrate that the proposed method brings significant and consistent improvements on multiple LMM baselines, achieving new performance records in the 2B, 7B, and 8B settings. Notably, R-CoT-8B significantly outperforms previous state-of-the-art open-source mathematical models by 16.6% on MathVista and 9.2% on GeoQA, while also surpassing the closed-source model GPT-4o by an average of 13% across both datasets. The code is available at https://github.com/dle666/R-CoT.

[Arxiv](https://arxiv.org/abs/2410.17885)