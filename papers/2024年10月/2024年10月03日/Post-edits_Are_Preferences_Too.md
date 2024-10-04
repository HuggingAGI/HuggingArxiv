# 后编辑也是偏好选择

发布时间：2024年10月03日

`LLM应用` `机器翻译`

> Post-edits Are Preferences Too

# 摘要

> Preference Optimization (PO) 技术是目前微调大型语言模型 (LLM) 的尖端方法之一，但机器翻译中获取成对偏好反馈较为困难。Kreutzer 等人 (2018) 指出，机器翻译中成对偏好不如 5 分制评分可靠。我们研究后编辑，探讨其是否能提供可靠的人类偏好。在 PO 中，人类标注者比较 $s_1$ 和 $s_2$，而在后编辑中，编辑者创建 $s_1$ 并确保其优于 $s_2$。我们利用这些隐含偏好进行 PO，发现模型更倾向于后编辑而非机器翻译的假设。此外，通过在后编辑数据上进行监督微调预训练，模型能更好地将后编辑假设置于高排名。

> Preference Optimization (PO) techniques are currently one of the state of the art techniques for fine-tuning large language models (LLMs) on pairwise preference feedback from human annotators. However, in machine translation, this sort of feedback can be difficult to solicit. Additionally, Kreutzer et al. (2018) have shown that, for machine translation, pairwise preferences are less reliable than other forms of human feedback, such as 5-point ratings.
  We examine post-edits to see if they can be a source of reliable human preferences by construction. In PO, a human annotator is shown sequences $s_1$ and $s_2$ and asked for a preference judgment, %$s_1 > s_2$; while for post-editing, editors \emph{create} $s_1$ and know that it should be better than $s_2$. We attempt to use these implicit preferences for PO and show that it helps the model move towards post-edit-like hypotheses and away from machine translation-like hypotheses. Furthermore, we show that best results are obtained by pre-training the model with supervised fine-tuning (SFT) on post-edits in order to promote post-edit-like hypotheses to the top output ranks.

[Arxiv](https://arxiv.org/abs/2410.02320)