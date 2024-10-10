# 多功能运动语言模型助力多轮交互代理

发布时间：2024年10月07日

`LLM应用` `人工智能` `运动控制`

> Versatile Motion Langauge Models for Multi-Turn Interactive Agents

# 摘要

> 大型语言模型 (LLM) 的进步使其生成自然且上下文相关的文本能力大幅提升，使 AI 交互更加人性化。然而，生成和理解交互式类人运动，尤其是两人协调运动，仍具挑战性。此外，处理多样交互场景（如遵循用户指令或适应角色的聊天系统）需要多功能模型。为此，我们推出 VIM，一种集语言与运动模态于一体的多功能交互运动语言模型，旨在多轮对话中有效理解、生成和控制交互运动。为弥补多轮交互运动数据的不足，我们创建了合成数据集 INERT-MT2。首先，训练运动标记器将交互运动编码为离散标记。预训练阶段，模型学习对齐运动与文本表示。指令微调阶段，VIM 适应多轮对话。我们评估了 VIM 在运动到文本、文本到运动、反应生成、运动编辑和运动序列推理等任务中的表现，结果显示其在复杂交互运动合成中的多功能性和有效性。

> Recent advancements in large language models (LLMs) have greatly enhanced their ability to generate natural and contextually relevant text, making AI interactions more human-like. However, generating and understanding interactive human-like motion, where two individuals engage in coordinated movements, remains a challenge due to the complexity of modeling these coordinated interactions. Furthermore, a versatile model is required to handle diverse interactive scenarios, such as chat systems that follow user instructions or adapt to their assigned role while adjusting interaction dynamics. To tackle this problem, we introduce VIM, short for the Versatile Interactive Motion language model, which integrates both language and motion modalities to effectively understand, generate, and control interactive motions in multi-turn conversational contexts. To address the scarcity of multi-turn interactive motion data, we introduce a synthetic dataset, INERT-MT2, where we utilize pre-trained models to create diverse instructional datasets with interactive motion. Our approach first trains a motion tokenizer that encodes interactive motions into residual discrete tokens. In the pretraining stage, the model learns to align motion and text representations with these discrete tokens. During the instruction fine-tuning stage, VIM adapts to multi-turn conversations using the INTER-MT2 dataset. We evaluate the versatility of our method across motion-related tasks, motion to text, text to motion, reaction generation, motion editing, and reasoning about motion sequences. The results highlight the versatility and effectiveness of proposed method in handling complex interactive motion synthesis.

[Arxiv](https://arxiv.org/abs/2410.05628)