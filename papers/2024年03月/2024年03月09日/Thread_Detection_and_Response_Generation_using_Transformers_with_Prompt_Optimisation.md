# 通过优化提示的Transformer模型实现对线程的精准检测与智能响应生成

发布时间：2024年03月09日

`Agent`

> Thread Detection and Response Generation using Transformers with Prompt Optimisation

> 对话系统作为人机交互的关键，能通过识别对话线索并优先回应来驾驭复杂对话，尤其在多方交流场合，精准捕捉线索及策略性安排回应顺序是保证对话高效管理的核心。为此，我们研发了一款端到端模型，它能根据对话的重要性识别线索并优先生成回复，通过将问题分解成可操作的模块——线索识别、优先级排序和性能优化，并深入剖析与优化这三个环节。这些精心雕琢的模块完美融入对话系统的统一架构之中，目前选用的是 Llama2 7b 模型，因其具备出色的泛化能力，当然未来也可配合任何开源大型语言模型 (LLM) 进行升级。为了进一步提升 Llama2 模型的运算效能，我们运用了微调技术和策略性提示手段，有效缩短了计算时间，提高了模型精确度。最终，这款模型不仅将速度提升了高达10倍，还相较现有模型生成了更为连贯的对话内容。

> Conversational systems are crucial for human-computer interaction, managing complex dialogues by identifying threads and prioritising responses. This is especially vital in multi-party conversations, where precise identification of threads and strategic response prioritisation ensure efficient dialogue management. To address these challenges an end-to-end model that identifies threads and prioritises their response generation based on the importance was developed, involving a systematic decomposition of the problem into discrete components - thread detection, prioritisation, and performance optimisation which was meticulously analysed and optimised. These refined components seamlessly integrate into a unified framework, in conversational systems. Llama2 7b is used due to its high level of generalisation but the system can be updated with any open source Large Language Model(LLM). The computational capabilities of the Llama2 model was augmented by using fine tuning methods and strategic prompting techniques to optimise the model's performance, reducing computational time and increasing the accuracy of the model. The model achieves up to 10x speed improvement, while generating more coherent results compared to existing models.

[Arxiv](https://arxiv.org/abs/2403.05931)