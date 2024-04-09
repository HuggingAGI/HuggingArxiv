# 探究大型语言模型的推理能力：构建新评估体系、推理资源库，并深入分析其逐步推理过程。

发布时间：2024年04月08日

`LLM理论` `推理评估` `自动化工具`

> LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models

# 摘要

> 对于大型语言模型（LLMs）而言，精确地生成逐步推理是解决复杂问题、提升模型鲁棒性和解释力的关键。尽管研究不断推进高级推理技术，但系统性地分析各种LLMs和推理策略在构建推理链条上的表现仍是一大难题。这主要因为缺少两个核心要素：一是自动化评估不同任务中推理链条的方法；二是统一的形式化框架和实现多样化推理方法，以便进行系统性比较。本文力图填补这一空白：首先，我们提出了AutoRace，一个全自动推理链条评估工具。与传统依赖高昂人工注释或固定LLM提示的度量方法不同，AutoRace能够自动生成针对特定任务的详尽评估标准，并利用GPT-4依据这些标准进行精确评估。其次，我们构建了LLM Reasoners库，它以统一的结构实现了现有及新型推理算法的标准化模块化。借助这一新评估工具和库，我们深入研究了多种推理方法（如CoT、ToT、RAP）。研究结果揭示了影响推理的多个有趣因素，包括奖励机制的引导作用、搜索策略中的广度与深度权衡、世界模型的应用，以及提示格式的多样性等。

> Generating accurate step-by-step reasoning is essential for Large Language Models (LLMs) to address complex problems and enhance robustness and interpretability. Despite the flux of research on developing advanced reasoning approaches, systematically analyzing the diverse LLMs and reasoning strategies in generating reasoning chains remains a significant challenge. The difficulties stem from the lack of two key elements: (1) an automatic method for evaluating the generated reasoning chains on different tasks, and (2) a unified formalism and implementation of the diverse reasoning approaches for systematic comparison. This paper aims to close the gap: (1) We introduce AutoRace for fully automated reasoning chain evaluation. Existing metrics rely on expensive human annotations or pre-defined LLM prompts not adaptable to different tasks. In contrast, AutoRace automatically creates detailed evaluation criteria tailored for each task, and uses GPT-4 for accurate evaluation following the criteria. (2) We develop LLM Reasoners, a library for standardized modular implementation of existing and new reasoning algorithms, under a unified formulation of the search, reward, and world model components. With the new evaluation and library, (3) we conduct extensive study of different reasoning approaches (e.g., CoT, ToT, RAP). The analysis reveals interesting findings about different factors contributing to reasoning, including the reward-guidance, breadth-vs-depth in search, world model, and prompt formats, etc.

[Arxiv](https://arxiv.org/abs/2404.05221)