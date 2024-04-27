# GUIDE：图形用户界面数据执行指南

发布时间：2024年04月09日

`LLM应用` `机器人流程自动化` `自然语言理解`

> GUIDE: Graphical User Interface Data for Execution

# 摘要

> 本文提出了GUIDE，一个专为推动多模态大型语言模型（MLLM）应用而设计的新数据集，重点聚焦于机器人流程自动化（RPA）的实际应用。该数据集广泛采集了包括Apollo、Gmail、Calendar和Canva在内的多个网站数据，每个数据条目都包含了图像、任务说明、最近一次操作、上下文信息（CoT）、待执行的下一步操作及其执行位置的详细信息。我们利用自主研发的先进注释工具NEXTAG进行数据采集，确保数据能够适应不同的操作系统、浏览器和显示设备，并由多位注释者共同完成，以确保捕捉到网站设计多样性及用户使用习惯的差异。通过GUIDE数据集，我们期望推动LLM在图形用户界面领域的研究与开发，尤其是在RPA相关任务上。其跨平台的特性和对多样化网站的广泛覆盖，为探索自动化任务中的界面间协作能力提供了可能。我们相信GUIDE将成为提升多平台LLM实际应用能力、激发自动化和自然语言理解领域创新的重要资源。利用GUIDE，我们开发了V-Zen，这是首个利用我们自主研发的自动化工具AUTONODE，实现多网站自动化的RPA模型。

> In this paper, we introduce GUIDE, a novel dataset tailored for the advancement of Multimodal Large Language Model (MLLM) applications, particularly focusing on Robotic Process Automation (RPA) use cases. Our dataset encompasses diverse data from various websites including Apollo(62.67\%), Gmail(3.43\%), Calendar(10.98\%) and Canva(22.92\%). Each data entry includes an image, a task description, the last action taken, CoT and the next action to be performed along with grounding information of where the action needs to be executed. The data is collected using our in-house advanced annotation tool NEXTAG (Next Action Grounding and Annotation Tool). The data is adapted for multiple OS, browsers and display types. It is collected by multiple annotators to capture the variation of design and the way person uses a website.
  Through this dataset, we aim to facilitate research and development in the realm of LLMs for graphical user interfaces, particularly in tasks related to RPA. The dataset's multi-platform nature and coverage of diverse websites enable the exploration of cross-interface capabilities in automation tasks. We believe that our dataset will serve as a valuable resource for advancing the capabilities of multi-platform LLMs in practical applications, fostering innovation in the field of automation and natural language understanding. Using GUIDE, we build V-Zen, the first RPA model to automate multiple websites using our in-House Automation tool AUTONODE

[Arxiv](https://arxiv.org/abs/2404.16048)