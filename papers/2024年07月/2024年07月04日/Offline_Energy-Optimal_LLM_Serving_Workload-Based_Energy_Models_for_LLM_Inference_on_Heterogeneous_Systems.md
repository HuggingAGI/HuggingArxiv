# 离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。

发布时间：2024年07月04日

`LLM应用` `人工智能`

> Offline Energy-Optimal LLM Serving: Workload-Based Energy Models for LLM Inference on Heterogeneous Systems

# 摘要

> 随着大型语言模型（LLM）的广泛应用，自然语言处理和文本生成领域取得了巨大进展。但LLM推理过程中的高能耗，成为可持续AI部署的一大难题。为此，我们针对异构GPU-CPU系统，构建了依赖于工作负载的LLM推理任务能耗与运行时间模型。通过深入分析多个前沿LLM在不同输入输出规模下的能耗与运行表现，我们为每个LLM量身定制了高精度（R^2>0.96）的能耗与运行模型。基于这些模型，我们探索了一种离线、追求能耗最优的LLM工作负载调度框架，并通过实证研究，验证了该框架在能耗与精度方面相较于传统最佳实践的显著优势。

> The rapid adoption of large language models (LLMs) has led to significant advances in natural language processing and text generation. However, the energy consumed through LLM model inference remains a major challenge for sustainable AI deployment. To address this problem, we model the workload-dependent energy consumption and runtime of LLM inference tasks on heterogeneous GPU-CPU systems. By conducting an extensive characterization study of several state-of-the-art LLMs and analyzing their energy and runtime behavior across different magnitudes of input prompts and output text, we develop accurate (R^2>0.96) energy and runtime models for each LLM. We employ these models to explore an offline, energy-optimal LLM workload scheduling framework. Through a case study, we demonstrate the advantages of energy and accuracy aware scheduling compared to existing best practices.

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x1.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x2.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x3.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x4.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x5.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x6.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x7.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x8.png)

![离线模式下，LLM 服务追求能量最优：针对异构系统中 LLM 推理，构建基于工作负载的能量模型。](../../../paper_images/2407.04014/x9.png)

[Arxiv](https://arxiv.org/abs/2407.04014)