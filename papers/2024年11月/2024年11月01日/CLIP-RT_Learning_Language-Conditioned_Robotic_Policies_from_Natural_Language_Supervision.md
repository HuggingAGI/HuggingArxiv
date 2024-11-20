# CLIP-RT：从自然语言监督中习得语言条件下的机器人策略

发布时间：2024年11月01日

`Agent` `机器人`

> CLIP-RT: Learning Language-Conditioned Robotic Policies from Natural Language Supervision

# 摘要

> 这篇论文探究了非专家怎样在他们所处的环境中教授机器人所需技能。我们觉得自然语言是机器人学习的直观且易用的接口。为此，我们探究了两个关键方面：（1）非专家怎样通过自然语言监督来收集机器人数据；（2）预训练的视觉语言模型怎样直接从这种监督中学习端到端策略。我们提出了一个数据收集框架，它能依据自然语言监督（比如“向前移动”）来收集机器人演示，并进一步扩充这些演示。接着，我们引入了一个从自然语言监督中学习语言条件策略的模型，叫做 CLIP-RT。我们的模型运用预训练的 CLIP 模型，并通过对比模仿学习来学习预测以语言呈现的动作。我们先在大规模机器人数据上训练 CLIP-RT，然后让它能够利用从我们框架收集的数据来学习所需技能。CLIP-RT 在获取新的操作技能上展现出强大的能力，在平均成功率方面比最先进的 OpenVLA 模型（70 亿参数）高出 17%，而使用的参数少 7 倍（10 亿）。

> This paper explores how non-experts can teach robots desired skills in their environments. We argue that natural language is an intuitive and accessible interface for robot learning. To this end, we investigate two key aspects: (1) how non-experts collect robotic data using natural language supervision and (2) how pre-trained vision-language models learn end-to-end policies directly from this supervision. We propose a data collection framework that collects robot demonstrations based on natural language supervision (e.g., "move forward") and further augments these demonstrations. Next, we introduce a model that learns language-conditioned policies from natural language supervision called CLIP-RT. Our model employs pre-trained CLIP models and learns to predict actions represented in language via contrastive imitation learning. We first train CLIP-RT on large-scale robotic data and then enable it to learn desired skills using data collected from our framework. CLIP-RT shows strong capabilities in acquiring novel manipulation skills, outperforming the state-of-the-art model, OpenVLA (7B parameters), by 17% in average success rates, while using 7x fewer parameters (1B).

[Arxiv](https://arxiv.org/abs/2411.00508)