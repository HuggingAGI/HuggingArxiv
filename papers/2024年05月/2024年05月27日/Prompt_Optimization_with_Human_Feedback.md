# 借助人类反馈优化提示策略

发布时间：2024年05月27日

`Agent

理由：这篇论文主要探讨了基于人类反馈的提示优化（POHF），并设计了自动化POHF（APOHF）算法，这是一种智能Agent的行为，因为它涉及到在迭代中智能选择提示对以获取偏好反馈，并优化黑盒LLM的提示。这种基于反馈的优化过程符合Agent的定义，即一个能够感知环境并采取行动以达到目标的实体。此外，论文中提到的应用场景（如优化用户指令、文本到图像生成模型的提示等）也体现了Agent在实际应用中的作用。因此，这篇论文更适合归类到Agent分类中。` `人工智能` `用户交互`

> Prompt Optimization with Human Feedback

# 摘要

> 大型语言模型（LLMs）在多任务中表现出色，但其性能高度依赖于输入提示，这引发了提示优化的新研究。然而，传统方法需依赖数值评分来评估提示质量，这在人类与黑盒LLM交互时难以实现且不可靠。相比之下，获取人类用户的偏好反馈更为简便可靠，即展示两个提示的响应，询问用户偏好。本文探讨了基于人类反馈的提示优化（POHF），旨在仅通过人类偏好反馈优化黑盒LLM的提示。借鉴决斗式多臂老虎机的原理，我们设计了自动化POHF（APOHF）算法，每次迭代中智能选择提示对以获取偏好反馈。APOHF应用于优化用户指令、文本到图像生成模型的提示，以及基于反馈的响应细化。实验证明，APOHF能高效利用有限反馈找到优质提示。代码地址：\url{https://github.com/xqlin98/APOHF}。

> Large language models (LLMs) have demonstrated remarkable performances in various tasks. However, the performance of LLMs heavily depends on the input prompt, which has given rise to a number of recent works on prompt optimization. However, previous works often require the availability of a numeric score to assess the quality of every prompt. Unfortunately, when a human user interacts with a black-box LLM, attaining such a score is often infeasible and unreliable. Instead, it is usually significantly easier and more reliable to obtain preference feedback from a human user, i.e., showing the user the responses generated from a pair of prompts and asking the user which one is preferred. Therefore, in this paper, we study the problem of prompt optimization with human feedback (POHF), in which we aim to optimize the prompt for a black-box LLM using only human preference feedback. Drawing inspiration from dueling bandits, we design a theoretically principled strategy to select a pair of prompts to query for preference feedback in every iteration, and hence introduce our algorithm named automated POHF (APOHF). We apply our APOHF algorithm to various tasks, including optimizing user instructions, prompt optimization for text-to-image generative models, and response optimization with human feedback (i.e., further refining the response using a variant of our APOHF). The results demonstrate that our APOHF can efficiently find a good prompt using a small number of preference feedback instances. Our code can be found at \url{https://github.com/xqlin98/APOHF}.

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x1.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x2.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x3.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x4.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x5.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x6.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x7.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x8.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x9.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x10.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x11.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x12.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x13.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x14.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x15.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x16.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x17.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x18.png)

![借助人类反馈优化提示策略](../../../paper_images/2405.17346/x19.png)

[Arxiv](https://arxiv.org/abs/2405.17346)