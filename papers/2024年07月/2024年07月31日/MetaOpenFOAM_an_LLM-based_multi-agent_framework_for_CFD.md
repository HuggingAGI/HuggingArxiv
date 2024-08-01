# MetaOpenFOAM：一款基于大型语言模型的多智能体框架，专为计算流体动力学设计。

发布时间：2024年07月31日

`Agent` `流体动力学`

> MetaOpenFOAM: an LLM-based multi-agent framework for CFD

# 摘要

> 基于大型语言模型（LLM）的代理社会在自动问题解决方面取得了显著进展。计算流体动力学（CFD）作为一个复杂问题，在自动模拟中提出了独特的挑战，需要复杂的解决方案。MetaOpenFOAM，作为一个新颖的多代理协作框架，旨在仅使用自然语言完成CFD模拟任务。这些模拟任务包括网格预处理、模拟和后处理等。MetaOpenFOAM利用了MetaGPT的装配线范式，该范式为不同代理分配多样化的角色，有效地将复杂的CFD任务分解为可管理的子任务。Langchain通过集成检索增强生成（RAG）技术进一步补充了MetaOpenFOAM，该技术通过集成一个可搜索的OpenFOAM教程数据库来增强框架的能力。在一个包含8个CFD模拟任务的自然语言基准测试中，MetaOpenFOAM在每次测试中都取得了高通过率（85%），每个测试案例平均成本仅为$0.22。这8个CFD模拟任务包括可压缩和不可压缩流动、2D和3D流动、热传递和燃烧，展示了仅使用自然语言输入自动化CFD模拟并迭代纠正错误以低成本实现所需模拟的能力。进行了消融研究以验证多代理系统中每个组件和RAG技术的必要性。对LLM随机性的敏感性研究表明，具有较低随机性的LLM可以获得更稳定和准确的结果。此外，MetaOpenFOAM具有识别和修改用户需求中关键参数的能力，并且在发生故障时无论是否有人参与都能出色地纠正错误，这展示了MetaOpenFOAM的泛化能力。

> Remarkable progress has been made in automated problem solving through societies of agents based on large language models (LLMs). Computational fluid dynamics (CFD), as a complex problem, presents unique challenges in automated simulations that require sophisticated solutions. MetaOpenFOAM, as a novel multi-agent collaborations framework, aims to complete CFD simulation tasks with only natural language as input. These simulation tasks include mesh pre-processing, simulation and post-processing, etc. MetaOpenFOAM harnesses the power of MetaGPT's assembly line paradigm, which assigns diverse roles to various agents, efficiently breaking down complex CFD tasks into manageable subtasks. Langchain further complements MetaOpenFOAM by integrating Retrieval-Augmented Generation (RAG) technology, which enhances the framework's ability by integrating a searchable database of OpenFOAM tutorials for LLMs. Tests on a benchmark for natural language-based CFD solver, consisting of 8 CFD simulation tasks, have shown that MetaOpenFOAM achieved a high pass rate per test (85%), with each test case costing only $0.22 on average. The 8 CFD simulation tasks include compressible and incompressible flows, 2D and 3D flows, heat transfer, and combustion, demonstrating the ability to automate CFD simulations using only natural language input and iteratively correct errors to achieve the desired simulation at a low cost. An ablation study was conducted to verify the necessity of each component in the multi-agent system and the RAG technology. A sensitivity study on the randomness of LLM showed that LLM with low randomness can obtain more stable and accurate results. Additionally, MetaOpenFOAM own the ability to identify and modify key parameters in user requirements and excels in correcting bugs when failures occur, with or without human participation, which demonstrates the generalization of MetaOpenFOAM.

[Arxiv](https://arxiv.org/abs/2407.21320)