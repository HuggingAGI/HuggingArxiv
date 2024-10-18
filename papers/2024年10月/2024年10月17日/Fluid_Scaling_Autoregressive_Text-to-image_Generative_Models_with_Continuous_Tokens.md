# Fluid：通过连续标记扩展自回归文本到图像生成模型的规模

发布时间：2024年10月17日

`LLM应用` `图像生成`

> Fluid: Scaling Autoregressive Text-to-image Generative Models with Continuous Tokens

# 摘要

> 在视觉领域，自回归模型的扩展并未带来如语言模型般的显著收益。我们深入探讨了文本到图像生成中的扩展问题，特别关注模型使用离散或连续token，以及生成顺序是随机还是固定。实证显示，尽管验证损失均有效降低，但评估指标如FID、GenEval分数和视觉质量却呈现不同趋势。连续token模型在视觉质量上远超离散token模型，且随机顺序模型在GenEval分数上表现更佳。基于此，我们训练了Fluid，一个基于连续token的随机顺序自回归模型，其在MS-COCO 30K上创下6.16的零-shot FID新纪录，GenEval基准测试中获0.69高分。期待这些发现能推动未来缩小视觉与语言模型间的扩展差距。

> Scaling up autoregressive models in vision has not proven as beneficial as in large language models. In this work, we investigate this scaling problem in the context of text-to-image generation, focusing on two critical factors: whether models use discrete or continuous tokens, and whether tokens are generated in a random or fixed raster order using BERT- or GPT-like transformer architectures. Our empirical results show that, while all models scale effectively in terms of validation loss, their evaluation performance -- measured by FID, GenEval score, and visual quality -- follows different trends. Models based on continuous tokens achieve significantly better visual quality than those using discrete tokens. Furthermore, the generation order and attention mechanisms significantly affect the GenEval score: random-order models achieve notably better GenEval scores compared to raster-order models. Inspired by these findings, we train Fluid, a random-order autoregressive model on continuous tokens. Fluid 10.5B model achieves a new state-of-the-art zero-shot FID of 6.16 on MS-COCO 30K, and 0.69 overall score on the GenEval benchmark. We hope our findings and results will encourage future efforts to further bridge the scaling gap between vision and language models.

[Arxiv](https://arxiv.org/abs/2410.13863)