# GUIDE：图形用户界面数据执行指南

发布时间：2024年04月09日

`分类：LLM应用` `机器人流程自动化`

> GUIDE: Graphical User Interface Data for Execution

# 摘要

> 本文提出了GUIDE，这是专为推动多模态大型语言模型（MLLM）应用而设计的全新数据集，尤其针对机器人流程自动化（RPA）场景。该数据集广泛采集了包括Apollo、Gmail、Calendar和Canva在内的多个网站数据，占比分别为62.67%、3.43%、10.98%和22.92%。每项数据记录都包含了图像、任务说明、最后操作、CoT、下一步操作及其执行位置的详细信息。这些数据通过我们自研的先进标注工具NEXTAG收集，支持多种操作系统、浏览器和显示设备，并由多位标注者协作完成，以确保捕捉到网站设计多样性及用户使用习惯。我们期望通过GUIDE数据集，推动LLM在图形用户界面领域的研究与开发，特别是在RPA相关任务上的应用。该数据集的跨平台特性和广泛网站覆盖，为自动化任务中的界面交互能力研究提供了可能。我们相信GUIDE将极大促进多平台LLM在实际应用中的发展，推动自动化和自然语言理解领域的创新。利用GUIDE，我们开发了V-Zen，这是首个利用我们自研的AUTONODE自动化工具，实现多网站自动化的RPA模型。

> In this paper, we introduce GUIDE, a novel dataset tailored for the advancement of Multimodal Large Language Model (MLLM) applications, particularly focusing on Robotic Process Automation (RPA) use cases. Our dataset encompasses diverse data from various websites including Apollo(62.67\%), Gmail(3.43\%), Calendar(10.98\%) and Canva(22.92\%). Each data entry includes an image, a task description, the last action taken, CoT and the next action to be performed along with grounding information of where the action needs to be executed. The data is collected using our in-house advanced annotation tool NEXTAG (Next Action Grounding and Annotation Tool). The data is adapted for multiple OS, browsers and display types. It is collected by multiple annotators to capture the variation of design and the way person uses a website.
  Through this dataset, we aim to facilitate research and development in the realm of LLMs for graphical user interfaces, particularly in tasks related to RPA. The dataset's multi-platform nature and coverage of diverse websites enable the exploration of cross-interface capabilities in automation tasks. We believe that our dataset will serve as a valuable resource for advancing the capabilities of multi-platform LLMs in practical applications, fostering innovation in the field of automation and natural language understanding. Using GUIDE, we build V-Zen, the first RPA model to automate multiple websites using our in-House Automation tool AUTONODE

[Arxiv](https://arxiv.org/abs/2404.16048)