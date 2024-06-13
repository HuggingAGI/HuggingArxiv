# LT4SG@SMM4H24：借助预训练语言模型，对儿童健康相关的推文进行分类，以探索数字流行病学的新领域。

发布时间：2024年06月11日

`Agent

理由：这篇论文主要关注的是如何通过特定的模型（RoBERTa-large和BERTweet-large）来识别和分类特定的社交媒体内容（报告儿童医疗障碍的英语推文）。这种类型的研究通常属于Agent的范畴，因为它涉及使用模型或算法来处理和响应特定的输入数据，以完成特定的任务（如分类或识别）。这与Agent的概念相符，即一个能够感知环境并采取行动以达到目标的系统。虽然使用了大型语言模型（LLM）的技术，但论文的重点在于应用这些模型来解决实际问题，而不是探讨LLM的理论或架构。因此，将其归类为Agent更为合适。` `社交媒体分析` `医疗健康`

> LT4SG@SMM4H24: Tweets Classification for Digital Epidemiology of Childhood Health Outcomes Using Pre-Trained Language Models

# 摘要

> 本文探讨了在SMM4H24共享任务5中，如何通过二元分类识别报告儿童医疗障碍的英语推文。我们采用了两种策略：一是微调单个RoBERTa-large模型，二是集成三个BERTweet-large模型的结果。尽管两者在验证数据上表现相当，但BERTweet-large集成在测试数据上更胜一筹。我们的最佳系统在测试数据上取得了0.938的F1分数，超越了基准分类器1.18%。

> This paper presents our approaches for the SMM4H24 Shared Task 5 on the binary classification of English tweets reporting children's medical disorders. Our first approach involves fine-tuning a single RoBERTa-large model, while the second approach entails ensembling the results of three fine-tuned BERTweet-large models. We demonstrate that although both approaches exhibit identical performance on validation data, the BERTweet-large ensemble excels on test data. Our best-performing system achieves an F1-score of 0.938 on test data, outperforming the benchmark classifier by 1.18%.

![LT4SG@SMM4H24：借助预训练语言模型，对儿童健康相关的推文进行分类，以探索数字流行病学的新领域。](../../../paper_images/2406.07759/confusion_matrices.png)

[Arxiv](https://arxiv.org/abs/2406.07759)