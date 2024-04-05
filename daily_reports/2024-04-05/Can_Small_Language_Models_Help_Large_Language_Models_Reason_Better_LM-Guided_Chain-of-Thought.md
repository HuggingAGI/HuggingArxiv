# 小型语言模型能否助力大型语言模型提升推理能力？——通过LM引导的思维链条探究
`提示工程`
> 我们提出了一个创新的框架——LM引导的CoT，它使用一个小型（参数量小于10亿）的语言模型来引导一个大型黑盒（参数量超过100亿）的语言模型完成推理任务。在这个框架中，小型LM先为每个输入生成一个推理依据，然后大型LM根据这个依据来预测任务的答案。这种方法资源消耗低，因为它仅需要对小型LM进行训练。通过知识蒸馏和基于理由及任务的奖励信号进行强化学习，我们对模型进行了优化。在多跳问答任务的基准测试中，如HotpotQA和2WikiMultiHopQA，我们的实验结果显示，这种方法在答案预测的准确性上超越了所有对比基准。此外，我们还发现强化学习有助于提升理由的质量，进而改善问答任务的表现。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03414/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03414/reward_new2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03414/annotation_example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.03414/barplot_annotation.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/5122188251251414](https://wx.zsxq.com/dweb2/index/topic_detail/5122188251251414)
