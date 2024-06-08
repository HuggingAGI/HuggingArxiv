# 是否信任你的大型语言模型（LLM）？这是一个值得深思的问题。

发布时间：2024年06月04日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）中的不确定性量化问题，特别是如何识别和量化模型响应中的不确定性。研究内容涉及认识论和偶然性不确定性，并提出了一种基于信息理论的度量方法来检测模型输出的可靠性。这种方法通过迭代提示来改进模型对特定输出的概率分配，从而检测幻觉。由于论文的核心内容是关于LLMs的理论分析和方法论创新，因此将其归类为LLM理论。` `人工智能`

> To Believe or Not to Believe Your LLM

# 摘要

> 我们研究了大型语言模型（LLMs）中的不确定性量化，旨在识别何时响应中的不确定性较高。我们综合考虑了认识论和偶然性不确定性，前者源于对真实情况的无知，后者源于不可避免的随机性。我们特别提出了一种信息理论度量，能有效检测仅认识论不确定性高的情况，此时模型输出不可靠。通过基于先前响应的迭代提示，我们可以仅从模型输出中计算出这一条件。这种方法能有效检测幻觉，无论是在单个还是多个答案的响应中，与传统的阈值化对数似然方法不同，后者无法在多答案情况下检测幻觉。我们的实验证明了这种方法的优势，并揭示了迭代提示如何增强LLM对特定输出的概率分配，这一发现可能具有独立的研究价值。

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