# Auto-SPICE：借助从模拟电路图自动提取 SPICE 网表，利用大型语言模型来创建数据集

发布时间：2024年11月21日

`LLM应用` `集成电路` `电路设计`

> Auto-SPICE: Leveraging LLMs for Dataset Creation via Automated SPICE Netlist Extraction from Analog Circuit Diagrams

# 摘要

> Auto-SPICE 乃是首个借助大型语言模型（LLMs）来生成集成电路重点模拟程序（SPICE）网表的全自动化框架。它化解了电路设计自动化中模拟电路网表生成自动化这一长期难题。实现此工作流程的自动化能够加快为模拟电路设计和验证打造微调后的 LLMs。我们明确了这一自动化过程中的关键挑战，并评估了前沿 LLMs（尤其是 GPT-4）的多模态能力来应对这些问题。我们提出了一个包含三步的工作流程以突破当下的局限：标记模拟电路、调整提示以及网表验证。该方法旨在从电路原理图图像构建端到端的 SPICE 网表生成器，攻克长期存在的准确生成网表的难关。我们的框架在约 2100 个复杂程度各异的原理图上进行了测试，展现出了显著的性能提升。我们将此解决方案开源，以推动社区驱动式的开发。

> Auto-SPICE is the first fully automated framework leveraging large language models (LLMs) to generate Simulation Programs with Integrated Circuit Emphasis (SPICE) netlists. It addresses a long-standing challenge in automating netlist generation for analog circuits within circuit design automation. Automating this workflow could accelerate the creation of finetuned LLMs for analog circuit design and verification. We identify key challenges in this automation and evaluate the multi-modal capabilities of state-of-the-art LLMs, particularly GPT-4, to address these issues. We propose a three-step workflow to overcome current limitations: labeling analog circuits, prompt tuning, and netlist verification. This approach aims to create an end-to-end SPICE netlist generator from circuit schematic images, tackling the long-standing hurdle of accurate netlist generation. Our framework demonstrates significant performance improvements, tested on approximately 2,100 schematics of varying complexity. We open-source this solution for community-driven development.

[Arxiv](https://arxiv.org/abs/2411.14299)