# 针对未知情境和环境的元认知（MUSE）

发布时间：2024年11月20日

`Agent` `自主系统` `元认知`

> Metacognition for Unknown Situations and Environments (MUSE)

# 摘要

> 元认知，即对自身认知过程的认知与调控，乃是人类在未知情境中适应能力的核心所在。相较而言，当下的自主智能体因适应能力有限，在新环境中往往力不从心。我们推测，元认知是自适应自主系统中关键的缺失成分，能赋予其应对陌生挑战所需的认知灵活性。鉴于元认知能力范畴广泛，我们着重于两个关键方面：新任务的能力认知与策略选择。为此，我们提出了针对未知情境和环境的元认知（MUSE）框架，将元认知过程，尤其是自我认知和自我调控，融入到自主智能体当中。我们展示了 MUSE 的两个初步实现：一个基于世界模型，另一个借助大型语言模型（LLM），二者均实例化了元认知循环。我们的系统持续学习评估其在给定任务上的能力，并凭借这种自我认知来引导策略选择的迭代循环。MUSE 智能体在自我认知和自我调控方面有显著提升，相较于基于 Dreamer-v3 的强化学习和纯提示型的 LLM 智能体方法，能更有效地解决新的、分布外的任务。此项工作凸显了受认知和神经系统启发的方法在助力自主系统适应新环境方面的潜力，克服了当前严重依赖大量训练数据的方法的局限性。

> Metacognition--the awareness and regulation of one's cognitive processes--is central to human adaptability in unknown situations. In contrast, current autonomous agents often struggle in novel environments due to their limited capacity for adaptation. We hypothesize that metacognition is a critical missing ingredient in adaptive autonomous systems, equipping them with the cognitive flexibility needed to tackle unfamiliar challenges. Given the broad scope of metacognitive abilities, we focus on two key aspects: competence awareness and strategy selection for novel tasks. To this end, we propose the Metacognition for Unknown Situations and Environments (MUSE) framework, which integrates metacognitive processes--specifically self-awareness and self-regulation--into autonomous agents. We present two initial implementations of MUSE: one based on world modeling and another leveraging large language models (LLMs), both instantiating the metacognitive cycle. Our system continuously learns to assess its competence on a given task and uses this self-awareness to guide iterative cycles of strategy selection. MUSE agents show significant improvements in self-awareness and self-regulation, enabling them to solve novel, out-of-distribution tasks more effectively compared to Dreamer-v3-based reinforcement learning and purely prompt-based LLM agent approaches. This work highlights the promise of approaches inspired by cognitive and neural systems in enabling autonomous systems to adapt to new environments, overcoming the limitations of current methods that rely heavily on extensive training data.

[Arxiv](https://arxiv.org/abs/2411.13537)