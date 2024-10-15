# “谁来监督监督者？” —— 探讨如何检测 AI 生成的同行评审

发布时间：2024年10月13日

`LLM应用` `学术出版` `人工智能`

> 'Quis custodiet ipsos custodes?' Who will watch the watchmen? On Detecting AI-generated peer-reviews

# 摘要

> 同行评审的完整性对学术界的科学严谨和信任至关重要。随着ChatGPT等大型语言模型在学术写作中的普及，AI生成的文本对科学出版（包括同行评审）的潜在威胁日益引起关注。以往研究多聚焦于通用AI文本检测或估计AI生成评审的比例。我们则致力于解决实际问题：帮助编辑或主席判断评审是否由ChatGPT撰写。为此，我们提出了术语频率（TF）模型和评审再生（RR）模型，前者基于AI常重复标记的假设，后者基于ChatGPT在重新提示时生成相似输出的原理。我们通过压力测试评估了这些模型对标记攻击和改写的应对能力，并提出防御策略以减少改写的影响。研究显示，我们的方法优于其他AI文本检测器，RR模型尤为稳健。我们公开了代码、数据集和模型。

> The integrity of the peer-review process is vital for maintaining scientific rigor and trust within the academic community. With the steady increase in the usage of large language models (LLMs) like ChatGPT in academic writing, there is a growing concern that AI-generated texts could compromise scientific publishing, including peer-reviews. Previous works have focused on generic AI-generated text detection or have presented an approach for estimating the fraction of peer-reviews that can be AI-generated. Our focus here is to solve a real-world problem by assisting the editor or chair in determining whether a review is written by ChatGPT or not. To address this, we introduce the Term Frequency (TF) model, which posits that AI often repeats tokens, and the Review Regeneration (RR) model, which is based on the idea that ChatGPT generates similar outputs upon re-prompting. We stress test these detectors against token attack and paraphrasing. Finally, we propose an effective defensive strategy to reduce the effect of paraphrasing on our models. Our findings suggest both our proposed methods perform better than the other AI text detectors. Our RR model is more robust, although our TF model performs better than the RR model without any attacks. We make our code, dataset, and model public.

[Arxiv](https://arxiv.org/abs/2410.09770)