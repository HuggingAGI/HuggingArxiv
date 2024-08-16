# Text2BIM：借助大型语言模型驱动的多智能体框架，实现建筑模型的生成。

发布时间：2024年08月15日

`Agent` `软件开发`

> Text2BIM: Generating Building Models Using a Large Language Model-based Multi-Agent Framework

# 摘要

> 为了简化设计表达，我们推出了Text2BIM，一个基于大型语言模型的多智能体框架，能将自然语言指令转化为3D建筑模型。该框架通过协调多个智能体，将用户文本输入转化为BIM工具的API调用，直接在软件中生成包含内部布局、外部结构和语义信息的可编辑模型。同时，我们引入了基于规则的模型检查器，利用领域知识优化模型，确保其质量。实验证明，我们的方法能高效生成与用户概念相符的高质量建筑模型。此外，我们还开发了集成该框架的Vectorworks原型软件，展示了通过对话进行建模的可能性。

> The conventional BIM authoring process typically requires designers to master complex and tedious modeling commands in order to materialize their design intentions within BIM authoring tools. This additional cognitive burden complicates the design process and hinders the adoption of BIM and model-based design in the AEC (Architecture, Engineering, and Construction) industry. To facilitate the expression of design intentions more intuitively, we propose Text2BIM, an LLM-based multi-agent framework that can generate 3D building models from natural language instructions. This framework orchestrates multiple LLM agents to collaborate and reason, transforming textual user input into imperative code that invokes the BIM authoring tool's APIs, thereby generating editable BIM models with internal layouts, external envelopes, and semantic information directly in the software. Furthermore, a rule-based model checker is introduced into the agentic workflow, utilizing predefined domain knowledge to guide the LLM agents in resolving issues within the generated models and iteratively improving model quality. Extensive experiments were conducted to compare and analyze the performance of three different LLMs under the proposed framework. The evaluation results demonstrate that our approach can effectively generate high-quality, structurally rational building models that are aligned with the abstract concepts specified by user input. Finally, an interactive software prototype was developed to integrate the framework into the BIM authoring software Vectorworks, showcasing the potential of modeling by chatting.

[Arxiv](https://arxiv.org/abs/2408.08054)