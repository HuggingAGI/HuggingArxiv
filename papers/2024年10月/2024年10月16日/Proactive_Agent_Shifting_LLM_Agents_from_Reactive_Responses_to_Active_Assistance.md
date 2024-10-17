# 主动代理：让 LLM 代理从被动响应转变为主动协助

发布时间：2024年10月16日

`Agent` `人工智能` `人机协作`

> Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance

# 摘要

> 大型语言模型驱动的代理在解决复杂任务上表现出色，但多数系统仍停留在被动反应阶段，难以应对需要预见性和自主决策的场景。本文探讨了开发无需明确指令即可预测和启动任务的主动代理的挑战。我们提出了一种数据驱动的新方法：首先，通过收集真实人类活动生成主动任务预测，并由人类注释者标记为接受或拒绝；接着，利用这些标记数据训练奖励模型，模拟人类判断，自动评估LLM代理的主动性；随后，构建了一个包含6,790个事件的多样化数据集ProactiveBench。实验表明，使用ProactiveBench微调的模型在主动提供帮助方面表现优异，F1分数达到66.47%，超越了所有开源和闭源模型。这不仅展示了我们方法的潜力，更为未来人机协作的进步奠定了基础。

> Agents powered by large language models have shown remarkable abilities in solving complex tasks. However, most agent systems remain reactive, limiting their effectiveness in scenarios requiring foresight and autonomous decision-making. In this paper, we tackle the challenge of developing proactive agents capable of anticipating and initiating tasks without explicit human instructions. We propose a novel data-driven approach for this problem. Firstly, we collect real-world human activities to generate proactive task predictions. These predictions are then labeled by human annotators as either accepted or rejected. The labeled data is used to train a reward model that simulates human judgment and serves as an automatic evaluator of the proactiveness of LLM agents. Building on this, we develop a comprehensive data generation pipeline to create a diverse dataset, ProactiveBench, containing 6,790 events. Finally, we demonstrate that fine-tuning models with the proposed ProactiveBench can significantly elicit the proactiveness of LLM agents. Experimental results show that our fine-tuned model achieves an F1-Score of 66.47% in proactively offering assistance, outperforming all open-source and close-source models. These results highlight the potential of our method in creating more proactive and effective agent systems, paving the way for future advancements in human-agent collaboration.

[Arxiv](https://arxiv.org/abs/2410.12361)