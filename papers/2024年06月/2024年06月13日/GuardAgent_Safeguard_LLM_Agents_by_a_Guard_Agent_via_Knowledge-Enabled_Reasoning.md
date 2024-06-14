# GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士

发布时间：2024年06月13日

`Agent

这篇论文介绍了一个名为GuardAgent的LLM驱动的代理，其目的是作为其他LLM代理的安全屏障。它通过监控目标LLM代理的输入/输出，并确保它们符合用户设定的防护请求来实现这一目标。论文中提到的GuardAgent的工作流程、其作为核心推理引擎的LLM、以及其可扩展的工具箱，都表明这是一个关于Agent的应用和设计。因此，这篇论文应归类于Agent分类。` `网络安全` `医疗保健`

> GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning

# 摘要

> 随着大型语言模型（LLMs）技术的飞速进步，LLM驱动的代理在多个领域广泛应用，同时也带来了对其安全性和可信度的新挑战。由于目标和输出模式的多样性，现有的LLMs安全增强方法难以直接应用于这些代理。为此，我们提出了GuardAgent，首个作为其他LLM代理安全屏障的LLM代理。GuardAgent通过监控目标LLM代理的输入/输出，确保它们符合用户设定的防护请求。其工作流程包括两个关键步骤：首先，通过分析防护请求制定任务计划；其次，依据任务计划生成并执行护栏代码，这一过程通过调用API或利用外部引擎实现。在整个过程中，LLM作为核心推理引擎，辅以从内存模块中提取的上下文示例，确保GuardAgent能准确理解并执行各种文本防护请求，将其转化为可靠的执行代码。GuardAgent还配备了一个包含丰富函数和API的可扩展工具箱，无需额外训练，展现了其强大的泛化能力和低操作成本。此外，我们推出了两个创新基准：EICU-AC用于评估医疗保健代理的隐私访问控制，Mind2Web-SC用于评估网络代理的安全性。实验结果显示，GuardAgent在这两个基准上分别实现了98.7%和90.0%的准确率，有效管理了无效的输入和输出。此外，GuardAgent还能根据新兴的LLM代理和防护请求灵活定义新功能，进一步证明了其卓越的泛化能力。

> The rapid advancement of large language models (LLMs) has catalyzed the deployment of LLM-powered agents across numerous applications, raising new concerns regarding their safety and trustworthiness. Existing methods for enhancing the safety of LLMs are not directly transferable to LLM-powered agents due to their diverse objectives and output modalities. In this paper, we propose GuardAgent, the first LLM agent as a guardrail to other LLM agents. Specifically, GuardAgent oversees a target LLM agent by checking whether its inputs/outputs satisfy a set of given guard requests defined by the users. GuardAgent comprises two steps: 1) creating a task plan by analyzing the provided guard requests, and 2) generating guardrail code based on the task plan and executing the code by calling APIs or using external engines. In both steps, an LLM is utilized as the core reasoning component, supplemented by in-context demonstrations retrieved from a memory module. Such knowledge-enabled reasoning allows GuardAgent to understand various textual guard requests and accurately "translate" them into executable code that provides reliable guardrails. Furthermore, GuardAgent is equipped with an extendable toolbox containing functions and APIs and requires no additional LLM training, which underscores its generalization capabilities and low operational overhead. Additionally, we propose two novel benchmarks: an EICU-AC benchmark for assessing privacy-related access control for healthcare agents and a Mind2Web-SC benchmark for safety evaluation for web agents. We show the effectiveness of GuardAgent on these two benchmarks with 98.7% and 90.0% accuracy in moderating invalid inputs and outputs for the two types of agents, respectively. We also show that GuardAgent is able to define novel functions in adaption to emergent LLM agents and guard requests, which underscores its strong generalization capabilities.

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/figure1_v3.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/benchmark_example.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/case_study.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/n_demo_eicu-ac.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/n_demo_mind2web-sc.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/access_all.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/access_physician.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/access_nursing.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/access_general_administration.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/access_query.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/prompt_baseline_naive.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/input_system_guardagent.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/input_data_guardagent.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/output_guardagent.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/functions.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/prompt_baseline.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/example_demos.png)

![GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士](../../../paper_images/2406.09187/codegen.png)

[Arxiv](https://arxiv.org/abs/2406.09187)