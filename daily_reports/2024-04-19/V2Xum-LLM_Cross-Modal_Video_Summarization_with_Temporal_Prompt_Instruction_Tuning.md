# V2Xum-LLM：利用时间提示指令优化的跨模态视频摘要技术
发布时间：2024年04月18日
`多模态大模型`
> 视频摘要致力于提炼出长视频的精华，制作出精炼、准确、通顺的短片。尽管众多视频摘要数据集相继问世，但其源视频数量的匮乏仍是一大短板，限制了高端大型视觉-语言模型（VLMs）的精细调整。而且，目前多数数据集仅服务于视频到视频的摘要，忽略了对多模态视频内容摘要的现代需求。近期，研究者们致力于将视频摘要从单一模态向多模态转变，将其细分为三个子任务：视频转视频（V2V）、视频转文本（V2T）以及视频与文本结合摘要（V2VT）。但现有多模态数据集中的文本摘要质量尚显不足。为应对这些挑战，我们推出了Instruct-V2Xum，这是一个跨界视频摘要数据集，精选了来自YouTube的3万段多样化视频，时长大至40至940秒，平均摘要率为16.39%。Instruct-V2Xum的每个视频摘要均配有指向特定帧的文本摘要，便于生成同步的视频与文本摘要。此外，我们提出了一个创新的视频摘要框架——V2Xum-LLM。在本研究中，特别是V2Xum-LLaMA，这是首个将不同视频摘要任务整合至单一大型语言模型（LLM）文本解码器的框架，通过时间提示和任务指令实现可控制的视频摘要任务。实验结果表明，V2Xum-LLaMA在多个视频摘要任务上均优于强劲的基线模型。进一步地，我们还提出了一种改进的评估指标，专门用于V2V和V2VT摘要任务的评估。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/teaser.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/sankey.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/model.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/vera.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/grammar.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.12353/sample0.png)

[https://wx.zsxq.com/dweb2/index/topic_detail/4844588222454828](https://wx.zsxq.com/dweb2/index/topic_detail/4844588222454828)

[https://arxiv.org/abs/2404.12353](https://arxiv.org/abs/2404.12353)