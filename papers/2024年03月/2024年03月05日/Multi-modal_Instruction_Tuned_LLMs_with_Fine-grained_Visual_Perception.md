# [通过细粒度视觉感知优化的多模态指令训练LLM技术，使模型能够更好地理解并融合多种模态信息，特别是在处理包含丰富视觉元素的任务时。](https://arxiv.org/abs/2403.02969)

> Multi-modal Instruction Tuned LLMs with Fine-grained Visual Perception

发布时间：2024年03月05日

> MLLM巧妙运用大型语言模型构建了一个处理多元视觉-语言任务的强大认知体系。尽管已有努力让其具备视觉感知与定位功能，但在提供精细至像素级的感知以及拓展超文本输入以外的交互上仍有不足。为此，我们提出了一种名为{\bf{AnyRef}}的通用MLLM模型，它能从文本、边框、图像甚至音频等多种模态参照中生成逐像素对象感知及自然语言描述。此创新赋予用户更大灵活性，使其能够在无须依赖特定模态设计的情况下，与模型以更为丰富的方式互动。我们独创的“重聚焦”机制确保生成的定位输出能够精准聚焦于所指对象，无形中引入了像素级的深层监督，而这一改进仅通过对LLM推理时生成的注意力得分加以利用，无需增加额外计算成本，却能在定位掩膜和指代表达生成方面显著提升性能。仅凭公开的训练数据，我们的模型已在多个基准测试中力拔头筹，涵盖了各类模态的指代分割任务以及区域级别的指代表达生成任务。

> Multimodal Large Language Model (MLLMs) leverages Large Language Models as a cognitive framework for diverse visual-language tasks. Recent efforts have been made to equip MLLMs with visual perceiving and grounding capabilities. However, there still remains a gap in providing fine-grained pixel-level perceptions and extending interactions beyond text-specific inputs. In this work, we propose {\bf{AnyRef}}, a general MLLM model that can generate pixel-wise object perceptions and natural language descriptions from multi-modality references, such as texts, boxes, images, or audio. This innovation empowers users with greater flexibility to engage with the model beyond textual and regional prompts, without modality-specific designs. Through our proposed refocusing mechanism, the generated grounding output is guided to better focus on the referenced object, implicitly incorporating additional pixel-level supervision. This simple modification utilizes attention scores generated during the inference of LLM, eliminating the need for extra computations while exhibiting performance enhancements in both grounding masks and referring expressions. With only publicly available training data, our model achieves state-of-the-art results across multiple benchmarks, including diverse modality referring segmentation and region-level referring expression generation.

`Agent`