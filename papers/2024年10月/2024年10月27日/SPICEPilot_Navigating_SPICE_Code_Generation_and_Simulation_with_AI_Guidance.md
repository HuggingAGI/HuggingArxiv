# SPICEPilot：借助人工智能指引，驾驭 SPICE 代码生成与仿真

发布时间：2024年10月27日

`LLM应用` `代码生成`

> SPICEPilot: Navigating SPICE Code Generation and Simulation with AI Guidance

# 摘要

> 大型语言模型（LLMs）在自动化代码生成领域展现出极大的潜力；但由于缺乏硬件方面的特定知识，其生成精确电路级 SPICE 代码的能力尚有不足。本文中，我们对现有 LLMs 在 SPICE 代码生成方面的典型局限进行了分析和确认。为克服这些局限，我们推出了 SPICEPilot，这是一个借助 PySpice 生成的基于 Python 的全新数据集，还有配套框架。这在各种电路配置的 SPICE 代码生成自动化进程中是重大的一步。我们的框架实现了 SPICE 模拟脚本的自动创建，引入了标准化的基准指标以评估 LLM 的电路生成能力，并描绘出将 LLMs 融入硬件设计流程的路线图。SPICEPilot 在宽松的 MIT 许可证下于 https://github.com/ACADLab/SPICEPilot.git 开源。

> Large Language Models (LLMs) have shown great potential in automating code generation; however, their ability to generate accurate circuit-level SPICE code remains limited due to a lack of hardware-specific knowledge. In this paper, we analyze and identify the typical limitations of existing LLMs in SPICE code generation. To address these limitations, we present SPICEPilot a novel Python-based dataset generated using PySpice, along with its accompanying framework. This marks a significant step forward in automating SPICE code generation across various circuit configurations. Our framework automates the creation of SPICE simulation scripts, introduces standardized benchmarking metrics to evaluate LLM's ability for circuit generation, and outlines a roadmap for integrating LLMs into the hardware design process. SPICEPilot is open-sourced under the permissive MIT license at https://github.com/ACADLab/SPICEPilot.git.

[Arxiv](https://arxiv.org/abs/2410.20553)