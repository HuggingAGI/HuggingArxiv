# PPTC-R基准测试旨在深入探究大型语言模型在应对PowerPoint任务挑战时的稳健性表现。

发布时间：2024年03月06日

`Agent`

> PPTC-R benchmark: Towards Evaluating the Robustness of Large Language Models for PowerPoint Task Completion

> 随着LLMs在实际操作中承担更多用户指令执行的责任，其应对复杂任务挑战的稳健性亟待全面探究。为此，我们设计了一个名为PPTC-R的PowerPoint任务完成稳健性基准，该基准能够衡量LLMs在不同用户PPT任务指令和软件版本情境下的适应力。我们构造了针对句子、语义及跨语言层面的对抗性用户指令，同时通过调整API接口数量模拟新旧版本软件环境，以此检测LLMs对软件版本变更的抗干扰能力。我们运用这个包含了各类稳健性测试场景的基准，对3款闭源和4款开源LLMs进行了评估，重点关注微小变化对LLMs完成任务所需API调用的影响。实验揭示了GPT-4在该基准测试中不仅表现出卓越的性能，而且尤其在版本升级与多语言环境中展现了极强的稳健性。不过，当LLMs需要同时应对多个难题（如连续对话交互）时，所有模型的稳健性均有不同程度的下滑，造成明显性能衰退。我们深入剖析了LLMs在基准测试中的稳健性表现及其出错原因，为科研人员深入了解LLMs任务完成过程中的稳健性特征以及研发更为坚固的LLMs与智能代理提供了宝贵洞见。相关代码与数据现已公开在GitHub项目地址<https://github.com/ZekaiGalaxy/PPTCR>。

> The growing dependence on Large Language Models (LLMs) for finishing user instructions necessitates a comprehensive understanding of their robustness to complex task completion in real-world situations. To address this critical need, we propose the PowerPoint Task Completion Robustness benchmark (PPTC-R) to measure LLMs' robustness to the user PPT task instruction and software version. Specifically, we construct adversarial user instructions by attacking user instructions at sentence, semantic, and multi-language levels. To assess the robustness of Language Models to software versions, we vary the number of provided APIs to simulate both the newest version and earlier version settings. Subsequently, we test 3 closed-source and 4 open-source LLMs using a benchmark that incorporates these robustness settings, aiming to evaluate how deviations impact LLMs' API calls for task completion. We find that GPT-4 exhibits the highest performance and strong robustness in our benchmark, particularly in the version update and the multilingual settings. However, we find that all LLMs lose their robustness when confronted with multiple challenges (e.g., multi-turn) simultaneously, leading to significant performance drops. We further analyze the robustness behavior and error reasons of LLMs in our benchmark, which provide valuable insights for researchers to understand the LLM's robustness in task completion and develop more robust LLMs and agents. We release the code and data at \url{https://github.com/ZekaiGalaxy/PPTCR}.

[Arxiv](https://arxiv.org/abs/2403.03788)