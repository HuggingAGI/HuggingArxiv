# SPINE：在不规则环境中，为任务提供在线语义规划，即使自然语言规范不完整

发布时间：2024年10月03日

`Agent` `机器人` `应急响应`

> SPINE: Online Semantic Planning for Missions with Incomplete Natural Language Specifications in Unstructured Environments

# 摘要

> 随着机器人能力的提升，用户将希望描述高层次任务，让机器人填补细节。在许多现实场景中，预建地图难以获取，任务执行需探索与特定任务相关的环境。例如，在紧急响应中，用户命令机器人“分类受影响区域”，机器人需推断相关语义（如受害者）和探索目标（如受损区域），并在线调整计划。这些任务虽未完全指定，但蕴含子任务与语义。尽管现有语义规划方法多在线操作，但常针对明确任务（如物体搜索）。近期，大型语言模型（LLM）在处理自然语言描述的机器人任务时表现出色，但现有LLM规划器多不涉及在线规划或复杂任务，相关子任务常由预建地图或用户提供。我们通过SPINE（在不结构化环境中处理不完全自然语言规范任务的在线语义规划器）解决这些局限。SPINE利用LLM推理任务隐含的子任务，并在递减地平线框架中实现，任务自动验证安全并在线优化。我们在模拟与真实环境中评估SPINE，任务涉及多步语义推理与探索，覆盖超过20,000平方米的杂乱户外环境。我们在单一代理与空地团队应用中对比SPINE与竞争基线。更多详情请访问项目页面：https://zacravichandran.github.io/SPINE。

> As robots become increasingly capable, users will want to describe high-level missions and have robots fill in the gaps. In many realistic settings, pre-built maps are difficult to obtain, so execution requires exploration and mapping that are necessary and specific to the mission. Consider an emergency response scenario where a user commands a robot, "triage impacted regions." The robot must infer relevant semantics (victims, etc.) and exploration targets (damaged regions) based on priors or other context, then explore and refine its plan online. These missions are incompletely specified, meaning they imply subtasks and semantics. While many semantic planning methods operate online, they are typically designed for well specified tasks such as object search or exploration. Recently, Large Language Models (LLMs) have demonstrated powerful contextual reasoning over a range of robotic tasks described in natural language. However, existing LLM planners typically do not consider online planning or complex missions; rather, relevant subtasks are provided by a pre-built map or a user. We address these limitations via SPINE (online Semantic Planner for missions with Incomplete Natural language specifications in unstructured Environments). SPINE uses an LLM to reason about subtasks implied by the mission then realizes these subtasks in a receding horizon framework. Tasks are automatically validated for safety and refined online with new observations. We evaluate SPINE in simulation and real-world settings. Evaluation missions require multiple steps of semantic reasoning and exploration in cluttered outdoor environments of over 20,000m$^2$ area. We evaluate SPINE against competitive baselines in single-agent and air-ground teaming applications. Please find videos and software on our project page: https://zacravichandran.github.io/SPINE

[Arxiv](https://arxiv.org/abs/2410.03035)