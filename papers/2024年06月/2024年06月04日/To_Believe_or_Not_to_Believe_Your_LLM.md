# 是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的不确定性量化问题，特别是如何识别模型输出中的不确定性。它提出了一种基于信息论的方法来判断模型输出的可靠性，并分析了迭代提示对模型输出概率评估的影响。这些内容属于对LLM工作原理的深入理论分析，因此归类为LLM理论。` `人工智能`

> To Believe or Not to Believe Your LLM

# 摘要

> 我们研究了大型语言模型（LLMs）中如何量化不确定性，旨在识别何时响应中的不确定性较大。我们综合考虑了认识论和偶然性不确定性：前者源于对真实情况的无知，后者源于不可避免的随机性。我们特别提出了一种信息论方法，能准确判断何时仅因知识不足导致模型输出不可靠。这一判断基于模型对先前响应的迭代提示输出。此方法能有效识别幻觉现象（即知识不足导致的高不确定性），无论答案是单一还是多个，这与传统的不确定性量化方法（如对数似然阈值化）不同，后者无法在多答案情况下检测幻觉。我们的实验验证了这一方法的有效性，并揭示了迭代提示如何影响LLM对输出概率的评估，这一发现本身也颇具价值。

> We explore uncertainty quantification in large language models (LLMs), with the goal to identify when uncertainty in responses given a query is large. We simultaneously consider both epistemic and aleatoric uncertainties, where the former comes from the lack of knowledge about the ground truth (such as about facts or the language), and the latter comes from irreducible randomness (such as multiple possible answers). In particular, we derive an information-theoretic metric that allows to reliably detect when only epistemic uncertainty is large, in which case the output of the model is unreliable. This condition can be computed based solely on the output of the model obtained simply by some special iterative prompting based on the previous responses. Such quantification, for instance, allows to detect hallucinations (cases when epistemic uncertainty is high) in both single- and multi-answer responses. This is in contrast to many standard uncertainty quantification strategies (such as thresholding the log-likelihood of a response) where hallucinations in the multi-answer case cannot be detected. We conduct a series of experiments which demonstrate the advantage of our formulation. Further, our investigations shed some light on how the probabilities assigned to a given output by an LLM can be amplified by iterative prompting, which might be of independent interest.

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_London.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_GW.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_JS.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_Russia.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_harp.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_actor.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_rat.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_monday.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_name_city.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_name_fruit.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_name_drink.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/prob_name_game.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/x1.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/PR-TriviaQA-all.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/PR-AmbigQA-all.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/PR-TriviaQA-WN.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/PR-AmbigQA-WN.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/recall-TriviaQA.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/error-TriviaQA.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/recall-AmbigQA.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/error-AmbigQA.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/x2.png)

![是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。](../../../paper_images/2406.02543/x3.png)

[Arxiv](https://arxiv.org/abs/2406.02543)