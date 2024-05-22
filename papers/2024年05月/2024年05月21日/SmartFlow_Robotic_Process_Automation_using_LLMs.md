# 智能流：借助大型语言模型实现机器人流程自动化

发布时间：2024年05月21日

`Agent

理由：论文摘要中提到的SmartFlow系统是一个基于AI的RPA（Robotic Process Automation）系统，它结合了预训练的大型语言模型和深度学习图像理解技术来处理复杂的流程和多样化的屏幕布局。该系统能够自动适应用户界面变化和数据输入差异，并通过计算机视觉和自然语言处理技术将图形用户界面上的元素转换为文本，进而由大型语言模型生成操作指令，实现任务自动化。这些特性表明SmartFlow系统作为一个智能代理（Agent），能够自主执行任务，适应环境变化，并在多种企业应用中展现出强大的适应性和鲁棒性。因此，它被归类为Agent。` `企业自动化` `客户服务`

> SmartFlow: Robotic Process Automation using LLMs

# 摘要

> SmartFlow，一款基于AI的RPA系统，通过结合预训练的大型语言模型与深度学习图像理解技术，有效应对复杂流程和多样化屏幕布局的挑战。该系统不仅能够自动适应用户界面变化和数据输入差异，还通过计算机视觉和自然语言处理技术，将图形用户界面上的元素转换为文本，进而由大型语言模型生成操作指令，实现任务自动化。SmartFlow在多种企业应用中展现出强大的适应性和鲁棒性，能够广泛应用于表单填写、客户服务、发票处理等业务流程，显著提升组织的工作效率。欲了解更多信息，请访问https://smartflow-4c5a0a.webflow.io/。

> Robotic Process Automation (RPA) systems face challenges in handling complex processes and diverse screen layouts that require advanced human-like decision-making capabilities. These systems typically rely on pixel-level encoding through drag-and-drop or automation frameworks such as Selenium to create navigation workflows, rather than visual understanding of screen elements. In this context, we present SmartFlow, an AI-based RPA system that uses pre-trained large language models (LLMs) coupled with deep-learning based image understanding. Our system can adapt to new scenarios, including changes in the user interface and variations in input data, without the need for human intervention. SmartFlow uses computer vision and natural language processing to perceive visible elements on the graphical user interface (GUI) and convert them into a textual representation. This information is then utilized by LLMs to generate a sequence of actions that are executed by a scripting engine to complete an assigned task. To assess the effectiveness of SmartFlow, we have developed a dataset that includes a set of generic enterprise applications with diverse layouts, which we are releasing for research use. Our evaluations on this dataset demonstrate that SmartFlow exhibits robustness across different layouts and applications. SmartFlow can automate a wide range of business processes such as form filling, customer service, invoice processing, and back-office operations. SmartFlow can thus assist organizations in enhancing productivity by automating an even larger fraction of screen-based workflows. The demo-video and dataset are available at https://smartflow-4c5a0a.webflow.io/.

[Arxiv](https://arxiv.org/abs/2405.12842)