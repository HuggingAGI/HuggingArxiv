# 在 SemEval-2024 的第三项任务中，nicolay-r 利用 Flan-T5 模型，通过情绪状态的思维链推理对话中的情绪成因。

发布时间：2024年04月04日

`LLM应用` `对话系统` `情感分析`

> nicolay-r at SemEval-2024 Task 3: Using Flan-T5 for Reasoning Emotion Cause in Conversations with Chain-of-Thought on Emotion States

# 摘要

> 情感交流是对话中不可或缺的元素，其成因多样，可能源自个体本身或受他人言行触发。这些因素，如对话的前因后果、交谈者的情绪状态等，都可能激发更深层的情感反应。本研究借鉴了思维链的最新发展，运用三跳推理策略（THOR）对大型语言模型进行指令调优，以识别和解析对话中的情感状态（THOR-state）和由一方引起的情感变化（THOR-cause）。我们为THOR-cause引入了推理修正机制（rr），以优化微调过程中的推理路径。特别是，我们依据标注的情感状态数据来调整推理路径。我们的最终方案基于Flan-T5-base（250M）模型和规则驱动的跨度校正技术，首先通过THOR-state进行初步微调，再结合THOR-cause-rr进行精细调整，竞赛成绩在15支参赛队伍中荣获第3、4名（按F1比例评分）和第5名（按F1严格评分）。我们的THOR实现代码已公开：https://github.com/nicolay-r/THOR-ECAC

> Emotion expression is one of the essential traits of conversations. It may be self-related or caused by another speaker. The variety of reasons may serve as a source of the further emotion causes: conversation history, speaker's emotional state, etc. Inspired by the most recent advances in Chain-of-Thought, in this work, we exploit the existing three-hop reasoning approach (THOR) to perform large language model instruction-tuning for answering: emotion states (THOR-state), and emotion caused by one speaker to the other (THOR-cause). We equip THOR-cause with the reasoning revision (rr) for devising a reasoning path in fine-tuning. In particular, we rely on the annotated speaker emotion states to revise reasoning path. Our final submission, based on Flan-T5-base (250M) and the rule-based span correction technique, preliminary tuned with THOR-state and fine-tuned with THOR-cause-rr on competition training data, results in 3rd and 4th places (F1-proportional) and 5th place (F1-strict) among 15 participating teams. Our THOR implementation fork is publicly available: https://github.com/nicolay-r/THOR-ECAC

[Arxiv](https://arxiv.org/abs/2404.03361)