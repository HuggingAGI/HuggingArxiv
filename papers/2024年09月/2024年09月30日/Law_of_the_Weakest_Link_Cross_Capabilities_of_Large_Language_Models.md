# 最弱环节法则：探究大型语言模型的跨领域能力

发布时间：2024年09月30日

`LLM理论` `人工智能`

> Law of the Weakest Link: Cross Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLM）的开发与评估多聚焦于单一能力，却忽视了现实任务中常需的多领域能力交叉，我们称之为“交叉能力”。为系统探究这一概念，我们首先定义了七种核心个体能力，并将其配对形成七种常见交叉能力，每种均由精心构建的分类法支持。基于此，我们推出了 CrossEval 基准，包含 1,400 个人工标注提示，每种个体与交叉能力各 100 个。为确保评估可靠性，我们邀请专家对 4,200 个模型响应进行评估，收集了 8,400 个人类评分及详细解释作为参考。研究发现，无论在静态评估还是能力增强尝试中，当前 LLM 均显现“最弱环节法则”，即交叉能力表现受制于最弱环节。具体而言，17 个模型的 58 个交叉能力评分中，38 个低于所有个体能力，20 个介于强弱之间，更偏向较弱能力。这凸显了 LLM 在交叉能力任务中的不足，识别并强化最弱能力成为未来优化复杂多维场景性能的关键。

> The development and evaluation of Large Language Models (LLMs) have largely focused on individual capabilities. However, this overlooks the intersection of multiple abilities across different types of expertise that are often required for real-world tasks, which we term cross capabilities. To systematically explore this concept, we first define seven core individual capabilities and then pair them to form seven common cross capabilities, each supported by a manually constructed taxonomy. Building on these definitions, we introduce CrossEval, a benchmark comprising 1,400 human-annotated prompts, with 100 prompts for each individual and cross capability. To ensure reliable evaluation, we involve expert annotators to assess 4,200 model responses, gathering 8,400 human ratings with detailed explanations to serve as reference examples. Our findings reveal that, in both static evaluations and attempts to enhance specific abilities, current LLMs consistently exhibit the "Law of the Weakest Link," where cross-capability performance is significantly constrained by the weakest component. Specifically, across 58 cross-capability scores from 17 models, 38 scores are lower than all individual capabilities, while 20 fall between strong and weak, but closer to the weaker ability. These results highlight the under-performance of LLMs in cross-capability tasks, making the identification and improvement of the weakest capabilities a critical priority for future research to optimize performance in complex, multi-dimensional scenarios.

[Arxiv](https://arxiv.org/abs/2409.19951)