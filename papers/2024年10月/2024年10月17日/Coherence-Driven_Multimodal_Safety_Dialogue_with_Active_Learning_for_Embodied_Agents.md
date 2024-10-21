# 连贯驱动下的多模态安全对话，结合具身代理的主动学习

发布时间：2024年10月17日

`Agent` `机器人`

> Coherence-Driven Multimodal Safety Dialogue with Active Learning for Embodied Agents

# 摘要

> 在日常任务中协助人类时，机器人需精准解读视觉线索，并在安全关键场景中迅速反应，如处理地板上的尖锐物品。为此，我们推出了 M-CoDAL，一个专为具身代理设计的跨模态对话系统，旨在提升其在安全关键情况下的理解和沟通能力。该系统通过利用话语连贯关系，增强上下文感知和交流效率。为训练此系统，我们创新性地采用了基于聚类的主动学习机制，借助外部大型语言模型 (LLM) 识别关键信息。我们利用一个包含 1K 安全违规的多模态数据集进行评估，这些违规从 2K Reddit 图像中提取，并经大型多模态模型 (LMM) 标注及人工验证。结果显示，我们的方法显著提升了安全问题的解决效率、用户情感及对话安全性。随后，我们将此系统部署于 Hello Robot Stretch 机器人，并进行真实世界用户的同主体研究。参与者与机器人模拟不同严重程度的安全场景，并接受我们系统及基于 OpenAI 的 ChatGPT 基线系统的干预。研究结果进一步证实，我们的系统在实际应用中表现更为出色，更具说服力和专业性。

> When assisting people in daily tasks, robots need to accurately interpret visual cues and respond effectively in diverse safety-critical situations, such as sharp objects on the floor. In this context, we present M-CoDAL, a multimodal-dialogue system specifically designed for embodied agents to better understand and communicate in safety-critical situations. The system leverages discourse coherence relations to enhance its contextual understanding and communication abilities. To train this system, we introduce a novel clustering-based active learning mechanism that utilizes an external Large Language Model (LLM) to identify informative instances. Our approach is evaluated using a newly created multimodal dataset comprising 1K safety violations extracted from 2K Reddit images. These violations are annotated using a Large Multimodal Model (LMM) and verified by human annotators. Results with this dataset demonstrate that our approach improves resolution of safety situations, user sentiment, as well as safety of the conversation. Next, we deploy our dialogue system on a Hello Robot Stretch robot and conduct a within-subject user study with real-world participants. In the study, participants role-play two safety scenarios with different levels of severity with the robot and receive interventions from our model and a baseline system powered by OpenAI's ChatGPT. The study results corroborate and extend the findings from automated evaluation, showing that our proposed system is more persuasive and competent in a real-world embodied agent setting.

[Arxiv](https://arxiv.org/abs/2410.14141)