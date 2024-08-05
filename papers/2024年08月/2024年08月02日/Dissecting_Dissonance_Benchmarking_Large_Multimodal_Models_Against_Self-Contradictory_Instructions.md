# 深入解析矛盾：在自相矛盾的指令下，对大型多模态模型进行性能基准测试

发布时间：2024年08月02日

`LLM应用` `人工智能`

> Dissecting Dissonance: Benchmarking Large Multimodal Models Against Self-Contradictory Instructions

# 摘要

> 大型多模态模型 (LMMs) 擅长遵循人类指令，但随着多模态交互和上下文长度的增加，自相矛盾的指令可能出现，对语言初学者和弱势群体构成挑战。为此，我们创建了自相矛盾指令基准，包含 20,000 个冲突，均匀分布于语言和视觉领域，通过创新的自动数据集创建框架构建。全面评估显示，LMMs 因缺乏自我意识而难以识别指令冲突。我们提出认知唤醒提示，通过外部认知注入，显著提升冲突检测能力。数据集和代码详见：https://selfcontradiction.github.io/。

> Large multimodal models (LMMs) excel in adhering to human instructions. However, self-contradictory instructions may arise due to the increasing trend of multimodal interaction and context length, which is challenging for language beginners and vulnerable populations. We introduce the Self-Contradictory Instructions benchmark to evaluate the capability of LMMs in recognizing conflicting commands. It comprises 20,000 conflicts, evenly distributed between language and vision paradigms. It is constructed by a novel automatic dataset creation framework, which expedites the process and enables us to encompass a wide range of instruction forms. Our comprehensive evaluation reveals current LMMs consistently struggle to identify multimodal instruction discordance due to a lack of self-awareness. Hence, we propose the Cognitive Awakening Prompting to inject cognition from external, largely enhancing dissonance detection. The dataset and code are here: https://selfcontradiction.github.io/.

[Arxiv](https://arxiv.org/abs/2408.01091)