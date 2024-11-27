# 从响应而非偏好中学习：运用非并行数据为 LLM 解毒的斯塔克尔伯格式方法

发布时间：2024年10月26日

`LLM应用` `社交媒体` `文本处理`

> Learning from Response not Preference: A Stackelberg Approach for LLM Detoxification using Non-parallel Data

# 摘要

> 文本解毒，作为风格迁移任务的一种变体，在在线社交媒体中有着广泛的应用。本研究提出了一种微调方法，仅利用非平行数据就能将大型语言模型（LLM）转化为解毒改写器。我们把微调过程构建为大型语言模型（主导者）与毒性筛选器（跟随者，即一个二元风格分类器，有毒或无毒）之间的斯塔克尔伯格博弈。大型语言模型的目标是依照筛选器调整自身偏好，并生成能通过筛选的释义。非平行数据微调面临的主要难题是不完全偏好。释义不成功时，由于输入和释义都属于相同的有毒风格，分类器无法在两者间建立偏好。所以，像直接偏好优化（DPO）这类偏好对齐微调方法不再适用。为应对不完全偏好的挑战，我们从DPO改编出斯塔克尔伯格响应优化（SRO），让大型语言模型能从跟随者的响应中学习。关键在于，如果释义未通过跟随者的筛选，SRO会降低生成该释义的可能性，同时在有毒输入及其通过筛选的释义对进行DPO。实验表明，经过SRO微调的大型语言模型在风格准确性、内容相似性和流畅性方面表现出色，能与最先进的模型媲美。整体解毒性能优于其他计算方法，与人类参考相当。额外的经验证据显示，SRO对筛选器的反馈很敏感，稍有扰动就会导致性能大幅下降。我们在 url{https://github.com/XXXinhong/Detoxification_LLM} 上发布了代码和大型语言模型。

> Text detoxification, a variant of style transfer tasks, finds useful applications in online social media. This work presents a fine-tuning method that only uses non-parallel data to turn large language models (LLM) into a detoxification rewritter. We model the fine-tuning process as a Stackelberg game between an LLM (leader) and a toxicity screener (follower), which is a binary style classifier (toxic or non-toxic). The LLM aims to align its preference according to the screener and generate paraphases passing the screening. The primary challenge of non-parallel data fine-tuning is incomplete preference. In the case of unsuccessful paraphrases, the classifier cannot establish a preference between the input and paraphrase, as they belong to the same toxic style. Hence, preference-alignment fine-tuning methods, such as direct preference optimization (DPO), no longer apply. To address the challenge of incomplete preference, we propose Stackelberg response optimization (SRO), adapted from DPO, to enable the LLM to learn from the follower's response. The gist is that SRO decreases the likelihood of generating the paraphrase if it fails the follower's screening while performing DPO on the pair of the toxic input and its paraphrase when the latter passes the screening. Experiments indicate that the SRO-fine-tunned LLM achieves satisfying performance comparable to state-of-the-art models regarding style accuracy, content similarity, and fluency. The overall detoxification performance surpasses other computing methods and matches the human reference. Additional empirical evidence suggests that SRO is sensitive to the screener's feedback, and a slight perturbation leads to a significant performance drop. We release the code and LLM models at url{https://github.com/XXXinhong/Detoxification_LLM}.

[Arxiv](https://arxiv.org/abs/2410.20298)