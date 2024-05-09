![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# CoS技术：借助上下文导航，提升个性化体验，同时有效降低偏见风险。
发布时间：2024年05月02日

`提示工程`
> CoS: Enhancing Personalization and Mitigating Bias with Context Steering
>
> 在向大型语言模型（LLM）发起查询时，上下文信息——包括个人、人口统计和文化背景等用户特定信息——会显著影响模型的回复。比如，以“我是一个小孩子”为上下文询问牛顿第二定律，与以“我是一名物理教授”为上下文得到的回答会有所差异。恰当地利用上下文能够让LLM提供定制化的回答，而不当的上下文应用则可能产生刻板且可能有害的输出（如将“女性”等同于“家政妇”）。实际操作中，如何恰当地利用上下文是一个复杂且充满挑战的任务，往往因情况而异。一种常见的解决方案是对LLM进行微调，以便其能够根据上下文适当的回答进行学习。但这种方法成本高、耗时长，且对于不同场景下的最终用户而言难以控制。在本项研究中，我们提出了一种名为上下文引导（CoS）的新方法，它无需额外训练即可在自动回归LLM的推理阶段轻松应用。通过评估上下文对词符预测可能性的影响并进行调节，CoS方法允许用户根据具体应用场景和目标用户群体来确定恰当的上下文影响程度。我们展示了CoS在多种场景下的应用，包括增强上下文影响以提升个性化服务，以及减少不当影响以降低模型偏见。此外，我们还展示了CoS可以与贝叶斯推断结合使用，以评估互联网上仇恨言论的规模。我们在当前最先进的LLM和相关基准测试中验证了CoS的有效性。
>
> https://arxiv.org/abs/2405.01768

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/lanmbda_inference_qualitative_v2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x14.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x15.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x16.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x17.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/exp4-3-hate-quantify_v1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/appendix_lanmbda_inference_qualitative_v0.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x22.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x23.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x24.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x25.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x26.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.01768/x27.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.01768](https://arxiv.org/abs/2405.01768)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886