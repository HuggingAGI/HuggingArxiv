# 通过协作提示，赋能大型语言模型实现持续视频问答

发布时间：2024年10月01日

`LLM应用` `视频内容` `在线教育`

> Empowering Large Language Model for Continual Video Question Answering with Collaborative Prompting

# 摘要

> 近年来，在线视频内容的激增暴露了传统视频问答（VideoQA）模型在适应新问题上的不足。本文探讨了在持续学习框架下进行视频问答的新挑战，并发现微调大型语言模型（LLM）容易导致灾难性遗忘。为此，我们提出了协作提示（ColPro），通过整合问题约束、知识获取和视觉时间感知提示，全面捕捉视频问答中的文本、视觉和时间动态。实验结果表明，ColPro在NExT-QA和DramaQA数据集上分别达到了55.14%和71.24%的准确率，显著优于现有方法，展现了其强大的实用性和有效性。

> In recent years, the rapid increase in online video content has underscored the limitations of static Video Question Answering (VideoQA) models trained on fixed datasets, as they struggle to adapt to new questions or tasks posed by newly available content. In this paper, we explore the novel challenge of VideoQA within a continual learning framework, and empirically identify a critical issue: fine-tuning a large language model (LLM) for a sequence of tasks often results in catastrophic forgetting. To address this, we propose Collaborative Prompting (ColPro), which integrates specific question constraint prompting, knowledge acquisition prompting, and visual temporal awareness prompting. These prompts aim to capture textual question context, visual content, and video temporal dynamics in VideoQA, a perspective underexplored in prior research. Experimental results on the NExT-QA and DramaQA datasets show that ColPro achieves superior performance compared to existing approaches, achieving 55.14\% accuracy on NExT-QA and 71.24\% accuracy on DramaQA, highlighting its practical relevance and effectiveness.

[Arxiv](https://arxiv.org/abs/2410.00771)