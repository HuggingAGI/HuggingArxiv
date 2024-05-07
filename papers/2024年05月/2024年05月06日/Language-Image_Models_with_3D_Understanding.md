# 融合3D理解的语言与图像模型

发布时间：2024年05月06日

`LLM应用` `计算机视觉`

> Language-Image Models with 3D Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在二维视觉和语言任务中展现了卓越性能。本研究进一步拓展了MLLMs的感知范畴，使其能够在三维空间中对图像进行定位和推理。为此，我们创建了一个名为LV3D的大规模预训练数据集，整合了多个现有的二维和三维识别数据集，以多轮问答的形式统一构建任务。随后，我们推出了一款新的MLLM——Cube-LLM，并在LV3D上对其进行了预训练。我们发现，仅通过数据规模的增长，即使没有特定的三维架构设计或训练目标，也能显著提升三维感知能力。Cube-LLM展现出了与LLMs相似的特质：（1）能够通过思维链提示增强从二维信息中理解三维场景的能力；（2）能够遵循复杂多样的指令，并适应多变的输入输出格式；（3）能够通过视觉提示，如二维框或专家提供的一组候选三维框，进行交互。在户外基准测试中，Cube-LLM在3D地面推理任务上以21.3点的AP-BEV得分超越了现有基准，在DriveLM数据集上针对复杂驾驶场景推理的任务上也以17.7点的优势领先。此外，Cube-LLM在通用MLLM基准测试如refCOCO的二维定位任务中取得了87.0的平均分，并在视觉问答基准测试如VQAv2、GQA、SQA、POPE等中展现了强劲的竞争力。项目详情可访问 https://janghyuncho.github.io/Cube-LLM。

> Multi-modal large language models (MLLMs) have shown incredible capabilities in a variety of 2D vision and language tasks. We extend MLLMs' perceptual capabilities to ground and reason about images in 3-dimensional space. To that end, we first develop a large-scale pre-training dataset for 2D and 3D called LV3D by combining multiple existing 2D and 3D recognition datasets under a common task formulation: as multi-turn question-answering. Next, we introduce a new MLLM named Cube-LLM and pre-train it on LV3D. We show that pure data scaling makes a strong 3D perception capability without 3D specific architectural design or training objective. Cube-LLM exhibits intriguing properties similar to LLMs: (1) Cube-LLM can apply chain-of-thought prompting to improve 3D understanding from 2D context information. (2) Cube-LLM can follow complex and diverse instructions and adapt to versatile input and output formats. (3) Cube-LLM can be visually prompted such as 2D box or a set of candidate 3D boxes from specialists. Our experiments on outdoor benchmarks demonstrate that Cube-LLM significantly outperforms existing baselines by 21.3 points of AP-BEV on the Talk2Car dataset for 3D grounded reasoning and 17.7 points on the DriveLM dataset for complex reasoning about driving scenarios, respectively. Cube-LLM also shows competitive results in general MLLM benchmarks such as refCOCO for 2D grounding with (87.0) average score, as well as visual question answering benchmarks such as VQAv2, GQA, SQA, POPE, etc. for complex reasoning. Our project is available at https://janghyuncho.github.io/Cube-LLM.

[Arxiv](https://arxiv.org/abs/2405.03685)